## 2026-01-20 - [Dynamic Text Image Accessibility]
**Learning:** Dynamic text generation services (like readme-typing-svg) often provide generic defaults like 'Typing SVG', completely hiding the text content from screen readers.
**Action:** Manually extract the text content from the URL parameters (e.g., 'lines=...') and mirror it in the `alt` attribute.
