---
name: crear-agente
description: Crear un agente especializado para mi ecosistema mediante una entrevista profunda. El agente hace TODAS las preguntas necesarias para construir un CLAUDE.md + playbook completo. Activar cuando yo diga crear agente, nuevo agente, quiero un agente para X, o /crear-agente.
argument-hint: "[nombre-del-agente]"
---

# Crear Agente — Entrevista Profunda

## Propósito
Construir agentes especializados para mi ecosistema. Cada agente se crea a través de una entrevista donde yo cargo toda la información, criterio y conocimiento. El agente NUNCA inventa — todo sale de lo que yo digo.

## Flujo completo

### FASE 1: Contexto inicial
Preguntar:
1. Nombre del agente — "¿Cómo se llama esta funcionalidad? (ej: creador-de-emails, analizador-de-llamadas)"
2. Qué hace — "Explicame en tus palabras qué tiene que hacer este agente. Como si se lo explicaras a un empleado nuevo."
3. Para quién — "¿Quién va a usar este agente? Vos, tu equipo, o un cliente directo?"
4. Input típico — "¿Qué le vas a pasar al agente? (ej: transcript, brief, descripción, screenshot)"
5. Output esperado — "¿Qué tiene que entregar? Describime el output ideal."

### FASE 2: El conocimiento (la más importante)
6. Tu proceso — "Si vos hicieras esto a mano, ¿cuáles son los pasos exactos? Enumeralos."
7. Criterio de calidad — "¿Cómo distinguís un output bueno de uno malo? Dame ejemplos concretos."
8. Errores comunes — "¿Qué errores se cometen frecuentemente al hacer esto? ¿Qué NO debería hacer el agente?"
9. Frameworks o estructuras — "¿Tenés algún framework, plantilla, o estructura que uses? Si sí, pasala."
10. Ejemplos reales — "¿Tenés un ejemplo de un output que consideres 10/10? Pasalo."
11. Variaciones — "¿Hay distintos tipos o variaciones de este output?"
12. Dependencias — "¿Este agente necesita información de otro agente o proceso previo?"

### FASE 3: Personalización
13. Datos que necesita — "¿Qué datos míos o de mi cliente necesita el agente para personalizar el output?"
14. Tono — "¿En qué tono tiene que hablar/escribir? ¿Hay algo que NUNCA debería decir?"

### FASE 4: Iteración
15. ¿Algo más? — "¿Hay algo que no te pregunté y que es importante para que este agente sea épico?"

Después de cada respuesta, si es vaga o incompleta, REPREGUNTAR con ejemplos concretos. No avanzar hasta tener una respuesta sólida. Si digo "no sé" o "lo que vos creas", insistir: "Necesito tu criterio real. Si no me lo das, el agente va a inventar y no va a ser bueno."

## Qué se genera al final

### 1. Playbook (playbooks/[NOMBRE].md)
Qué es y para qué sirve. El framework paso a paso. Criterio de calidad. Anti-patrones (lo que NO hacer). Ejemplos si los di. Variaciones si existen.

### 2. Agente (agentes/[nombre]/CLAUDE.md)
Rol en 1 párrafo. "Solo actúa cuando yo lo pido" (siempre). Qué leer antes de empezar (playbook + feedbacks). Input que necesita. Proceso paso a paso. Formato del output. Después de entregar: guardar en templates/ o feedback/ según corresponda. Reglas y restricciones.

### 3. Actualizar el CLAUDE.md raíz
Agregar el agente nuevo a la tabla de agentes activos.

## Reglas de la entrevista
- NUNCA saltear preguntas
- NUNCA asumir respuestas — todo sale de mí
- Si doy respuestas largas, resumir y confirmar: "Entendí que [X]. ¿Está bien?"
- Preguntar de a una o dos, no tirar las 15 de golpe
- Al final, mostrar un preview del agente antes de guardarlo
- Hablar en el idioma y tono que yo use
