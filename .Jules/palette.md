## 2024-05-22 - readme-typing-svg Accessibility
**Learning:** Dynamic text images like `readme-typing-svg` default to generic "Typing SVG" alt text, which completely hides the hero content from screen readers.
**Action:** Always manually override the `alt` attribute with the full text content from the `lines` parameter for these components.
