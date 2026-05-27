# PolarFog

<p align="center">
  <b>PolarFog: A Computational Imaging Framework for Controllable Foggy Polarization Image Generation</b>
</p>

<p align="center">
  <a href="#overview">Overview</a> |
  <a href="#dolp-video-demo">DoLP Demo</a> |
  <a href="#installation">Installation</a> |
  <a href="#inference">Inference</a> |
  <a href="#citation">Citation</a>
</p>

---

## Overview

**PolarFog** is a physics-informed computational imaging framework for controllable foggy polarization image generation from a single clear intensity image.

Polarization imaging provides useful information for vision and restoration tasks in foggy environments. However, acquiring strictly pixel-aligned clear and foggy polarization image pairs in real-world scenes is difficult. PolarFog aims to alleviate this data bottleneck by generating foggy polarization-related images under controllable fog densities.

Given a clear intensity image, PolarFog can generate:

- foggy intensity image `I`
- maximum polarization image `Imax`
- minimum polarization image `Imin`
- degree of linear polarization image `DoLP`
---
## DoLP Demo

The following video shows the generated DoLP results by the comutational imaging framework PolarFog.

<p align="center">
  <video src="assets/dolp.mp4" width="900" controls muted loop>
    Your browser does not support the video tag.
  </video>
</p>

If the video is not displayed correctly, please open it directly:

<p align="center">
  <a href="assets/dolp.mp4">View DoLP demo video</a>
</p>
