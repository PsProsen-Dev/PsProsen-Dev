# PALETTE'S JOURNAL - CRITICAL LEARNINGS ONLY

## 2024-05-22 - Dynamic Content Accessibility in Profile READMEs
**Learning:** Dynamic text generators (like readme-typing-svg) default to generic alt text (e.g., "Typing SVG") which degrades the screen reader experience by hiding the actual content being displayed.
**Action:** Always manually override the `alt` parameter in the URL or img tag to mirror the `lines` parameter content, ensuring screen readers announce the *message* rather than the *mechanism*.
