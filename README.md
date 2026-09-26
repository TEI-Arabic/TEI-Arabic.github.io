# TEI-Arabic.github.io

Landing site for the TEI-Arabic scholarly network — a group of scholars
marking up Arabic-script texts for digital publication and databases using
TEI.

## Structure

- `index.html` — landing page (title, description, curators)
- `projects.html` — list of member projects
- `resources.html` — standards, tools, examples and a short glossary
- `members.html` — names, affiliations, and existing public contact details
- `index-ar.html`, `projects-ar.html`, `resources-ar.html`, `members-ar.html` — Arabic (RTL) counterparts
- `style.css` — shared styles, including RTL and keyboard-navigation rules
- `404.html` — bilingual missing-page response
- `sitemap.xml`, `robots.txt` — discovery metadata
- `CONTRIBUTING.md` — proposed contribution guidance for curator review
- `.github/` — proposed issue/PR templates and public planning/audit notes

Plain HTML/CSS, no build step. GitHub Pages serves the site.

## Arabic version

Each English page links to its Arabic counterpart and each Arabic page links back. Keep both toggle links and reciprocal hreflang entries aligned. Arabic pages use `<html lang="ar" dir="rtl">`. Both languages request the Arabic fonts needed by the bilingual header. Keep stable project IDs identical across each language pair. Mark the actual language of foreign phrases when known; LTR text is not necessarily English.

## Editing

See [CONTRIBUTING.md](CONTRIBUTING.md). Edit both language versions, or explicitly request translation help. For this audit use a working branch and review the diff before proposing a merge. No permission settings are changed by these instructions.

To add a project, copy a project section in both project pages and assign matching unique IDs. For a resource, use the appropriate category in both resource pages. For a member, obtain curator confirmation and permission for any new public contact details; do not assume an internal sign-up entry authorizes publication.

## Preview and publishing

For a local preview, run `python -m http.server 8000` from the repository folder and open `http://localhost:8000/` in a browser. Check keyboard use, narrow screens and both languages.

Existing GitHub Pages configuration is left unchanged. The intended public site is `https://tei-arabic.github.io/`. A working branch does not by itself provide a deployed preview. Review before merging into the publishing branch.

## Audit scope

See [.github/planning/AUDIT_2026-09-26.md](.github/planning/AUDIT_2026-09-26.md) for tests and limitations, and [.github/planning/PROPOSALS.md](.github/planning/PROPOSALS.md) for decisions deliberately not applied. These documents contain no confidential meeting materials and do not establish a new forum policy.
