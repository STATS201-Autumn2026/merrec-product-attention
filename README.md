# MerRec Product-Level Observable Attention

## Project Overview

This repository contains an exploratory analysis of product-level observable attention using the MerRec dataset.

The project examines how observed attention is distributed across product groups within e-commerce categories and explores product-level signals associated with attention differences.

## Dataset

The processed dataset is available on Hugging Face:

https://huggingface.co/datasets/DKU-STATS201-Autumn2026/merrec-product-attention

The released dataset contains 4,874 product groups and 10 variables.

## Repository Contents

- `midterm_workshop.ipynb`: Notebook containing the data sampling, processing, and exploratory analysis.
- The processed dataset is hosted on Hugging Face.

## Reproducibility

The notebook uses Python, pandas, and Hugging Face Datasets. Run the notebook cells in order to reproduce the sampling, aggregation, and exploratory analysis.

## Limitations

The analysis uses a shuffled sample of 10,000 event records rather than the full dataset. Event counts measure observed interactions, not impressions or algorithmic exposure. Therefore, the results should be interpreted as exploratory evidence about observable attention, not direct measures of platform visibility or causal effects.
