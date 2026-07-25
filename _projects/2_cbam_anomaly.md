---
layout: page
title: CBAM Anomaly Detection
description: Attention-guided autoencoder for one-class anomaly detection and localization
img:
importance: 2
category: research
---

An attention-guided convolutional autoencoder for **one-class anomaly detection and localization** on CIFAR-10, combining **CBAM (Convolutional Block Attention Module)** with reconstruction-based anomaly scoring.

Training uses only normal samples; anomalies are identified through reconstruction error, while the attention maps provide spatial localization of where the anomaly occurs — an interpretability benefit that plain autoencoders lack.

**Stack:** PyTorch, CBAM, convolutional autoencoders

[View on GitHub](https://github.com/Rashiin/cbam-autoencoder-anomaly-detection)
