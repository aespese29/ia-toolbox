---
name: nombre-de-tu-skill
description: Qué hace la skill y cuándo debe utilizarse. Incluye palabras clave que ayuden al agente a identificar las tareas relevantes. Máx. 1024 caracteres.
---

<!--
════════════════════════════════════════════════════════════════════
 PLANTILLA SKILL.md · IA Toolbox de Adrián Espés
 Basada en "¿Qué es SKILL.md y por qué usar skills de IA?"
 https://adrianespes.com/que-es-skill-md/
────────────────────────────────────────────────────────────────────
 CÓMO USARLA
 1. Copia esta plantilla dentro de una carpeta con el nombre de la skill.
 2. El archivo debe llamarse exactamente SKILL.md.
 3. El campo "name" debe coincidir con el nombre de la carpeta:
    minúsculas, números y guiones · sin guiones al inicio/final
    ni consecutivos · máx. 64 caracteres.
 4. Rellena los 6 bloques. Borra lo que no uses y estos comentarios.
 5. Mantén el archivo por debajo de 500 líneas; lo extenso, a references/.

   nombre-de-tu-skill/
   ├── SKILL.md        ← obligatorio
   ├── scripts/        ← opcional · código ejecutable
   ├── references/     ← opcional · documentación consultable
   └── assets/         ← opcional · plantillas y recursos

 ANTES DE EMPEZAR · ¿merece ser una skill?
 Marca las que se cumplan. Con varias, adelante:
 [ ] Se repite con frecuencia
 [ ] Sigue unos pasos reconocibles
 [ ] Usa reglas relativamente estables
 [ ] Necesita recursos similares en cada ejecución
 [ ] Produce un resultado claramente identificable
 [ ] Distingo un buen resultado de uno incompleto
 [ ] Requiere comprobaciones antes de finalizar
 [ ] Hoy necesita prompts muy largos o instrucciones repetidas
════════════════════════════════════════════════════════════════════
-->

# 1 · Objetivo

<!-- Qué resultado produce esta skill. Una o dos frases, sin ambigüedad. -->

Ejemplo: crear un resumen fiel al contenido proporcionado, sin añadir información externa.

# 2 · Cuándo utilizarla

<!-- Situaciones en las que aplica y, si ayuda, cuándo NO aplica. -->

- Se utiliza cuando: …
- No se utiliza cuando: …

# 3 · Contexto y fuentes

<!-- La información que puede usar y de dónde sale. Aquí evitas
     que la IA rellene huecos por su cuenta. -->

- Información de entrada necesaria: …
- Fuentes permitidas: …
- Fuentes no permitidas: …
- Si falta un dato: indicarlo expresamente, nunca deducirlo.

# 4 · Procedimiento

<!-- Los pasos, en orden. Numerados y accionables. -->

1. …
2. …
3. …
4. …
5. …

# 5 · Reglas, tono y formato de salida

## Reglas

<!-- Lo que siempre debe hacerse y lo que nunca debe hacerse. -->

- Utilizar únicamente la información proporcionada.
- No completar datos que no aparezcan en la fuente.
- …

## Excepciones

<!-- Casos particulares y cómo resolverlos. -->

- Si … entonces …

## Tono

<!-- Cómo debe sonar el resultado. Sé concreto: registro, trato, longitud. -->

- Registro: …
- Trato: …
- Evitar: …

## Formato de salida

<!-- La estructura exacta del entregable. -->

- Estructura: …
- Extensión: …
- Elementos obligatorios: …

# 6 · Comprobación final

<!-- Qué debe verificarse antes de entregar el resultado. -->

Antes de entregar el resultado:

- [ ] Todas las afirmaciones proceden de la fuente indicada.
- [ ] No se ha inventado ningún dato, fecha ni funcionalidad.
- [ ] Se han seguido todos los pasos del procedimiento.
- [ ] Se respetan el tono y el formato de salida definidos.
- [ ] …

<!--
────────────────────────────────────────────────────────────────────
 RECURSOS VINCULADOS (opcional)
 - scripts/      …
 - references/   …
 - assets/       …

 MEJORA CONTINUA
 Cuando detectes un error recurrente, actualiza la skill: añade una
 regla, documenta una excepción, mejora una comprobación, incorpora
 un ejemplo o cambia el orden del procedimiento. La mejora deja de
 vivir en una conversación y pasa a la capacidad reutilizable.
────────────────────────────────────────────────────────────────────
 IA Toolbox · Adrián Espés · Microsoft MVP Microsoft 365 Copilot
 adrianespes.com/que-es-skill-md/
-->
