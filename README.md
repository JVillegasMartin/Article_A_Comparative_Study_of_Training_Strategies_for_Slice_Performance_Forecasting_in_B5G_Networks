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

- `data/`: Contains the `slice_performance_data.parquet` file with the dataset.
- `metadata.json`: Provides detailed information about the dataset's variables, including descriptions and data types.
- `LICENSE`: Specifies the terms under which the dataset can be used.
- `README.md`: This document, providing an overview of the dataset and usage guidelines.

## Data Usage

To load the dataset in Python using the `pandas` library:

```python
import pandas as pd

# Load the dataset
df = pd.read_parquet('data/slice_performance_data.parquet')
```
## License

This dataset is made available under the CC0 1.0 Universal (CC0 1.0) Public Domain Dedication. You are free to copy, modify, distribute, and use the data, even for commercial purposes, without asking permission. While attribution is not legally required, it is appreciated.


