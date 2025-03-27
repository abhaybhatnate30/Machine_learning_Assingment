# Machine_learning_Assingment
# Machine Learning Assignment - Support Vector Machines (SVM)

This Jupyter Notebook explores the use of **Support Vector Machines (SVM)** with different kernel functions (Linear, Polynomial, and RBF) using the classic **Iris dataset**. The goal is to visualize how each kernel affects decision boundaries and to evaluate model performance based on training and testing accuracy.

## 📂 File
- `Machin_Learning_Assingment.ipynb`: Main notebook with full implementation and visualizations.

## 📊 Dataset
- **Iris Dataset** from `scikit-learn.datasets`: Contains 150 samples across 3 flower species (`setosa`, `versicolor`, `virginica`) with 4 features each.
- PCA (Principal Component Analysis) is used to reduce the dataset to 2 dimensions for decision boundary visualization.

## 🧠 Techniques Used
- **Support Vector Classification (SVC)** with:
  - Linear kernel
  - Polynomial kernel (degree=3)
  - Radial Basis Function (RBF) kernel
- **PCA** for dimensionality reduction
- **Train/Test Split** to evaluate generalization

## 📈 Results Summary
| Kernel     | Training Accuracy | Testing Accuracy |
|----------  |-------------------|------------------|
| Linear     | 96.20%            | 95.60%           |
| Polynomial | 95.2%             | 88.9%            |
| RBF        | 95.2%             | 95.6%            |

## 📌 Key Insights
- The **linear kernel** performs well for linearly separable data (e.g., `setosa` class).
- The **polynomial kernel** can overfit if the degree is high or the data is not complex enough.
- The **RBF kernel** balances complexity and generalization, making it effective for a wide range of datasets.

## 🛠️ Requirements
- Python 3.x
- Libraries:
  - `scikit-learn`
  - `matplotlib`
  - `numpy`

Install dependencies via pip:
```bash
pip install scikit-learn matplotlib numpy
**License**
This project is for educational use. Free to reuse with attribution.
