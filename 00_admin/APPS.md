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

## CAD — Fusion status & exit plan (researched)

**Fusion for personal use still exists** (autodesk.com/products/fusion-360/personal):
free for qualifying hobbyists, renewed annually. Limits:
- non-commercial only, **<$1,000/yr revenue** from designs (watch this if you ever sell poster-adjacent merch)
- **10 active document cap** (archive finished designs to work around it)
- limited CAM (2/2.5-axis mill, turning, FFF print prep — fine for desktop machines)
- community verdict: most hobbyists "will not even notice the limitations" (r/Fusion360)

**If Fusion ever becomes unusable, ranked for our use:**
1. **FreeCAD 1.1.x** — full parametric CAD, free forever, 100% offline, you own the files. Clunky UX moments, but 1.0/1.1 fixed the broken-dependency-tree era. Best plain-CAD fallback.
2. **Plasticity** — **perpetual/one-time** ($175 Indie, $299 Studio; 10+ employee companies need Studio). You own it forever; 12 months of updates included, after which you can freeze on your last version indefinitely — renewals are optional, not required. Indie runs on 2 machines. No subscriptions/payment plans exist. Trial: 30 days, non-commercial, OBJ/STL export only. Not parametric (no rollback) — great modelling, weaker re-editing. **Free academic license** (per plasticity.xyz/eula): also **perpetual**, non-commercial only, Indie edition; open to students, educators, veterans, retirees, persons with disabilities. It keeps working after graduation — you keep the last version forever — but renewing updates requires re-verifying eligibility, and any commercial work requires buying a paid license. **How to apply (per FAQ):** email contact@plasticity.xyz from your university email with a student ID or certificate of enrollment attached. No account/password exists — license token arrives by email. Node-locked: Indie = 2 machines, 10 activations/yr. **Email-deletion risk (if school retires your address):** installed copy keeps working (perpetual, offline activation) — the email only delivered the token; before graduating, save the token + installer offline and ask support to update the contact email on the license.
3. **Onshape free** — browser-based, excellent sketcher, but **all documents public** and online-only. Only for non-confidential work.
- Dark horses: **Dune 3D** (new, unusually easy to learn), **SolidWorks Maker** (~$48/yr promo pricing seen).
- **Siemens NX (if employer uses it):** company seats are work-only — never borrow for personal projects. Legit personal path: **NX Student Edition** (free, Windows 64-bit, proof of enrollment; watermarks, non-commercial, files NOT openable in commercial NX → export STEP for the vault). Note also Solid Edge Student Edition (2D free for all, 3D free verified students).
- Interchange format: **STEP**. Keep `60_cad/step-library/` app-independent so a switch never loses assets. .f3d carries nothing over.
- Vault touchpoint: `60_cad/` (.f3d/.FCStd + STEP).
