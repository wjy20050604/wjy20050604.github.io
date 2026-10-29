---
title: "Research"
permalink: /research/
layout: single
author_profile: true
---

My research explores the intersection of hydrology, physical modeling, and machine learning. Across these projects, I focus on making forecasts more useful under changing environmental conditions.

## Generalizable high-resolution urban flood forecasting

**2026 · Physics-guided spatiotemporal modeling**

**Research question.** How can a flood forecasting model transfer to cities with different terrain and hydrological responses?

The framework integrates terrain information and dynamic rainfall forcings to predict high-resolution water-depth maps. A mass-conservation loss introduces physical constraints without requiring explicit runoff labels. An encoder–decoder architecture compresses the spatial grid, uses a Transformer-based processor in the latent space, and reconstructs forecasts at the original **1 m resolution** for a **60-minute horizon**.

**My contributions:** methodology design, core code implementation, loss-function design, data preprocessing, and cross-city generalization experiments. Training uses multiple simulated city environments; zero-shot evaluation includes Los Angeles and San Francisco.

**Keywords:** physics-guided learning · mass conservation · zero-shot generalization · spatiotemporal modeling

---

## Water-level interval forecasting with TDSAN

**March–August 2025 · Hydropower reservoir forecasting**

**Research question.** How can a forecasting model handle temporal distribution shifts while representing predictive uncertainty?

I proposed the **Temporal Distribution Smoothing Alignment Network (TDSAN)**, integrating temporal distribution alignment with domain-adversarial learning for reservoir water-level prediction. The work addresses the challenges of non-stationary hydrological time series and interval forecasting.

**My contributions:** framework and architecture design, methodology development, comparative experiments, and systematic validation.

**Output:** first-author paper accepted in *Journal of Hydrology*.

[Read the paper →](https://doi.org/10.1016/j.jhydrol.2026.135360)

---

## Real-time flood forecasting and graded defense in mountainous cities

**2025–2026 · Guiyang Penshuichi flood case study**

**Research question.** How can physical simulation help overcome the scarcity of extreme flood observations?

A physics-guided data augmentation pipeline uses the **Xinanjiang (XAJ) model** to generate **8,000 synthetic scenarios**. A hybrid **BiLSTM–Multi-Head Attention** forecasting network captures temporal dependencies and hydrological lag effects. Forecasts inform quantitative risk assessment and graded flood defense.

**My contributions:** end-to-end methodology design, model implementation, physics-based data augmentation, baseline comparisons, and ablation experiments.

**Output:** first-author manuscript under review at *Journal of Hydrology: Regional Studies*.

---

## Mid-to-long-term solar irradiance prediction with CASTformer

**February–August 2025 · Renewable energy forecasting**

**Research question.** How can a model capture the nonlinear, non-stationary, and multiscale dynamics of solar irradiance?

**CASTformer** combines channel attention, STL decomposition, and Transformer-based feature fusion for mid-to-long-term irradiance prediction in photovoltaic systems.

**My contributions:** model implementation and optimization, data cleaning and normalization, decomposition visualization, and manuscript preparation.

**Output:** fourth-author manuscript submitted to *Electrical Engineering*.
