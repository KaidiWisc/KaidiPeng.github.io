---
layout: default
title: Hydrologic Modeling Uncertainty Quantification
permalink: /showcase/proj2
show: true
date: 2024-11-05 00:01:00 +0800
---

# Hydrologic Modeling Uncertainty Quantification

## Overview
Satellite-based quantitative precipitation estimates (QPE), such as NASA's Integrated Multi-satellitE Retrievals for GPM (IMERG), provide easily accessible continental-to-global precipitation forcings for flood prediction and other hydrologic applications. Nevertheless, when used in hydrologic prediction, uncertainty in satellite-based QPE often leads to significant bias. This forcing uncertainty is further blended with other error sources, including process representation, parameter values, and their interactions. The identification and decoupling of these uncertainties can enhance our understanding of their respective impacts, thereby improving hydrologic predictions. Addressing this issue worldwide is challenging, however, largely due to the scarcity of precipitation ground truth and complex uncertainty interactions. Therefore, we propose an efficient uncertainty quantification framework for ensemble streamflow prediction, which keeps different uncertainty sources separable through hierarchical Bayesian inference. Satellite-based QPE uncertainty is characterized by a novel near-realtime quasi-global satellite-only ensemble precipitation dataset (STREAM-Sat), which is completely independent of ground-based precipitation measurements. Model parameter uncertainty in a distributed physics-based hydrologic model is inferred by an Iterative Ensemble Smoother (IES). To illustrate the impact and limitations of precipitation uncertainty, we compared ensemble streamflow predictions driven by both model parameter and satellite precipitation uncertainties and ensemble streamflow predictions driven by model parameter uncertainty and deterministic QPE. We demonstrate that the quantification of satellite-based QPE uncertainty notably improves the accuracy and reliability of streamflow predictions. This study also lays a foundation for satellite-based streamflow prediction in ungauged regions.

<div class="text-center mt-4">
  <img data-src="{{ 'assets/images/proj22_2.png' | relative_url }}" class="lazy w-100 rounded" src="{{ '/assets/images/empty_300x200.png' | relative_url }}" alt="Hydrologic Modeling Uncertainty Quantification">
</div>
