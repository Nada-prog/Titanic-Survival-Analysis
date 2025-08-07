Titanic Survival Prediction - Data Science Project

This project applies Exploratory Data Analysis (EDA), Data Visualization, Machine Learning, and Hyperparameter Tuning on the famous Titanic dataset to predict passenger survival.

Sections Covered

Data Exploration & Visualization
- Total survivors vs non-survivors (bar chart)
- Survival percentage by gender (pie chart / countplot)
- Survival rate across passenger classes (Pclass)
- Age distribution and comparison between survivors vs non-survivors
- Family status impact on survival (SibSp & Parch)
- Fare-based survival rate (above average fare)
- Age group categorization (Child, Adult, Senior) and survival rates
- Handling missing values and their impact
- Heatmap of feature correlations
- Survival rates by Embarked location

Modeling & Evaluation
- Decision Tree classifier (train/test accuracy & overfitting check)
- Random Forest classifier (comparison to Decision Tree)
- XGBoost classifier (best performance evaluation)
- ROC Curve and AUC Score for all models
- Cross-validation with `cross_val_score` (mean accuracy & std deviation)
- Confusion matrix analysis
- Hyperparameter Tuning using GridSearchCV for:
  - Random Forest
  - XGBoost

Feature Engineering
- New features created from existing data:
  - `Group_Size` from SibSp + Parch
- Retrained models using engineered features
- Performance comparison (before vs after)

---

Technologies Used
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- XGBoost
- GridSearchCV

---

Summary
After analyzing the Titanic dataset and applying different ML models, XGBoost provided the best performance in terms of accuracy and AUC score. Feature engineering like group size further improved prediction quality. This project demonstrates a full pipeline of a machine learning workflow on a real-world dataset.

---

By: Nada Ragab  
Student at Faculty of Computers and Artificial Intelligence – Pharos University  
Department of Artificial Intelligence and Machine Learning  

هذا المشروع يوضح تحليل شامل لبيانات سفينة تيتانيك من خلال استكشاف البيانات، التصوير البياني، تدريب نماذج تعلم آلي مثل Decision Tree وRandom Forest وXGBoost، وتحسين أدائها باستخدام GridSearchCV.  
كما يتضمن إنشاء ميزات جديدة وتحليل أدائها في التنبؤ بنجاة الركاب.

