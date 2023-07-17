---
layout: post
title:  "Gift wrapping algorithm"
summary: "Senior Technical Designer"
date:   2023-07-07 15:39:40
preview: /assets/gift_wrapping_preview.jpg
---

![Picture 1](/assets/image.png)

I was tinkering around with a library called openframeworks, a simple wrapper for OpenGL, and wanted to code something simple to get used to the framework. The gift wrapping was a suitable and intriguing challenge for this task. The goal of the problem is to find the convex hull(the minimum of points that create a "wrapping" around all points) from an input set of points. It's not the fastest algorithm out there to achieve a convex hull, but for me, it was a good start to get back to graphics algorithms and understand important concepts. 

The crux of the idea is to start with the leftmost point in the whole set which you know for sure must be in the convex hull, then iteratively scan all the points to find the leftmost point from the current point you're looking at and update that point to be the current one. Once you find that you're back to the beginning point you chose, you know that the convex hull has wrapped itself, and you're done! The image is what the result might look like. 

I'm looking forward to implementing faster and more efficient variants of this algorithm (i.e. Chan's algorithm).
