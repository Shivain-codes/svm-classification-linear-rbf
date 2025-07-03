# svm-classification-linear-rbf
Implementation of Support Vector Machines for linear and non-linear classification using Scikit-learn. Includes hyperparameter tuning, visualization of decision boundaries, and performance evaluation with cross-validation.
# SVM Classification - Linear & RBF Kernels

This project implements Support Vector Machines (SVM) for both linear and non-linear (RBF kernel) classification using Scikit-learn.  
It demonstrates model training, hyperparameter tuning, decision boundary visualization, and evaluation using cross-validation.

## 🚀 Features
- SVM with **linear** and **RBF** kernels  
- 2D decision boundary visualization  
- Hyperparameter tuning with GridSearchCV (C, gamma)  
- Cross-validation for performance evaluation  
- Clean, modular, well-documented Python code  

## 📂 Dataset
This project uses the Breast Cancer dataset provided by Scikit-learn:
```python
from sklearn.datasets import load_breast_cancer
⚙️ Installation
Requirememts :->
numpy  
matplotlib  
scikit-learn  


install dependencies :->
pip install -r requirements.txt
▶️ Usage
Run the main script:

nginx
Copy
Edit
python svm_classification.py
The script will:

Train SVM models with linear and RBF kernels

Visualize decision boundaries

Perform hyperparameter tuning

Output accuracy scores and best hyperparameters


📈 Example Outputs
Decision boundary plots

Accuracy scores for test data

Classification report

Best hyperparameters from GridSearchCV

📌 File Structure
bash
Copy
Edit
svm_classification.py      # Main implementation script
requirements.txt           # Python dependencies
README.md                  # Project documentation
