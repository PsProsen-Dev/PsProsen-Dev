# Palette's UX Journal

## 2024-05-18 - Accessible Dynamic Images
**Learning:** Dynamic image generators (like readme-typing-svg and capsule-render) rely on URL parameters to render text but often lack descriptive default alt attributes (e.g., defaulting to "Typing SVG"). This makes the content invisible or confusing to screen reader users.
**Action:** When using dynamic image generators, always inspect the URL parameters to extract the intended text and manually replicate it in the `alt` attribute to ensure the content is accessible.
