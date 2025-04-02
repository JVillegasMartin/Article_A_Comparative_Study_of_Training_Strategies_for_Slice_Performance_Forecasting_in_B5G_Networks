# Dataset for "A Comparative Study of Training Strategies for Slice Performance Forecasting in B5G Networks"

This repository contains the dataset utilized in the research article titled "A Comparative Study of Training Strategies for Slice Performance Forecasting in B5G Networks."

## Table of Contents

- [Dataset Description](#dataset-description)
- [Repository Structure](#repository-structure)
- [Data Usage](#data-usage)
- [License](#license)

## Dataset Description

This repository contains synthetic datasets designed to emulate the behavior and characteristics of measurements and metrics collected from B5G network slices. These synthetic data were generated to analyze and compare various training strategies for performance forecasting, as discussed in the article. The datasets are stored in Parquet format to ensure efficient storage and quick access.

## Repository Structure

- `LICENSE`: Specifies the terms under which the dataset can be used.
- `README.md`: This document, providing an overview of the dataset and usage guidelines.

## Data Usage

To load the dataset in Python using the `pandas` library:

```python
import pandas as pd

# Load the dataset
df_Train = pd.read_parquet('data/slice_performance_data.parquet')
df_Test = pd.read_parquet('')
```
## Data Availability

The dataset associated with this work is available on Zenodo.  
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.15125203.svg)](https://doi.org/10.5281/zenodo.15125203)
