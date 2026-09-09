<!--
TEMPLATE APROBADO — Roadmap MVP
Agente: arquitecto-producto-mvp · Playbook: playbooks/arquitecto-producto-mvp.md
Aprobado el 7 de septiembre de 2026, sin correcciones.
Corrida original: outputs/2026-09-07/arquitecto-producto-mvp/Roadmap-MVP-Genesis.md

POR QUÉ FUNCIONÓ — la vara para el próximo roadmap

1. Cada dato trazado a su fuente. Ningún problema, solución ni número salió de la nada:
   todo apunta a Avatar / Metodo-Unico / Oferta. Cuando no había data, se marcó como
   hueco en vez de rellenarlo.

2. Respetó el mapeo dolor -> pieza que ya existía. El avatar ya asignaba una pieza del
   método a cada dolor. El agente lo usó tal cual en vez de rehacerlo. No se reinventa
   lo que el negocio ya definió.

3. Ordenó por ejecución, no por el orden del listado. Las fases van en el orden en que
   una habilita a la siguiente (sin la cuenta no se precifica la variante, sin variante
   no hay qué ofrecer, sin primer cobro no hay LTV probado). El orden numérico de los
   dolores es de research, no de entrega.

4. No infló las fases. Siete piezas del método no son siete fases: dos quedaron fuera
   con la razón escrita (una es consecuencia de otra, la otra es el resultado del
   conjunto). Sacar cosas es parte del MVP.

5. Marcó los problemas que faltaban. El paso 1 del proceso lo pide y acá dio lo mejor
   del output: detectó tres huecos que el research no tenía, uno de ellos citando una
   contradicción interna de los propios documentos del negocio.

6. Cerró con el chequeo contra los cuatro filtros, explícito y respondido uno por uno,
   más "qué se sacó por MVP". Sin eso el roadmap no se puede auditar.

7. Voz correcta: argentino directo, con los números propios adelante (2,5x, 1,28%,
   30.000 vs 75.000) y cero relleno motivacional.
-->

# ROADMAP MVP — Génesis (Escalar Hacia Adentro)
Generado el 7 de septiembre de 2026 por el agente `arquitecto-producto-mvp`.
Fuentes: `contexto/Avatar-Genesis.md` · `contexto/Metodo-Unico-Genesis.md` · `contexto/Oferta-Genesis.md`
Formato de entrega al que aplica: 3 meses · USD 5.000 · 1:1 · DFY · 3 a 5 clientes del piloto.

---

## SITUACIÓN INICIAL — Gonza, el 1 del mes

Marca de consumibles en compra única. Factura entre 30 y 80 millones por mes con Meta Ads
(el filtro del piloto, no todo el rango del avatar). Sabe operar: creativos, campañas,
proveedor, logística. Pero cada venta le cuesta lo mismo que la anterior, el CPM le subió
todo el año y la marca está en break-even. El 1 del mes arranca en cero y no sabe con
cuánto va a cerrar. Si pasa a responsable inscripto, no cierra. Si Meta le baja la cuenta,
se termina. Ya pagó dos mentorías que le enseñaron a buscar producto — y él ya tiene
producto.

---

## EL ROADMAP

