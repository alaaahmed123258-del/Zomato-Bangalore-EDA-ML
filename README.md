🍴 Zomato Bangalore EDA & Machine Learning Project  

📖 Overview  
This is an end-to-end Data Science project based on the Zomato Bangalore Restaurants dataset.  
The project covers the full workflow from data preprocessing to exploratory data analysis (EDA), model building, and evaluation.  
The goal is to extract valuable business insights and build predictive models to help decision-making in the restaurant industry.  

---

🔍 Exploratory Data Analysis (EDA)  
- Handled missing values and performed data cleaning.  
- Analyzed restaurant ratings, locations, cuisines, and cost distribution.  
- Created visualizations to highlight patterns and customer preferences.  
- Extracted actionable insights for business growth.  

---

🤖 Machine Learning Models  
Implemented and compared the performance of several classification models:  
- Logistic Regression  
- Random Forest  
- XGBoost  
- Neural Network  

Evaluation metrics: accuracy, precision, recall, and F1-score.  

---

📈 Results and Insights  
- Identified the best-performing classifier with high accuracy.  
- Discovered factors that influence customer ratings and restaurant success.  
- Provided insights that can help optimize restaurant business strategies.  

---

🛠️ Technologies Used  
- Python (Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn)  
- Jupyter Notebook  
- XGBoost, TensorFlow/Keras  

---

📂 Project Structure  
- Final_Project(1).ipynb → Jupyter Notebook with code and analysis  
- README.md → Project documentation  
- .gitignore  

---

🧩 Detailed Methodology  

1. Data Cleaning  
   - Removed duplicates and handled missing values.  
   - Treated outliers using the IQR method to improve data quality.  

2. Feature Engineering  
   - Created a new column cuisine_main from the original cuisines feature.  
   - Categorized restaurant ratings into Low, Medium, and High classes.  

3. Data Preprocessing  
   - Applied Label Encoding to categorical variables.  
   - Standardized numerical features using StandardScaler.  

4. Feature Selection  
   - Identified the most important features using Random Forest feature importance.  

5. Model Training and Tuning  
   - Built and compared several models: Logistic Regression, Random Forest, XGBoost, and a Deep Neural Network.  
   - Used GridSearchCV for hyperparameter tuning.  

6. Model Evaluation  
   - Evaluated models using Accuracy, Precision, Recall, F1-score, and Confusion Matrix.  
   - Performed Cross-Validation to ensure robust performance.  

7. Deep Learning Model  
   - Designed a neural network with multiple dense layers, Dropout, and Batch Normalization.  
   - Implemented EarlyStopping to prevent overfitting and improve generalization.  

---

🚀 Conclusion  
This project demonstrates the complete workflow of a Data Analyst / Data Scientist, including data wrangling, visualization, model building, and generating insights.
