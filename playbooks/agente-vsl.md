# Playbook — Agente VSL

## Qué es y para qué sirve

El framework para escribir **VSLs (Video Sales Letters)** de Génesis. Un VSL no es "un video de
ventas lindo": es un guión donde **cada bloque cumple una función psicológica concreta**, calibrado
a las variables del negocio, que convierte tráfico en lead calificado o en venta.

La creencia que este playbook corrige: la gente cree que un buen VSL es hablar bien del producto.
Un buen VSL es **un recorrido lógico y emocional donde el que mira llega solo a la conclusión de
que necesita la solución**. El copy no depende del nicho: depende de calibrar bien las variables.

**Fuente:** `agentes/Agente Creador de VSLs — Prompt instalable.md`, adaptado a Génesis.
**Relación con el Agente Copy:** este playbook **NO repite** la voz de Manu, los números canónicos
ni los 11 anti-patrones generales. Viven en `playbooks/agente-copy.md`. Acá va solo lo específico
del formato VSL.

**Cambio de registro respecto del framework original.** El original está escrito en femenino y con
tono B2C ("la viewer", "vas a sentirte plena"). El avatar de Génesis es **B2B**: dueño de marca que
ya factura. Lógica, impacto, riesgo, resultado medible, emoción contenida. Acá se dice
**"el que mira"** y el tono es el del analista, no el del coach.

---

## 1. Antes de escribir: la data

El framework original pide llenar un bloque de configuración con los datos del negocio. **En
Génesis ese bloque no se completa a mano: ya existe en `contexto/`.**

| Input del framework | Dónde está |
|---|---|
| Referente que lee en cámara, cómo habla, palabras que no usa | `contexto/Personaje.md` + `contexto/Voz-Genesis.md` |
| Oferta, qué incluye, ticket, forma de pago | `contexto/Oferta-Genesis.md` |
| Avatar, dolores literales, objeciones, deseos, sub-segmentos | `contexto/Avatar-Genesis.md` |
| Nicho y competencia (lenguaje, tono, clichés a evitar) | `contexto/Personaje.md` (carril analista vs. carril auto/Dubái) |
| Mecanismo único: nombre, frase, componentes | `contexto/Metodo-Unico-Genesis.md` |
| Contexto del funnel | `contexto/Personaje.md`, sección FUNNEL DE LA VENTANA |
| Números canónicos y reglas de tono | `playbooks/agente-copy.md` |

**Lo que NO está y hay que pedir antes de escribir:**

- **Testimonios reales, con link al video o audio.** **José es el caso principal y se explota en
  todo el contenido** (ver sección 2). Lo que falta son casos que cubran el resto de los
  sub-segmentos: esos se piden, y si no están se marca `[FALTA CASO REAL]`. **Nunca se inventa.**
- **Marco global / scarcity real.** El negocio está en **validación, no en lanzamiento**: hoy no
  hay fecha de cierre ni cupos. Si no hay nada real, se declara "no hay" y **el VSL no usa
  urgencia**.
- **Nivel de conciencia del tráfico** de la pieza puntual. Cambia todo. Se pregunta, no se supone.
- **Tipo de VSL y lugar exacto en el funnel.** Se confirma antes de escribir una línea.
- **Si Manu lee de teleprompter o improvisa** en esa pieza (ver sección 2).

**Si dos archivos de `contexto/` se contradicen, no se elige solo:** se muestran las dos versiones
y se pregunta cuál manda.

---

## 2. El contexto de Génesis — lo que condiciona todo

**El referente es Manu (Manuel Dominguez), "el que muestra el tablero".** Voseo argentino, sin
mezclar con tuteo. Analista, no ganador de la lotería. Prueba con métricas de retención, no con
facturación en pesos.

**Teleprompter o improvisación — define el formato de entrega:**

- **Escenario 1 (estudio, pizarra de fondo)** — hay teleprompter. Video largo de YouTube y webinar.
  → El guión se entrega **palabra por palabra**.
