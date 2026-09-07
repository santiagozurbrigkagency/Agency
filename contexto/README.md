# contexto/ — Data del negocio

## Qué va acá
La **versión vigente** de la data fundacional de Genesis OS. No son frameworks
(eso es `playbooks/`) ni entregables (eso es `outputs/`): es **qué es verdad sobre
el negocio**.

Archivos canónicos:

| Archivo | Qué contiene |
|---|---|
| `Avatar-Genesis.md` | Quién es el cliente, específico. Escalera de niveles, descripción general, mapa de dolores. |
| `Oferta-Genesis.md` | La oferta cerrada, sus componentes, el precio y su validación. |
| `Metodo-Unico-Genesis.md` | Escalar Hacia Adentro: transformación, obstáculos, las siete piezas, el nombre. |

## La regla
**Una sola fuente de verdad.** Todos los agentes leen de acá. Ningún agente guarda su
propia copia del avatar ni de la oferta — si un agente necesita esa data, la referencia
desde `contexto/`, no la duplica.

Si se actualiza el avatar, se actualiza **acá**, y todo el sistema queda al día de una.

## Cómo llega un archivo a esta carpeta

**Caso 1 — lo escribí yo a mano.** Va directo acá. No pasa por `outputs/`.

**Caso 2 — lo produjo un agente** (ej: un agente que define avatar).
Entonces el archivo vive en dos lugares, y no es redundancia:

- `outputs/<fecha>/<agente>/<archivo>.md` → **la corrida**. Registro histórico de qué
  produjo ese agente ese día. Inmutable. Permite comparar versiones y volver atrás.
- `contexto/<archivo>.md` → **la versión vigente**. Dirección estable: el contenido
  cambia, la ruta no. Es la que referencian los demás agentes.

El output aprobado se **promueve** de `outputs/` a `contexto/`.

Los archivos vigentes llevan versión y fecha en la primera línea ("Versión consolidada al …").
Al promover una versión nueva, se reemplaza el archivo y se actualiza esa línea.

## Promoción: `templates/` vs `contexto/`
Es el mismo patrón, cambia el criterio:

- `templates/` promueve por **forma** → "así se ve un output bien hecho".
- `contexto/` promueve por **contenido** → "esto es verdad sobre mi negocio".

Un avatar aprobado puede ir a los dos: a `templates/` como ejemplo de cómo se arma un
buen avatar, a `contexto/` como el avatar real del negocio.

## Cadena de dependencias
El orden importa: el avatar alimenta a la oferta, y los dos alimentan al método único.

```
Avatar-Genesis.md  →  Metodo-Unico-Genesis.md  →  Oferta-Genesis.md
```

Un agente que trabaje sobre la oferta lee primero el avatar. Si un eslabón cambia,
revisar los que vienen después.
