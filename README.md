# Heart Disease Risk Prediction

This project aims to predict the 10-year risk of coronary heart disease (CHD) using health and lifestyle data from the Framingham Heart Study. Our team built and evaluated multiple models—Logistic Regression, Classification Tree, and Neural Network—to identify individuals at high risk and to provide actionable insights for early intervention.

## 🩺 Objective

To analyze various health indicators and lifestyle factors to predict whether an individual is at risk of developing CHD within the next ten years. 

## 👨‍👩‍👧‍👦 Target Audience

- **Healthcare Providers**
- **Public Health Officials**
- **Health Insurance Companies**
- **Patients and General Public**
- **Researchers and Students**

## 📊 Dataset

The dataset consists of demographic, medical history, and lifestyle variables including:
- **Numerical:** Age, BMI, Blood Pressure, Cholesterol, Glucose, etc.
- **Categorical:** Gender, Education, Diabetes, Hypertension, Smoking, etc.
- Source: Framingham Heart Study

## ❓ Business Questions Addressed

1. How much does diabetes increase the likelihood of CHD?
2. Are early-life factors predictive of CHD?
3. Is there a socioeconomic gradient in CHD risk?
4. What are the significant predictors of CHD?
5. Can we build a reliable model to predict CHD early?
6. How can predictions inform public health interventions?

## 🧹 Data Preprocessing

- Missing value handling and imputation
- Log transformation of skewed variables (e.g., cigarettes per day, pulse pressure)
- Feature engineering (e.g., Pulse Pressure = SysBP - DiaBP)
- Outlier detection
- Correlation analysis

## 🤖 Models Developed

### Logistic Regression (Final Model)
- Chosen for its interpretability and good performance
- AUC (Train): 0.728 | AUC (Validation): 0.665
- High recall after cutoff tuning

### Classification Tree
- Captures non-linear relationships
- Interpretable, but prone to overfitting without pruning

### Neural Network
- Deeper modeling with hidden layers
- Highest recall but least interpretability

## 🔍 Evaluation Metrics

- **Precision:** 20–25%
- **Recall:** 70–83%
- **F1 Score:** ~33–37%
- **ROC-AUC:** ~0.66–0.73
- **Decile-wise lift and gain charts**

## 📈 Model Interpretation

The final logistic regression model indicates:
- Age, pulse pressure, smoking, and glucose levels are strong predictors
- Being male or on BP meds increases CHD risk
- Diabetes and hypertension significantly raise CHD probability

## 💡 Recommendations

- Promote early screening for high-risk individuals
- Public health programs targeting smoking and hypertension
- Insurance incentives for lifestyle interventions
- Use interpretable models like logistic regression in clinical settings


## 📁 Report

See `Final Report.pdf` for detailed methodology, preprocessing steps, visualizations, and full results.

---

