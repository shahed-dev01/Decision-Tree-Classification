# Decision-Tree-Classification
# 🚢 Titanic Survival Prediction using Decision Tree

This is an end-to-end Machine Learning project that predicts whether a passenger survived the Titanic disaster based on features like age, sex, passenger class, and family size.



## 📌 Project Overview
The goal of this project is to build a classification model using the **Decision Tree** algorithm. We performed extensive data cleaning, feature engineering, and hyperparameter tuning to achieve a high accuracy score.

## 🛠️ Tech Stack
- **Language:** Python 3.x
- **Libraries:** Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn

## 📊 Key Steps Performed
1. **Data Cleaning:** Handled missing values for 'Age' and 'Embarked'.
2. **Feature Engineering:** - Created a new feature `FamilySize` by combining `SibSp` and `Parch`.
   - Dropped redundant columns to improve model efficiency.
3. **Data Encoding:** Converted categorical data (`Sex`, `Embarked`) into numerical format.
4. **Model Building:** - Initial model using `DecisionTreeClassifier`.
   - Tuned hyperparameters (`max_depth=3`, `criterion='entropy'`) to prevent overfitting.
5. **Evaluation:** Achieved an accuracy of **~80%** on the test set.
6. **Visualization:** Plotted the Decision Tree and Feature Importance chart.

## 📈 Results
- **Accuracy Score:** 0.7988 (Approx 80%)
- **Feature Importance:** The model identified **'Sex'** as the most significant factor in survival.



## 🚀 How to Run
1. Clone the repository:
   ```bash
   git clone [https://github.com/shahed-dev01/Decision-Tree-Classification.git](https://github.com/shahed-dev01/Decision-Tree-Classification.git)
2. Install dependencies:
   pip install numpy pandas scikit-learn matplotlib seaborn
3. 📜 License
This project is licensed under the MIT License.
