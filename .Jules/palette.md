# PALETTE'S JOURNAL - CRITICAL LEARNINGS ONLY

## 2024-05-21 - Dynamic SVG Accessibility
**Learning:** Dynamic image generators like `readme-typing-svg` produce inaccessible content by default (often just "Typing SVG" or no alt text). The semantic content is hidden in the URL parameters (e.g., `lines=...`).
**Action:** When auditing profile READMEs, always parse the URL parameters of dynamic SVGs to generate meaningful `alt` text, rather than relying on the generator's default output.
