# PALETTE'S JOURNAL - CRITICAL LEARNINGS ONLY

## 2024-10-24 - Dynamic Image Generators & Accessibility
**Learning:** Dynamic image generators (like readme-typing-svg) often default to generic alt text (e.g., "Typing SVG"), which fails to convey the actual content encoded in their URL parameters to screen reader users.
**Action:** Always manually override the `alt` attribute for these images by extracting the relevant text content from the URL parameters (e.g., `lines=...`).
