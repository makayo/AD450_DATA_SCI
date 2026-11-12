# Video Game Sales Correlations

## Overview

A Python data analysis project exploring relationships between video game sales across North America, Europe, Japan, and other global markets.

Using Pandas and Seaborn, the project calculates Pearson correlation coefficients and visualizes regional sales patterns through a heatmap.

## Technologies

- Python
- Pandas
- Seaborn
- Matplotlib
- Jupyter Notebook
- uv

## Key Findings

| Sales Regions            | Correlation | Relationship    |
| ------------------------ | ----------- | --------------- |
| North America vs. Global | 0.94        | Strong positive |
| Europe vs. Global        | 0.90        | Strong positive |
| Japan vs. Other Regions  | 0.29        | Weak positive   |

### Observations

- **North America:** Strongly correlated with worldwide sales, suggesting that games performing well in North America generally perform well globally.
- **Europe:** Also shows a strong relationship with global sales.
- **Japan:** Has a weaker relationship with other regional markets, potentially reflecting differences in gaming preferences, console popularity, and audience demographics.

Global sales include regional sales totals, which partly explains the strong correlations with North America and Europe.

Correlation indicates relationships between variables, not causation.

## Project Structure

```text
videogame-correlations/
├── README.md
├── pyproject.toml
├── uv.lock
├── sales_correlations.ipynb
└── video_game_sales.csv
```

## Getting Started

Install dependencies:

```bash
uv sync
```

Open `sales_correlations.ipynb` in VS Code or Jupyter Notebook and run all cells.

The included `video_game_sales.csv` contains the data needed to reproduce the analysis.

## Summary

Video game sales across global markets are positively correlated, but the strength of these relationships varies by region.

North American and European sales closely track worldwide performance, while Japan shows more distinct regional sales patterns.
