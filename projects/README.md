# Projects assets

This folder holds the media for the **Projects** section of the site.
Images live in `projects/img/`. Each project is an `<article class="project-card">`
block in `index.html`.

## Current cards
- **Dog/Cat Classifier** — img `img/dog-cat.webp`, links to the notebook in Personal_Projects
- **Arduino iPod** — img `img/arduino-ipod.webp`, links to the demo video in Personal_Projects
- **Vampire Survive** — img `img/vampire.png`, links to the CS32 code in Class_Projects

## Adding a new project
1. Drop the image in `projects/img/` (webp/png/jpg all fine; keep it reasonably small).
2. Copy an existing `<article class="project-card">` block in `index.html`.
3. Update the `<img src>`, `.project-title`, `.project-desc`, `.project-tags`,
   and the `.project-links` href(s). Delete any link you don't have.

## Other media types the card layout supports
- **Video file:** replace the `<img>` in `.project-media` with
  `<video controls preload="metadata" poster="..."><source src="img/your.mp4" type="video/mp4"></video>`
- **Embed (YouTube/CodePen/live app):** replace the `<img>` with an
  `<iframe src="..." loading="lazy" allowfullscreen></iframe>` and add the
  class `project-embed` to the `.project-media` div.
- **Image gallery:** add class `project-gallery` to `.project-media` and put
  multiple `<img>` tags inside.

## Projects not yet added (on the Webflow site, no code links found)
SpaceDash, Free for Sale, Emergency Detector, Car Plate Detector, Pitch Guesser.
Add these once their code/descriptions are available.
