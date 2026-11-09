---
name: kit-anuncio-evento
description: Usa esta skill cuando el usuario pida preparar la comunicación de un evento, webinar o sesión (anuncio de Teams, correo o post interno) a partir de un brief. No la uses para notas de prensa ni contenido comercial.
---

# Kit de anuncio de evento

## Entrada esperada
Un brief (Word o texto) con: nombre del evento, fecha, hora y zona horaria, formato, público, enlace de registro y ponentes.

## Proceso
1. Lee el brief y extrae los datos en una tabla "Dato | Valor | ¿Confirmado?".
2. Si falta algún dato obligatorio o el brief lo marca como "sin confirmar" o "sin decidir", NO lo inventes: márcalo como [PENDIENTE] y lístalo al final.
3. Aplica la guía de estilo de `references/guia-estilo.md`. Si el brief incluye su propia guía de estilo, prevalece la del brief.
4. Genera los entregables usando `templates/plantilla-kit.md`:
   - Anuncio para Teams (máximo 80 palabras).
   - Correo (asunto + máximo 150 palabras).
   - Post interno para Viva Engage (máximo 120 palabras, máximo 3 hashtags).
5. Separa claramente HECHOS (vienen del brief) de PROPUESTAS (redacción tuya).

## Reglas
- Nunca envíes ni publiques nada: solo prepara borradores.
- Incluye siempre la zona horaria junto a la hora, o [PENDIENTE] si no está confirmada.
- Termina con la lista de datos pendientes.
