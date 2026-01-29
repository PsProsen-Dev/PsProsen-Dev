# PALETTE'S JOURNAL - CRITICAL LEARNINGS ONLY

## 2026-01-29 - [Dynamic Image Accessibility]
**Learning:** Dynamic image generators (like readme-typing-svg) often default to generic alt text (e.g., "Typing SVG"). This makes the content completely inaccessible to screen reader users who cannot see the generated text.
**Action:** When using dynamic image generators, always manually override the `alt` attribute with the actual text content that the image is generating, derived from its URL parameters.