- **Escenario 3 (pantalla compartida, haciendo la cuenta de un negocio real)** — no se lee, se
  hace la cuenta en vivo. → El guión se entrega **en beats**: bullets con la intención de cada
  momento, no texto para leer.

Si no está claro cuál de los dos, **se pregunta antes de escribir**.

**Lugar en el funnel.** TikTok e historias → link en bio → **formulario** → **video largo de
YouTube** → descripción → **WhatsApp directo de Manu**. El VSL de Génesis hoy vive en el eslabón
del video largo. La thank-you page del formulario y el mensaje de WhatsApp son los otros dos
lugares donde entra un VSL corto.

**Fase del negocio: validación.** Manu no está lanzando: está auditando negocios uno por uno. El
webinar sale después de cerrar 3. Un VSL con urgencia de lanzamiento **contradice la fase**.

**La pieza que convierte es la cuenta del otro en pantalla**, no la de Manu. El tablero (2.200
activos, 1,28% de churn) es la prueba de fondo.

**José es el caso principal de todo VSL.** Fue caso de éxito primero y socio después: migró como
cliente, le funcionó, y recién entonces pasó a ayudar a Manu a entregar el servicio. **El doble rol
no lo invalida como testimonio — se declara, y en ese orden.** Es el único caso fuerte que hay, así
que no se esquiva ni se relega: es el que va en el bloque PRUEBA. Las cuatro reglas para usarlo
están en `contexto/Personaje.md`:

1. Prueba el **mecanismo**, no el resultado del avatar — está muy por encima del rango 30-80M.
   Nunca se presenta como "esto te va a pasar a vos".
2. **Retención adelante** (activos, churn, LTV real medido), **profit atrás** como contexto.
3. **El doble rol se declara** en orden: primero cliente, después socio. Escondido queda peor.
4. **Un ángulo distinto por pieza**, no el relato entero cada vez. Repetir el mismo nombre con
   ángulos distintos lo construye; repetir el mismo relato lo quema.

Falta su **OK para usar los números en público**. Si un VSL los usa, se marca en DATOS FALTANTES.

**Ticket USD 4.000 con anclaje declarado a 6.000.** Riesgo percibido alto → duración larga, y los
bloques de objeción y elegibilidad pesan más que en un ticket bajo.

---

## 3. Los 5 tipos de VSL

Antes de escribir hay que saber **cuál de los cinco** se está escribiendo. Cada uno tiene otro
trabajo, otra duración y otro CTA.

### TIPO 1 — LANDING PAGE
Convierte tráfico de una landing en lead calificado o compra. **5-25 min según nivel de
conciencia.** Es el más completo: los otros cuatro son recortes o variantes de este.

### TIPO 2 — RESOLUCIÓN DE OBJECIONES
Desarma **UNA** objeción específica antes de la próxima fase del funnel. Típico: thank-you page
post-agendamiento. **3:30-4:00 min.**

### TIPO 3 — MECANISMO ÚNICO / YOUTUBE
Capta audiencia nueva con contenido educativo de alto valor que termina en **soft CTA** (recurso,
suscripción), no en venta dura. **8-15 min.**

### TIPO 4 — CHAT
Se manda **1 a 1 por DM o WhatsApp** a leads ya calificados. **15-25 min, flexible.** Misma
columna vertebral que el Landing, pero con más historia personal del referente, más detalle en la
oferta (precio, plan de pago, garantías), CTA cálido ("escribime", no "tocá el botón") y permite
tangentes.

### TIPO 5 — THANK-YOU PAGE
Confirma el agendamiento, baja la ansiedad y **previene el no-show**. **1-3 min.**

**Cuál aplica hoy en Génesis:** el video largo de YouTube post-formulario es TIPO 1 o TIPO 3 según
la temperatura del tráfico —se confirma, no se asume—; el WhatsApp de Manu habilita TIPO 4; y
cuando entre el agendamiento de calls, TIPO 5 y TIPO 2.

---

## 4. El proceso — orden estricto, con checkpoints

**Nunca se entrega un VSL entero sin checkpoints previos.**

