# Term Deposit Subscription Prediction Using SVM

This project is a Python-based machine learning application that uses a Support Vector Machine (SVM) model to predict whether a customer will subscribe to a term deposit based on their banking behavior and demographic details.

## Features

- **Data Loading and Preprocessing**: Load and clean banking data for training and evaluation.
- **Feature Selection and Scaling**: Select relevant features and scale them to improve model performance.
- **SVM Model Training**: Train an SVM model using the Scikit-learn library.
- **Model Evaluation**: Evaluate the model using metrics such as accuracy, precision, recall, and F1-score.
- **Prediction**: Make predictions on new customer data.

## Requirements

- Python 3.8+
- Jupyter Notebook
- Libraries:
  - `numpy`
  - `pandas`
  - `scikit-learn`
  - `matplotlib`

Install the required libraries using pip:

```bash
pip install numpy pandas scikit-learn matplotlib
```

## Dataset

The project uses a banking dataset containing customer information and their response to term deposit offers. The dataset includes attributes such as age, job, marital status, education, balance, and campaign-related information.

## Usage

1. Clone this repository to your local machine:

   ```bash
   git clone https://github.com/shafat21/Bank-Term-Deposit-Prediction-Using-SVM.git
   cd TermDepositPrediction
   ```

2. Open the Jupyter Notebook:

   ```bash
   jupyter notebook TermDepositPrediction.ipynb
   ```

3. Run the cells step-by-step to:
   - Preprocess the data
   - Train the SVM model
   - Evaluate the model
   - Test with new data

## Output

- Confusion matrix to evaluate model performance.
- Classification report including precision, recall, and F1-score.
- Visualizations of the decision boundary (if applicable).

## Contributions

Feel free to fork this repository and contribute to improving the model or adding new features. Pull requests are welcome!

## License

This project is licensed under the MIT License. See the LICENSE file for details.

## Acknowledgements

- [Scikit-learn Documentation](https://scikit-learn.org/)
- [Pandas Documentation](https://pandas.pydata.org/)
- [Matplotlib Documentation](https://matplotlib.org/)

---
