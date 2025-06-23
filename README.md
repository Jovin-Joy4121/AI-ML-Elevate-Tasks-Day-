# 🚢 Titanic Dataset – Data Cleaning & Preprocessing (Google Colab Version)

This project demonstrates how to clean and prepare the Titanic dataset for machine learning using **Google Colab**. It walks through handling missing values, encoding, outlier removal, and feature scaling — all in a cloud environment.

---

## 📌 Objective

- Perform data cleaning on the Titanic dataset
- Use Google Colab for a no-install, browser-based workflow
- Generate boxplots and a cleaned CSV ready for model training

---

## 📂 Files Used

- `Titanic-Dataset.csv` — input file (uploaded manually in Colab)
- `titanic_cleaned.csv` — output file (downloadable in Colab)

---

## ⚙️ Technologies Used

- Python
- Pandas, NumPy
- Seaborn, Matplotlib
- Scikit-learn
- Google Colab

---

## 📊 Key Preprocessing Steps

1. **Load the Dataset**
   - Uploaded via Colab UI
2. **Handle Missing Values**
   - Fill `Age` with median
   - Fill `Embarked` with mode
   - Drop `Cabin`
3. **Convert Categorical Features**
   - Label encode `Sex`
   - One-hot encode `Embarked`
4. **Remove Irrelevant Columns**
   - `Name`, `Ticket`, `PassengerId`
5. **Detect and Remove Outliers**
   - Boxplot of `Age` and `Fare`
   - IQR method to remove extreme values
6. **Standardize Numeric Features**
   - `Age`, `Fare` scaled using `StandardScaler`
7. **Export Final Dataset**
   - Saved and downloaded as `titanic_cleaned.csv`

---

## ▶️ How to Run in Google Colab

1. Open the notebook in Colab.
2. Upload your `Titanic-Dataset.csv` when prompted.
3. Run all cells.
4. View plots and download the cleaned dataset automatically.

---

## 📷 Output

- `boxplot_before`: visualizing outliers in Age and Fare before removal
- Cleaned CSV: ready for ML model input

---

## 🔗 Resources

- [Google Colab](https://colab.research.google.com/)
- [Titanic Dataset on Kaggle](https://www.kaggle.com/datasets/yasserh/titanic-dataset)

---

## ✅ Result

Final dataset includes:
- Clean numeric and encoded categorical features
- No missing values
- No significant outliers
- Standardized scale for modeling

---

![download](https://github.com/user-attachments/assets/59276ccf-be6c-474d-9b91-1decec350590)
