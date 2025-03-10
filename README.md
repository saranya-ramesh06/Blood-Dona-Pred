# 🩸 Blood Donation Prediction

This project focuses on building a predictive model to identify potential future blood donors based on their historical donation behavior. The dataset used in this project is part of a warm-up challenge aimed at introducing participants to data science and machine learning workflows.

---

## 📌 Problem Statement

Blood is a vital resource in healthcare, and maintaining an adequate supply is crucial for emergency situations, surgeries, and various treatments. However, predicting future donations is a significant challenge for blood donation centers. Identifying donors who are likely to donate again allows centers to improve outreach strategies and ensure a steady blood supply.

The primary objective of this project is to **predict whether a donor will donate blood in a future month**, based on their past donation records.

---

## 🎯 Project Objectives

- To understand and analyze donor behavior using exploratory data analysis (EDA).
- To preprocess the data and engineer relevant features.
- To build and evaluate various machine learning models to predict future donations.
- To identify key features that influence a donor’s likelihood of donating again.
- To provide insights that can help blood banks make data-driven decisions.

---

## 📊 Dataset Description

The dataset consists of anonymized donor records with the following features:

| Feature Name                        | Description |
|------------------------------------|-------------|
| `Months since Last Donation`       | Number of months since the last donation |
| `Number of Donations`              | Total number of donations made |
| `Total Volume Donated (c.c.)`      | Total volume donated in c.c. (should be a multiple of Number of Donations) |
| `Months since First Donation`      | Number of months since the first donation |
| `Made Donation in March 2007`      | **Target variable**: 1 if the donor gave blood in March 2007, 0 otherwise |

The dataset is relatively small but provides an excellent opportunity to work on binary classification problems and build interpretable models.

---

## 📁 Project Structure

```
├── BloodDonaPred.ipynb                  # Jupyter Notebook with EDA, preprocessing, and ML modeling
├── Warm_Up_Predict_Blood_Donations_-_Traning_Data.csv   # Training dataset
├── README.md                            # Project description and instructions
```

---

## 🔍 Data Insights & Observations

- Donors who have donated frequently in the past tend to donate again.
- The total volume donated is directly proportional to the number of donations.
- Time-based features like "Months since First Donation" and "Months since Last Donation" are strong predictors of future donations.
- The dataset has no missing values and requires minimal cleaning.

---

## 🛠️ Technologies Used

- **Python**
- **Jupyter Notebook**
- **Pandas**, **NumPy** – for data manipulation
- **Matplotlib**, **Seaborn** – for data visualization
- **Scikit-learn** – for machine learning models and evaluation
- **Logistic Regression**, **Random Forest**, **KNN**, etc.

---

## 🚀 How to Run This Project

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/blood-donation-prediction.git
   cd blood-donation-prediction
   ```

2. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```

3. Launch the Jupyter Notebook:
   ```bash
   jupyter notebook BloodDonaPred.ipynb
   ```

---

## 📈 Model Development & Evaluation

Several machine learning algorithms were explored in this project including:

- Logistic Regression
- K-Nearest Neighbors (KNN)
- Random Forest Classifier
- Support Vector Machine (SVM)

### Evaluation Metrics Used:
- **Accuracy**
- **Precision**
- **Recall**
- **F1 Score**
- **ROC-AUC Curve**

The best-performing model was selected based on its ability to generalize well on unseen data.

---

## ✅ Key Takeaways

- Historical donation behavior can effectively predict future donations.
- Simple models like Logistic Regression performed reasonably well.
- Feature importance analysis highlights that recency and frequency of donations are strong predictors.
- Such a model can help blood banks optimize their donor outreach efforts.

---

## 💡 Future Improvements

- Collect more data points including donor demographics or behavioral data.
- Implement ensemble methods or deep learning for potentially better performance.
- Deploy the model using a web app or dashboard for real-time predictions.

---

## 📮 Contributions

Contributions are welcome! Feel free to fork the repository and submit pull requests. Suggestions for improving model performance or visualizations are highly appreciated.

---

