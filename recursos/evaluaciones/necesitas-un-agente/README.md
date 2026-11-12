# ¿Necesitas realmente un agente?

[Español](README.md) · [English](README.en.md)

**Traduciendo la IA · Adrián Espés · Microsoft MVP · M365 Copilot**

Herramienta interactiva y orientativa para reflexionar antes de crear un agente. Acompaña al carrusel *El primer error al crear un agente*.

> Primero la necesidad. Después el agente. Y solo entonces, la herramienta.

## Abrir la herramienta

**[Iniciar «¿Necesitas realmente un agente?»](https://aespese29.github.io/ia-toolbox/recursos/evaluaciones/necesitas-un-agente/)**

Se abre directamente en el navegador mediante GitHub Pages. No necesitas instalar nada ni iniciar sesión. También puedes [consultar el archivo fuente `index.html`](./index.html) y abrirlo en local: es un único archivo autónomo, con el isotipo y la caricatura incrustados en base64.

## Privacidad por diseño

- Funciona **solo en el navegador**. No hay servidor, ni analítica, ni cookies, ni almacenamiento local.
- **No guarda ni envía** ninguna respuesta. Al cerrar o recargar la página, todo se borra.
- **No hay campos de texto libre**: todas las respuestas son de opción cerrada.
- **No pide información confidencial**: solo los datos mínimos para dar la orientación.
- El resultado es una **orientación para ayudar a pensar**, no una recomendación definitiva. No nombra productos concretos.

## Preguntas (9, de opción cerrada)

| # | Pregunta | Opciones |
|---|---|---|
| 1 | ¿Qué tarea quieres mejorar? | Buscar o consultar información · Responder preguntas que se repiten · Resumir o analizar contenido · Guiar a alguien en un proceso · Ejecutar acciones en otros sistemas · Todavía no lo tengo claro |
| 2 | ¿Quién realiza actualmente esa tarea? | Yo · Mi equipo · Otras áreas o muchas personas · No lo sé |
| 3 | ¿Con qué frecuencia se repite? | Varias veces al día · Varias veces por semana · De forma ocasional · No lo sé |
| 4 | ¿Necesita consultar información concreta? | Sí · No · No lo sé |
| 5 | ¿Esa información cambia con frecuencia? | Sí · No · No lo sé |
| 6 | ¿Necesita mantener una conversación con el usuario? | Sí · No · No lo sé |
| 7 | ¿Debe ejecutar acciones en otros sistemas? | Sí · No · No lo sé |
| 8 | ¿Qué resultado esperas obtener? | Ahorrar tiempo · Respuestas más consistentes · Cometer menos errores · Que más personas accedan a la información · No lo sé |
| 9 | ¿Cómo medirías su utilidad? | Tiempo dedicado a la tarea · Consultas o tareas resueltas · Calidad o número de errores · Satisfacción de quien lo usa · No lo sé |

## Lógica de orientación (en este orden)

1. **La necesidad todavía no está suficientemente definida**: si la P1 es «Todavía no lo tengo claro» o la P8 o la P9 es «No lo sé».
2. **La necesidad apunta a un agente con acciones o integraciones**: si la P7 es «Sí» o la P1 es «Ejecutar acciones».
3. **La necesidad apunta a un agente centrado en conocimiento**: si la P4 es «Sí».
4. **Puede que un buen prompt reutilizable sea suficiente**: si la P6 es «Sí».
5. **Quizá basta con mejorar el proceso o usar una plantilla**: en el resto de casos.

**Aviso adicional «Datos, permisos y gobierno»**, que se suma a cualquier resultado cuando:

- la P5 es «Sí» (la información cambia con frecuencia);
- debe ejecutar acciones en otros sistemas;
- la P2 es «Otras áreas o muchas personas».

Si hay respuestas «No lo sé» en las P4, P6 o P7, el resultado lo indica y recomienda aclararlas.

## Pantalla de resultado

- La orientación, con su etiqueta y una breve explicación.
- **¿Por qué esta orientación?**: las respuestas que la han provocado.
- El aviso de datos, permisos y gobierno, cuando aplica.
- **La siguiente pregunta que conviene hacerte**.
- El cierre: *Primero la necesidad. Después el agente. Y solo entonces, la herramienta.*

## Diseño y accesibilidad

- Colores de marca: `#075E63` petróleo · `#F2544B` coral · `#123238` azul noche · `#FAFBF9` fondo.
- Tipografía: Manrope (títulos) e Inter (texto), si están instaladas; si no, se usa la fuente del sistema. No carga recursos externos.
- Una pregunta por pantalla, barra de progreso, botones «Anterior» y «Siguiente», y «Revisar respuestas» desde el resultado.
- Controles nativos (radio buttons), navegable con teclado, foco visible, `aria-live` en los cambios, adaptado a móvil (desde 320 px) y respeta `prefers-reduced-motion`.

## Recursos relacionados

- 🧭 [¿Prompt, agente o skill?](../../prompt-agente-skill/) — cuando ya tienes clara la necesidad y quieres generar el artefacto.
- 🧩 [Plantilla SKILL.md en 6 bloques](../../plantilla-skill-md/) — para definir la tarea una vez decidido el enfoque.

---

**Adrián Espés** · Microsoft MVP · M365 Copilot  
[adrianespes.com](https://adrianespes.com)

**Versión:** 1.0
