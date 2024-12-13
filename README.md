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
├── data/               # Contains raw and processed datasets
├── notebooks/          # Jupyter notebooks for experimentation and analysis
├── src/                # Source code for ML models and utility functions
├── results/            # Outputs and performance metrics
├── README.md           # Project overview (this file)
```

## Installation

Clone the repository and install the required dependencies:

```bash
git clone https://github.com/your-username/financial-stress-index.git
cd financial-stress-index
pip install -r requirements.txt
```

## Usage

### Running the Models

1. Preprocess the data:
   ```bash
   python src/preprocess.py
   ```

2. Train models:
   ```bash
   python src/train_models.py
   ```

3. Evaluate results:
   ```bash
   python src/evaluate.py
   ```

## Results

The project demonstrates how restructuring the Financial Stress Index using machine learning techniques significantly improves accuracy in predicting financial stress events. The rolling window and AR-X framework were particularly effective in capturing temporal patterns.

## Contributing

Contributions are welcome! If you have ideas for improvement or additional features, feel free to fork the repository and submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments

- [LightGBM Documentation](https://lightgbm.readthedocs.io/)
- [Scikit-learn Documentation](https://scikit-learn.org/)
- Research on AR-X frameworks and financial indices.
