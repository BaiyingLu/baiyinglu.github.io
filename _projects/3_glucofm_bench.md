---
layout: page
title: GlucoFM-Bench
description: Benchmarking time-series foundation models for blood glucose forecasting.
img: assets/img/3.jpg
importance: 2
category: research
related_publications: true
---

Time-series foundation models promise strong zero-shot forecasting across domains. Blood glucose is a demanding test of that promise: the signal is high-frequency, highly non-stationary, and driven by unobserved exogenous events such as meals, insulin, and exercise.

**GlucoFM-Bench** is a systematic benchmark evaluating how well modern time-series foundation models and LLM-based architectures forecast blood glucose, compared against established deep learning baselines.

## Scope

- Evaluated **time-series foundation models** (Chronos, TimesFM), **LLM-for-time-series** approaches (TimeLLM), and conventional architectures (LSTM, Transformer) under a common protocol.
- Tested across **uni- and multimodal data** from both medical-grade and consumer wearables.
- Standardized preprocessing, forecast horizons, and evaluation metrics so that differences reflect the models rather than the experimental setup.

The benchmark provides a common reference point for whether general-purpose foundation models transfer to physiological forecasting, and where they still fall short of task-specific models {% cite Lu2026_GlucoFMBench %}.
