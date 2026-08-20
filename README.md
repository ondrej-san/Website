# Ondrej Szorad — portfolio site

A small, dependency-free static website showcasing my projects. Pure HTML + CSS
(one tiny inline script for the footer year), so it runs anywhere — open it locally
or publish it to the web unchanged.

## Pages

| File | Purpose |
|------|---------|
| `index.html` | Home / hero + featured projects |
| `projects.html` | Grid of all projects |
| `atlas.html` | The Atlas browser |
| `chiron.html` | The Chiron language |
| `mods.html` | Minecraft mods (fill in the placeholder cards) |
| `styles.css` | Shared theme (dark, matches Atlas) |
| `assets/` | Icons and images |

## Viewing it locally

Just open `index.html` in a browser — including **Atlas** (`📂 Open new file…` → pick
`index.html`). No build step, no server needed.

## Editing

- **Add a project:** copy a `<a class="card">…</a>` block in `projects.html`, change the
  title/description/tags, and point `href` at a new page (copy `atlas.html` as a template).
- **Add a mod:** edit the placeholder cards in `mods.html`. Link a card to Modrinth/CurseForge
  by wrapping it in `<a class="card" href="…">`.
- **Screenshots:** drop images into `assets/` and embed with `<img src="assets/name.png">`.
- **Name / contact:** search-and-replace “Ondrej Szorad” and the email in each page's header/footer.

## Publishing to the web (later)

The site is already GitHub Pages ready:

1. Put this folder in a git repo and push to GitHub.
2. Repo **Settings → Pages → Source: deploy from branch** (e.g. `main`, root).
3. It goes live at `https://<username>.github.io/<repo>/`.

All links are relative, so it works the same locally and once deployed. (A custom domain
can be added later in the Pages settings.)
# Website
