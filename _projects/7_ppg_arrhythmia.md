---
layout: page
title: Arrhythmia Detection from Smartwatch PPG
description: Detecting and counting ectopic beats from consumer smartwatch photoplethysmography at scale.
img: assets/img/7.jpg
importance: 2
category: industry
related_publications: true
---

Photoplethysmography from a consumer smartwatch is noisy, motion-corrupted, and indirect compared to an ECG — but it is worn continuously by millions of people, which makes it uniquely suited to catching intermittent cardiac events that a clinical recording would miss.

This work, done with the Digital Health team at **Samsung Research America**, asked whether ectopic beats can be reliably detected _and counted_ from wrist PPG alone.

## Contributions

- Designed and implemented a **scalable end-to-end data pipeline** to ingest, preprocess, and manage **over 1 million real-world smartwatch PPG segments**, enabling large-scale training and evaluation.
- Built and optimized deep learning models — ResNet, VGG, and attention-based architectures — reaching **>85% F1** for arrhythmia detection while reducing per-segment count estimation error to **<0.05 MAE**.
- Integrated arrhythmia detection as a task in a **multimodal healthcare foundation model**, contributing reusable components to an internal ML platform used by several downstream teams.

Published at ICASSP 2026 {% cite Lu2026_ICASSP %}.

_Work conducted during an industry internship; described here at the level of publicly shareable methods and outcomes._
