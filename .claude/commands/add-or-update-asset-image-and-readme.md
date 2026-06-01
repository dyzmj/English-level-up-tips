---
name: add-or-update-asset-image-and-readme
description: Workflow command scaffold for add-or-update-asset-image-and-readme in English-level-up-tips.
allowed_tools: ["Bash", "Read", "Write", "Grep", "Glob"]
---

# /add-or-update-asset-image-and-readme

Use this workflow when working on **add-or-update-asset-image-and-readme** in `English-level-up-tips`.

## Goal

Add or update an image asset (e.g., PNG, JPG) and update the README.md to reference or describe the new/changed asset.

## Common Files

- `assets/*.png`
- `assets/*.jpg`
- `README.md`

## Suggested Sequence

1. Understand the current state and failure mode before editing.
2. Make the smallest coherent change that satisfies the workflow goal.
3. Run the most relevant verification for touched files.
4. Summarize what changed and what still needs review.

## Typical Commit Signals

- Add or replace image file in assets/ (e.g., *.png, *.jpg)
- Update README.md to reference or describe the image
- Commit both files together

## Notes

- Treat this as a scaffold, not a hard-coded script.
- Update the command if the workflow evolves materially.