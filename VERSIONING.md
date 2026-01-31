# Versioning

## Version Format
Use **MAJOR.MINOR.PATCH** (e.g., 1.2.0).

- **MAJOR**: big change that breaks compatibility or changes core structure.
- **MINOR**: new content or features that don’t break existing usage.
- **PATCH**: fixes, small tweaks, or documentation improvements.

## When to Bump
- **MAJOR** when:
  - File or folder structure changes in a breaking way.
  - Core asset style or format changes enough to break existing work.
- **MINOR** when:
  - You add new assets, templates, or variants.
  - You expand functionality without breaking existing use.
- **PATCH** when:
  - You fix mistakes, typos, or minor errors.
  - You make small improvements that don’t change usage.

## Release Naming
Use a short, clear name that matches the update:
- **MAJOR**: “Rebuild”, “Overhaul”, “V2”
- **MINOR**: “Expansion”, “New Set”, “Additions”
- **PATCH**: “Fixes”, “Cleanup”, “Docs Update”

## Archiving Old Versions
1. Move older versions to an `/archive` folder.
2. Include the version number in the folder name (e.g., `archive/1.2.0`).
3. Keep a brief `ARCHIVE_NOTES.md` inside the archive folder with:
   - Version number
   - Date
   - One-sentence summary of what changed
