# PALETTE'S JOURNAL - CRITICAL LEARNINGS ONLY

## 2026-01-26 - Accessible Dynamic Images
**Learning:** Dynamic image generators (e.g., `readme-typing-svg`) create visual text that is invisible to screen readers if the default `alt` text ("Typing SVG") is used.
**Action:** Always manually override `alt` text for these images, deriving the content from the URL parameters (e.g., `lines=...`) to ensure screen reader users receive the same information.
