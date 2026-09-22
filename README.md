# Image and text to editable jewelry CAD

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

The current illustration was generated with `google/gemini-3-pro-image-preview` through OpenRouter. `assets/editable-rhino-ring-cad-full.jpg` preserves the 5056 × 3392 source bytes. The WebP files and social JPEG are smaller display copies, not pixel-identical originals. The page explicitly labels the image as an illustration, not an actual CAD export. Previous assets are preserved.

## Search setup

The page includes a descriptive title and summary, crawlable article text, semantic headings, author information, Article and ImageObject structured data, a canonical URL, social previews, responsive images and an image sitemap. It links directly to https://formanova.ai/image-to-cad.

After publication, verify the URL-prefix property `https://abdullahanxie.github.io/procedural-rhino-jewelry/` in Google Search Console, submit its `sitemap.xml`, and request indexing of the page. Bing Webmaster Tools can receive the same sitemap. These account actions have not been performed here. Project-level robots.txt cannot control the GitHub Pages host, so no ineffective project robots.txt is included. Search visibility and rankings are not guaranteed.

## Editable CAD wording

The project exporter was checked: generated parts receive names and layer assignments and are written as separate objects in millimetres. Editable objects do not imply a parametric feature history. Import and export compatibility depends on the chosen format and receiving software. CAD review is required before manufacturing release.

Text and artwork © 2026 abdullahanxie. All rights reserved.
