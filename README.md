# ArtProof Studio v3

An offline-capable Progressive Web App for painting, illustration, retouching, vector artwork, and delivery preparation.

## Professional starter canvas

The app opens with **Aurelia · Editorial sample**, an original high-end studio photograph on its own editable layer. A blank paint layer sits above it, so artists can immediately test brushes, masks, selections, typography, and retouching. Hide or delete the sample layer whenever a blank canvas is preferred.

## Included working capabilities

- **Brush Studio:** pencil, ink, marker, charcoal, airbrush, oil, watercolour, and texture brushes. Pointer Events use pen pressure, tilt, and twist/rotation when the device exposes them. Brush stabilisation, symmetry, palm-rejection behaviour, custom presets, keyboard shortcuts, and workspace modes are included.
- **Layers:** paint layers, groups, group rendering, masks, clipping masks, blend modes, opacity, pixel/alpha/position locks, and live adjustment layers (brightness, contrast, saturation, hue, blur, and monochrome).
- **Selections:** lasso, rectangle, ellipse, magic wand, colour range, feather, refine edge, invert, quick-mask preview, and constrained painting/fill/effects.
- **Transforms and retouching:** scale, rotate, perspective handles, warp, mesh-warp approximation, liquify, smudge, blur, sharpen, dodge/burn, clone stamp, and healing.
- **Colour Studio:** RGB, HSL, HEX, CMYK values, palette extraction, harmony palettes, gradients, colour history, and colour-vision proof previews.
- **Reference tools:** side-by-side reference board, perspective grid, rulers, pose mannequin, lighting arrow, symmetry guide, and custom guide lines.
- **Vector and text:** editable Bézier anchor paths, basic SVG path import/export, vector icons, and editable Arabic/English text with RTL support.
- **Export:** PNG, JPG, uncompressed RGB TIFF, flattened compatibility PSD, SVG with live ArtProof paths/text, Device-CMYK PDF proof, transparent background, and high-resolution social, poster, print, and portfolio presets. The .artproof.json file retains layers, masks, adjustments, vectors, and project data.

## Important delivery notes

- The PSD export is a valid flattened RGB compatibility file. Keep the .artproof.json project alongside it for editable ArtProof layers.
- The PDF creates Device-CMYK raster data at a nominal 300 DPI page size. For a colour-critical commercial print run, ask the printer for the final ICC-profiled conversion and proof.
- C2PA signing and shareable review URLs still require a separate production signing/collaboration service; they are not represented as completed features in this offline build.

## Run locally

Serve this folder from any static web server, then open index.html.

    python3 -m http.server 8080

Open http://localhost:8080 and install it from the browser when prompted.

## Microsoft Store / PWA Builder

Deploy the folder to HTTPS hosting first. Then submit the public URL to PWA Builder, generate the Windows package, test it on Windows, and submit that package through Partner Center.
