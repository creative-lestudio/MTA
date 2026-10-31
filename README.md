# Marquina Talent Agency — rediseño web

Sitio estático (HTML + CSS + JS, sin build). `index.html` es la página completa; `a/` contiene las imágenes optimizadas.

## Versiones
- **Propuesta A (versión final original):** `/` (`index.html`).
- **Propuesta B (con mejoras de conversión):** `/v2/` (`v2/index.html`). Comparte las imágenes de `a/`.
- `a/mediakit-mta.pdf`: media kit del roster en PDF.

## Ver en vivo
GitHub Pages: Settings → Pages → Source: **GitHub Actions**. El workflow `.github/workflows/pages.yml` publica la raíz del repo.

## Local
```bash
python3 -m http.server 8000
```
