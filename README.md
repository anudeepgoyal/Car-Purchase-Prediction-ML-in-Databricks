# Car Purchase Prediction (Databricks ML Project)

## 📌 Project Overview
This project aims to predict whether a customer will purchase a car based on demographic and financial data. The model is built using **Databricks**, **PySpark**, and **Machine Learning algorithms**, leveraging Databricks' distributed computing capabilities for efficient data processing and model training.

## 🚀 Technologies Used
- **Databricks**: Cloud-based platform for big data and AI
- **PySpark**: Scalable data processing and ML library
- **MLlib**: Apache Spark's ML library for training models
- **Streamlit** (optional): For deploying an interactive UI
- **Power BI** (optional): For visualization

## 📊 Dataset Details
- The dataset contains features like **Age, Estimated Salary, Gender**, and whether the user purchased a car.
- Preprocessing steps include handling categorical data, feature scaling, and missing values.
- The target variable is **Purchased** (Binary: 0 = No, 1 = Yes).

## ⚙️ Setup Instructions
1. **Clone the Repository**
   ```bash
   git clone https://github.com/your-username/car-purchase-prediction.git
   cd car-purchase-prediction
   ```
2. **Upload the dataset to Databricks File System (DBFS)**
   ```python
   dbutils.fs.cp("/mnt/data/suv_data.csv", "dbfs:/FileStore/tables/")
   ```
3. **Run the Databricks Notebook**
   - Open Databricks workspace and import the `.ipynb` file.
   - Execute all cells to process data, train the model, and evaluate performance.

## 📈 Model Training & Evaluation
- Used **Logistic Regression / Random Forest / Gradient Boosting**.
- Evaluated model performance using **accuracy, precision, recall, and F1-score**.
- Hyperparameter tuning performed for optimal results.

## 🌐 Deployment (Optional)
- **Streamlit UI**: Allows users to input data and get real-time predictions.
- **Power BI Integration**: Enables visualization of customer trends and insights.

## 📊 Results & Insights
- The best-performing model achieved **X% accuracy**.
- Key findings from data analysis are presented in **Power BI / Matplotlib visualizations**.

## 🤝 Contribution
Feel free to contribute by improving feature engineering, model performance, or adding new deployment methods.

## 📜 License
This project is open-source and available under the **MIT License**.
