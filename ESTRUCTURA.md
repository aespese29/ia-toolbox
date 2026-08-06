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
│   ├── _plantilla/         → Plantilla para nuevos agentes
│   └── redaccion-inclusiva/→ Agente de ejemplo (relleno)
├── htmls/                  → 🎨 Piezas HTML visuales
│   ├── README.md
│   ├── informes-visuales/  → ejemplo-informe.html
│   ├── infografias/        → ejemplo-infografia.html
│   └── plantillas/         → plantilla-base.html
├── prompts/                → 💬 Pronteca (librería de prompts)
│   └── README.md
├── tutoriales/             → 📚 Guías paso a paso
│   ├── README.md
│   └── como-publicar-en-github-pages.md
├── recursos/               → 📦 Cheat sheets, checklists, descargables
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

## Cómo activar la web (GitHub Pages)
1. Sube el repo a GitHub (público) con el nombre `ia-toolbox`.
2. Settings → Pages → Source: **GitHub Actions** → plantilla **Static HTML** → Commit.
3. Al hacer push a `main`, se publica solo en:
   **https://aespese29.github.io/ia-toolbox/**
