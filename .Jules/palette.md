# PALETTE'S JOURNAL - CRITICAL LEARNINGS ONLY

## 2024-05-22 - Dynamic SVG Accessibility
**Learning:** Dynamic image generators like `readme-typing-svg` produce generic alt text ("Typing SVG") which is inaccessible. The actual content is embedded in the URL parameters.
**Action:** When encountering `readme-typing-svg`, always parse the `lines` parameter from the URL to construct meaningful `alt` text manually.