| Fase (nombre + objetivo) | Problema(s) | Solución | Vehículo de entrega |
|---|---|---|---|
| **Fase 1 — Auditoría y Variante**<br><br>*Objetivo: saber cuánto podés pagar por un cliente y tener la variante de suscripción definida y precificada, sin tocar lo que hoy factura.* | **P6** "Ya pagué dos mentorías y me enseñaron a buscar producto. Yo ya tengo producto."<br><br>**P2** "El CPM sube todos los meses y estoy en break-even." | **La Cuenta del CPA (auditoría):** sobre sus números reales — margen por pedido, CPA actual, techo de pauta hoy. Y el techo nuevo con LTV 2,5. El caso: 30.000 hoy → 75.000 con suscripción.<br><br>**Migración sin Frenar:** variación de producto sobre lo que YA vende — formato, dosis, tamaño y ciclo de reposición. Cada cuántos días se termina es cada cuántos días se cobra. Se define y se precifica con el margen de la auditoría. | **Async:** formulario de números previo (margen, CPA, ticket, recompra, ciclo del producto).<br><br>**Sync:** sesión 1 a 1 — se hace la cuenta con él en pantalla y se define la variante. Es el punto donde se traba: hay que sacarle de la cabeza que la solución es otro producto. |
| **Fase 2 — Primer Cobro**<br><br>*Objetivo: que la base de compradores que ya tiene empiece a pagar recurrente, sin gastar un peso de CPA.* | **P1** "Cada venta me cuesta lo mismo que la anterior. No acumulo nada." | **De Pedido a Suscriptor:** se cambia la unidad de venta. La suscripción se instala en la tienda como variante paralela — la compra única no se toca — y se le ofrece primero a los compradores anteriores. Sin CPA, es el camino más corto al primer cobro. El primer cobro recurrente cae al cumplirse el primer ciclo de reposición. | **Async:** instalación de la suscripción en la tienda (DFY) + secuencia de mail y WhatsApp de conversión de la base (DFY). Es ejecución, no concepto: se entrega hecho.<br><br>**Sync:** chat para destrabar la instalación si la plataforma no acompaña. |
| **Fase 3 — Piso de Facturación**<br><br>*Objetivo: una base de suscriptores medida que arranque el mes cobrada y que no dependa de Meta.* | **P3** "El 1 del mes arranco en cero. No sé con cuánto voy a cerrar."<br><br>**P4** "Si Meta me baja la cuenta, se termina el negocio." | **Piso de Facturación:** base de suscriptores activos medida y seguida con tracker (Scalify). Objetivo de churn: 1,28%. Backend de retención + proyecciones de stock sobre la base.<br><br>**Estructura de anuncios al CPA nuevo:** recién acá, con el LTV ya probado por el primer cobro, la pauta se reestructura al techo nuevo. La pauta suma suscriptores; no sostiene la facturación.<br><br>**Facturación a Prueba de Meta** es la misma base leída desde el riesgo. No necesita trabajo aparte. | **Async:** tablero de suscriptores, churn y recompra (DFY) + backend de retención (DFY).<br><br>**Sync:** revisión semanal del tablero [corregido 9-sep 2026: decía quincenal, Santi confirmó que la cadencia real es semanal, igual que en Oferta-Genesis.md]. Acá se traba: leer churn y decidir qué tocar es criterio, no dato. |
| **Fase 4 — Margen Formalizable**<br><br>*Objetivo: saber en qué punto de la base el blanco cierra, y llegar a ese punto.* | **P5** "Facturo bien pero no puedo blanquear. Si paso a responsable inscripto, no cierra." | **Margen Formalizable:** la hoja de costeo de la Fase 1, ahora corrida con IVA y ganancias como RI. No es un problema fiscal, es de margen: con LTV 2,5 el margen por cliente se multiplica y el blanco entra. Primero el modelo, después el contador.<br><br>*No incluye:* fabricación legal, ANMAT ni laboratorio. El contador lo pone el cliente. | **Async:** la cuenta de formalización entregada (DFY).<br><br>**Sync:** una sesión para leerla. Es un concepto que se entiende una vez, pero la decisión de blanquear necesita a alguien enfrente. |

**Ventaja Invisible (P7 — "todos venden lo mismo que yo, me copian la landing")** no es una
fase. Es el resultado del conjunto: la landing se copia en 48 horas, 2.200 suscriptores no
se scrapean. Se nombra en el cierre y es lo que dice el testimonio, no algo que se ejecuta.

---

## SITUACIÓN DESEADA — Punto B

Marca de suscripción con base de suscriptores activos. El mes arranca cobrado. Puede pagar
2,5 veces más por cliente que su competencia y seguir rentable — y la competencia de compra
única se queda afuera de la subasta. Los clientes se acumulan como activo: la segunda,
tercera y cuarta compra no tienen costo de adquisición. El margen aguanta IVA y ganancias.
Si cae la cuenta de Meta, los suscriptores siguen cobrándose.

---

## PROBLEMAS QUE FALTAN EN EL MAPA

Tres huecos entre fases. No están en los siete dolores del avatar, pero el roadmap se
traba en ellos. No los resuelvo acá porque no hay data — los marco.

**1. El cobro recurrente. Entre Fase 1 y Fase 2 — el más grave.**
[RESUELTO 9-sep, respuesta de Santi] Es la suscripción nativa de Tiendanube — no hay que instalar
ninguna app de terceros. Las marcas que no están en Tiendanube: la migración se resuelve con
Manu en llamada 1 a 1, caso por caso — no hay todavía un proceso DFY estandarizado para esto,
es criterio de Manu en cada cliente. No entra al filtro de calificación del setter (no se
descarta a nadie por la plataforma); se resuelve en el diagnóstico/llamada.

**2. La baja del suscriptor. Dentro de Fase 3.**
Hay un objetivo de churn (1,28%) pero no un dolor que diga "se me dan de baja al segundo
mes". Y en los pendientes del método figura *"qué hace concretamente Manu para el 1,28%"*.
O sea: hay número, no hay mecanismo. Sin eso, la Fase 3 entrega un tablero que mide un
problema que no sabe resolver.

**3. El stock comprometido. Dentro de Fase 3.**
"Proyecciones de stock sobre la base" es un entregable del DFY, pero no hay dolor asociado.
La suscripción cambia la logística: hay que tener producto en una fecha, sí o sí. Para una
marca que hoy compra por tandas según lo que vende, es un problema nuevo que el modelo le
crea. Nadie lo nombró todavía.

---

## QUÉ FALTA DEFINIR

