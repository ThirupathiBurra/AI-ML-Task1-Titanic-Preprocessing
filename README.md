
# AI & ML Internship — Task 1

## 🎯 Objective:
To perform **data cleaning and preprocessing** on the Titanic dataset as part of the AI & ML internship.

## 📁 Dataset:
- [Titanic Dataset on Kaggle](https://www.kaggle.com/datasets/yasserh/titanic-dataset)
- File used: `Titanic-Dataset.csv`

## ✅ What I Did:
1. **Loaded and explored** the dataset
2. **Handled missing values** using median (for Age) and mode (for Embarked)
3. **Dropped high-missing column** (Cabin) for simplicity
4. **Encoded categorical variables**:
   - `Sex`: Label Encoding
   - `Embarked`: One-Hot Encoding
5. **Feature scaling** using `StandardScaler` on `Age` and `Fare`
6. **Detected and removed outliers** using boxplot and IQR method

## 🛠 Tools Used:
- Python
- Pandas
- NumPy
- Seaborn / Matplotlib
- Scikit-learn

## 📌 Output:
A clean, numeric, and ML-ready Titanic dataset.

