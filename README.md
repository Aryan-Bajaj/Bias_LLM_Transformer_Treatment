# Bias Detection and Mitigation Model

This repository contains a project focused on detecting and mitigating bias in machine learning models. The project includes scripts for preprocessing data, training multiple machine learning models, evaluating their performance, and measuring bias using various metrics. The goal is to ensure fairness and reduce bias in predictive analytics.

## Built With

- Python
- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn
- tabulate
- vaderSentiment
- BERT
- LSTM
- SVC
- RFC
- GBC

## Prerequisites

- Python 3.x
- Required libraries (can be installed via `requirements.txt`)

## Getting Started

1. Clone this repository:
    ```bash
    git clone https://github.com/Aryan-Bajaj/Bias_LLM_Transformer_Treatment.git
    cd Bias_LLM_Transformer_Treatment
    ```

2. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

3. Ensure you have the your own dataset in the project directory.

## Usage

1. **Preprocess Data**: Load and preprocess the data to handle missing values, encode categorical features, and apply transformations.
2. **Train Models**: Train Support Vector Machine (SVM), Random Forest, and Gradient Boosting classifiers on both male and female subsets of the data.
3. **Evaluate Models**: Evaluate the models using accuracy, False Positive Rate (FPR), and False Negative Rate (FNR).
4. **Bias Detection**: Measure disparate mistreatment across different groups and analyze the results.
5. **Outlier Detection**: Use Isolation Forest for outlier detection to improve model robustness.

## Features

- Data preprocessing including sentiment analysis and pseudonym generation.
- Training and evaluating multiple machine learning models.
- Bias detection using FPR, FNR, and disparate mistreatment metrics.
- Outlier detection with Isolation Forest.
- Detailed performance comparison and analysis.

## Algorithm

1. Load and preprocess data.
2. Encode categorical features and split data by gender.
3. Train SVM, Random Forest, and Gradient Boosting classifiers.
4. Evaluate model performance using accuracy, FPR, and FNR.
5. Calculate disparate mistreatment to detect bias.
6. Apply Isolation Forest for outlier detection.
7. Retrain models on cleaned data and reassess performance.

## Disclaimer

This project is for educational purposes only. The methodologies and results presented are based on the provided datasets and specific configurations.

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/Aryan_Bajaj/Bias_LLM_Transformer_Treatment.git
    ```
2. Navigate to the project directory:
    ```bash
    cd Bias_LLM_Transformer_Treatment
    ```
3. Install the dependencies:
    ```bash
    pip install -r requirements.txt
    ```

## Author

- **Your Name** - [your_github_username](https://github.com/your_github_username)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
