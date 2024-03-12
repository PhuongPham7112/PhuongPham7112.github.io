---
layout: post
title:  "Soft body animation: Jello Cube demo"
summary: "CSCI 520: Simulating a jello cube in OpenGL"
date:   2023-08-16
preview: /assets/jello_demo/jello_cube_preview.webp
---

I attempted to recreate a jiggly jello cube's physics from CSCI 520. It's a fun challenge with mass spring systems where one has to balance a cube's original structure with spring and external forces. Here are some *bouncy* animations to look at.

Extra fancy stuff:
- Textured cube with hand-drawn texture image (JJK reference)
- Inclined plane collision logic & render
- Customized lighting and material
- Optimized conversion from float to int and avoid float division in external force interpolation
- Interactivity with the cube (drag left mouse anywhere on the screen and the force will apply to the cube)

<iframe width="560" height="315" src="https://www.youtube.com/embed/_agj89SzhhE?si=tIaK5ICll78FBAoc" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

### Resources
🔗 [CSCI 520: Jello Cube assignment](https://viterbi-web.usc.edu/~jbarbic/cs520-s24/assign1/)