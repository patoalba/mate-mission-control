# mate-roadmap

Mission control de **Mate AI** — roadmap MVP + Coach Wave 1.

Servido como página estática vía GitHub Pages.

URL en vivo: https://patoalba.github.io/mate-roadmap/

## Qué hay acá

Una sola página (`index.html`) que muestra las 4 fases del MVP, con checkboxes para marcar progreso. El estado se guarda en `localStorage` del browser — cada persona tiene su propia vista, no se sincroniza entre dispositivos.

## Cómo actualizar

La fuente de verdad vive en el repo principal (privado): `mateai/coach-roadmap.html`. Cada vez que cambia el roadmap allá, se copia a `index.html` acá y se pushea.

```bash
cp ../mateai/coach-roadmap.html index.html
git add index.html && git commit -m "sync: roadmap update" && git push
```

A futuro: un GitHub Action en `mateai` que sincronice automáticamente.

## Privacidad

Este repo es público pero no contiene código fuente, secrets, ni datos de usuarios. Solo task names y fechas del plan operativo.
