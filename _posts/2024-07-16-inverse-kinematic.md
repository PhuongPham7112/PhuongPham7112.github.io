---
layout: post
title:  "Deforming 3D characters"
summary: "CSCI 520: Inverse Kinematics in Computer Animation"
preview: /assets/ik/preview.webp
---

### Implementation
Using OpenGL and math libraries like Eigen and ADOL-C, I implemented linear skin blending, forward kinematics (FK), and inverse kinematics (IK) algorithms to deform a character represented as an obj mesh, given its skinning weights and skeleton data.

There are two ways to go about IK: regularization vs pseudo inverse. I experimented with both, and as bonus, I tried out the more unstable method pseudo inverse with dual quaternion skin blending.

### Demo
<iframe width="800" height="450" src="https://www.youtube.com/embed/AA19c3Jzv-Q?si=Lpo08munJUCcPLQJ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

### 🛠️ Tools used
- C++
- Eigen
- ADOL-C
- OpenGL