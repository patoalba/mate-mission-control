# mate-mission-control

Panel operativo de **Mate AI** — arquitectura, pipelines y roadmap MVP + Coach Wave 1.

Servido como página estática vía GitHub Pages.

## Vistas

| URL | Qué muestra |
|-----|-------------|
| **/** — `index.html` | Mission Control: panel de arquitectura, IAM, pipelines y secretos |
| **/landing.html** | Landing pública del producto (marketing, value prop) |
| **/roadmap.html** | Roadmap MVP + Coach Wave 1 con checkboxes y progreso |

URLs en vivo:
- https://patoalba.github.io/mate-mission-control/
- https://patoalba.github.io/mate-mission-control/landing.html
- https://patoalba.github.io/mate-mission-control/roadmap.html

## Fuente de verdad

Los HTML viven en repos privados:
- `index.html` ← `Mate AI/Mate Branding/mate-mission-control.html`
- `landing.html` ← `Mate AI/Mate Branding/mate-landing.html`
- `roadmap.html` ← `mateai/coach-roadmap.html`

Cada vez que cambian allá, se copian acá y se pushean:

```bash
cd "/Users/.../Mate/mate-roadmap"
cp "../Mate Branding/mate-mission-control.html" index.html
cp "../Mate Branding/mate-landing.html" landing.html
cp ../mateai/coach-roadmap.html roadmap.html
git add . && git commit -m "sync: update" && git push
```

A futuro: GitHub Action que sincronice automáticamente.

## Privacidad

Este repo es público pero no contiene código fuente, secrets, ni datos de usuarios. Solo describe la arquitectura del sistema y el plan operativo — info de nivel "página About / Whitepaper" de un startup.
