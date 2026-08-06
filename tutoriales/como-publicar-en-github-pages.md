# 📚 Cómo publicar este repo con GitHub Pages

Convierte tu repositorio en una web real donde los HTMLs se ven renderizados
(no como código). Sin conocimientos técnicos.

## 🎯 Qué vas a conseguir
Tu contenido online en: **https://aespese29.github.io/ia-toolbox/**

## ✅ Requisitos
- Un repositorio **público** en GitHub (ej. `ia-toolbox`).
- El archivo `index.html` en la **raíz** del repo.

## 🪜 Paso a paso

1. Sube los archivos al repo (**Add file → Upload files** → arrastra → **Commit changes**).
2. Ve a **Settings → Pages**.
3. En **Build and deployment → Source**, elige **GitHub Actions**.
4. En las plantillas sugeridas, pulsa **Configure** en **Static HTML**
   (es la correcta: publica archivos estáticos sin "compilar").
5. En el editor que se abre, no toques nada → **Commit changes...** → **Commit changes**.
6. Ve a la pestaña **Actions** y espera a que el despliegue se ponga en verde ✅ (1-2 min).
7. Vuelve a **Settings → Pages**: arriba verás tu enlace publicado.

## 💡 Consejos y errores comunes
- **¿No aparece?** Espera unos minutos la primera vez y revisa que `index.html` esté en la raíz.
- **Nombres de archivo**: minúsculas y con guiones, sin espacios ni acentos.
- **Se actualiza solo**: cada push a `main` republica la web automáticamente.
- **Todo es público**: no subas datos sensibles.
- **Un solo workflow**: si tienes `static.yml` y `pages.yml` a la vez, deja solo uno
  para evitar despliegues duplicados.
