# 💬 Pronteca · Librería de prompts reutilizables

Colección de prompts que funcionan bien, organizados por tarea. Copia, adapta y usa.

> 💡 Un buen prompt suele tener 4 piezas: **rol · tarea · contexto · formato**.

## 📇 Índice por tarea

| Tarea | Prompt de ejemplo |
|---|---|
| ✍️ Redactar | Ver abajo · "Borrador de correo" |
| 📄 Resumir | Ver abajo · "Resumen accionable" |
| 📊 Analizar datos | Ver abajo · "De la tabla al insight" |
| 🎨 Visualizar | Ver abajo · "Infografía en HTML" |

---

### ✍️ Borrador de correo
```
Actúa como [rol]. Redacta un correo para [audiencia] sobre [tema].
Contexto: [detalles clave]. Tono: [cercano / formal]. Longitud: máx. 10 líneas.
Incluye un asunto claro y una llamada a la acción.
```

### 📄 Resumen accionable
```
Resume el siguiente texto en 5 puntos clave y una lista de tareas con responsable
y fecha si aparecen. Marca lo urgente. Texto: [pega aquí].
```

### 📊 De la tabla al insight
```
Analiza estos datos y dime las 3 tendencias más relevantes en lenguaje natural,
sin fórmulas. Señala cualquier valor atípico. Datos: [pega tabla / CSV].
```

### 🎨 Infografía en HTML
```
Genera el código de una infografía en HTML que visualice estos datos, con diseño
moderno, tarjetas visuales y tipografía limpia. Datos: [pega aquí].
```

---

## ➕ Añadir tu prompt
Crea un archivo `mi-prompt.md` en esta carpeta con: **título**, **para qué sirve**,
**el prompt** (en bloque de código) y **dónde usarlo**.