Ordenado por lo que más bloquea.

**Ya resueltos (9-sep, respuestas de Santi)**
- Ciclo de reposición típico: no hay uno único, varía por cliente, se define en la Fase 1 de
  cada caso. Ver `Oferta-Genesis.md`, sección "TIEMPO".
- Cómo se cobra recurrente: por Tiendanube. Falta el detalle técnico (suscripción nativa o
  app de terceros) y qué pasa con marcas que no están en Tiendanube — ver hueco 1 arriba.

**Bloquea una fase**

**Bloquea una fase**
3. [RESUELTO 9-sep] **La hoja de costeo con LTV ya existe**, en Google Sheet (confirmado por
   Santi). Ojo: no está confirmado si es la misma herramienta que "la calculadora de suscripción
   de tres escenarios" que pide `Oferta-Genesis.md` (sección 8, bloquea la venta) y que
   `Personaje.md` describe como idea de Manu que "hoy no existe" — esa calculadora proyecta
   conservador/realista/deseado y se usa en vivo en el diagnóstico. Puede que la hoja de Google
   Sheet sea el motor de cálculo y falte la capa de presentación para el diagnóstico, o puede que
   sean dos cosas distintas. [DIFERIDO 9-sep, decisión de Santi: por ahora no se resuelve. No
   bloquea nada activo mientras tanto — sigue marcado como bloqueante de `Oferta-Genesis.md`
   sección 8 para cuando se retome.]
4. **Qué hace Manu para el 1,28% de churn.** [RESUELTO PARCIAL 9-sep, respuesta de Santi]: se
   explica en la llamada 1 a 1 con cada cliente — es criterio de Manu en vivo, no un SOP
   documentado ni un mecanismo escrito. Sigue siendo un hueco para CONTENIDO y para la página
   de oferta (no se puede publicar un mecanismo que solo existe hablado), pero no bloquea la
   Fase 3 del DFY: Manu lo resuelve 1 a 1, igual que la migración de plataforma (hueco 1).
   [DIFERIDO 9-sep, decisión de Santi: documentarlo como pieza de contenido/SOP queda en pausa
   por ahora.]
5. [ACLARADO 9-sep, respuesta de Santi] **La variante paralela es la Etapa 1, no el estado
   final.** El objetivo real es migrar la tienda completa a suscripción con el tiempo; cuándo
   conviene pasar a full migración se define con Manu en llamada, caso por caso. Ver
   `Metodo-Unico-Genesis.md`, pieza "Migración sin Frenar". Sigue sin confirmar el criterio
   concreto de cuándo conviene el salto a full migración — eso todavía es de Manu.

**Define el alcance del piloto**
6. [RESUELTO 9-sep, respuesta de Santi] **Stock: SÍ entra al roadmap**, confirmado — el manejo
   de stock es parte del producto. Sigue faltando el dolor/obstáculo explícito que lo sostenga
   (ver "PROBLEMAS QUE FALTAN EN EL MAPA", punto 3, arriba): hoy es un entregable sin un "O"
   propio en `Metodo-Unico-Genesis.md`. Falta también el mecanismo — "proyecciones de stock" es
   un renglón de la oferta, pero no está escrito CÓMO se proyecta.
7. **Dónde termina la Fase 4.** El programa dura 3 meses. ¿La formalización se ejecuta, o
   se entrega la cuenta que dice cuándo hacerla? Cambia bastante la carga de entrega.
   [DIFERIDO 9-sep, decisión de Santi: por ahora no se resuelve.]

---

## CHEQUEO CONTRA LOS FILTROS

- **¿Mapa o rejunte?** Mapa. Cada fase habilita la siguiente: sin la cuenta no se precifica
  la variante, sin la variante no hay qué ofrecer a la base, sin primer cobro no hay LTV
  probado para subir la pauta, sin base no hay margen que aguante el blanco.
- **¿Cada recurso en una etapa puntual?** Sí. Las siete piezas del método entran una vez y
  en un solo lugar. Dos no son fase y se declara por qué: Facturación a Prueba de Meta es
  lectura del piso, Ventaja Invisible es el resultado.
- **¿Se arma en una semana?** Sí, si la hoja de costeo ya existe. Lo que se arma es: un
  formulario de números, la hoja de costeo, una secuencia de mail/WhatsApp, un tablero y la
  cuenta de formalización. Todo lo demás es 1 a 1 y no se produce por adelantado. Si la hoja
  de costeo hay que hacerla de cero, son dos semanas.
- **¿Nombres ejecutables o marketineros?** Ejecutables. Son los nombres de las piezas del
  método, que ya describen qué se hace. "Auditoría y Variante" dice qué pasa esa semana.

**Qué se sacó por MVP:** el webinar, los SOPs documentados y la versión grupal. Con 3 a 5
clientes 1 a 1 no aportan al resultado — se documentan mientras se entrega el piloto, no
antes.
