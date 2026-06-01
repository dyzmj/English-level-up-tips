---
name: update-readme-and-section-md
description: Workflow command scaffold for update-readme-and-section-md in English-level-up-tips.
allowed_tools: ["Bash", "Read", "Write", "Grep", "Glob"]
---

# /update-readme-and-section-md

Use this workflow when working on **update-readme-and-section-md** in `English-level-up-tips`.

## Goal

Update the main README and one or more section markdown files (e.g., listening.md, reading.md, vocabulary.md) to add or revise content.

## Common Files

- `README.md`
- `*.md (section files like listening.md, reading.md, vocabulary.md, speaking.md, understanding.md)`

## Suggested Sequence

1. Understand the current state and failure mode before editing.
2. Make the smallest coherent change that satisfies the workflow goal.
3. Run the most relevant verification for touched files.
4. Summarize what changed and what still needs review.

## Typical Commit Signals

- Edit README.md to add or update links/overview
- Edit or create a section markdown file (e.g., listening.md, reading.md, vocabulary.md)
- Commit both files together

## Notes

- Treat this as a scaffold, not a hard-coded script.
- Update the command if the workflow evolves materially.