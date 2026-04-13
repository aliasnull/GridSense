## 2025-05-15 - [Blogger Image Serving & FOUC Prevention]
**Learning:** Blogger's `resizeImage` operator is essential for performance, but often ignored in themes. Serving original images and resizing with CSS is a massive bottleneck for LCP. Also, placing dark mode logic at the end of the `<body>` causes a distinct FOUC that impacts perceived performance.
**Action:** Always use `resizeImage` with `srcset` and `sizes` for Blogger templates. Move critical theme-switching logic to the `<head>` to ensure correct rendering from the first frame.
