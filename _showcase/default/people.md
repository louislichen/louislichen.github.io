---
show: true
width: 4
date: 2021-09-12 00:01:00 +0800
height: 230px
images:

- src: /assets/images/photos/pipi.jpg
  title: Hong Kong, China
  desc: My best friend Pipi and me.
- src: /assets/images/photos/xing_rui.jpeg
  title: Changbai Mountain, China
  desc: With my friends Xing and Rui.
---

{% include widgets/carousel.html id=page.id images=page.images height=page.height %}
