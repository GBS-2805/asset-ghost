# ASSET VAULT 🛒 → [**Open the live asset store**](https://gbs-2805.github.io/asset-ghost/)

> Live GitHub-mining store with sidebar categories → [tools/store.html](https://gbs-2805.github.io/asset-ghost/tools/store.html) (the .html file also works locally by double-clicking it)

Single source of truth for design assets across four apps:
**Figma** (app/web UI) · **Illustrator** (vector/posters) · **Plasticity** (personal CAD) · **Blender** (3D illustration).

## The rules

1. **Apps are databases for what they manage.** Figma cloud holds UI kits/components/plugins. Blender's Asset Browser catalogs 3D. Only files apps can't manage live here.
2. **License-first:** no license → doesn't enter the vault. Log every addition in `00_admin/LICENSES.md`.
3. **Inbox triage:** downloads land in `01_inbox/` and are sorted or deleted weekly. Weekly, no exceptions.
4. **Naming:** `source-name_variant_license.ext` (e.g. `blush_outline-woman_cc0.svg`).
5. **One format, one copy:** store the travel format (SVG / OTF / PNG / blend / STEP), never per-app duplicates.
6. **Asset Browser test:** a 3D asset that isn't marked/cataloged in Blender's Asset Browser isn't in the library.
7. **Secrets stay out of git:** tokens/keys live only in `80_private/` (gitignored). Never paste tokens, keys, or passwords into chats, issues, or READMEs.

## Map

| Folder | Feeds | Holds |
|---|---|---|
| `10_fonts/` | Figma, Illustrator | .otf/.ttf + license.txt per family, grouped display/serif/sans/mono |
| `20_vector/` | Illustrator, Figma, Blender | .svg only: illustrations, icons, logos, textures |
| `30_ui/` | Figma (cloud-first) | exported kit bits + plugin reinstallers not kept in Figma |
| `40_raster/` | all | photos, textures, mockups, palettes |
| `50_blender/` | Blender | addons (.zip), asset libraries (.blend, marked as assets), HDRI, brushes |
| `60_cad/` | Plasticity (later: NX Student) | STEP exports (`step-library/`) + read-only `.f3d` Fusion archive (`fusion/`) |
| `70_poster/` | Illustrator | poster templates, print presets, final exports |
| `80_private/` | (you) | tokens, license keys, installer copies — **never committed, gitignored** |

## Admin files

- `00_admin/LICENSES.md` — one line per asset: name, source, license
- `00_admin/SOURCES.md` — stores, kit pages, GitHub repos you buy/download from
- `00_admin/WISHLIST.md` — future purchases/downloads with priority

## Weekly triage checklist

- [ ] `01_inbox/` empty
- [ ] every new file named `source-name_variant_license.ext`
- [ ] new assets logged in LICENSES.md
- [ ] Blender: new materials/models marked as assets + cataloged
- [ ] Figma: new kits/components published to team library, local copies deleted

## Blender wiring (once)

`Preferences → File Paths → Asset Libraries` → add `50_blender/libraries/`.
Asset Browser catalogs mirror that folder: `Materials`, `Models`.
