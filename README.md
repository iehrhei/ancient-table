# The Ancient Table

A seasonal menu of dishes recreated from historical sources: cookbooks, clay tablets, poems, court records. Chosen for your city and season, each with its story, a shopping list, and steps to cook it today.

A static site with no build step and no server. All files are ready to serve as they are.

## Publish on GitHub Pages

1. Create a repository and put everything in this folder at its root (keep `.nojekyll`).
2. In the repository: **Settings → Pages → Build and deployment → Deploy from a branch**, choose `main` and `/ (root)`.
3. The site appears at `https://<your-user>.github.io/<repo>/` after a minute or two.

Live at https://iehrhei.github.io/ancient-table/

## What works where
- Menu, stories, shopping lists, cooking steps, timers: everywhere.
- Cooking notes and plate photos are kept in the visitor's own browser. "Save a copy" / "Load a copy" (at the end of the menu) export and import them as a file.
- "Ask the dish" (a chat about the recipe) only runs inside Claude and is hidden on this site.

## Files
- `index.html`: the whole site (HTML, CSS, JS). Fonts load from Google Fonts.
- `img/*.webp`: cut-out masks for the collages, inked by CSS.
- `credits.html`: every picture source and licence.
- `og.png`: share image.

## Picture credits and licences
Museum images: The Metropolitan Museum of Art, Open Access (public domain). Photographs: Flickr, rawpixel and StockSnap via Openverse, under CC0, CC BY 2.0 or CC BY-SA 2.0. All are cut out and reprinted as one-ink halftone. Adaptations of CC BY-SA 2.0 photographs are shared under CC BY-SA 2.0. The full list is in `credits.html`, and each dish page lists its own.
