# Iris-Classification-with-Artificial-Neural-Networks-ANN
End-to-end ML pipeline on the Iris dataset using Keras-based models: a baseline Feedforward Neural Network and an Autoencoder-enhanced FFNN. Includes preprocessing, outlier handling, dimensionality reduction, hyperparameter tuning, and rich visualizations (t-SNE, heatmaps). Final notebook: ANN-CW-12th-Final.ipynb.


Dataset: Iris dataset from the UCI Machine Learning Repository  
Classes: Setosa, Versicolour, Virginica  
Features: Sepal Length, Sepal Width, Petal Length, Petal Width

## Models Implemented
- Feedforward Neural Network (FFNN) using Keras
- Autoencoder + FFNN for dimensionality reduction and classification

## Repository Structure
```
abuabdot-sem2/
├── ANN-CW-12th-Final.ipynb      ← Final working notebook
├── requirements.txt             ← Python environment dependencies
├── other *.ipynb files          ← Iterative development notebooks
```

## Features & Techniques
- Exploratory Data Analysis (EDA)
- Feature scaling and data splitting
- Feedforward Neural Network with Keras
- Autoencoder-based dimensionality reduction
- Model evaluation using:
  - Accuracy
  - Precision
  - Recall
  - F1-score
  - Confusion Matrix
  - t-SNE visualization

## Getting Started
1. Clone this repository:
   ```bash
   git clone https://github.coventry.ac.uk/abuabdot/abuabdot-sem2.git 
   cd abuabdot-sem2
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Open the final notebook:
   - `ANN-CW-12th-Final(2).ipynb`

4. Run all cells in Google Colab or Jupyter Notebook.

## Results Summary

### Feedforward Neural Network (FFNN)
- Accuracy: 95.65%
- Precision: 1.00 (Setosa), 1.00 (Versicolour), 0.88 (Virginica)
- Recall: 1.00 (Setosa), 0.88 (Versicolour), 1.00 (Virginica)
- F1-Score: 1.00 (Setosa), 0.93 (Versicolour), 0.93 (Virginica)

### Autoencoder + FFNN
- Accuracy: 73.91%
- Precision: 1.00 (Setosa), 1.00 (Versicolour), 0.88 (Virginica)
- Recall: 1.00 (Setosa), 0.88 (Versicolour), 1.00 (Virginica)
- F1-Score: 1.00 (Setosa), 0.93 (Versicolour), 0.93 (Virginica)
