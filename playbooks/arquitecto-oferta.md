# Playbook — Arquitecto de Oferta

## Qué es y para qué sirve
Framework para escribir ofertas de infoproducto en una sola frase con la **Estructura
Main**, y para **cruzar** una versión nueva de una oferta contra la data vigente del
negocio.

No se hace teoría. Se entregan ofertas listas para validar, ya presionadas contra los
errores típicos.

## Principio que ordena todo
**Se vende el sueño, no el mecanismo.** El resultado lidera porque el cliente compra el
destino; el método va al final, subordinado, porque justifica pero no vende.

Corolario: **una oferta es una hipótesis.** La primera versión es un borrador. Si el
mercado no responde no es un fracaso, es data: se ajusta el componente que falló y se
vuelve a probar.

---

# MODO 1 — ESCRIBIR UNA OFERTA

## La Estructura Main (fórmula fija)

```
"Ayudo a [AVATAR] a lograr [RESULTADO] en [TIEMPO], sin tener que [DOLOR 1]
 ni [DOLOR 2], con el [MÉTODO ÚNICO]."
```

El verbo puede cambiar según la voz del negocio ("Ayudo a…", "Escalo tu…", "Paso tu…").
Lo que no cambia es el orden: **resultado adelante, método último y subordinado**.

## El framework paso a paso

### 1. Armar la oferta base
Con la fórmula y la data vigente del negocio. Sin variantes todavía.

### 2. Generar 3-5 variantes
Cambiando **el resultado, el tiempo o los dos dolores**. El avatar no se cambia sin
avisar: es el componente más caro de mover y el que más data tiene detrás.

### 3. Presionar cada variante contra el checklist
Se descarta o se corrige la que falle:

- ¿El resultado es **tangible**, no una emoción?
- ¿El tiempo es realista y **NO es la duración del programa**? El tiempo de la oferta es
  cuánto tarda el resultado. Poner la duración del programa es humo.
- ¿Los dos dolores salen del **mapa de dolores** y son los que más pesan en la decisión
  de compra? Un miedo no es lo mismo que una solución que ya le falló: los miedos van al
  contenido, las soluciones fallidas van a la frase.
- ¿El método tiene **nombre propio** y va al final?
- ¿Es **UNA sola promesa**? Si hay dos resultados, son dos ofertas.

### 4. Elegir la más fuerte
Y explicar en una línea por qué.

### 5. Bajar la elegida a bio de Instagram
Estructura de 5 líneas: **resultado → sin dolores → autoridad → CTA → método**.
Mayúsculas estratégicas en la categoría y en el nombre del método.

## Cuándo no poner el tiempo
Si no hay data de cuánto tarda el resultado, **no se pone un plazo**. En su lugar va una
**velocidad anclada al mecanismo** ("el primer cobro cae al cumplirse el primer ciclo de
reposición"). Es la forma correcta cuando no todos los clientes arrancan del mismo lugar.

## Categoría vs método
En la frase va la **categoría** (lo que el avatar busca y entiende). El **nombre del
método** va donde se recuerda: encabezado, bio, cierre de reel, webinar, SOPs.

> Se busca por categoría, se recuerda por método.

## Formato de output — Modo 1
1. 3-5 ofertas en la fórmula.
2. La recomendada + por qué, en una línea.
3. La bio de Instagram con la recomendada (5 líneas).
4. Qué queda por validar: cuál es el componente más incierto y qué lo prueba.

---

# MODO 2 — CRUZAR UNA OFERTA

Se usa cuando llega una **versión nueva desde afuera** (una oferta reescrita, un pitch de
la call, una página de ventas) y hay que reconciliarla con la data vigente de `contexto/`.
Sirve igual para avatar, método o entrega.

Vara de calidad: `templates/Cruce-Oferta-Consultoria.md`.

## El framework paso a paso

### 1. Empezar por lo que coincide
Y demostrarlo, no afirmarlo: mapear los entregables contra las piezas del método, uno por
uno. Prueba que se leyó la data en serio y deja claro que las divergencias que siguen son
puntuales, no un rechazo del documento entero.

### 2. Listar las divergencias, cada una con su decisión
No alcanza con marcar la diferencia. Cada una lleva **etiqueta** (`[CAMBIAR]`,
`[AGREGAR]`, `[PRECISAR]`, `[DECISIÓN DEL DUEÑO]`) y **la corrección escrita, lista para
copiar**. Un cruce que solo lista diferencias obliga a hacer el trabajo dos veces.

### 3. Justificar cada corrección citando el documento vigente
Se discute contra `contexto/`, no contra el gusto. Si una corrección no se puede anclar a
una línea de la data vigente, es una opinión y se marca como tal.

### 4. Hacer las cuentas de lo que ya está escrito, antes de proponer cambios
La solución suele estar adentro de los propios números de la versión nueva. Un solo
reencuadre puede desactivar varios problemas que parecían separados.

### 5. Auditar la base, no solo la versión nueva
Si aparece una **contradicción interna entre los documentos vigentes**, se marca. No la
trajo la versión nueva, pero el cruce la deja a la vista y ese es parte del valor.

### 6. No decidir lo que no corresponde
Lo que depende de data que no existe, o de una decisión del dueño, queda como pendiente
**con dueño y con qué lo desbloquea**. No se rellena con hipótesis.

### 7. Cerrar con la versión lista para copiar
La oferta ya corregida, entera. Sin obligar a reconstruirla juntando las correcciones una
por una.

## Formato de output — Modo 2
1. Veredicto en una línea.
2. Qué coincide (no tocar).
3. Divergencias, numeradas, cada una con etiqueta y corrección.
4. El bloque que más rompe, desarrollado aparte si lo amerita.
5. La versión cruzada, lista.
6. Lo que este cruce no puede resolver: pendientes con dueño.

## Después del cruce
Si se aprueba y es data fundacional del negocio, la versión nueva **se promueve a
`contexto/`** y la corrida queda en `outputs/`. Ver `contexto/README.md`.

---

# ERRORES TÍPICOS (los dos modos)

- **Poner la duración del programa como tiempo del resultado.** Es el error más común y
  el más fácil de detectar.
- **Meter dos promesas en una frase.** Si querés dos resultados, son dos ofertas.
- **Liderar con el mecanismo.** "Con mi método X vas a…" invierte el orden y vende lo que
  al cliente no le importa todavía.
- **Nombrar el método una sola vez.** Se define, se usa en un lugar y se olvida. Tiene que
  aparecer en el encabezado, en el cierre, en la bio y en el contenido.
- **Usar un miedo como "sin".** Los dos "sin" salen de soluciones que ya le fallaron al
  avatar, no de sus miedos. Los miedos van al contenido.
- **Abrir el avatar con una palabra más amplia.** Cambiar "ecomm" por "marca" parece
  inocuo y rompe el filtro de calificación aguas abajo.
- **Bajar el precio sin marco.** Un precio más bajo valida un precio que después no se
  vende. Si hay que cobrar menos, es un **descuento con nombre y contrapartida**, no otro
  precio.
- **Inventar entregables para cubrir un dolor.** Si un dolor no tiene pieza propia, se
  cobra en copy, no fabricando un módulo.

# REGLAS

- Nunca inventar resultados, números ni casos. Si falta data, se dice "falta data" y se
  pide.
- Una promesa por oferta.
- Escribir en argentino, directo, con la voz del negocio.
- Cero relleno motivacional. Cada línea aporta un dato o una decisión.
