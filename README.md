# RE-Crackmes

This repo is organized to make it easy to upload my reverse-engineering journey and each crackme write-up, including both original and patched files.

## Suggested structure

```text
RE-Crackmes/
├── journey/
│   └── YYYY-MM-DD.md
├── crackmes/
│   └── crackme-name/
│       ├── original/
│       ├── patched/
│       └── notes.md
└── templates/
    ├── crackme-notes-template.md
    └── journey-entry-template.md
```

## Quick workflow

1. Add progress notes to `journey/` (daily or per-session).
2. Create a folder under `crackmes/` for each target.
3. Place untouched files in `original/`.
4. Place patched output in `patched/`.
5. Copy the template from `templates/crackme-notes-template.md` into `notes.md` and fill in findings.

## Notes

- Keep binary names descriptive (example: `crackme1.exe`, `crackme1_patched.exe`).
- Include offsets, function names, or patch bytes in notes so your work is reproducible.
