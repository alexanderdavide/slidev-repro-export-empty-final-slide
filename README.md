# Describe the bug

From [v0.36.7](https://github.com/slidevjs/slidev/releases/tag/v0.36.7) the export has an empty final slide.

# To Reproduce

Steps to reproduce the behavior:

1. Install [v0.36.7](https://github.com/slidevjs/slidev/releases/tag/v0.36.7) or later
2. `npm run export` exemplary slides.md

```md
---
theme: seriph
---

See empty final slide.
```

3. See empty final slide in pdf

# Desktop

- OS: Ubuntu 22.04.1
- Browser: Chromium Version 108.0.5359.124
- Slidev version: v0.36.7 - v0.38.2
