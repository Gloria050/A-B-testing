# Cookie Cats A/B Testing Analysis

## Overview

This project analyzes the impact of progression gate placement in "Cookie Cats," a mobile puzzle game, through rigorous A/B testing methodology. We examine how moving the first gate from level 30 to level 40 affects user retention and engagement.

## Experimental Design

- **Group A (Control)**: First gate at level 30
- **Group B (Treatment)**: First gate at level 40
- **Sample**: 90,189 users randomly assigned upon installation

## Data Description

| Variable | Description |
|----------|-------------|
| `userid` | Unique user identifier |
| `version` | Treatment group (`gate_30` or `gate_40`) |
| `sum_gamerounds` | Game rounds played in first week |
| `retention_1` | 1-day retention (binary) |
| `retention_7` | 7-day retention (binary) |

## Methodology

Our analysis employs:
- Bootstrapped confidence intervals for retention metrics
- Hypothesis testing for equality of means
- Effect size quantification
- Visualization of retention curves

## Project Files

```
├── A/B Testing【Python】.ipynb
├── cookie_cats.csv
└── README.md
```

## Reproduction Steps

1. Environment: Python 3.9+
2. Dependencies: `pandas`, `numpy`, `scipy`, `matplotlib`, `seaborn`
3. Execute Jupyter notebook in sequence

## References

- Kohavi, R., et al. (2009). Controlled experiments on the web
- Imbens, G. W., & Rubin, D. B. (2015). Causal inference for statistics
- Seufert, E. B. (2014). Freemium economics# A-B-testing
