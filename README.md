# HTML Apps

A collection of vibe-coded HTML apps for personal use.

## Apps

### 🖼️ Image Background Remover
- **Link**: [remove-bg-opus.html](./remove-bg-opus.html)
- **Prompt used to create**: [View on Claude.ai](https://claude.ai/share/d5053f18-1848-4c84-8d1d-f95202df19de)
- **Description**: Remove backgrounds from images using AI

---

### 🔁 Replication Coding Meta Helper
- **Link**: [replication_meta_helper.html](./replication_meta_helper.html)
- **Prompt used to create**: [View on Claude.ai](https://claude.ai/share/cfaeacc2-a5f8-45ff-abda-8e0eedd7fa3f) + some local GPT-5-mini follow-up
- **Description**: Helper for extracting bibliographic metadata from DOIs

---

### 🌸 FLoRA Explorer
- **Link**: [flora-explorer.html](./flora-explorer.html)
- **Description**: Interactive explorer for the FORRT Library of Replication Attempts (FLoRA) database. Features searchable table with expandable row details showing full references, replication outcomes, and study metadata. Data sourced from the [FORRT FReD Project](https://github.com/forrtproject/FReD-data).


### 📄 PDF Merger
- **Link**: [pdf_merge.html](./pdf_merge.html)
- **Description**: Merge multiple PDFs in-browser with visual page thumbnails. Drag-and-drop to reorder individual pages or entire files, remove unwanted pages, then download the merged result. All processing happens locally — no uploads.

---

### 📸 Doc Snap
- **Link**: [doc-scanner.html](./doc-scanner.html)
- **Description**: Webcam document scanner. Live preview highlights the detected page, then capture crops and perspective-corrects it to a straight rectangle. Detection is edge/line based (Sobel → Hough → quads scored by how much of their perimeter sits on real edges), so a hand holding the page doesn't get cropped in. Corners are draggable before cropping, auto-crop can be switched off entirely, and results download as `scan_YYYY-MM-DD_HH-MM-SS.png`. All processing happens locally — no uploads.

---

## Deployment

These apps are deployed via GitHub Pages. Visit the live site at: https://lukaswallrich.github.io/html_apps/