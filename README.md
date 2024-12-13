# Financial Stress Index Restructuring

This project focuses on restructuring the Financial Stress Index (FSI) using various types of financial index data. By leveraging advanced machine learning (ML) techniques, the project provides a robust and accurate approach to modeling and predicting financial stress.

## Overview

The methodology includes:

1. **Data Processing**: Analysis using both non-differenced and differenced models.
2. **Machine Learning Models**:
    - Linear Regression
    - LightGBM
    - Random Forest
    - Multi-Level Perceptron (MLP)
    - Simple Recurrent Neural Network (SimpleRNN)
    - Auto Regressive Exogenous Input (AR-X)
3. **Frameworks**:
    - Implemented AR-X framework with various ML models.
    - Utilized a rolling window mechanism to enhance model accuracy.

## Key Features

- Comparison of machine learning techniques on raw and differenced datasets.
- Integration of AR-X framework for structured time-series modeling.
- Application of rolling windows to capture temporal dependencies and improve predictive performance.

## Project Structure

```
financial-stress-index/
├── Index data/               # Contains raw and processed datasets
├── FSI_(on-levels-model)/          # Modelling was done on levels without differencing the data
├── FSI_(Differenced_model)/                # Modelling was done on differenced data
├── README.md           # Project overview (this file)
```

## Installation

Clone the repository and install the required dependencies:

```bash
git clone https://github.com/your-username/financial-stress-index.git
cd financial-stress-index
pip install -r requirements.txt
```



## Results

The project demonstrates how restructuring the Financial Stress Index using machine learning techniques significantly improves accuracy in predicting financial stress events. The rolling window and AR-X framework were particularly effective in capturing temporal patterns as it spiked higher than the orginal FSI. 

## Acknowledgments

- [LightGBM Documentation](https://lightgbm.readthedocs.io/)
- [Scikit-learn Documentation](https://scikit-learn.org/)
- Research on AR-X frameworks and financial indices.
