# PALETTE'S JOURNAL - CRITICAL LEARNINGS ONLY

## 2026-01-25 - Dynamic Image Accessibility
**Learning:** Dynamic image generators (e.g., `readme-typing-svg`, `capsule-render`) often default to generic or missing `alt` text (e.g., "Typing SVG" or filename), rendering the content inaccessible to screen readers.
**Action:** Always manually override `alt` attributes for these images. For text-containing images, mirror the content (e.g., "Initializing..."). For purely decorative elements (separators, effects), explicitly set `alt=""` to prevent screen reader noise.