### FASE 0 — Chequeo de pre-requisitos
Antes de escribir se chequea que existan: avatar definido, oferta clara, **testimonios reales** y
voz del referente. Si falta algo clave se dice de frente:

> "Antes de escribir un VSL que convierta necesito [X]. Sin esto el VSL va a ser genérico o la
> prueba va a ser floja. ¿Lo tenés o lo trabajamos primero?"

**José siempre está disponible como caso principal**, así que el bloque PRUEBA nunca arranca
vacío. Lo que se chequea es si hay casos para los **otros** sub-segmentos. Si no los hay, se avisa
qué sub-segmento queda descubierto y se sugiere grabarlo — no se frena el VSL por eso.

### FASE 1 — Lectura y validación de inputs
Se lee todo `contexto/` y el material cargado, y se devuelve este resumen para validar:

```
## Lo que entendí de tu material
Referente que lee el VSL:  [quién es, cómo habla, teleprompter o improvisa]
Oferta:                    [qué vende, qué incluye, ticket]
Avatar:                    [demográfico, psicográfico, dolores literales, objeciones, deseos]
Nivel de conciencia:       [inferido]
Testimonios disponibles:   [nombre + fuente + qué sub-segmento cubre cada uno]
Voz del referente:         [tono, muletillas, región/pronombre, palabras que no usa]
Lo que NO encontré:        [lista de gaps]
```

Y se pregunta: **"¿Esto es correcto? ¿Algo para ajustar o completar?"**

### FASE 2 — CHECKPOINT: calibración, y se espera el OK
1. Se confirma **el contexto del funnel** — cambia duración, tono y CTA más que ninguna otra
   variable.
2. Se define **el tipo de VSL** entre los cinco.
3. Se llena **la tabla de calibración** (sección 11). Si una celda queda vacía, **se pide el dato:
   no se empieza a escribir**.
4. Se resuelven **los 3 pre-writing** (sección 6) y se validan.

### FASE 3 — Producción
Se escribe el VSL del tipo elegido, **bloque por bloque**, aplicando los principios de copy y las
reglas de cadencia. Cada caso anclado a su testimonio real.

### FASE 4 — CHECKPOINT FINAL: checklist + validación
Se pasa el **checklist anti-vacíos** (sección 12) y se devuelve junto con el VSL completo.
Después se pregunta: **"¿Quedó bien o hay algo que ajustar?"**

---

## 5. Las variables de calibración

**VARIABLE A — Nicho.** Cada nicho tiene su tono y su tipo de prueba:

| Nicho | Tono | Prueba |
|---|---|---|
| B2C (fitness, salud, beauty) | emocional, vulnerable, anti-guru | transformaciones + testimonios con quotes textuales |
| Finanzas / trading | sobrio, data, anti-hype | cuentas reales verificables + screenshots |
| Coaching / mentoring | transformacional, autoridad por experiencia | historia del referente + 2-3 casos con arco completo |
| **B2B / consultoría ← Génesis** | **lógico, profesional, eficiente** | **case studies con números (ROI, métricas)** |
| Ecommerce / producto físico | demostrativo, visual | demos en cámara + reviews + UGC |

Del research de los competidores del nicho se saca: su lenguaje, su tono, **lo que NO dicen**, y
los clichés que copian todos (para evitarlos). En Génesis eso ya está relevado: el mercado hispano
está en el carril auto/Dubái/cadenas, y el avatar de Nivel 3 ya se quemó con ese packaging.

**VARIABLE B — Nivel de conciencia.** Define cuánto revelar antes de la oferta:

- **No sabe que tiene el problema** → el bloque DOLOR es el más largo. Hay que revelarle el
  problema. Oferta muy tarde.
- **Sabe el problema, no las soluciones** → DOLOR confirma y agita. El reveal del mecanismo es la
  pieza clave.
- **Sabe que hay soluciones, no la tuya** → DOLOR breve. Foco en diferenciar el mecanismo de lo
  que ya conoce.
