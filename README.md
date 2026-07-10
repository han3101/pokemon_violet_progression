# Pokémon Violet Pokédex Path Guide (with route maps)

A fully static GitHub Pages site.

## What's included

- `index.html` — clickable 18-step route
- `challenges/` — one standalone HTML page per milestone
- `assets/styles.css` — shared visual styling
- `assets/maps/paldea-map.svg` — stylized base map of Paldea
- `assets/maps/routes/*.svg` — route overlays from Mesagoza
- `sources.html` — data references
- `.nojekyll` — prevents GitHub Pages from applying Jekyll processing

There is no framework, build process, account system, database, local storage, cookie, or required JavaScript.

## Route logic

Each challenge page shows a recommended route from Mesagoza under this rule:

- assume the player completed all earlier milestones in the recommended order
- allow only the ride abilities unlocked before the current challenge
- highlight which unlocked abilities are meaningfully used on that route

## Publish with GitHub Pages

1. Create a GitHub repository.
2. Upload the contents of this folder to the repository root.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, select **Deploy from a branch**.
5. Select the `main` branch and `/ (root)`, then save.

All internal links are relative, so the site works from a GitHub Pages repository subpath.

## Image note

Pokémon artwork is loaded from the public PokeAPI sprites GitHub repository. The HTML pages themselves remain static. To make the site completely self-contained, download those images into `assets/` and replace the external image URLs.
