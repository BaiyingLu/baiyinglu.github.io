---
layout: page
title: Biosignal Compression Toolbox
description: Compression pipelines for wearable biosignals, achieving up to 130x reduction with under 2% information loss.
img: assets/img/5.jpg
importance: 5
category: research
related_publications: true
---

Longitudinal wearable monitoring produces enormous volumes of data, and storage cost becomes a real constraint on the scale of digital biomarker research. But biosignals cannot be compressed indiscriminately — the features that matter clinically must survive the round trip.

This project built and evaluated compression pipelines combining algorithmic and encoding-based methods, and characterized the trade-off between storage footprint and recoverability for each signal type.

## Methods evaluated

- **Algorithmic:** singular value decomposition, discrete cosine transform, biorthogonal discrete wavelet transform, autoencoders.
- **Encoding:** run-length encoding, Huffman encoding.
- **Signals:** ECG, PPG, accelerometry, electrodermal activity, and skin temperature.

Different signals favored different pipelines — direct compression with Huffman encoding for ECG and PPG, SVD with Huffman encoding for EDA and accelerometry, and the biorthogonal wavelet transform for skin temperature — reaching up to **130× compression with under 2% information loss**.

The resulting toolbox is released as open source through the Digital Biomarker Discovery Pipeline {% cite s21020516 %}.
