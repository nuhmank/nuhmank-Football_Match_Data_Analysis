#  Football_Match_Data_Analysis
⚽ Predicting Football Match Outcomes & Analyzing Performance Using Machine Learning & Power BI

🎯 Project Goal  
The goal of this project is to use machine learning and visual analytics to predict the outcome of football matches (Win, Draw, Loss) and uncover key patterns in team performance using historical match data. The results support better strategic planning for analysts, coaches, and enthusiasts.

📚 Data Source & Description  
- **Source**: [Kaggle Football Match Dataset](https://www.kaggle.com/datasets/aslanahmedov/walmart-sales-forecast)  
- **Type**: Structured tabular match data  
- **Format**: CSV (`England 2 CSV.csv`)  
- **Size**: 11,351 rows × 25 columns  
- **Data Types**:  
  - `float64`: 14 columns  
  - `int64`: 3 columns  
  - `object`: 8 columns  

🧰 Tools & Libraries Used  
- **Data Manipulation**: `pandas`, `numpy`  
- **Visualization**: `matplotlib`, `seaborn`, `Power BI`  
- **Machine Learning**:  
  - `train_test_split`, `SMOTE`, `LabelEncoder`  
  - `RandomForestClassifier`, `XGBoostClassifier`  
- **Evaluation Metrics**:  
  - `accuracy_score`, `classification_report`, `GridSearchCV`

🔍 Data Understanding & Cleaning  
- Reviewed structure, null values, and duplicates  
- Encoded match results (`H`, `D`, `A`) into numeric labels  
- Engineered features like `Goal_Difference`, `Team Strength`, and encoded `Referee`  
- Removed outliers using IQR  
- Balanced imbalanced target data using **SMOTE**  

📊 Exploratory Data Analysis (EDA)  
- **Match Outcome Distribution**: Class balance visualized with bar charts  
- **Home vs. Away Goals**: Histogram comparisons  
- **Feature Correlation**: Heatmaps to analyze relationships  
- **Boxplots**: Checked for skewness and outliers  
- **Power BI Visuals**:  
  - Win/Draw/Loss trends  
  - Team comparisons  
  - Shot and goal analytics  
  - Referee and card impact analysis  

🤖 Machine Learning Models  

**a. Random Forest Classifier**  
- Trained on balanced data  
- Hyperparameters optimized using GridSearchCV  
- Evaluated on accuracy and classification report  

**b. XGBoost Classifier**  
- Handled multi-class predictions  
- Tuned for efficient performance  
- Compared with Random Forest for model selection  

📈 Results & Insights  
- Random Forest model provided strong predictive performance  
- Features like `Shots on Target` and `Goal Difference` were key predictors  
- Dashboard revealed patterns in team strengths, home advantage, and result frequency  
- Balanced modeling improved fairness across Win/Draw/Loss outcomes  

✅ Conclusion  
This project demonstrates how machine learning, combined with data visualization, can effectively predict football match results and offer actionable insights. The use of EDA, SMOTE balancing, and ensemble models like Random Forest and XGBoost ensures accurate and interpretable predictions. The Power BI dashboard enhances this by delivering visual clarity and strategic insight.

📂 Resources  
- **Dataset**: [`England 2 CSV.csv`](https://www.kaggle.com/datasets/aslanahmedov/walmart-sales-forecast)  
- **ML Notebook**: `Football_Match_Outcome_Prediction_1.ipynb`  
- **Power BI Dashboard**: [`Download Power BI File`](#)  
- **Project Slides**: `Untitled presentation.pptx`  

---

🧠 *Built with a passion for football and data science by Nuhman K*

