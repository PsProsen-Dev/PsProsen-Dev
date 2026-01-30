# PALETTE'S JOURNAL - CRITICAL LEARNINGS ONLY

## 2025-01-30 - Accessible Dynamic SVGs
**Learning:** `readme-typing-svg` and `capsule-render` generate images containing critical text (headers, typing animations) that are invisible to screen readers by default because they lack `alt` text.
**Action:** Always manually inspect the URL parameters (e.g., `lines=...`, `text=...`) and add a descriptive `alt` attribute that mirrors the content.
