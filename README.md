# Paperly — Advanced PDF Maker

A static, responsive, browser-based PDF design tool. No backend or account required.

## Getting started
Open `index.html` in a browser with internet access, or upload these three files to StackBlitz / Cloudflare Pages. No build step needed.

## Features
- Editable text boxes, font family/size/color, bold/italic/underline, alignment
- Upload multiple JPG/PNG/WebP images, drag and resize
- Multiple pages, page sizes (A4, A5, Letter), orientation, background color
- Live page preview and multi-page PDF export
- Client-side processing: no user files are sent to a project server

## Dependencies
The HTML loads html2canvas 1.4.1 and jsPDF 2.5.2 from cdnjs. Internet access is required for these libraries unless you host local copies.

## Limitations
- PDF text and images are rasterized for export; PDF text will not be selectable.
- This is a PDF maker, not an existing-PDF importer/editor.
- Work is not automatically saved across browser refreshes.
- Very large images or many pages can consume significant memory.
