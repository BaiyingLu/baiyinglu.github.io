---
layout: page
title: Reproducibility in Glucose Prediction
description: Can published deep learning models for blood glucose prediction be reproduced — and do they generalize?
img: assets/img/4.jpg
importance: 3
category: research
related_publications: true
---

Deep learning for blood glucose prediction has advanced quickly, and these models are intended for safety-critical settings such as artificial pancreas systems. Yet little is known about whether published results can actually be reproduced, or whether they hold up on populations other than the one they were developed on.

## What we did

We reviewed **67 recent papers** proposing deep learning methods for glucose prediction to identify recurring reproducibility obstacles. We then reimplemented **eight representative methods** and evaluated them under a standardized framework covering technical, statistical, and conceptual reproducibility — using **over 1.36 million CGM samples (5,061 days) from 128 individuals with type 1 diabetes** across three public datasets: OhioT1DM, DiaTrend, and T1DEXI.

## What we found

- The models were largely **technically and statistically reproducible** — reimplementations behaved consistently on their original data.
- **Conceptual reproducibility was limited**: performance degraded when models were moved to datasets reflecting different diabetes management patterns.
- Prediction error was **strongly tied to individual glycemic control**. Participants who spent less time in the target range (70–180 mg/dL) were consistently predicted worst — precisely the people such systems most need to serve.

These results argue for greater transparency, more diverse datasets, standardized evaluation practices, and accessible code before these models can be relied upon clinically {% cite Lu2026_PLOSDigitalHealth %}.
