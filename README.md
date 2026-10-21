# House image-model public package v1

Public gallery: https://ezekiel-kifla.github.io/house-image-model-package/

This package contains:

- six redacted room-specific plan crops;
- fifteen selected room-render references;
- forty-five complete prompts, one for each view and A/B/C option, all updated for ultra-high-end contemporary avant-garde design;
- `prompts.json` and individual plain-text prompt files;
- a responsive gallery with one-click prompt copying;
- `manifest.json` with hashes and reference mappings.

## URL-only limitation

The prompts are designed for a browsing-capable ChatGPT or Gemini session that can open public image URLs. Each prompt tells the model to return `REFERENCE_URL_INPUT_NOT_SUPPORTED` instead of guessing when it cannot access the images.

Adobe Firefly does not reliably convert pasted URLs into Composition references. Its geometry-lock workflow still requires an uploaded image and therefore does not meet the owner’s no-upload requirement.

## Privacy

The address and full plan are omitted. The public room crops still expose exact internal dimensions, door/window IDs and swings, fixtures, service zones, and some adjacent spaces. The offers and Blender source are not included.

## Hosting

The site is published through GitHub Pages at the stable HTTPS URL above. `robots.txt` explicitly permits real-time reference use while reserving the content from AI training.
