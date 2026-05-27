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

The following videos show the clear input images, the generated foggy intensity images, and the corresponding DoLP results produced by the computational imaging framework PolarFog.

<p align="center">
  <b>Clear Input Video</b>
</p>

<p align="center">
  <video width="900" controls muted loop>
    <source src="https://github.com/polarhi/PolarFog/raw/main/assets/clear.mp4" type="video/mp4">
    Your browser does not support the video tag.
  </video>
</p>

<p align="center">
  <b>Generated Foggy Intensity Video</b>
</p>

<p align="center">
  <video width="900" controls muted loop>
    <source src="https://github.com/polarhi/PolarFog/raw/main/assets/foggy_intensity.mp4" type="video/mp4">
    Your browser does not support the video tag.
  </video>
</p>

<p align="center">
  <b>Generated DoLP Video</b>
</p>

<p align="center">
  <video width="900" controls muted loop>
    <source src="https://github.com/polarhi/PolarFog/raw/main/assets/dolp.mp4" type="video/mp4">
    Your browser does not support the video tag.
  </video>
</p>

If the videos are not displayed correctly, please open them directly:

<p align="center">
  <a href="assets/clear.mp4">View clear input video</a> |
  <a href="assets/foggy_intensity.mp4">View foggy intensity video</a> |
  <a href="assets/dolp.mp4">View DoLP demo video</a>
</p>
