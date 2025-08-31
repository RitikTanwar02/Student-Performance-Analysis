# Student-Performance-Analysis
🎓 Student Performance Prediction
📌 Overview
This project analyzes and predicts student performance (exam scores) based on various socio-economic and academic factors such as gender, ethnicity, parental education, lunch type, and test preparation course.
The project follows the complete Machine Learning Project Lifecycle:
1.	Problem Understanding
2.	Data Collection & Exploration
3.	Data Preprocessing & Feature Engineering
4.	Model Training & Evaluation
5.	Hyperparameter Tuning and Model Selection
________________________________________
📊 Dataset
•	Rows: 1000
•	Columns: 8
•	Features:
o	gender: Male/Female
o	race/ethnicity: Groups A–E
o	parental level of education: Bachelor's, Master's, College, etc.
o	lunch: Standard / Free-reduced
o	test preparation course: Completed / None
o	math score, reading score, writing score
Target variable: Student performance scores
________________________________________
🔍 Exploratory Data Analysis (EDA)
•	Distribution of scores by gender, ethnicity, and parental education
•	Correlation analysis of subjects (math, reading, writing)
•	Visualization with Matplotlib & Seaborn
•	Handling missing values and checking data quality
________________________________________
🤖 Model Training
Implemented and compared multiple machine learning models:
•	Linear Regression
•	K-Nearest Neighbors Regressor
•	Decision Tree Regressor
•	Random Forest Regressor
•	XGBoost Regressor
•	CatBoost Regressor
Evaluation Metrics:
•	Mean Absolute Error (MAE)
•	Mean Squared Error (MSE)
•	R² Score
Final model chosen based on best performance across metrics.
________________________________________
⚙️ Tech Stack
•	Languages: Python
•	Libraries: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, CatBoost, XGBoost
•	Environment: Jupyter Notebook
________________________________________
🚀 How to Run
1.	Clone the repository
2.	git clone https://github.com/your-username/student-performance-prediction.git
3.	cd student-performance-prediction
4.	Install required libraries
5.	pip install -r requirements.txt
6.	Open and run notebooks
o	EDA STUDENT PERFORMANCE.ipynb → for data exploration
o	MODEL TRAINING.ipynb → for training & evaluation
________________________________________
📈Final Model: Linear Regression
•	Chosen for its simplicity, interpretability, and stable performance.
•	Performance Metrics (on test data):
o	R² Score: ~80–85% (≈ 0.82 – 0.85)
o	Mean Absolute Error (MAE): Low
o	Root Mean Squared Error (RMSE): Low
This shows that Linear Regression is able to capture most of the variance in student performance with minimal error.
________________________________________
📬 Contact
For any queries, feel free to connect with me on GitHub or LinkedIn.

📜 License
This project is licensed under the MIT License.


