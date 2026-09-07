# 🏨 Hotel Reservations Analysis & Cancellation Prediction

## 📌 Project Overview

This project focuses on analyzing hotel reservation data and building Machine Learning models to predict whether a hotel reservation will be **Canceled** or **Not Canceled**.

The goal is to understand the factors that influence booking cancellations and build a predictive model that can help hotels make better decisions for **revenue planning and reservation management**.

This project was developed as part of the **Samsung Innovation Campus (SIC) AI Program – Team 11**.

---

## 🎯 Project Objectives

* Explore and understand the hotel reservation dataset.
* Perform Exploratory Data Analysis (EDA) to discover meaningful patterns.
* Prepare and preprocess the data for Machine Learning.
* Analyze the relationship between reservation features and booking status.
* Train and compare different Machine Learning classification models.
* Evaluate model performance using multiple classification metrics.
* Identify a suitable model for predicting reservation cancellations.

---

## 📊 Dataset

The dataset contains **36,275 hotel reservations** with **19 columns** describing different aspects of each booking.

Some of the main features include:

* Number of adults and children
* Weekend and week nights
* Meal plan
* Room type
* Lead time
* Arrival year, month, and date
* Market segment
* Repeated guest status
* Previous cancellations
* Previous successful bookings
* Average price per room
* Number of special requests

### Target Variable

`booking_status`

* `Canceled`
* `Not_Canceled`

---

## 🔍 Exploratory Data Analysis

The project includes several EDA steps to understand the dataset and identify patterns such as:

* Distribution of numerical features
* Categorical feature analysis
* Booking cancellation patterns
* Relationships between features
* Correlation analysis
* Data quality and preprocessing requirements

---

## 🧹 Data Preprocessing

The preprocessing stage includes preparing numerical and categorical features for Machine Learning.

The workflow covers:

* Data cleaning
* Feature preparation
* Encoding categorical variables
* Feature scaling where required
* Train/Test splitting
* Preparing the final feature matrix for model training

---

## 🤖 Machine Learning Models

Several classification algorithms were trained and evaluated:

* Logistic Regression
* K-Nearest Neighbors (KNN)
* Decision Tree
* Pruned Decision Tree
* Random Forest
* Tuned Random Forest

---

## 📈 Model Evaluation

The models were evaluated using:

* Accuracy
* Precision
* Recall
* F1 Score

### Model Comparison

| Model                  |   Accuracy |   F1 Score |     Recall |  Precision |
| ---------------------- | ---------: | ---------: | ---------: | ---------: |
| 🥇 Random Forest       | **90.39%** | **84.80%** |     81.78% | **88.04%** |
| Tuned Random Forest    |     89.40% |     82.98% |     78.84% |     87.57% |
| Pruned Decision Tree   |     88.41% |     81.84% |     79.72% |     84.07% |
| Unpruned Decision Tree |     87.33% |     80.98% | **82.29%** |     79.71% |
| KNN                    |     87.14% |     79.98% |     78.42% |     81.61% |
| Logistic Regression    |     81.39% |     69.21% |     63.82% |     75.59% |

The **Random Forest** achieved the highest overall Accuracy and F1 Score among the evaluated models, with an accuracy of approximately **90.39%** and an F1 Score of approximately **84.80%**.

---

## 💡 Key Takeaway

The results show that Machine Learning can be effectively used to predict hotel reservation cancellations.

Among the tested models, **Random Forest** provided the strongest overall performance, making it the best-performing model in this project based on the evaluated metrics.

---

## 🛠️ Technologies & Libraries

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Google Colab
* Jupyter Notebook

---

## 📁 Project Structure

```text
Hotel-Reservations-Analysis/
│
├── Project_2_(SIC_AI_Team_11).ipynb
├── README.md
└── requirements.txt
```

---

## 👩‍💻 Team

**Samsung Innovation Campus – AI Program**
**AI Team 11**

---

## 🚀 Future Improvements

Possible future improvements include:

* Hyperparameter optimization for additional models.
* Feature engineering to improve predictive performance.
* Cross-validation and more extensive model tuning.
* Deployment of the final model as a web application or API.
* Building a dashboard to visualize cancellation predictions and business insights.

---

## ⭐ Conclusion

This project combines **Data Analysis, Data Preprocessing, Exploratory Data Analysis, and Machine Learning** to address a real-world business problem in the hotel industry.

The project demonstrates how historical reservation data can be transformed into useful insights and predictive models that may support better **reservation and revenue management decisions**.
