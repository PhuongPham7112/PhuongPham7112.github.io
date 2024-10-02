---
layout: post
title:  "Lanesplitterz"
summary: "Making effects for a stylized bowling game"
preview: /assets/lanesplitterz/preview.webp
---

### Intro
First time trying out a project that's very stylized.

### Implementation
#### Toon Shading
Since my art team wanted a flatter cartoon-ish look, I made a toon outline & shading post-processing effect using Sobel edge detection algorithm based on normal, depth, and color. With some cel-shading on top and a LOT of tuning, we had a pretty cool effect that feels like a comic book. 
![Toon shading](/assets/lanesplitterz/content.webp)

#### VFX
More stylized effects compared to my previous projects. It looks really cool with the toon post-processing look!
- Smoke
- Toon impact
- Launch explosion

<iframe width="800" height="450" src="https://www.youtube.com/embed/9SAyBnVn4tU?si=Q_g7Vn8-zRlEG1pG" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

![Explosion](/assets/lanesplitterz/explosion.gif)

### 🛠️ Tools used
- C#
- HLSL
- Unity
- Procreate
- Figma