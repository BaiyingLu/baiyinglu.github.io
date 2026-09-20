---
layout: page
title: HealthMine
description: A mobile health platform that unifies fragmented wearable data streams to support diabetes management.
img: assets/img/healthminelogo.png
importance: 1
category: research
related_publications: true
---

Wearable and mobile devices now make it possible to continuously monitor physiological, behavioral, and environmental signals outside the clinic. But most of these devices operate in isolation: a continuous glucose monitor knows nothing about the wearer's activity, sleep, or context, and vice versa. The result is a set of disconnected data streams that individually capture only a narrow slice of a person's health.

**HealthMine** addresses this gap by integrating disparate streams from consumer and medical-grade devices into a single research platform, so that health-relevant data can be interpreted in context rather than in isolation.

## What I built

- **Cross-platform mobile clients** in Kotlin (Android) and Flutter, with authenticated background synchronization from the Dexcom CGM and Fitbit APIs for continuous, unattended data collection.
- **Backend services on Google Cloud Platform** written in Go, with Firebase for user management and scalable storage of high-frequency time-series sensor data.
- **End-to-end research data pipelines** spanning study design, ingestion, preprocessing, feature engineering, and statistical analysis — reused across multiple digital health studies in the lab.

## Ongoing user study

Our team is actively recruiting for a user study on this project. We invite anyone over 18 years of age who has diabetes, uses a Dexcom/Freestyle Libre continuous glucose monitor, and owns an Android phone to consider participating. Please email [ah-lab@dartmouth.edu](mailto:ah-lab@dartmouth.edu) to learn more and sign up.
