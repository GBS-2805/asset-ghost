# Apps — roles & cheat sheets

Four apps, four jobs. No overlap in what each manages.

## Figma — UI & app/web design
- Cloud library is the database: kits, components, styles, plugins stay in Figma.
- Plugin must-haves: Iconify (icons), Blush (illustrations), Themer (themes).
- Vault touchpoint: `30_ui/` only for exports/reinstallers.

## Illustrator — vector & poster finishing
- Final composition/print engine for posters; SVG in/out with the vault.
- Vault touchpoints: `10_fonts/`, `20_vector/`, `70_poster/`.

## Blender — 3D illustration & depth
- Grease Pencil (4.3+) for 2D illustration; Asset Browser is the 3D database.
- Add-ons (max ~5): nijiGPen, Grease Pencil Tools, Malt NPR.
- Setup: File Paths → Asset Libraries → `50_blender/libraries/`; catalogs = Materials, Models.
- Vault touchpoint: `50_blender/`. Test: if it's not marked as an Asset, it's not in the library.

## CAD — Fusion → what now?
- **Fusion free personal license** still exists (annual re-confirmation, hobbyist features).
- If leaving Fusion:
  - **FreeCAD 1.x** — full GUI parametric CAD, free forever, .f3d won't carry over, STEP does.
  - **Onshape free tier** — browser-based, cloud documents, strong sketcher.
  - **Plasticity** — one-time purchase, CAD-style modeling with a designer-friendly UI.
- Interchange format: STEP. Keep `60_cad/step-library/` app-independent so a switch never loses assets.
- Vault touchpoint: `60_cad/` (.f3d/.FCStd + STEP).
