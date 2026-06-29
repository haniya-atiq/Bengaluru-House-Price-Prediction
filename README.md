# 🏠 Bengaluru House Price Prediction

An end-to-end machine learning solution that predicts residential property prices in Bengaluru based on location, area, BHK, and bathroom count.

---

## 📋 Project Overview

This project implements a complete data science pipeline:

- **Data Cleaning** – Handling missing values and inconsistent data
- **Feature Engineering** – Creating meaningful features from raw data
- **Outlier Removal** – Eliminating extreme values to improve model accuracy
- **Model Building** – Training a **Linear Regression** model using Scikit-Learn
- **Flask Server** – Serving the model via REST API
- **Web Interface** – Interactive HTML/CSS/JS frontend for predictions
- **AWS Deployment** – Deployed to production on AWS

---

## 🧰 Technologies Used

| Category | Tools |
|----------|-------|
| Language | Python, JavaScript, HTML/CSS |
| ML Library | Scikit-Learn, Pandas, NumPy |
| Framework | Flask |
| Frontend | HTML, CSS, JavaScript |
| Deployment | AWS (nginx) |
| IDE | PyCharm |

---

## 📊 Dataset

- **Source:** Kaggle – Bengaluru Home Prices
- **Features:** Location, Total Sq. Ft, BHK, Bathroom, Price

---

## 🔧 Project Pipeline

1. **Data Cleaning**
   - Removed rows with missing values
   - Handled size_sqft and bath columns

2. **Feature Engineering**
   - Extracted BHK from size column
   - Created new features for better prediction

3. **Outlier Removal**
   - Removed properties with extreme sqft per BHK
   - Filtered unrealistic price ranges

4. **Model Building**
   - Used Linear Regression
   - Achieved high accuracy on test data

5. **Flask Server**
   - Loaded trained model
   - Created `/predict` endpoint for API calls

6. **Web Interface**
   - User-friendly form with dropdowns
   - Real-time price display

7. **AWS Deployment**
   - Deployed on AWS with nginx
   - Production-ready setup
