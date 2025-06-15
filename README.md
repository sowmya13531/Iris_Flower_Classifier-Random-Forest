## 🌼 Iris Flower Classification using Random Forest
This project demonstrates a basic machine learning workflow using the classic Iris dataset and Random Forest Classifier from scikit-learn.

# ✅ Project Summary
Dataset: Iris (150 samples, 3 classes)

Algorithm: Random Forest Classifier

Tools: Python, Pandas, scikit-learn, NumPy

Train/Test Split: 75% training, 25% testing (randomly assigned)

## 🧪 Dataset Information
# Features:
Sepal length (cm)

Sepal width (cm)

Petal length (cm)

Petal width (cm)


# Target:
Setosa

Versicolor

Virginica



# 📊 Model Performance
Accuracy: 93.75%
# Confusion Matrix:
Predicted     setosa  versicolor  virginica
Actual                            
setosa           13           0    0

versicolor        0           5    2

virginica         0           0   12

# 📁 Key Steps
1.Load and explore the Iris dataset

2.Convert species names to numeric labels

3.Split data into train/test using random uniform sampling

4.Train a RandomForestClassifier

5.Evaluate using confusion matrix and accuracy score


# 📦 Requirements
bash
``` pip install pandas scikit-learn numpy ```
bash
▶️ Run the notebook
You can run the code directly in Google Colab or any local Python environment.
Or simply clone it from my repo
## 📥 Clone This Repository

```bash
git clone https://github.com/sowmya13531/Iris_Flower_Classifier-Random-Forest.git
cd Iris_Flower_Classifier-Random-Forest

