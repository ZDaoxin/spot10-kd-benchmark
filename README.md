# SPOTS10-KD-Benchmark

A benchmark and implementation of modern knowledge distillation methods on the SPOT-10 animal pattern dataset, including Logit Standardization, TTM, and WTTM.

This repository provides a clean benchmark for evaluating modern knowledge distillation (KD) techniques on the SPOT-10 dataset — a challenging greyscale animal pattern recognition dataset designed for low-light conditions.

We implement and compare the following KD methods:
- **Classical Knowledge Distillation** (Hinton et al.)
- **Logit Standardization (LS)**
- **Transformed Teacher Matching (TTM)**
- **Weighted TTM (WTTM)**

## 🔍 Motivation
While the original SPOT-10 paper used only classical KD, we extend its utility by introducing and evaluating more advanced distillation methods. This allows us to explore their effectiveness on low-contrast, texture-based tasks in a compact but realistic setting.

## 📈 Contributions
- 📦 First application of LS, TTM, and WTTM on SPOT-10
- 🧪 Unified training and evaluation pipeline for reproducible experiments
- 📊 Performance comparison (validation & per-class accuracy)
- 📁 Per-sample disagreement analysis between distillation methods

## 🗂 Directory Structure
