# Credit-Card-Fraud-Detection-System-week-14
-Credit-Card-Fraud-Dete-ction-System
Project Overview

This project focuses on analyzing credit card transaction data to identify fraudulent activities, understand transaction patterns, and assess transaction risk levels. The project uses data preprocessing, exploratory data analysis (EDA), visualization, and Machine Learning techniques to gain insights into fraud detection.

The dataset used is the popular Credit Card Fraud Detection dataset from Kaggle.

🎯 Objectives Load and analyze credit card transaction data Clean and preprocess the dataset Perform exploratory data analysis (EDA) Visualize fraud and normal transaction patterns Categorize transactions based on risk levels Build a Linear Regression model for transaction amount prediction Evaluate model performance Generate interactive dashboards Export the cleaned dataset 🛠️ Technologies Used Python Pandas NumPy Matplotlib Seaborn Plotly Scikit-Learn KaggleHub Google Colab 📂 Dataset Information

Dataset: Credit Card Fraud Detection Dataset

The dataset contains anonymized credit card transactions made by European cardholders.

Features Feature Description Time Seconds elapsed between transactions V1 - V28 Anonymized transaction features Amount Transaction amount Class Transaction class (0 = Normal, 1 = Fraud)

📂 Dataset Source

This project uses the Credit Card Fraud Detection Dataset from Kaggle.

Dataset Link:

Credit Card Fraud Detection Dataset (Kaggle)

Dataset Details Total Transactions: 284,807 Fraud Transactions: 492 Normal Transactions: 284,315 Fraud Rate: 0.172% Features: Time, Amount, V1–V28 (PCA-transformed features), Class Source: Machine Learning Group, Université Libre de Bruxelles (ULB) and Worldline.

⚙️ Project Workflow

Dataset Loading Downloaded dataset directly from Kaggle using KaggleHub. Loaded the CSV file into a Pandas DataFrame.
Data Preprocessing Checked dataset structure and information. Identified missing values. Removed duplicate records. Generated descriptive statistics.
Exploratory Data Analysis (EDA)
Performed analysis on:

Fraud vs Normal Transaction Distribution Transaction Amount Distribution Transaction Amount Boxplots Fraud vs Transaction Amount Comparison Time vs Transaction Amount Relationship Correlation Heatmap 4. Risk Analysis

Transactions were categorized into risk levels based on amount:

Transaction Amount Risk Level Less than ₹100 Low Risk ₹100 - ₹999 Medium Risk ₹1000 and above High Risk 5. Machine Learning Model

Implemented a Linear Regression Model.

Input Feature Time Target Variable Amount 6. Model Evaluation

Performance was measured using:

R² Score Mean Squared Error (MSE) 7. Visualization Dashboard

Interactive dashboards were created using Plotly:

Fraud vs Normal Transactions (Pie Chart) Transaction Amount Distribution Time vs Amount Scatter Plot Risk Level Distribution 8. Fraud Investigation

Filtered and analyzed:

High-Risk Fraudulent Transactions Fraud transaction patterns Risk-level distribution among fraudulent transactions 9. Data Export

The cleaned dataset was exported as:

cleaned_creditcard_dataset.csv 📊 Visualizations Included Static Visualizations Count Plot of Fraud vs Normal Transactions Histogram of Transaction Amounts Amount Boxplots Fraud vs Amount Analysis Time vs Amount Scatter Plot Correlation Heatmap Risk Level Distribution Interactive Visualizations Pie Chart Histogram Scatter Plot Bar Chart 📈 Key Insights Fraudulent transactions represent only a very small portion of total transactions. Most transactions fall into the Low Risk category. Transaction amount distributions are highly skewed. Fraudulent transactions can occur across different transaction amounts. Risk categorization helps identify transactions that require additional review. Data visualization provides a clear understanding of transaction behavior. 🚀 How to Run the Project Clone the Repository git clone https://github.com/your-username/credit-card-fraud-detection.git

cd credit-card-fraud-detection Install Required Libraries pip install pandas numpy matplotlib seaborn plotly scikit-learn kagglehub Run the Program python credit_card_fraud_detection.py

Or run the notebook directly in Google Colab.

📁 Project Structure 📦 Credit-Card-Fraud-Detection │ ├── credit_card_fraud_detection.ipynb ├── cleaned_creditcard_dataset.csv ├── README.md │ └── visualizations/ ├── fraud_distribution.png ├── amount_distribution.png ├── heatmap.png └── risk_analysis.png

📊 Sample Output 
<img width="719" height="579" alt="image" src="https://github.com/user-attachments/assets/3d4b3217-4f0f-46fe-b0d0-04ba5bd97312" />
<img width="974" height="514" alt="image" src="https://github.com/user-attachments/assets/cd760178-bf63-4fb8-872a-413bcf5680d8" />
<img width="803" height="594" alt="image" src="https://github.com/user-attachments/assets/3f7f1990-60af-461e-945b-60ef3d11b98e" />
<img width="905" height="603" alt="image" src="https://github.com/user-attachments/assets/41d12237-d35a-4f02-9d18-c962e9cfa91e" />
<img width="900" height="600" alt="image" src="https://github.com/user-attachments/assets/f2b51e82-7d3e-4c47-9352-e47f87be7157" />
<img width="858" height="576" alt="image" src="https://github.com/user-attachments/assets/278deaf0-aac1-4f24-b1d5-bdc291e5e90d" />
<img width="613" height="446" alt="image" src="https://github.com/user-attachments/assets/3c6a3073-7139-4297-a030-a72a88990acf" />
<img width="796" height="443" alt="image" src="https://github.com/user-attachments/assets/4aa082f7-3e06-4700-a14f-c4d00339ef63" />
<img width="819" height="438" alt="image" src="https://github.com/user-attachments/assets/8e5350bb-c15a-4076-ba5c-987438f464ef" />
<img width="1717" height="572" alt="Screenshot 2026-06-05 103407" src="https://github.com/user-attachments/assets/d3b8007a-4817-4353-bd0e-8d3dab28f54e" />
<img width="1679" height="474" alt="image" src="https://github.com/user-attachments/assets/bd4dd727-eae0-488f-a7f3-71e2dcf36ec2" />
<img width="1675" height="444" alt="image" src="https://github.com/user-attachments/assets/cab13f0a-ed03-4f26-89c5-77b9e41fe4b4" />
<img width="1672" height="469" alt="image" src="https://github.com/user-attachments/assets/75ef6c99-e519-4546-9394-ba596ff32346" />


The project generates:

Fraud detection statistics Risk level analysis Machine Learning predictions Interactive dashboards Transaction insights Cleaned dataset export

👨‍💻 Author

Shivaperumal.G

Student Project – Credit Card Fraud Detection and Transaction Risk Analysis using Python, Data Analytics, and Machine Learning.