- **Conoce el producto, no decidió** → se saltean DOLOR y ORIGIN. Foco en oferta + elegibilidad +
  urgencia.
- **Listo para comprar** → VSL ultra-corto. Oferta + urgencia + CTA.

**VARIABLE C — Ticket y nivel de miedo → duración.** El ticket es un proxy; el dato real es el
miedo:

- Avatar lógico/analítico, decisor profesional → **8-12 min**, quiere método y métricas.
- Avatar emocional con dolor profundo → **15-25 min**, necesita acompañamiento e identificación.
- Avatar warm que ya te conoce → **5-8 min**, no hay que reestablecer autoridad.
- Riesgo percibido alto (ticket alto + decisión difícil) → **hasta 30 min** para bajar fricción.

**VARIABLE D — Objetivo.** Cambia el CTA: agendar llamada / comprar directo / dejar el mail /
registrarse a evento / reactivar / upsell.

---

## 6. Los 3 pre-writing — se resuelven ANTES de escribir

**MARCO GLOBAL** — el contexto que define por qué se está viendo esto **ahora**: los 7 días antes
del cierre, la cohorte que arranca, el método nuevo que nadie enseña todavía. Sin scarcity real el
VSL pierde urgencia. **Si no hay marco real, se avisa. No se inventa.**

**BIG IDEA** — la única idea que, si se adopta, acomoda todo lo demás. Es el reframe de la creencia
común del nicho. Estructura: **"No es X, es Y."**

**BIG PROBLEM** — el problema raíz, en una frase incómoda que probablemente nadie le dijo.
Ej. de forma: *"El método que estás usando está estructuralmente roto."*

**Mini-frameworks para destilarlos cuando no están:**

- **Big Problem:** ¿cuál es el dolor más profundo que no se atreve a verbalizar? → ¿por qué los
  métodos actuales no lo resuelven, qué les falla **estructuralmente**? → reformularlo en una
  frase incómoda.
- **Big Idea:** ¿cuál es la única idea que acomoda todo lo demás? → ¿es el opuesto o el reframe de
  la creencia común? → formularla como "no es X, es Y".
- **Marco global:** ¿qué hace que vea esto en este momento? ¿fecha de cierre? ¿novedad? ¿cupo real?

---

## 7. La estructura, bloque por bloque

### TIPO 1 — LANDING PAGE

```
[HOOK]           Promesa + loop de curiosidad + autoridad + marco global + 2-3 dolores + identificación
[DOLOR]          El avatar específico que se reconoce y se siente validado
[ORIGIN STORY]   La epifanía / por qué nació el método
[EL VEHÍCULO]    El mecanismo único como sistema (logic-first walkthrough)
[PRUEBA]         Caso real profundo + INSERT testimonio + montaje mapeando sub-segmentos
[OFERTA]         El stack que escala (con transiciones, no lista paralela)
[OBJECIÓN]       La objeción principal, devastada en 2 líneas
[ELEGIBILIDAD]   "No es para… / es para…" + pivot a identidad futura
[CTA]            Instrucción exacta + qué pasa después + los 3 elementos
[REFORZADOR]     Cierra loops + future pacing sensorial + frase memorable
```

**HOOK — el bloque que más se revisa.** Tiene que incluir **los 6 elementos**: promesa específica,
mini resumen de qué se toca, autoridad del referente, intro al marco global, 2-3 dolores literales,
identificación ("este video es para mí"). **Si falta uno, está incompleto.**

**DOLOR:** apertura ("le quiero hablar a alguien muy específico") → descripción cotidiana del
Avatar 2 → el entorno que lo mina, con frases textuales → el reveal del dolor profundo → el
reframe que alivia ("el problema no es X, es Y") → el costo de seguir igual → cierre quotable.

**ORIGIN STORY:** "yo viví exactamente eso" → el momento de quiebre (la causa real, no el síntoma)
→ la verdad que cambia todo (quotable) → nacimiento y nombre del método.

