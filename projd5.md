---
layout: default
title: Diffusion Model-based Pecipitation Downscaling
permalink: /showcase/proj4
show: true
date: 2024-11-07 00:01:00 +0800
---

# Diffusion Model-based Pecipitation Downscaling
## Overview
Deep learning models have been explored for precipitation error modeling, typically relying on ground-based radar data for training. In this study, we leverage diffusion models for their inherent probabilistic generative ability to create a satellite-based ensemble precipitation dataset. Specifically, DPR observations are used as a space-based precipitation ground truth to quantify uncertainties in IMERG estimates. The residual-based diffusion model architecture from Mardani et al (2025) is adopted. Our approach first applies a nowcasting technique to address the four-hour latency gap in IMERG Early, followed by bias correction and spatial downscaling to improve both accuracy and resolution. Atmospheric variables from GEOS-FP and DEM are used as auxiliary conditional variables in the diffusion model. This method generates a thirty-member precipitation ensemble with a 0.05°, 30-minute spatiotemporal resolution, suitable for real-time applications. Preliminary results from a multi-day heavy rainfall event in Iowa (June 2024) show notable improvements from our diffusion model. Ongoing work includes integrating flash flood modeling to further assess the precipitation ensembles’ applicability.

<div class="text-center mt-4">
  <img data-src="{{ 'assets/images/proj55_2.png' | relative_url }}" class="lazy w-100 rounded" src="{{ '/assets/images/empty_300x200.png' | relative_url }}" alt="Hydrologic Modeling Uncertainty Quantification">
</div>

<div class="text-center mt-4">
  <video data-src="{{ 'assets/videos/proj55_2.mp4' | relative_url }}" class="lazy w-100 rounded" poster="{{ '/assets/images/empty_300x200.png' | relative_url }}" alt="Diffusion" controls>
    <source src="{{ 'assets/videos/proj55_2.mp4' | relative_url }}" type="video/mp4">
    Your browser does not support the video tag.
  </video>
</div>



