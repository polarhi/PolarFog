# PolarFog

<p align="center">
  <b>PolarFog: Physics-Informed Information Fusion for Controllable Foggy Polarization Image Generation</b>
</p>

<p align="center">
  <a href="#overview">Overview</a> |
  <a href="#visual-results">Visual Results</a> |
  <a href="#video-demo">Video Demo</a> |
  <a href="#installation">Installation</a> |
  <a href="#inference">Inference</a> |
  <a href="#citation">Citation</a>
</p>

---

## Overview

**PolarFog** is a physics-informed fusion imaging framework for controllable foggy polarization image generation from a clear intensity image.

Polarization imaging provides useful information for vision and restoration tasks in foggy environments. However, acquiring strictly pixel-aligned clear and foggy polarization image pairs in real-world scenes is difficult. PolarFog aims to alleviate this data bottleneck by generating foggy polarization-related images under controllable fog densities.

Given a clear intensity image, PolarFog can generate:

- Foggy intensity image `I`
- Maximum polarization image `Imax`
- Minimum polarization image `Imin`
- Degree of linear polarization image `DoLP`

---

## Visual Results

The figures below are taken from the manuscript and its supplementary material.

### Generation across fog densities

<p align="center">
  <img src="assets/figures/fig5_density.jpg" width="920">
</p>

On the polar test set, fog density increases from top to bottom. Each row shows the generated intensity image `I`, `Imax`, `Imin`, the predicted DoLP, and the reference DoLP.

### Results on GoPro and O-HAZE

<p align="center">
  <img src="assets/figures/fig7_external.jpg" width="920">
</p>

PolarFog applied to clear intensity images from external datasets. (a) GoPro. (b) O-HAZE. Purple boxes mark the enlarged regions.

### Real-world polarization defogging

<p align="center">
  <img src="assets/figures/fig11_defog.jpg" width="920">
</p>

A network trained on Polar-GoPro, tested on real aerial foggy scenes and compared with intensity-based and polarization-based defogging methods.

### Additional qualitative results

<p align="center">
  <img src="assets/figures/figs5_more.jpg" width="820">
</p>

Further generation examples on GoPro (a) and O-HAZE (b) under different fog densities.

<p align="center">
  <img src="assets/figures/figs8_defog.jpg" width="920">
</p>

Additional real-world defogging pairs. Each pair shows the foggy intensity image and the restored result.

---

## Video Demo

The following demos show the clear input images, the generated foggy intensity images and the corresponding DoLP results produced by the computational imaging framework PolarFog.

<table>
  <tr>
    <td align="center"><b>Clear Input Video</b></td>
    <td align="center"><b>Generated Foggy Intensity Video</b></td>
    <td align="center"><b>Generated DoLP Video</b></td>
  </tr>
  <tr>
    <td align="center">
      <a href="https://github.com/polarhi/PolarFog/raw/main/assets/clear.mp4">
        <img src="assets/clear_cover.png" width="280">
      </a>
    </td>
    <td align="center">
      <a href="https://github.com/polarhi/PolarFog/raw/main/assets/foggy_intensity.mp4">
        <img src="assets/foggy_intensity_cover.png" width="280">
      </a>
    </td>
    <td align="center">
      <a href="https://github.com/polarhi/PolarFog/raw/main/assets/dolp.mp4">
        <img src="assets/dolp_cover.png" width="280">
      </a>
    </td>
  </tr>
  <tr>
    <td align="center">
      <a href="https://github.com/polarhi/PolarFog/raw/main/assets/clear.mp4">View video</a>
    </td>
    <td align="center">
      <a href="https://github.com/polarhi/PolarFog/raw/main/assets/foggy_intensity.mp4">View video</a>
    </td>
    <td align="center">
      <a href="https://github.com/polarhi/PolarFog/raw/main/assets/dolp.mp4">View video</a>
    </td>
  </tr>
</table>

## Installation
More details will be published soon.
