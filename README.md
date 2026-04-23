# MGNREGA Causal Impact Analysis

This project estimates the causal impact of MGNREGA participation on household consumption using modern causal inference techniques.

## Methods Used
- Naive comparison vs causal estimation
- DAG-based reasoning
- Frisch-Waugh-Lovell (FWL)
- Double Machine Learning (DML)
- Causal Forests for heterogeneity
- Targeting policy simulation

## Key Insights
- Naive estimates are biased due to selection
- After controlling for confounders, MGNREGA increases consumption
- Benefits are heterogeneous across households
- Targeted allocation improves welfare under budget constraints

## Files
- `notebook/mgnrega_causal_analysis.ipynb`: Full analysis pipeline

## Tools
- Python
- pandas, numpy
- econml
- scikit-learn

## Note
This project focuses on causal inference methodology and policy implications.
