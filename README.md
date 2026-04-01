<div align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=28&pause=1000&color=60A5FA&center=true&vCenter=true&lines=Heart+Disease+Prediction;Random+Forest+%7C+85%25+Accuracy;Statistical+Analysis+%2" />
  <br><br>
  <img src="https://img.shields.io/badge/❤️-Heart%20Disease%20ML-1E40AF?style=for-the-badge&logo=heart&logoColor=white" />
  <img src="https://img.shields.io/badge/⭐-85%25%20Accuracy-3B82F6?style=for-the-badge&logo=accuracy&logoColor=white" />
  <img src="https://img.shields.io/badge/📊-MANOVA%20%7C%20p%3C0.0001-60A5FA?style=for-the-badge&logo=chart&logoColor=white" />
</div>

---

## <div align="center"><b style="color:#1E40AF">❤️ Project Overview</b></div>

**Heart Disease Prediction & Analysis** uses **Random Forest ML** (85% accuracy) and **advanced statistical analysis (MANOVA, t-tests)** to predict heart disease severity from clinical data. Comprehensive pipeline includes preprocessing, feature engineering, model training, and multivariate statistical testing.

<div align="center">
  <img src="https://img.shields.io/badge/🤖-Random%20Forest-3B82F6?style=for-the-badge&logo=brain&logoColor=white" />
  <img src="https://img.shields.io/badge/📈-Statistical%20Analysis-60A5FA?style=for-the-badge&logo=calculator&logoColor=white" />
  <img src="https://img.shields.io/badge/🎯-920%20Patients-1E40AF?style=for-the-badge&logo=users&logoColor=white" />
</div>

---

## ✨ **Key Capabilities**


Analysis Type

Implementation

🤖 ML Prediction

Random Forest (85.16% CV accuracy)

📊 MANOVA

Multivariate effects (p < 0.0001)

🔬 T-Tests

Paired samples (oldpeak: p=0.0364)

📈 EDA

Correlation matrix & feature analysis

🔧 Preprocessing

SMOTE, imputation, encoding, scaling

🏗️ Tech Stack & Pipeline
<div align="center">
mermaid


Missing Data: Imputed with SimpleImputer(mean)

🎯 Model Performance
python


# Cross-Validation Scores
[0.8267, 0.8511, 0.8419, 0.8754, 0.8628]
Average: 85.16% ± 2.1%

# Test Set Classification Report


              precision    recall  f1-score   support

              
Class 0        0.83      0.88      0.86       85

Class 1        0.85      0.68      0.75       81

Class 2        0.77      0.86      0.81       72

Class 3        0.84      0.88      0.86       84

Class 4        0.99      0.97      0.98       89

Accuracy: **86%**


🔬 Statistical Analysis Results
MANOVA (Multivariate ANOVA)


Dependent vars: age, thalch, oldpeak
Independent: num (disease severity)
Result: p < 0.0001 **(Highly Significant)**
Paired T-Tests
Variable            T-statistic          P-value            Significance

age                  -0.2912             0.7710             ❌ Not significant

thalch               1.4062              0.1600             ❌ Not significant

oldpeak             -2.0954              0.0364             ✅ Significant

📈 Correlation Analysis
<div align="center"> ![Correlation Matrix](screenshots/correlation_heatmap.png) </div>
Strongest Predictors: oldpeak, age, thalch, ca

🖥️ Project Screenshots
<div align="center"> <table> <tr> <td><b>📊 Correlation Heatmap</b></td> <td><b>🎯 Model Results</b></td> <td><b>📈 Feature Importance</b></td> </tr> <tr> <td>![Correlation](screenshots/correlation.png)</td> <td>![Results](screenshots/results.png)</td> <td>![Features](screenshots/features.png)</td> </tr> </table> </div>
🚀 Quick Start
bash

Copy code
# 1. Clone Repository
git clone https://github.com/Nourhanmohamed12/multivariate.git
cd heart-disease-prediction

# 2. Install Dependencies
pip install -r requirements.txt

# 3. Run Analysis
multivariate_final_project(3)

# 4. View Results
multivariate_final_project(3).ipynb
📦 requirements.txt


pandas
numpy
scikit-learn
statsmodels
imbalanced-learn
seaborn
matplotlib
scipy
jupyter
🔧 Data Preprocessing Pipeline
python


# Complete Pipeline
1. SimpleImputer(strategy='mean') → Missing values
2. OneHotEncoder() → Categorical vars
3. StandardScaler() → Numeric features
4. SMOTE() → Class imbalance
5. train_test_split(0.2) → 80/20 split
👩‍💻 Author
<div align="center"> <a href="https://linkedin.com/in/nour-mohammed-614753278"> <img src="https://img.shields.io/badge/Nourhan%20Mohammed-1E40AF?style=for-the-badge&logo=linkedin&logoColor=white" /> </a> <img src="https://img.shields.io/badge/Data%20Scientist-3B82F6?style=for-the-badge&logo=datacamp&logoColor=white" /> <img src="https://img.shields.io/badge/ML%20Engineer-60A5FA?style=for-the-badge&logo=tensorflow&logoColor=white" /> </div>
🌟 Key Achievements
✅ 85%+ Accuracy Random Forest Classifier
✅ MANOVA p<0.0001 - Strong clinical correlations
✅ Full ML Pipeline - Production ready
✅ Statistical Rigor - Academic quality analysis
✅ Class Imbalance - SMOTE handling
