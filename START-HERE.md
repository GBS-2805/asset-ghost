# 🚀 START HERE — read once a week for a month, then never again

This is the idiot-proof version. The serious docs (README.md, 00_admin/) can wait until this feels natural.

## The whole system in 20 seconds

> One folder. When you download something for design work, put it here instead of `Downloads/`.
> Sorted folders so you can find things later. One clean-up day per week. That's it.

## "I downloaded something. Where does it go?"

| I downloaded... | Matches when you say... | Drop it in |
|---|---|---|
| a font | "letters / typography" | `10_fonts/` → pick display · serif · sans · mono |
| an icon, illustration, logo, shape (SVG) | "flat picture that scales" | `20_vector/icons/` or `.../illustrations/` etc. |
| a photo, texture, mockup | "flat picture that's a real image" | `40_raster/photos/` or `.../textures/` etc. |
| a Blender add-on zip | "a thing I install INSIDE Blender" | `50_blender/addons/` |
| a Blender material or model I like | "3D stuff" | `50_blender/libraries/materials/` or `.../models/` (then mark as Asset in Blender) |
| an HDRI sky | "the 360° lighting thing" | `50_blender/hdri/` (`.exr` = too big for GitHub, disk-only) |
| a CAD file (.step / .stl) | "a 3D printable / measurable thing" | `60_cad/step-library/` |
| a poster template | "something I edit in Illustrator" | `70_poster/templates/` |
| a license key or token | "a password-like secret" | `80_private/` — 🚫 never uploaded, never shared |
| don't know / in a hurry | "whatever" | `01_inbox/` — deal with it later |

**Still unsure?** Inbox it. Never let "hmm, which folder?" block a download.

## Real-life examples

**"I got a free font from Fontshare."**
Unzip → put the `.otf` files in `10_fonts/sans/` (or the right style) → keep the `license.txt` next to them → double-click the .otf → **Install** so it appears in Illustrator → one line in `00_admin/LICENSES.md`. Done.

**"I saved 10 icons from Iconify."**
They export as .svg → `20_vector/icons/iconify_whatitshows_open.svg` → one line in LICENSES.md. Done.

**"Poly Haven gave me a kitchen HDRI (.exr)."**
→ `50_blender/hdri/`. Those files are gitignored (too big for GitHub) — fine, they just live on disk.

**"Plasticity emailed me a license token."**
Copy it into `80_private/plasticity-academic_token.txt` AND into your password manager as a secure note. Keep the installer in `80_private/` too. Never commit, never paste into chats.

## The weekly cleanup (2 minutes, once a week)

1. Open `01_inbox/`.
2. For each file: move it home (table above) **or delete it**. Can't decide? Ask once per file type, then you know forever.
3. Spot a file with no license info anywhere in the vault? Delete it or find its license.
4. Close. Done. That is the entire maintenance cost.

Skipped a month? No disaster — the inbox just has 40 files. One long coffee, triage, back to normal.

## Rules of thumb (only 3)

- 🏷️ **No license = not kept.** (Check the download page for "free" / CC0 — 10 seconds.)
- 📛 **Name for future-you:** `source-name_whatitis.ext`. Too lazy? Fine — the folder already says a lot.
- 🚫 **`80_private/` never leaves your machine.**

## What this folder does NOT do (so nobody's disappointed)

- No app auto-scans it — **one exception:** Blender's Asset Browser, pointed at `50_blender/libraries/` once. Then materials/models really do appear inside Blender automatically.
- GitHub only backs up small/text files; secrets and giant .exr/.zip are excluded on purpose.
- Nothing replaces the apps. It's just the tidy shelf they all reach into.
