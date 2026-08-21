# 🗂️ Mapa de la estructura del repo

```
ia-toolbox/
├── index.html              → Hub visual (portada web con GitHub Pages)
├── README.md               → Portada del repo (lo primero que se lee)
├── CONTRIBUTING.md         → Cómo colaborar
├── LICENSE                 → CC BY 4.0 (contenido) + MIT (código)
├── ESTRUCTURA.md           → Este mapa
├── .gitignore
├── .github/
│   └── workflows/
│       └── static.yml      → Publica la web automáticamente (Static HTML)
├── agentes/                → 🤖 Agentes de Copilot Studio
│   ├── README.md           → Índice de agentes
│   ├── formatia/           → Agente FormatIA
│   └── m365-soporte-usuario/ → Agente Soporte Usuario
├── prompts/                → 💬 Pronteca (librería de prompts)
│   └── README.md
├── tutoriales/             → 📚 Guías paso a paso
│   ├── README.md
│   └── como-publicar-en-github-pages.md
├── recursos/               → 📦 Herramientas, infografías y descargables
│   ├── README.md           → Índice de recursos
│   ├── evaluaciones/       → Herramientas interactivas de diagnóstico
│   │   ├── README.md
│   │   └── evaluacion-preparacion-m365-copilot/
│   │       ├── README.md
│   │       ├── index.html
│   │       └── banner-*.png
│   └── infografias-m365/   → Infografías de novedades M365
│       ├── README.md
│       └── MC1443523-planner-copilot-chat/
│           ├── README.md
│           ├── *.png
│           └── *.pdf
├── sessions/               → 🎓 Webinarios y sesiones educativas
│   └── README.md
└── assets/                 → 🖼️ Logos, imágenes y CSS compartido
    ├── README.md
    ├── css/estilo-base.css
    └── img/README.md       → aquí va tu banner.png
```

## Criterio de organización

- **Por tipo de contenido**, no por tema. Fácil de recorrer y de crecer.
- Cada sección tiene su **README** que explica qué va dentro.
- Nombres de archivo en **minúsculas y con guiones**.
- Recursos estáticos siempre en `/assets`.
- `/recursos` agrupa herramientas interactivas, infografías y material descargable.

## Cambios recientes (v2.0)

- ✅ Eliminada carpeta `/htmls` (contenía solo ejemplos)
- ✅ Consolidado todo en `/recursos` con subcarpetas por tipo
- ✅ Normalizado `/infografias-m365` dentro de `/recursos`
- ✅ Agregada referencia a `/sessions` para webinarios y eventos

## Cómo activar la web (GitHub Pages)

1. Sube el repo a GitHub (público) con el nombre `ia-toolbox`.
2. Settings → Pages → Source: **GitHub Actions** → plantilla **Static HTML** → Commit.
3. Al hacer push a `main`, se publica en:
   **https://aespese29.github.io/ia-toolbox/**
