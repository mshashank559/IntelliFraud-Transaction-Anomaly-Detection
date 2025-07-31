# 💼 IntelliFraud: Machine Learning-Based Fraud Detection System

  

This project was developed as part of a business case study for an internship selection process. The objective is to build a robust machine learning model that proactively detects fraudulent financial transactions and derives actionable insights to strengthen fraud prevention strategies.

  

---

  

## 📌 Problem Statement

  

A leading financial institution seeks to leverage machine learning to detect fraudulent transactions in real-time. With over 6 million transaction records across 10 key features, the goal is to design a data-driven fraud detection system that enhances security and minimizes financial loss.

  

---

  

## 📂 Project Structure

  

```bash

fraud-detection-case-study/

├──  data/  # Raw dataset (CSV)

├──  notebooks/  # Jupyter Notebook (.ipynb)

├──  images/  # Visualizations from EDA and model interpretation

├──  requirements.txt  # Required Python libraries

└──  README.md  # Project documentation

```

  ⚠️ **Note**: Due to the large size of the dataset (~1 GB), it could not be uploaded directly to GitHub.  
You can download the dataset using the following Google Drive link:

🔗 [Click here to download the dataset](https://drive.google.com/file/d/1Ep5wepynEvylZMCIi1pu34cREcXj_39f/view?usp=sharing)

Once downloaded, please place the `fraud.csv` file inside the `data/` directory.

---

  
# 📊 Tasks Completed

**1. **Data Cleaning & Preprocessing****

• Checked and handled missing values

• Outlier detection and treatment

• Multicollinearity analysis and resolution

  

**2. Exploratory Data Analysis (EDA)**

• Visualized transaction trends and distributions

• Identified severe class imbalance (fraud vs. non-fraud)

  

**3. Feature Engineering & Selection**

• Encoded categorical variables (type)

• Dropped high-cardinality and irrelevant identifiers (nameOrig, nameDest)

• Extracted feature importance using Random Forest

**4. Model Building**

o Used a Random Forest Classifier with optimized parameters

o Applied class-weight balancing to address imbalance

o Trained the model on a 10% stratified sample for efficiency

**5. Model Evaluation**

o Measured performance using ROC-AUC, Precision, Recall, and F1-Score

o Interpreted results using confusion matrix and feature importance plots

6. Business Insights & Recommendations

o Identified high-risk patterns in fraudulent behavior

o Proposed preventive actions to reduce fraud exposure

________________________________________

# 📈Performance Metrics

 - Metric Value
   
   
 - Accuracy 94.2%

   

 - Precision 87.1%

   

 - Recall (Sensitivity) 91.6%

   

 - F1 Score 89.3%

   

 - ROC-AUC 0.970

________________________________________

# 🔍Key Features Influencing Fraud

• amount: Large or irregular transaction amounts

• oldbalanceOrg: Balance before transaction

• newbalanceOrig: Remaining balance after transaction

• type: Type of transaction (transfer, cash out, etc.)

These features align well with expected fraudulent behavior, such as high-value transfers or sudden drops in account balance.

________________________________________

# 🛡️Recommendations for Fraud Prevention

To improve the organization's fraud detection and prevention infrastructure:

• Deploy real-time anomaly detection with alert systems

• Implement multi-factor authentication for high-risk transactions

• Monitor suspicious IPs, geolocation, and time-based activity

• Use transaction velocity checks (frequency and amount spikes)


# 📦 Installation Instructions

To set up and run the project locally, follow these steps:

**Clone the repository**

git clone [https://github.com/your-username/fraud-detection-case-study.git](https://github.com/mshashank559/IntelliFraud-Transaction-Anomaly-Detection)
cd fraud-detection-case-study

# Install dependencies

    pip install -r requirements.txt

## ✅ Usage

Open the notebook located at:

`notebooks/fraud_detection.ipynb` 

Run each cell sequentially to explore the dataset, train the model, and visualize the results.

## 📑 License

This project is developed strictly for academic and internship evaluation purposes. All rights reserved © 2025.


---



