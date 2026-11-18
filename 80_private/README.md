# 80_private — tokens, keys, license files

**This folder is NEVER committed.** It's gitignored — GitHub backup intentionally does not cover it.

## What lives here
- `plasticity-license-token.txt` — the token from the academic license email
- Plasticity installer copies (so reinstalls don't depend on an email that dies)
- Blender add-on tokens, any paid font/asset license keys, activation files

## Rules
1. **Secrets never enter git** — if a file in here shows up in `git status`, it's a bug; stop and check .gitignore.
2. **One backup outside any single machine**: an encrypted USB drive or a password manager attachment entry (Bitwarden/1Password secure note). Passwords themselves live in the password manager, not here where possible.
3. **File naming**: `app-role_token.txt` (e.g. `plasticity-academic_token.txt`).
4. If a school email is about to die: move the token here + request the contact email change with the vendor support.

## Disaster-recovery order
1. Token file here → 2. password manager copy → 3. encrypted USB → 4. vendor support reissue (worst case, last resort).
