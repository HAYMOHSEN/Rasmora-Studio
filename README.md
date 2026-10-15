# ArtProof Studio

An offline-capable Progressive Web App prototype for creating, reviewing, protecting, and delivering visual artwork.

## Included working capabilities

- Raster brush, eraser, lines, rectangles, ellipses, full-layer fill, gradients, colour picker, and bilingual text.
- Editable local layers with visibility, import, undo/redo, checkpoints, and PNG/project export.
- Reference workspace with local-image import, palette actions, and composition guides.
- Project Health checks and print-proof modes.
- Delivery presets for social, print, poster, and portfolio output.
- Art Time Machine checkpoints, a local activity trail, licence ledger, project fingerprint, and a creation report export.

## Honest implementation boundary

The Creation Passport is a transparent local report. It does not claim legal copyright ownership or C2PA signing. A production release would connect a trusted C2PA signing provider and a secure collaboration backend for client review links.

## Run locally

Serve this folder from any static web server, then open `index.html`. For example:

```bash
python3 -m http.server 8080
```

Open `http://localhost:8080` and install it from the browser when prompted.

## Microsoft Store / PWA Builder

Deploy the folder to HTTPS hosting first. Then submit the public URL to PWA Builder, generate the Windows package, test it on Windows, and submit that package through Partner Center.
