# Uthej Alagani — Portfolio

A single-page, retro (Stardew-style) personal portfolio. Pure static **HTML/CSS/JS** — no build step, no dependencies.

## Files
- `index.html` — the entire site (content + styles + scripts, all inline)
- `README.md` — this file

## Run locally
Open `index.html` in a browser, or serve it:

    python3 -m http.server 8000

then visit http://localhost:8000

## Edit
Everything lives in `index.html`:
- **Content** (hero, about, skills, projects, experience, education, contact) is plain HTML — just find the words and change them.
- **Add a project:** copy one `<article class="card panel"> ... </article>` block inside `<div class="projects">` and edit it. The `data-cat` attribute controls the filter buttons (`da`, `de`, `ds`, `mlops`, space-separated).
- **Colours & fonts** are CSS variables in the `:root` block at the top of `<style>`.
