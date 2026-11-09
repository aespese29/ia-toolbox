---
name: analisis-inscripciones-evento
description: Usa esta skill en Excel cuando el usuario pida analizar, limpiar o resumir las inscripciones de un evento o webinar (registros, asistentes inscritos, canal de origen). No la uses para presupuestos, ventas ni datos financieros.
---

# Análisis de inscripciones de evento

## Objetivo
Convertir una lista de inscripciones con errores en un resumen fiable y siempre con la misma estructura, sin tocar los datos originales.

## Proceso
1. No modifiques la hoja original de inscripciones. Trabaja siempre en hojas nuevas.
2. Crea la hoja **Datos_limpios** con una copia normalizada:
   - País y canal de origen con un único valor por categoría ("españa", "ES" o "Spain" pasan a "España"; "Linkedin" pasa a "LinkedIn"; "Email" o "Mail" pasan a "Correo").
   - Fechas guardadas como texto convertidas a fecha.
   - Duplicados (mismo email, nombre y apellidos) excluidos; se conserva la primera aparición.
3. Crea la hoja **Incidencias**: ID | Campo | Valor original | Incidencia | Acción.
4. Crea la hoja **Resumen evento** con:
   - Datos del evento.
   - Indicadores: filas en origen, duplicados excluidos, inscripciones únicas, objetivo, % sobre objetivo, ocupación del aforo e incidencias.
   - Reparto por canal de origen, país y nivel de Copilot (recuento y %).
   - Gráfico de barras por canal de origen.
   - Bloque final "Datos pendientes".
5. Usa fórmulas que apunten a Datos_limpios, no valores escritos a mano.

## Reglas
- No inventes datos. Si falta un email, un departamento o un dato del evento (por ejemplo, la zona horaria), escribe [PENDIENTE] y añádelo a "Datos pendientes".
- No borres filas con datos ausentes: se registran en Incidencias.
- Los emails con formato no válido se registran, pero no se corrigen por intuición.
- Porcentajes con un decimal.

## Antes de terminar
Comprueba que cada tabla de reparto suma las inscripciones únicas y resume en el chat: inscripciones únicas, duplicados, incidencias y datos pendientes.
