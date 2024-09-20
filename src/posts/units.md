---
title: Rems vs Ems
author: Sean O'Reilly
---

```css
/* Button with padding based on its own font size */
button {
  font-size: 16px;
  padding: 1em; /* padding will be 16px (1em) based on the button's font size */
}

/* Nested elements scaling with their parent font-size */
.container {
  font-size: 20px;
}
.container p {
  font-size: 1.5em; /* The paragraph's font-size will be 30px (1.5 * 20px) */
}
```