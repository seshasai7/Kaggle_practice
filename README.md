# 🧼 Messy Food Waste Prediction - Data Cleaning with Pandas

## 📌 Overview
This repository contains **data cleaning and preprocessing scripts** for the **Messy Food Waste Prediction Dataset** from Kaggle. The dataset presents real-world challenges such as **inconsistent categorical values, missing data, duplicate records, and extreme outliers**. The goal of this project is to **prepare high-quality data** for further analysis and machine learning models.

## 📂 Dataset Information
- **Source:** [Kaggle - Messy Food Waste Prediction](https://www.kaggle.com/competitions/messy-food-waste-prediction-dataset/overview)
- **Data Challenges:**
  - Inconsistent categorical data (e.g., `MeAt`, `MEAT`, `meat`)
  - Missing values in key columns
  - Duplicate records affecting data integrity
  - Extreme outliers (e.g., unrealistic temperature values)

## 🚀 Data Cleaning Steps
The dataset was cleaned using **Python & Pandas**, following best practices in data preprocessing:

1. **Handled Inconsistent Categorical Values**
   - Standardized text formats (e.g., `MeAt`, `MEAT` → `Meat`).
   - Fixed spelling errors and unified categories.

2. **Managed Missing Data**
   - Analyzed missing values in numerical & categorical columns.
   - Used **mean/median imputation** for numerical values.
   - Applied **mode imputation** or **category assignment** for missing categorical data.

3. **Removed Duplicates**
   - Identified and dropped duplicate rows to ensure unique records.

4. **Addressed Extreme & Unrealistic Values**
   - Set **thresholds for valid data ranges** (e.g., temperatures must be between **10°C and 45°C**).
   - Replaced outliers with median values.

## 🛠️ Technologies Used
- **Python** 🐍
- **Pandas** 📊
- **Jupyter Notebook** 📓

## 🎯 Results & Insights
- The cleaned dataset is **free from duplicates, missing values, and extreme outliers**.
- Categorical inconsistencies were resolved, making the dataset more structured.
- The processed data is now **ready for exploratory data analysis (EDA) and machine learning models**.

## 📌 How to Use
1. Clone this repository:  
   ```bash
   git clone https://github.com/seshasai7/Kaggle_practice.git
Navigate to the repository:
cd Kaggle_practice
Open and run data_cleaning.ipynb in Jupyter Notebook.
💡 Contributions & Suggestions
If you have any suggestions for improving data cleaning techniques or know of better/easier methods, feel free to open an issue or submit a pull request! 🛠️🚀

📢 Connect with Me
🔗 LinkedIn: https://www.linkedin.com/in/sesha-sai-bellamkonda-99292324a/
📧 Email: seshasai39@gmail.com

📌 Want to Try the Dataset?
The dataset and data cleaning code are available in this repository. Feel free to explore, test your skills, and optimize the cleaning process! 🔥

📌 Rate this repo if you found it helpful!