**EL VEHÍCULO (logic-first):** bridge ("antes de mostrarte qué es [método], mirá dónde está el
problema") → premise del nicho → círculo causa-efecto → auditoría de intentos pasados → el insight
→ "no fallaste por X, fallaste porque [causa estructural]" → "por eso nació [método]" → estructura
del método.

**PRUEBA:** caso real con nombre → el antes con quotes textuales → `[INSERT TESTIMONIO 1]` → el
cambio concreto → resultado cuantitativo → "y este caso no es la excepción" → `[INSERT MONTAJE]` de
4-5 personas mapeando sub-segmentos.

**OFERTA (stack escalado):** "esto es lo que recibís cuando entrás" → la base + anchor de valor →
"pero eso solo no alcanza" → lo segundo → "y todavía hay más" → lo tercero y cuarto → la última
pieza → estructura temporal por fases → promesa de salida.

**OBJECIÓN:** "antes de que pienses [objeción literal], escuchame" → costo del retraso → cierre con
scarcity real.

**ELEGIBILIDAD:** "[método] no es para cualquiera" → quién NO entra (3-4) → "es para otra persona"
→ quién SÍ (3-4) → `[INSERT TESTIMONIO 3]` → "si ese sos vos, prestá atención a lo que sigue".

**CTA:** comando claro + qué pasa cuando lo toca, paso a paso + callback al dolor + consecuencia de
no hacerlo + reducción de fricción.

**REFORZADOR:** future pacing sensorial (día concreto, situación cotidiana) → la transformación
interna → montaje final → "la persona que va a estar lista el mes que viene no existe: sos vos,
hoy" → scarcity final → frase memorable.

### TIPO 2 — RESOLUCIÓN DE OBJECIONES · 3:30-4:00 min

```
[APERTURA]           La objeción literal en su boca + contradicción directa
[COSTO DE CREERLA]   Concreto y medible: qué le cuesta hoy seguir creyendo eso
[ROMPER LA CREENCIA] El mecanismo central en 3-4 puntos numerados + frase quotable
[MINI-PRUEBA]        Caso real con 2 quotes textuales
[EL PERMISO]         (opcional, solo para objeciones densas) reframe de responsabilidad
[CIERRE]             Una sola idea para llevarse + qué esperar de la próxima fase (SIN tareas)
```

- **APERTURA:** la objeción entre comillas, como si la dijera él → contradicción clara ("si estás
  pensando eso, te está costando más de lo que creés, y te explico por qué") → comando de atención.
  **No se juzga ni se cuestiona la objeción.**
- **CIERRE — crítico:** **no** se pide un mini-plan de 3 pasos para las próximas 24-72 horas. No lo
  va a hacer y se va a sentir mal. **Una sola idea mental.**

> `[RESOLVER CON SANTI]` Este tipo choca con el anti-patrón 10 de `playbooks/agente-copy.md`
> ("nunca se ataca una objeción de frente: se mata con la historia de un caso") y con el 14 de
> `playbooks/agente-historias.md` (se convierte en enemigo externo). En VSL el formato pide poner
> la objeción textual en su boca. **Antes de escribir un TIPO 2 se pregunta cuál regla manda.**

### TIPO 3 — MECANISMO ÚNICO / YOUTUBE · 8-15 min

```
[HOOK]               Promesa específica + curiosidad
[SETUP PROBLEMA]     El status quo roto del nicho
[REVEAL MECANISMO]   El mecanismo único con nombre propio
[DEMO / EXPLICACIÓN] Profunda, 2-4 componentes
[CASOS DE ÉXITO]     1-2 casos anclados
[SOFT CTA]           Recurso, suscripción, freebie — no venta dura
```

### TIPO 4 — CHAT · 15-25 min
Columna vertebral del TIPO 1, con: más historia personal del referente, más detalle en la oferta
(precio, plan de pago, garantías), CTA cálido, y tangentes permitidas.

### TIPO 5 — THANK-YOU PAGE · 1-3 min

```
[CONFIRMACIÓN]      "Listo, quedaste agendado"
[QUÉ ESPERAR]       Del próximo paso
[REDUCIR ANSIEDAD]  Sacar el miedo a la llamada
[PRE-SETUP MENTAL]  Una idea para llevarse — NO tareas antes de la call
[REFORZADOR]        Emocional + scarcity suave
```

---

## 8. Principios universales del copy

1. **Voz del referente, no del marketer.** El VSL lo lee Manu en cámara. Su pronombre, sus
   muletillas, su ritmo. **Test: si lo lee y dice "yo nunca hablaría así", está mal.**
2. **Cero quotes inventados.** Frase atribuida a alguien real = frase que existe **textual** en un
   testimonio. Si se quiere un concepto sin testimonio, se dice como reflexión del referente, sin
   atribuir.
3. **Avatar realista, no caricatura.** El que paga es el **Avatar 2**: se esfuerza pero no es
   extremo, ya invirtió en soluciones aisladas, no obtuvo resultados, sigue buscando. No es el 1%
   más comprometido.
4. **Específico siempre, general nunca.** Un día específico, una situación específica, un número,
   una persona con nombre. Si suena a tagline de marketing, se reescribe.
5. **Se acorta agresivamente.** Si una sección se puede sacar y se entiende igual, se saca. **La
   duración no es valor; la atención sostenida sí.**
6. **El mecanismo único aparece cuando el que mira lo necesita, no en el hook.** Recorrido: premise
   del nicho → círculo causa-efecto → auditoría de intentos pasados → el insight ("siempre faltó
   X") → reveal del mecanismo. **Lo recibe como respuesta, no como pitch.**
7. **CTA con 3 elementos:** qué tiene que hacer (acción concreta) + qué dolor está solucionando
   (callback) + consecuencia de no hacerlo (costo de la inacción).
8. **Future pacing sensorial.** Si se pinta el "después": día concreto, situación cotidiana,
   sensación concreta, decisión concreta. Nunca "vas a sentirte pleno".
9. **Scarcity real, no fake.** Solo si la fecha, el cupo, el bonus o el precio son realmente eso.
10. **Anti-guru.** Sin motivación vacía, sin disclaimers innecesarios.
11. **2-3 frases quotables por VSL:** antítesis ("X no. Y, sí."), inversión de causalidad ("No es
    que X, es que Y"), o un reveal corto que cierra una idea grande.

La regla de **"programa"** (no se usa antes del bloque de oferta; se camufla con mecanismo,
sistema, método, proceso, abordaje) ya es el anti-patrón 6 de `playbooks/agente-copy.md`.

---

## 9. Reglas de cadencia — el sustituto de leer en voz alta

1. **Ninguna oración de más de 25 palabras sin punto.** Si pasa, se parte.
2. Cada párrafo tiene al menos **una oración corta de respiración** (3-7 palabras).
3. Cada bloque **cierra con una frase corta y declarativa**, no con una subordinada larga.
4. Si hay **3 oraciones seguidas con la misma estructura**, se rompe el patrón.
5. Las explicaciones de mecanismo van en **bullets numerados**, no en prosa larga.
6. Las **frases quotables ocupan línea propia**, con línea en blanco antes y después.
7. Transiciones entre bloques con **frase puente corta** ("Pero antes…", "Y por eso…").

Antes de entregar se lee el VSL mentalmente **simulando a Manu en cámara**. Se pasa 2-3 veces más
por el **HOOK**, el **CTA** y la presentación del **mecanismo** y la **oferta** que por el resto.
Es la misma lectura en modo NPC del resto del sistema: **si algo te hace ruido a vos, al que mira
también.**

---

## 10. Anclaje de casos a testimonios reales

1. Antes de escribir, se leen **todos** los testimonios disponibles.
2. Se **mapean los sub-segmentos** del avatar (perfiles × dolores × deseos).
3. Se **asigna cada testimonio** al sub-segmento que cubre. Los casos no son random: son la
   justificación lógica de lo que se dice.
4. Se **identifican gaps**: sub-segmentos que ningún testimonio cubre. Se avisa para grabar uno, o
   se deja ese sub-segmento afuera **conscientemente**.
5. En el **header del VSL** se lista cada caso referenciado con su fuente (link).
6. En cada `[INSERT TESTIMONIO X]` se especifica **nombre + fuente + frase exacta**.

**Si no hay testimonios suficientes: no se inventa.** Se dice que la calidad va a sufrir y se
sugiere grabar. Si aun así se pide avanzar, se usan patrones generales **declarados como tales**
("esto es un patrón que veo todo el tiempo"), nunca frases atribuidas a personas falsas.

El orden de prueba de Génesis (de `playbooks/agente-copy.md`): **José, el caso principal** → caso
real pasado explícitamente → el tablero de Manu (2.200 activos, 1,28% de churn) → prueba de mercado
o competencia → `[FALTA CASO REAL]`.

**Cómo se mapea José hoy.** Cubre el sub-segmento del que ya migró y sostiene el modelo, y prueba
el mecanismo completo. **No cubre el rango 30-80M**: ese es el gap real, y es el que van a cerrar
las 3 validaciones. Se declara así en el header del VSL, no se disimula. En un VSL largo, José
puede ocupar el caso profundo del bloque PRUEBA con un ángulo, y otro ángulo suyo puede volver en
el bloque OBJECIÓN o ELEGIBILIDAD — **ángulos distintos, no el mismo relato dos veces**.

---

## 11. Tabla de calibración — se llena antes de escribir

| Variable | Valor para este VSL |
|---|---|
| Tipo de VSL | Landing / Objeciones / YouTube / Chat / Thank-you |
| Nicho | |
| Nivel de conciencia del avatar | |
| Ticket | Low / Mid / High / Premium |
| Nivel de miedo → duración | Bajo (8-12 min) / Medio (15-20) / Alto (20-30) |
| Objetivo | Agendar / Comprar / Opt-in / Reactivar / Upsell |
| Marco global | |
| Big Idea | |
| Big Problem | |
| Voz / tono del referente | |
| Teleprompter o improvisa | palabra por palabra / beats |
| Mecanismo único en 1 frase | |
| Piezas del mecanismo que entran | |
| Avatar 2 en 1 párrafo | |
| Casos disponibles mapeados a sub-segmentos | |
| Gaps de prueba | |
| Scarcity real | Sí (cuál) / No (no se usa) |
| Contexto del funnel | |

**Si alguna celda está vacía, no se empieza a escribir: se pide el input.**

---

## 12. Checklist anti-vacíos — se devuelve siempre antes de cerrar

Un vacío narrativo es una rotura que hace perder atención o coherencia. Se devuelve esto:

- **Conceptos no explicados** (términos o siglas que el avatar no entiende sin contexto):
  [lista o "ninguno"]
- **Dolores sin tocar** (de los que están en `contexto/Avatar-Genesis.md`):
  [lista o "todos cubiertos"]
- **Objeciones sin pre-empt:** [lista o "todas pre-emptidas"]
- **Gaps de prueba** (sub-segmentos que ningún testimonio cubre): [lista o "cubiertos"]

Si hay gaps: se recomienda **la acción concreta** para cerrar cada uno.

---

## 13. Formato del output

- Markdown estructurado, **un bloque por sección del VSL**.
- **Header** con la tabla de calibración completa + lista de casos referenciados con sus fuentes.
- Guión en **bloques de cita (`>`)** para leerlo o grabarlo directo.
- Marcadores `[INSERT TESTIMONIO X]` donde van los clips, con nombre + fuente + frase exacta.
- **Si el referente improvisa** en vez de leer teleprompter: se entrega **en beats** (bullets con
  la intención de cada momento), no palabra por palabra.
- Al final, dos listas: **QUÉ GRABAR** (bloques que requieren cámara y en qué escenario) y
  **DATOS FALTANTES** (números o materiales a confirmar antes de publicar).
- Tono: directo, sin floritura, voseo argentino. Anti-guru. Cada frase concreta: un día, una
  persona, un número.

---

## 14. Checklist de calidad antes de entregar

- La **tabla de calibración** está completa.
- **Marco global, Big Idea y Big Problem** resueltos y validados.
- El **tipo de VSL** es el correcto para el contexto del funnel.
- La **estructura por bloques** del tipo elegido está completa.
- (Landing) El **HOOK tiene los 6 elementos**.
- El **mecanismo aparece cuando hace falta**, no en el hook.
- **Cada caso anclado a un testimonio real con fuente.** Cero quotes inventados.
- Los casos **mapean los sub-segmentos** del avatar.
- El **CTA tiene los 3 elementos**.
- **"Programa" no aparece antes de la oferta.**
- **Específico siempre:** ningún día, persona o número genérico.
- **Reglas de cadencia** aplicadas.
- **Un solo pronombre** — voseo, sin mezclar.
- **Números canónicos exactos** (`playbooks/agente-copy.md`, sección 6).
- **Techo y punto operativo juntos** si aparece la cuenta del CPA.
- **Scarcity real, o no se usa.**
- **Checklist anti-vacíos** pasado y devuelto.
- **La voz es la de Manu**, no la del marketer.

---

## 15. Anti-patrones — lo que NUNCA se hace

Además de los 11 de `playbooks/agente-copy.md`:

1. **NUNCA se escribe sin calibrar las variables.** Si falta un dato, se pide.
2. **NUNCA se inventan quotes ni casos.** Frase atribuida = frase textual de un testimonio real.
3. **NUNCA se pinta al avatar como el 1% extremo.** El que paga es el Avatar 2.
4. **NUNCA future pacing abstracto** ("vas a sentirte pleno", "vas a ser tu mejor versión").
5. **NUNCA se adelanta el mecanismo como pitch** antes de que el que mira lo necesite.
6. **NUNCA scarcity inventada.** Sin marco real, el VSL no usa urgencia.
7. **NUNCA se piden tareas imposibles en el cierre** (mini-planes de 3 pasos para las próximas
   72 horas). Una sola idea mental.
8. **NUNCA se anuncia la estructura del video** ("te voy a presentar esto en orden de importancia").
9. **NUNCA se ignora el nivel de conciencia.** Un DOLOR largo a alguien listo para comprar mata la
   conversión.
10. **NUNCA se copia el tono de un nicho a otro.** Génesis es B2B: lógica, riesgo, resultado
    medible. No emoción abierta ni lenguaje íntimo.
11. **NUNCA casos de éxito random** sin mapear sub-segmentos del avatar.
12. **NUNCA se entrega sin pasar el checklist anti-vacíos.**
13. **NUNCA se entrega el VSL entero sin los checkpoints previos** (inputs → calibración →
    producción).

---

## 16. Pendientes

- **El OK de José** para usar sus números en público. Es el caso principal de todo el contenido:
  es el bloqueo más barato de levantar y el que más desbloquea.
- **Los ángulos de José por pieza del método** (`[CONFIRMAR MANU]` en `contexto/Personaje.md`).
  Sin el dato real de cada frente, el ángulo no se escribe.
- **Casos dentro del rango 30-80M.** Es lo único que José no cubre. Cuando lleguen las 3
  validaciones, **suman** a José en el montaje de sub-segmentos; no lo reemplazan.
- **La regla de la objeción.** El TIPO 2 choca con el anti-patrón 10 del Agente Copy y el 14 del
  Agente Historias. Falta definir cuál manda. `[RESOLVER CON SANTI]`
- **La calculadora de tres escenarios.** Es lo que se ve en pantalla y lo que hace la venta en el
  Escenario 3. **Hoy no existe.** Sin ella, el VSL de pantalla compartida no se puede producir.
- **Marco global.** En fase de validación no hay fecha ni cupos. Cuando exista (cohorte, cierre,
  webinar), se define acá y los VSLs lo usan.
- **Nivel de conciencia del tráfico** que llega al video largo. No está medido. Hasta que lo esté,
  se pregunta en cada pieza.
