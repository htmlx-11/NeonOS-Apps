# Neon Notes v1.1

Upgraded from the supplied Neon Notes v1.0 Productivity Upgrade.

## Included
- Existing IndexedDB notes, categories, tags, editor, search, theme, and original backup/restore.
- New folder and nested-folder path organizer.
- Daily notes, task tracker with due dates/completion, and floating Quick Notes panel.
- Separate v1.1 backup export for its new productivity data.
- Best-effort NeonOS accent sync from common localStorage accent keys; app accent picker remains available.
- NeonOS manifest.json (`neonos.app.v1`).

## Data note
The original notes remain in IndexedDB. The new v1.1 productivity add-ons are stored in localStorage under `neonNotesV11`; use **V1.1 Backup** to export/restore that add-on data. Browser storage is origin-specific.

## Install
Place this folder as `apps/NeonNotes/` in the NeonOS-Apps repository. The manifest is at the app folder root.
