---
layout: default
title: Data-Driving Hydrologic Modeling Uncertainty Quantification
permalink: /showcase/proj3
show: true
date: 2024-11-06 00:01:00 +0800
---

# Data-Driving Hydrologic Modeling Uncertainty Quantification

## Overview
Accurate and timely flood warnings are essential for reducing flooding risks. Achieving this objective requires both accurate data and careful model parameterization. The absence of high-resolution ground-based precipitation observations in many locations leaves lower-accuracy satellite-based precipitation products as one of the few alternatives. At the same time, advancements in deep learning-based flood prediction have led to improvements in both accuracy and computational efficiency. Despite the progress made by integrating satellite-based precipitation data and deep learning-based hydrologic models, the quantification of uncertainty—stemming from both input data and model components—remains largely unexamined. This gap results in less reliable predictions, as overfitting and explainability   are common concerns in deep learning models. In this paper, uncertainties arising from satellite-based precipitation inputs, limitations in data quantity, and model parameters are jointly addressed. Data limitation uncertainty is quantified using a mixture density network, while uncertainty in neural network parameters is captured through variational inference. Precipitation uncertainty is inferred from the deep learning-based hydrologic model—without the need for higher-accuracy “ground truth” precipitation data—and is represented as a probabilistic distribution. Our results demonstrate that this integrated approach to uncertainty quantification enhances both the prediction accuracy and the explainability of ensemble streamflow predictions. It provides a foundation for “uncertainty-aware” deep learning-based flood prediction. 
<div class="text-center mt-4">
  <img data-src="{{ 'assets/images/proj33_2.png' | relative_url }}" class="lazy w-100 rounded" src="{{ '/assets/images/empty_300x200.png' | relative_url }}" alt="Hydrologic Modeling Uncertainty Quantification">
</div>
