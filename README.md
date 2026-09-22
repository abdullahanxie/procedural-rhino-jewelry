# Image and text to native Rhino jewelry CAD

A technical article by **abdullahanxie**, documenting a team-developed image-to-CAD and text-to-CAD workflow, its deliverables, and its limitations.

Website: https://abdullahanxie.github.io/procedural-rhino-jewelry/

This repository contains only the public article, site styling, and an original conceptual workflow illustration. The underlying jewelry automation implementation is private.

## Local preview

Open `index.html`, or serve this directory with `python -m http.server 8094 --bind 127.0.0.1`.

## GitHub Pages

Publish from the `main` branch, root folder. `.nojekyll` keeps this a plain static site. No build step or dependencies are needed.

## Discoverability

The page includes an author byline, canonical URL, Article structured data, social preview metadata, descriptive image text, and a sitemap. Search indexing and ranking are controlled by search engines and are not guaranteed. Once live, the author can verify the URL-prefix property in Google Search Console and submit `sitemap.xml`.

The approximate six-month project history is the author's account. This article records this team's implementation; it makes no claim of worldwide invention priority. The publication date does not establish the earlier development date.

## Production scope

The project owner confirmed on September 22, 2026: production-ready for supported ring designs, with CAD review before manufacture. The article does not claim unrestricted design coverage, automatic manufacturing approval, or measured performance metrics.

## Artwork

The current image is `assets/image-text-to-cad-pipeline.png`. Generated with the built-in image tool, then edited with that tool to ensure an opaque warm-white background and crisp lines. Earlier images are preserved.

Final image brief: image and text inputs converge into input interpretation, procedural CAD generation, validation with a correction loop, and output files branching into native Rhino .3dm and .glb preview. Use navy and pale blue on warm white, clear directional arrows, no personal name or byline, and a footer explaining that internal methods are not shown. These are broad functional labels, not internal architecture.

Text and artwork © 2026 abdullahanxie. All rights reserved.
