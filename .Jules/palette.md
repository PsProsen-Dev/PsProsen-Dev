## 2024-05-23 - Cyberpunk Theme Accessibility Pattern
**Learning:** High-fidelity cyberpunk themes often rely heavily on decorative GIFs and animated separators (like `capsule-render` and Giphy) to create immersion. Without `alt=""`, these become "noise" for screen reader users, announcing filenames or URLs.
**Action:** Systematically audit all "visual flair" elements in themed READMEs. Apply `alt=""` to any image that is purely for atmosphere (dividers, glitch effects, spinning icons) and ensure dynamic content (Typing SVG) has descriptive alt text matching its output.
