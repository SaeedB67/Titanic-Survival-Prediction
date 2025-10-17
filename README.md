# Titanic-Survival-Prediction

# 🛳️ Titanic Survival Prediction

This project uses machine learning to predict passenger survival on the Titanic based on passenger data such as age, gender, class, and more. It’s built in a Jupyter Notebook using Python and popular data science libraries.

---

## 📁 Project Structure

├── TitanicSurvivalPrediction.ipynb # Main Jupyter notebook
├── train.csv # Training dataset
├── test.csv # Test dataset
├── gender_submission.csv # Sample submission file

markdown
Copy code

---

## 🧠 Objective

Predict whether a passenger survived the Titanic disaster using supervised learning.  
The project is based on the **Kaggle Titanic: Machine Learning from Disaster** competition.

---

## ⚙️ Workflow

1. **Data Loading**
   - Loaded datasets (`train.csv`, `test.csv`).
   - Libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`.

2. **Exploratory Data Analysis (EDA)**
   - Visualized survival distribution by gender, class, and age.
   - Checked for missing values and correlations.

3. **Data Cleaning**
   - Filled missing values in `Age`, `Fare`, and `Embarked`.
   - Encoded categorical columns (`Sex`, `Embarked`).

4. **Feature Engineering**
   - Added derived features like `FamilySize` and `IsAlone`.
   - Normalized numerical data where needed.

5. **Model Building**
   - Trained multiple classifiers:
     - Logistic Regression
     - Random Forest
     - Support Vector Machine (SVM)
   - Compared model accuracy and performance.

6. **Prediction**
   - Generated survival predictions on the test dataset.
   - Exported results to `predictions.csv`.

---

## 📊 Example Output

| PassengerId | Survived |
|--------------|-----------|
| 892 | 0 |
| 893 | 1 |
| 894 | 0 |

---

## 🧩 Technologies Used

- Python 3
- Jupyter Notebook
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

---

## 🚀 How to Run

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/titanic-survival-prediction.git
   cd titanic-survival-prediction
Install dependencies:

bash
Copy code
pip install -r requirements.txt
Open the notebook:

bash
Copy code
jupyter notebook TitanicSurvivalPrediction.ipynb
🏁 Results
Best model: Random Forest Classifier

Accuracy on test set: ~0.78–0.82 (depending on hyperparameters)

📚 Reference
Kaggle Titanic Dataset

👨‍💻 Author
Saeed Babun
University of La Verne — Computer Science (AI Concentration)
📧 [saeed.babun@laverne.edu]
📂 GitHub: SaeedB67

