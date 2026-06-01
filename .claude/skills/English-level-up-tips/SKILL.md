```markdown
# English-level-up-tips Development Patterns

> Auto-generated skill from repository analysis

## Overview
This repository, `English-level-up-tips`, is a TypeScript-based project focused on providing practical tips and structured guidance for improving English language skills. The codebase is organized around markdown documentation, with modular sections such as listening, reading, vocabulary, and more. Contributions typically involve updating documentation, adding new sections, or managing illustrative assets.

## Coding Conventions

- **File Naming:**  
  Uses `camelCase` for file names.  
  _Example:_  
  ```
  listeningTips.md
  readingGuide.md
  ```

- **Import Style:**  
  Uses relative imports in TypeScript files.  
  _Example:_  
  ```typescript
  import { getTips } from './listeningTips';
  ```

- **Export Style:**  
  Uses named exports.  
  _Example:_  
  ```typescript
  export function getTips() { ... }
  ```

- **Markdown Sections:**  
  Each major skill area has its own `.md` file (e.g., `listening.md`, `reading.md`).

## Workflows

### Update README and Section Markdown
**Trigger:** When adding new information, sections, or making significant edits to both the main README and a section file.  
**Command:** `/update-readme-section`

1. Edit `README.md` to add or update links/overview.
2. Edit or create a section markdown file (e.g., `listening.md`, `reading.md`, `vocabulary.md`).
3. Commit both files together.

_Example commit:_  
```
Update README and listening.md with new podcast tips
```

---

### Add or Update Asset Image and README
**Trigger:** When including a new diagram, illustration, or updating an existing one and reflecting this in the documentation.  
**Command:** `/add-asset-readme`

1. Add or replace an image file in `assets/` (e.g., `*.png`, `*.jpg`).
2. Update `README.md` to reference or describe the image.
3. Commit both files together.

_Example:_  
- Add `assets/listening-diagram.png`
- Update `README.md` with:
  ```markdown
  ![Listening Diagram](assets/listening-diagram.png)
  ```

---

### Minor README Edit
**Trigger:** For fixing typos, improving wording, or adjusting formatting in the main README.  
**Command:** `/edit-readme`

1. Edit `README.md` for minor changes.
2. Optionally update `.idea/workspace.xml` (editor state).
3. Commit changes.

---

### Add New Section
**Trigger:** When expanding the guide with a new topic or skill area.  
**Command:** `/add-section`

1. Create a new section markdown file (e.g., `speaking.md`, `understanding.md`).
2. Update `README.md` to link to the new section.
3. Commit both files together.

_Example:_  
- Create `speaking.md`
- Add to `README.md`:
  ```markdown
  - [Speaking](speaking.md)
  ```

---

### Update Section Markdown Only
**Trigger:** When updating content in a specific section without changing the main README.  
**Command:** `/edit-section`

1. Edit the section markdown file (e.g., `vocabulary.md`, `listening.md`).
2. Commit changes.

---

## Testing Patterns

- **Framework:** Unknown (not detected in analysis).
- **File Pattern:** Test files follow the `*.test.*` pattern.
  _Example:_  
  ```
  listeningTips.test.ts
  ```

Tests are likely written in TypeScript, but the specific framework (e.g., Jest, Mocha) is not specified.

## Commands

| Command                | Purpose                                                         |
|------------------------|-----------------------------------------------------------------|
| /update-readme-section | Update main README and one or more section markdown files        |
| /add-asset-readme      | Add or update an image asset and update README.md accordingly   |
| /edit-readme           | Make minor edits to README.md                                   |
| /add-section           | Add a new major section and link it from README.md              |
| /edit-section          | Update content in an existing section markdown file             |
```
