---
layout: post
title:  "GPU-driven Interactive Realtime Grass"
summary: "My touch-grass-simulator"
preview: /assets/grass/preview.webp
---

### Intro 
Inspired by this research paper, I'm building a procedural grass system with physics simulation driven by the GPU Compute Shader in Unity. Still an on-going project, but the physics simulation features are mostly done. Each blade of grass is represented as a quadratic Bezier curve, and the tip of the grass blade is affected by natural forces (wind + stiffness + gravity) and collision. I made a slight improvement on top of the Bezier curve representation for the grass, using legendre-gauss solution for better approximation of the arc length (i.e. the grass length). The next step is to do some culling optimization for better scale + procedural generation of fun shapes.

### Demo
In the mean time, this will be the only grass I'll be touching.
![Grass](/assets/grass/interactive-grass.gif)

### Resources
🔗 [Responsive Real-Time Grass Rendering for General 3D Scenes](https://www.cg.tuwien.ac.at/research/publications/2017/JAHRMANN-2017-RRTG/JAHRMANN-2017-RRTG-draft.pdf) \
🔗 [Bezier Arc Length](https://pomax.github.io/bezierinfo/#arclength)

### 🛠️ Tools used
- C#
- HLSL
- Unity