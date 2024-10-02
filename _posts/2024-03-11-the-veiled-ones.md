---
layout: post
title:  "The Veiled Ones"
summary: "A horror exorcism experience"
date:   2024-03-11
preview: /assets/the_veiled_ones/preview.webp
---

<iframe width="800" height="450" src="https://www.youtube.com/embed/M2wKEU77y4Q?si=5wfn8yishXLE-Gxw&amp;controls=0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

I'm currently working on a horror game with fellow USC students as a technical artist, which is my first time partaking in a game project under this role. Below is some stuff I've been working on:

### Magic Looking Glass
One of the game's main mechanism is player looking through a magical looking glass that helps them see and interact with hidden objects from the ghostly world of Jinn. My first task as a technical artist is to create that enchanting feeling of the glass. I created a volume profile for the night-vision-esque effect of the ghost world and worked on a scrolling-texture effect for glass material.

<iframe width="800" height="450" src="https://www.youtube.com/embed/I249mMw8_0c?si=eAu5maRifYZt60DK" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

### Jinn's Ghost Effect
The ghostly entity **Jinn** will always be in the player's presence, but depending on whether the player looks through the looking glass, Jinn will have different visual effects. I'm working on an interactive smoke that will emit from Jinn in the normal human world. Still in working progress :)

<iframe width="800" height="450" src="https://www.youtube.com/embed/6t93mlEv398?si=UKPmFPsaJW2ke1SX" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

### Screen FX
<iframe width="800" height="450" src="https://www.youtube.com/embed/wHDN_bBg90o?si=Gn_1FmxFx33rYXRI" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

### Flashlight
An auto adjusting flashlight based on the screen's luminance. 
<iframe width="800" height="450" src="https://www.youtube.com/embed/1ceNOvTyEPo?si=f33ZQruQmlwywAcJ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

### Candles
<iframe width="800" height="450" src="https://www.youtube.com/embed/7EwhWIKyCQE?si=hZkarkK4cSedqxwM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

### Cloth physics and shader
<iframe width="800" height="450" src="https://www.youtube.com/embed/wckqksqCzh4?si=Hht1-pEZbRHQhVGN" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

### Distortion FX
<iframe width="800" height="450" src="https://www.youtube.com/embed/t8vdosBwoks?si=Mv-YhloUz3ZSNAeF" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

### Exorcism VFX
<iframe width="800" height="450" src="https://www.youtube.com/embed/Eug50cLfX1A?si=5I2yimuzkS9DnyyR" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

### Footstep FX
(WIP)

### Lighting
(WIP)

### Performance and optimization
- Figure out why the grass is so slow? (answer: Unity built-in terrain is very limited *sad)
- Reduce overdraw from smoke VFX.
- Decrease flashlight's auto adjust mechanism from 20ms to sub 0.1ms.
- Setting up occlusion culling.

[TBD]

### Resources
🔗 [Scrolling caustics effects](https://www.youtube.com/watch?v=uxJZghsWQ-s) \
🔗 [Visual effects for smoke](https://www.youtube.com/watch?v=sNJ_SU20-o0&list=PLtRuo28h-g1mndib2hMyp-dVfx7Jq9cOH&index=2)

### 🛠️ Tools used
- C#
- HLSL
- Unity