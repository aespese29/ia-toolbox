# 🧭 ¿Prompt, Agente o Skill? — Decide y genera el artefacto

[Español](README.md) · [English](README.en.md)

Herramienta interactiva para resolver la duda de siempre: ¿esto lo resuelvo con un **prompt**, con un **agente** o con una **Skill**? Responde tres preguntas, elige el enfoque y la herramienta **te genera el artefacto listo para pegar en Copilot**.

## 🚀 Empezar

👉 **[Abrir el recurso](https://aespese29.github.io/ia-toolbox/recursos/prompt-agente-skill/)**

## 🧩 Qué te pide y qué te devuelve

| Si eliges | Te pide | Te devuelve |
|---|---|---|
| 💬 **Prompt** | Rol, tarea, contexto, formato de salida y restricciones | Un prompt estructurado para Copilot Chat |
| 🤖 **Agente** | Propósito, responsabilidades, conocimiento, límites y skills | Las instrucciones del agente en Markdown y el prompt en lenguaje natural para Agent Builder |
| 📦 **Skill** | `name`, `description`, pasos, reglas y formato de salida | Un `SKILL.md` válido con su frontmatter y el árbol de carpetas |

Todo lo que generas se puede **copiar al portapapeles** o **descargar en Markdown**.

## 🤔 Las tres preguntas

1. **¿Lo harás una sola vez?** → Prompt
2. **¿Se repite y debe salir siempre igual?** → Skill
3. **¿Es un rol con varias tareas, conocimiento propio y público?** → Agente + Skills

> Regla práctica: un agente nuevo por responsabilidad; una skill por tarea dentro de esa responsabilidad.

## 📐 Estructura obligatoria de una Skill

La herramienta valida y respeta la anatomía mínima:

```text
kit-anuncio-evento/
  ├─ SKILL.md                    ← obligatorio
  ├─ references/guia-estilo.md     (opcional)
  └─ templates/plantilla-kit.md    (opcional)
```

El `SKILL.md` empieza **siempre** con frontmatter YAML entre `---` y dos campos obligatorios:

- **`name`** — en minúsculas y kebab-case (la herramienta lo normaliza por ti).
- **`description`** — decide **cuándo se activa** la skill. Di cuándo usarla y cuándo **no**.

## 🔗 Recursos relacionados

- 🧩 [Plantilla SKILL.md en 6 bloques](../plantilla-skill-md/) — la guía conceptual detrás de este generador.
- 🎓 [Sesión: Cómo las Skills convierten Copilot en un verdadero compañero de trabajo](../../sessions/skills-copilot-companero-de-trabajo/) — la charla completa, con el kit de demos.

## 🛠️ Detalles técnicos

- Un **único archivo HTML**, sin dependencias ni backend. Descárgalo y funciona sin conexión.
- El logo va embebido en base64; las tipografías (Manrope e Inter) se cargan desde Google Fonts, con Arial de reserva.
- Los datos que introduces **no salen de tu navegador**: no hay analítica ni envío a ningún servidor.

---

**Adrián Espés** · Microsoft MVP · Microsoft 365 Copilot · [adrianespes.com](https://adrianespes.com)
