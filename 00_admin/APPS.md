# Apps — final loadout (4)

**Figma · Illustrator · Plasticity · Blender**, plus **Billfish** as the visual layer over the vault (free, Win+Mac).
One job per app; files travel via SVG/OTF/PNG/STEP/blend.

## Billfish — the vault's face
- Point its library at the vault's numbered folders; it indexes (no duplication) and adds thumbnails, tags, color search, drag-drop filing, browser clipper.
- Filing through Billfish = filing into the vault folders. Same single copy of everything.
- **Exclude `80_private/` and `01_inbox/` from its library scope** — secrets and unsorted stuff stay out of visual browsing.
- Setup notes in `START-HERE.md`. If Billfish ever dies: folders remain untouched, nothing to migrate.

## Figma — UI & app/web design
- Cloud library is the database: kits, components, styles, plugins stay in Figma.
- Plugin must-haves: Iconify (icons), Blush (illustrations), Themer (themes).
- Vault touchpoint: `30_ui/` only for exports/reinstallers.

## Illustrator — vector & poster finishing
- Final composition/print engine for posters; SVG in/out with the vault.
- Vault touchpoints: `10_fonts/`, `20_vector/`, `70_poster/`.

## Plasticity — personal CAD (replaced Fusion, Feb 2026)
- Direct NURBS modeling on Parasolid (same kernel as Fusion/NX — fillets/booleans feel familiar).
- Academic license: free, perpetual, non-commercial, Indie edition. Applied via contact@plasticity.xyz from university email + student ID. Email-deletion mitigation: save token + installer offline; ask support to move contact to a personal email.
- No feature tree — edit geometry directly; that's the only mental shift from Fusion.
- Update channels: Discord #releases-stable. Job-safe: never touch company NX seats for personal work.
- Vault touchpoint: `60_cad/`. Interchange: STEP.

## Blender — 3D illustration & depth
- Grease Pencil (4.3+) for 2D illustration; Asset Browser is the 3D database.
- Add-ons (max ~5): nijiGPen (Blender 3.3–5.3), Grease Pencil Tools, Malt NPR.
- Setup: File Paths → Asset Libraries → `50_blender/libraries/`; catalogs = Materials, Models.
- Vault touchpoint: `50_blender/`. Test: if it's not marked as an Asset, it's not in the library.

## Legacy / dormant
- **NX** — later, career-only path via free NX Student Edition (Windows, proof of enrollment; watermarks; files not openable in commercial NX → export STEP). Solid Edge Student is a lighter alternative.
- **Fusion** — personal-use license still exists (<$1k/yr, 10 active docs) if ever needed; membership discarded by choice. Migration checklist lives in `60_cad/README.md`.
