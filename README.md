# Beyond Labels: Visual Invariance in Self-Supervised Learning for Aramaic Bowls

This repository contains the dataset, extraction pipeline, and evaluation code for the research on spatial-cultural mapping of Aramaic incantation bowls from Late Antiquity using Self-Supervised Learning (SSL). 

Our approach systematically evaluates how different augmentation strategies—formulated as explicit hypotheses about visual identity—impact representation learning in highly degraded historical domains.

## 📖 Introduction

Aramaic incantation bowls present a challenging visual domain due to severe material degradation, irregular layouts, and ambiguous letter morphology. Traditional supervised learning struggles here due to the scarcity of reliable paleographic labels. 

This project facilitates the spatial-cultural mapping of these artifacts by capturing diverse ritual practices and regional writing conventions. Rather than relying on super-resolution methodologies, we leverage SSL to learn visual representations without explicit annotations. We evaluate how assumptions encoded in data augmentations shape embedding topology, cluster compactness, and inter-class separability.

## 🗄️ Dataset Overview

The curated dataset is derived from authentic historical materials, presenting conditions of extreme visual variability.

* **Source Material:** 32 Aramaic incantation bowls dated to Late Antiquity (4th-7th centuries CE).
* **Volume:** Approximately 8,600 extracted letter-like units (~260 units per bowl).
* **Annotations:** Baseline annotations, YOLO bounding box detections, and SAM segmentation masks.

*(See the GitHub Pages site for visual examples of preservation quality and dataset structure).*

## ⚙️ Extraction Pipeline

We utilize an automatic, multi-stage extraction pipeline to isolate letter instances consistently across diverse preservation conditions:

1.
