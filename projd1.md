---
layout: default
title: Satellite Precipitation Error Modeling
permalink: /showcase/proj1
show: true
date: 2024-11-04 00:01:00 +0800
---

# Satellite-based Precipitation Error Modeling

## Overview
 Satellite‐based precipitation observations can provide near‐global coverage with high
 spatiotemporal resolution in near‐realtime. Their utility, however, is hindered by oftentimes large uncertainties
 that vary substantially in space and time. This problem is particularly pronounced in regions which lack dense
 ground‐based measurements to quantify or reduce such uncertainty. Since this uncertainty is, by definition, a
 random process, probabilistic representations are needed to advance their operational application. Ensemble
 methods, in which uncertainty is depicted via multiple realizations of precipitation fields, have been widely used
 in numerical weather and climate prediction, but rarely in satellite contexts. Creating such an ensemble dataset is
 challenging due to the complexity of observational uncertainties and the scarcity of “ground truth” to
 characterize them. In this study, we attempt to resolve these two challenges and propose the first quasi‐global
 (covering all continental land masses within 50°N‐50°S) satellite‐only ensemble precipitation dataset
 (STREAM‐Sat), derived entirely from NASA's Integrated Multi‐SatellitE Retrievals for Global Precipitation
 Measurement (IMERG) and GPM's radar‐radiometer combined precipitation product (2B‐CMB). No ground
based measurements are used to generate STREAM‐Sat, and it is suitable for near‐realtime use without
 extending the 4‐hr latency and 0.1°, 30‐min spatiotemporal resolution of IMERG Early. We compare
 STREAM‐Sat against several precipitation datasets, including global satellite‐based, rain gage‐based,
 atmospheric reanalysis, and merged products. While our proposed approach faces some limitations and is not
 universally superior to the comparison datasets in all respects, it does hold relative advantages due to its unique
 combination of accuracy, resolution, rainfall spatiotemporal structure, latency, and utility in hydrologic and
 hazard applications

<div class="text-center mt-4">
  <img data-src="{{ 'assets/images/proj11_2.png' | relative_url }}" class="lazy w-100 rounded" src="{{ '/assets/images/empty_300x200.png' | relative_url }}" alt="STREAM-Sat Precipitation Map">
</div>
