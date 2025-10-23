# Hybrid Phishing Detection using Hybrid Feature + Hybrid Ensemble Model

This repository contains the reproducible workflow and ethical documentation for the research paper *"Hybrid Phishing Detection for Enhanced Email Security"*.

## Overview
The project investigates a hybrid feature extraction method (combining lexical, host-based, and content-based attributes)
and a hybrid ensemble classification strategy (Random Forest + XGBoost + LightGBM) to improve phishing detection accuracy.

### Objectives
- Combine diverse feature types into a single hybrid vector.
- Train and compare multiple ensemble models for performance benchmarking.
- Evaluate precision, recall, F1-score, and ROC-AUC on benchmark phishing datasets.

## Repository Structure
| Folder / File | Description |
|----------------|-------------|
| `notebooks/` | Jupyter notebooks implementing feature extraction, model training, and evaluation |
| `data/` | Processed datasets used for experiments |
| `metadata/DATA_README.md` | Provenance and preprocessing logs |
| `ETHICS.md` | Ethical statement about dataset use and research integrity |
| `README.md` | Project overview and documentation |

## Dataset Sources

This project utilizes open and publicly available phishing detection datasets:

1. [Phishing Dataset – Mendeley Data](https://data.mendeley.com/datasets/h3cgnj8hft/1)
2. [Phishing Websites – UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/327/phishing+websites)
3. [Phishing Dataset for Machine Learning – Kaggle](https://www.kaggle.com/datasets/shashwatwork/phishing-dataset-for-machine-learning)
4. [Tranco Top Sites List](https://tranco-list.eu/)

