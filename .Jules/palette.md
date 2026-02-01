# PALETTE'S JOURNAL - CRITICAL LEARNINGS ONLY

## 2024-05-22 - [Dynamic README Image Accessibility]
**Learning:** Dynamic README images (like `readme-typing-svg`) usually contain their textual content within URL parameters (e.g., `lines=...`). This data can be extracted to generate accurate `alt` text instead of using generic descriptions.
**Action:** When fixing accessibility for dynamic profile assets, parse the `src` URL to extract the actual content for the `alt` attribute.
