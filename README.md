# TEI-Arabic.github.io

Landing site for the TEI-Arabic scholarly network — a group of scholars
marking up Arabic-script texts for digital publication and databases using
TEI.

## Structure

- `index.html` — landing page (title, description, curators)
- `projects.html` — list of member projects
- `resources.html` — reference links (TEI Guidelines, Oxygen, examples) and a short glossary
- `style.css` — shared styles for all pages

Plain HTML/CSS, no build step. GitHub Pages serves it as-is.

## Publishing

1. In this repo on GitHub, go to **Settings → Pages**.
2. Under **Build and deployment → Source**, choose **Deploy from a branch**.
3. Set branch to `main`, folder to `/ (root)`, and save.
4. The site will be live at `https://tei-arabic.github.io/` within a few
   minutes (this special repo name — `TEI-Arabic.github.io` — makes it the
   org's root site rather than living under a `/reponame/` path).

## Adding a project

Copy one `<section class="project">…</section>` block in `projects.html` and
edit the heading, meta line, description, and link.

## Adding a resource

Copy one `<li>…</li>` block in the `<ul class="resource-list">` in
`resources.html` and edit the title, link, and note.
