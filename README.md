# Proyecto PingMatch — Notas de build y workflow

Recomendaciones rápidas:

- Para desarrollo: usar el watcher de Sass

```bash
npm run watch:css
```

- Para producción: generar CSS minificado

```bash
npm run build:prod
```

- Git: crear ramas por feature/bug, commits claros, PRs para revisión.
- Testing: usar BrowserStack o testing cross-browser manual para validar en Chrome/Firefox/Safari/Edge y móviles.
- Optimización: convertir imágenes a WebP, servir desde CDN en producción, y usar compresión gzip/brotli en servidor.

Arquitectura SCSS propuesta: `abstracts/`, `base/`, `components/`, `layout/`, `pages/`, `themes/`, `vendors/` y `main.scss` como entry.
