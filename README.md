# Movie-Content-Rating-Prediction-EDA-Project

This project focuses on analyzing and predicting content ratings using Machine Learning techniques. The dataset contains information about movies and series such as genre, platform, language, release year, engagement metrics, and more.

📊 Exploratory Data Analysis (EDA)

Performed detailed EDA to uncover key insights:

Distribution analysis of genre, platform, country, and language
Identified top genres and platforms based on content volume
Analyzed average rating by genre
Explored content trends over years by platform
Compared Movies vs Series distribution across platforms
Built interactive visualizations using Plotly
⚙️ Data Preprocessing
Applied One-Hot Encoding on categorical variables
Passed numerical features without transformation
Used ColumnTransformer for structured preprocessing
Handled unseen categories using handle_unknown='ignore'
🤖 Machine Learning Models

Built and compared two regression models:

Random Forest Regressor
XGBoost Regressor
🔹 Pipeline Implementation

Used Sklearn Pipeline to combine preprocessing and model training:

Ensures consistent transformations
Prevents data leakage
Simplifies workflow
📈 Model Performance

Achieved strong performance on test data:

Random Forest
RMSE: 0.0620
R² Score: 0.9959
XGBoost
RMSE: 0.0627
R² Score: 0.9958
🔍 Insight:
Both models performed exceptionally well
Random Forest slightly outperformed XGBoost in this case
Very high R² indicates strong predictive power of features
🚀 Key Highlights
End-to-end ML workflow (EDA → Preprocessing → Modeling → Evaluation)
Interactive visualizations using Plotly
Clean and scalable pipeline architecture
Real-world use case: OTT content rating prediction
🛠️ Tech Stack
Python
Pandas, NumPy
Scikit-learn
XGBoost
Plotly
📌 Conclusion

The project demonstrates how machine learning models can effectively predict content ratings using structured metadata. Random Forest and XGBoost both delivered high accuracy, with Random Forest achieving the best performance.

📎 Future Improvements
Hyperparameter tuning (GridSearchCV / RandomizedSearchCV)
NLP on description and tags
Deployment using Streamlit or Flask
Integration with recommendation systems
