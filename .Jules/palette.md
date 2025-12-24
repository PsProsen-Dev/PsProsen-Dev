## 2024-05-23 - Decorative Images in Developer Profiles
**Learning:** Heavy use of GIFs and dynamic SVGs in "Cyberpunk" themed profiles creates significant noise for screen readers if not properly marked. "Typing SVGs" are particularly problematic as they contain text that is inaccessible inside the `<img>` tag.
**Action:** Always mirror the text content of Typing SVGs in the `alt` attribute. Mark purely visual "header icons" and "separators" with `alt=""`.
