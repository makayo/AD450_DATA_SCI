# Network Intrusion Detection — CICIDS2017

AD450 Data Science | Week 9

## Overview

Exploratory data analysis and visualization of 61,381 network
flows across 15 cybersecurity traffic classifications.

## Dataset

- [CICIDS2017 — Kaggle](https://www.kaggle.com/datasets/datcolabssnet/cicids2017-network-attack-detection-dataset)
- [Original Research Dataset — UNB](https://www.unb.ca/cic/datasets/ids-2017.html)

## Visualizations

| Visualization | Focus                                        |
| ------------- | -------------------------------------------- |
| Line Chart    | Packet volume across flow duration intervals |
| Bar Chart     | Traffic classification distribution          |
| Heatmap       | Pearson feature correlations                 |
| Scatter Plot  | Flow duration versus transmitted data volume |

## Key Findings

- Significant class imbalance across traffic classifications.
- Strong correlation (0.98) between forward and backward packet counts.
- Negligible correlation (0.039) between flow duration and transmitted data volume.
- The largest observed traffic volume was classified as benign.

## Setup

Install dependencies:

    uv sync

Launch Jupyter Notebook:

    uv run jupyter notebook

Open `data_visualization_project.ipynb` and run all cells.

## Tech Stack

Python · Pandas · NumPy · Matplotlib · Seaborn · Jupyter Notebook · uv

## Limitations

The sampled dataset represents controlled cybersecurity experiments,
not real-world attack prevalence. Correlation does not establish
causation.
