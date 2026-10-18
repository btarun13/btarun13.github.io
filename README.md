# btarun13.github.io

Personal portfolio for Tarun Naithani. Plain HTML/CSS/JS, no build step.

## Publish

1. Create a **public** repo named exactly `btarun13.github.io`.
2. Put `index.html` and the `assets/` folder at the repo root (upload in the browser, or clone and push).
3. Settings → Pages → Source: *Deploy from a branch* → `main` / `/ (root)` → Save.
4. In about a minute the site is live at https://btarun13.github.io

## Edit

Everything is in `index.html`:

- Profile photo: replace `assets/tarun.jpg` (square works best).
- Hero text and links: the `<header class="hero">` block.
- Projects: the `<ul class="projects">` list — each `<li>` is one project.
- Project pictures: drop GIFs into `assets/` with the names listed in `assets/README.md`. If a GIF is missing, a built-in illustration shows instead. The GDC-Mutant-Peptide-Explorer entry already loads the chart from that repo's README.
- Colours and fonts: the `:root` variables at the top of the `<style>` block.
- The animated network in the hero: the `<script>` at the bottom. Set `LINK` to change how far apart nodes connect; delete the whole script to make it static.
