# Evaluación de preparación para Microsoft 365 Copilot

Descubre si tu organización necesita seguir preparándose, está lista para iniciar un piloto controlado o dispone de las condiciones necesarias para ampliar el despliegue de Microsoft 365 Copilot.

> **Evaluación orientativa basada en requisitos, guías y recomendaciones oficiales de Microsoft.**  
> No constituye una certificación oficial, una auditoría técnica ni una validación automática de la configuración del tenant.

## Abrir la evaluación interactiva

**[Iniciar ahora la evaluación de preparación para Microsoft 365 Copilot](https://aespese29.github.io/ia-toolbox/recursos/evaluacion-preparacion-m365-copilot/)**

La evaluación se abre como una aplicación web mediante GitHub Pages. No necesitas instalar aplicaciones, descargar archivos ni iniciar sesión.

Si el enlace anterior todavía no muestra la evaluación, comprueba que este recurso se haya publicado exactamente con esta estructura y nombres, respetando mayúsculas y minúsculas:

```text
recursos/
└── evaluacion-preparacion-m365-copilot/
    ├── README.md
    └── index.html
```

También puedes [consultar el archivo fuente `index.html`](./index.html) desde esta carpeta. Este segundo enlace muestra el archivo dentro de GitHub; para utilizar la evaluación renderizada, usa siempre el botón **Iniciar ahora la evaluación**.

## Qué permite evaluar

El recurso analiza el estado de preparación en cinco dimensiones:

1. **Estrategia y liderazgo**  
   Objetivos, patrocinio ejecutivo, equipo responsable, alcance y criterios de éxito.

2. **Preparación técnica**  
   Licenciamiento, identidad, Exchange Online, aplicaciones compatibles, canales de actualización y conectividad.

3. **Seguridad, datos y cumplimiento**  
   Permisos, acceso a la información, protección de datos, auditoría y controles de cumplimiento.

4. **Adopción y casos de uso**  
   Grupo piloto, escenarios prioritarios, champions, formación, comunicación, comunidad y soporte.

5. **Medición y mejora continua**  
   Métricas, feedback, revisión de licencias, casos de éxito y criterios para ampliar el despliegue.

La preparación para crear y desplegar agentes se presenta como un **módulo complementario**. No reduce la puntuación de una organización que quiera comenzar con Microsoft 365 Copilot sin crear agentes todavía.

## Cómo funciona

Cada comprobación ofrece cuatro respuestas cerradas:

- **Verificado:** la comprobación está completada y existe evidencia suficiente.
- **En curso:** se está trabajando en ella, pero todavía no está completada.
- **No iniciado:** no se ha comenzado o no existe una decisión al respecto.
- **No aplica:** la comprobación no corresponde al alcance de la evaluación y se excluye del cálculo.

La evaluación utiliza únicamente estas selecciones para calcular el resultado. No solicita datos de configuración, documentos ni información identificativa.

## Modelo de puntuación

La puntuación se calcula de forma orientativa:

- **Verificado:** 2 puntos.
- **En curso:** 1 punto.
- **No iniciado:** 0 puntos.
- **No aplica:** se excluye del cálculo.

```text
Puntuación = puntos obtenidos / puntos posibles aplicables × 100
```

Los requisitos imprescindibles funcionan como **controles de bloqueo**. Una puntuación general alta no compensa un requisito crítico sin resolver.

Por ejemplo, si la organización obtiene una puntuación elevada, pero no ha verificado un requisito esencial de licenciamiento, identidad o preparación técnica, el resultado indicará que todavía existe un bloqueo para iniciar el piloto.

## Estados de preparación

### Requiere preparación

Existe al menos un requisito imprescindible sin resolver. El resultado identifica los bloqueos y las acciones prioritarias.

### Preparación en curso

Los requisitos básicos están parcialmente cubiertos, pero todavía faltan elementos relevantes para iniciar un piloto controlado.

### Preparada para piloto

Los requisitos esenciales están verificados y la organización dispone de un equipo responsable, un grupo piloto, casos de uso iniciales, formación, soporte y métricas para evaluar el piloto.

### Preparada para ampliar

El piloto ha generado resultados y feedback, y la organización dispone de seguimiento de uso, formación continua, gobierno periódico y criterios para ampliar licencias y escenarios.

> Los niveles y umbrales utilizados son criterios orientativos de IA Toolbox. Microsoft no publica una puntuación universal que certifique el nivel de preparación de una organización.

## Resultado de la evaluación

Al finalizar se muestra:

- Estado general de preparación.
- Puntuación orientativa.
- Resultado por dimensión.
- Número de bloqueos críticos.
- Comprobaciones pendientes.
- Acciones prioritarias recomendadas.
- Decisión orientativa sobre el siguiente paso.

## Informe de resultados

La evaluación permite generar una vista resumida con:

- el estado general;
- la puntuación orientativa;
- el resultado por dimensión;
- los bloqueos detectados;
- y las acciones prioritarias pendientes.

La opción **Guardar informe en PDF** abre la función de impresión del navegador. Desde ella puedes seleccionar **Guardar como PDF**.

El informe se genera localmente y se guarda únicamente en el dispositivo desde el que realizas la evaluación.

## Privacidad y tratamiento de la información

Esta evaluación está diseñada para funcionar completamente en el navegador.

- Las respuestas se procesan localmente mediante JavaScript.
- No se envían respuestas a ningún servidor.
- No se utilizan formularios externos, APIs ni bases de datos.
- No se utilizan cookies, `localStorage` ni `sessionStorage` para conservar las respuestas.
- No se integra ningún servicio de analítica en el recurso.
- No se solicitan nombres, correos electrónicos, dominios, archivos ni información identificativa.
- Las respuestas desaparecen al actualizar o cerrar la página.
- El recurso solo utiliza las selecciones necesarias para calcular el resultado orientativo.

### Información que no debes introducir ni compartir

No introduzcas ni compartas:

- Información confidencial de la organización.
- Datos personales o identificativos.
- Nombres de clientes, personas, proyectos o departamentos.
- Configuraciones internas de seguridad.
- Políticas, credenciales, claves o información de acceso.
- Documentos, capturas o contenidos corporativos.
- Detalles técnicos que puedan revelar la configuración del tenant.

La evaluación no necesita esa información. Solo debes seleccionar el estado que mejor represente cada comprobación.

## Privacidad del informe

El informe también se genera completamente en el navegador.

- IA Toolbox no recibe ni almacena el informe.
- El informe no se envía a ningún servicio externo.
- El PDF se guarda únicamente en el dispositivo de la persona usuaria.
- El informe no contiene datos identificativos porque la evaluación no los solicita.

## Alcance y limitaciones

El resultado no constituye:

- Una certificación oficial de Microsoft.
- Una auditoría técnica o de seguridad.
- Una evaluación de cumplimiento normativo.
- Una validación automática de la configuración del tenant.
- Una garantía de preparación para desplegar Microsoft 365 Copilot.

Para validar la configuración real de un entorno deben utilizarse las herramientas e informes oficiales de Microsoft y realizarse las revisiones técnicas, de seguridad, cumplimiento y adopción correspondientes.

## Complementa la evaluación con herramientas oficiales

La autoevaluación ayuda a ordenar decisiones y detectar áreas pendientes, pero no consulta la configuración del tenant.

Para completar la revisión técnica, Microsoft dispone de recursos como:

- El **Microsoft Copilot Readiness Report** del Centro de administración de Microsoft 365, que muestra elegibilidad técnica, licencias, canales de actualización y señales de uso de aplicaciones.
- El **Microsoft Copilot Optimization Assessment**, recomendado por Microsoft antes del despliegue para evaluar la madurez del gobierno de datos y los controles de seguridad.
- El **Automated Readiness Assessment for Microsoft 365 Copilot and Agents**, que analiza configuraciones reales mediante APIs y genera observaciones y recomendaciones priorizadas.

## Referencias oficiales

- [Microsoft Copilot Readiness Report](https://learn.microsoft.com/en-us/microsoft-365/admin/activity-reports/microsoft-365-copilot-readiness?view=o365-worldwide)
- [Microsoft Copilot adoption and onboarding guide for IT admins](https://learn.microsoft.com/en-us/microsoft-365/copilot/microsoft-365-copilot-enablement-resources)
- [Microsoft 365 Copilot adoption planning checklist](https://adoption.microsoft.com/en-us/copilot/essential-guide/plan/)
- [Microsoft 365 Copilot Adoption Playbook](https://www.microsoft.com/en-us/microsoft-365-copilot/copilot-adoption-guide)
- [Automated Readiness Assessment for Microsoft 365 Copilot and Agents](https://github.com/microsoft/m365-copilot-automated-readiness-assessment)

## Verificación técnica de cada versión

Antes de publicar una versión del HTML se revisará que:

- no transmita respuestas;
- no conserve respuestas en el navegador;
- no utilice cookies;
- no utilice almacenamiento local o de sesión;
- no contenga formularios de envío;
- no permita subir archivos;
- no integre servicios de analítica;
- no solicite información confidencial;
- y no necesite datos identificativos para calcular el resultado.

### Verificación de la versión 1.0

La versión 1.0 se ha revisado para confirmar que no transmite ni conserva respuestas, no utiliza cookies o almacenamiento del navegador, no contiene formularios de envío, no permite subir archivos y no integra servicios de analítica.

**Fecha de verificación técnica:** 20 de agosto de 2026.

## Archivos del recurso

```text
recursos/
└── evaluacion-preparacion-m365-copilot/
    ├── README.md
    └── index.html
```

- `README.md`: explicación, metodología, privacidad, alcance y referencias.
- `index.html`: evaluación interactiva lista para utilizar desde GitHub Pages.

## Uso y contribuciones

Este recurso forma parte de **IA Toolbox**, una colección de materiales prácticos sobre inteligencia artificial aplicada, Microsoft 365 Copilot y agentes.

Si detectas un punto que deba actualizarse o quieres proponer una mejora, puedes abrir una incidencia en el repositorio.

---

**Adrián Espés** · Microsoft MVP · M365 Copilot  
[adrianespes.com](https://adrianespes.com)

**Versión del recurso:** 1.0  
Última actualización: 20 de agosto de 2026

