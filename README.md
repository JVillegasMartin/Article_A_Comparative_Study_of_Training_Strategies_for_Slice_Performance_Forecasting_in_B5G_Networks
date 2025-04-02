# Dataset for "A Comparative Study of Training Strategies for Slice Performance Forecasting in B5G Networks"

This repository originally hosted the dataset utilized in the research article titled "A Comparative Study of Training Strategies for Slice Performance Forecasting in B5G Networks." However, due to file size limitations, the complete dataset has been moved to Zenodo.

## Table of Contents

- [Dataset Description](#dataset-description)
- [Repository Structure](#repository-structure)
- [Data Usage](#data-usage)
- [Data Availability](#data-availability)

## Dataset Description

The dataset consists of synthetic canonical series designed to emulate the behavior and characteristics of measurements and metrics collected from B5G network slices. These synthetic data were generated after a detailed analysis of simulated data to identify seasonality and correlation patterns. The primary goal is to support the training and evaluation of various forecasting strategies for slice performance, as discussed in the article. The dataset is stored in Parquet format to ensure efficient storage and quick access.

## Repository Structure

- `LICENSE`: Specifies the terms under which the dataset can be used.
- `README.md`: This document, providing an overview of the dataset, usage guidelines, and information on data availability.

## Data Usage

To load the dataset in Python using the `pandas` library, you can use the following code:

```python
import pandas as pd

# Load the dataset (example)
df_train = pd.read_parquet('data/slice_performance_data_train.parquet')
df_test = pd.read_parquet('data/slice_performance_data_test.parquet')```

## Data Availability

The dataset associated with this work is available on Zenodo.  
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.15125203.svg)](https://doi.org/10.5281/zenodo.15125203)

