---
layout: page
title: MVG-VQA
description: No-reference video quality assessment fusing spatial MVG features with temporal features via XGBoost regression
img:
importance: 1
category: research
---

A no-reference VQA system fusing **spatial MVG features** (Log-Gabor, LBP, edge statistics) with **temporal features** (frame-to-frame motion, flicker) via XGBoost regression. Outperforms standard metrics on compression artifact and noise benchmarks across multiple NR-VQA datasets. Features were extracted in Python with hyperparameters tuned via cross-validation.