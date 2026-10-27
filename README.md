# JuBilee website

Editable homepage prototype built with HTML, CSS, and JavaScript. No install or build command required.

## Files
- `index.html`: page structure and copy
- `style.css`: layout, typography, colors, and pill buttons
- `app.js`: service tabs, inquiry dialog, gallery, mobile menu, and email inquiry
- `assets/`: logo and photography
- `ASSET_SOURCES.md`: photography sources and license references

## Preview locally
Run `python3 -m http.server 8000` from this folder, then open http://localhost:8000.

## GitHub Pages
Upload this folder's contents to the repository root, with index.html directly at the top level. Under Settings > Pages, choose Deploy from a branch, main, /(root), and Save. Share the published URL shown there.

## Continue development
Clone the repository into your editor. Commit changes to preserve versions. Invite collaborators through repository settings if they should edit directly.

## Current scope
This is a homepage prototype. The inquiry form opens the visitor's email app with a prepared message; it does not save submissions. Product cards prepare inquiries rather than shopping carts. Group stores are described as a service; this project does not yet implement store ordering or payments. These can be built in subsequent iterations.
