# Iris Flower Classification
## CodeAlpha Data Science Internship — Task 1

## 📌 Overview
A Machine Learning classification project that trains a Random Forest model to classify Iris flowers into three species (Setosa, Versicolor, Virginica) based on sepal and petal measurements. Achieved 100% accuracy on the test set.

## 🛠️ Tools & Libraries
- Python
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## 📓 Notebook Structure
1. **Data Overview** — Loading dataset, understanding shape, columns and basic statistics
2. **Data Cleaning** — Checking missing values, dropping unnecessary Id column
3. **Data Visualization** — Species distribution, pairplot, correlation heatmap, boxplots
4. **Model Building** — Label encoding, train/test split, Random Forest Classifier training
5. **Model Evaluation** — Accuracy score, classification report, confusion matrix
6. **Feature Importance** — Which features contributed most to classification
7. **Key Insights & Conclusions** — Summary of findings

## 🔍 Key Insights
- Random Forest Classifier achieved **100% accuracy** on the test set
- **Petal Length and Petal Width** are the most important features for classification
- **Iris-setosa** is the most clearly separable species
- **Iris-versicolor and Iris-virginica** have slight overlap but are still perfectly classified
- The confusion matrix confirms zero misclassifications on all 30 test samples

## 📁 Dataset
- `Iris.csv` — 150 samples of Iris flowers with 4 measurements and species label

## ▶️ How to Run
1. Clone the repository:
```bash
git clone https://github.com/mabdulrehman1319/CodeAlpha_Iris_Flower_Classification.git
```
2. Install required libraries:
```bash
pip install -r requirements.txt
```
3. Open `Iris_Flower_Classification.ipynb` in Jupyter Notebook or VS Code
4. Run all cells

## 👤 Author
**Muhammad Abdul Rehman**
CodeAlpha Data Science Internship
