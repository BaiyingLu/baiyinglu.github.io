---
layout: page
title: Mealtime Prediction
description: Personalized LSTM models that forecast when people with type 1 diabetes will eat, from insulin pump data alone.
img: assets/img/mealtimelogo.png
importance: 4
category: research
related_publications: true
giscus_comments: true
---

Post-meal hyperglycemia is one of the most common failure modes in type 1 diabetes management, and it is usually caused by something mundane: an insulin dose that was missed, or taken too late. A system that knew _when_ someone was about to eat could nudge them to bolus beforehand.

This project asked whether that is possible using data people already generate — the logs from their insulin pump — with no additional sensors, no manual input, and no burden on the user.

## Approach

Using two independent datasets containing **over 45,000 meal logs from 82 patients**, we first characterized how regular real-world mealtime patterns actually are, then trained **personalized LSTM models** to predict upcoming meals for each individual.

## Findings

- Roughly **60% of participants** had irregular and inconsistent mealtime patterns that shifted both across the day and across months of their own history — undermining the assumption that a population-level or fixed-schedule model would work.
- Despite that irregularity, personalized models reached an **average F1 score above 95%** with **fewer than 0.25 false positives per day**, a false-alarm rate low enough to be tolerable in a real nudging system.

Together these results lay the groundwork for a meal prediction system that prompts patients to administer bolus insulin _before_ eating, reducing post-meal highs {% cite Lu2024 %}.
