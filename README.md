# **Customer Satisfaction Analysis in the Airline Industry** ✈️  

## **Project Overview**  
The airline industry is **highly competitive**, and understanding **customer satisfaction drivers** is crucial for improving services and building brand loyalty. This project analyzes customer reviews from Kaggle to identify **key factors that influence whether a passenger would recommend an airline**.  

We developed **Decision Tree** and **Random Forest** classification models to predict customer recommendations based on various service aspects, including:  
- **Seat Comfort** 🪑  
- **Ground Service** 🛬  
- **Cabin Staff Service** 👩‍✈️  
- **Inflight Entertainment** 🎬  
- **Value for Money** 💰  

Using **feature selection, class balancing (SMOTE), and hyperparameter tuning**, we optimized model performance to provide actionable insights for airline service enhancements.  

## **Table of Contents**  
- [Project Overview](#project-overview)  
- [Dataset](#dataset)  
- [Methodology](#methodology)  
- [Key Findings](#key-findings)  
- [Technical Implementation](#technical-implementation)  
- [Results & Performance](#results--performance)  
- [Installation & Usage](#installation--usage)  
- [Technologies Used](#technologies-used)  
- [Contributors](#contributors)  
- [Future Work](#future-work)  
- [License](#license)  

---

## **Dataset** 📊  
- **Source:** [Kaggle - Airline Reviews Dataset](https://www.kaggle.com)  
- **23,171 reviews** across multiple airlines  
- **19 flight-related features**, including customer ratings on various service aspects  
- **Target variable:** Whether the reviewer recommended the airline (Yes/No)  

---

## **Methodology** 🔍  
1. **Data Preprocessing & Cleaning**  
   - Removed irrelevant/unnecessary columns (e.g., review text, timestamps)  
   - Encoded categorical variables (e.g., traveler type, seat type)  
   - Handled missing values & standardized numerical ratings  

2. **Exploratory Data Analysis (EDA)**  
   - Identified distributions, outliers, and trends in customer satisfaction  
   - Visualized relationships between flight experience factors and recommendations  

3. **Feature Engineering & Class Balancing**  
   - Applied **label encoding** to categorical features  
   - Used **SMOTE** to address class imbalance (recommended vs. not recommended)  

4. **Machine Learning Model Development**  
   - **Benchmark models:** Initial Decision Tree & Random Forest classifiers  
   - **Hyperparameter tuning:** Grid search optimization for best model performance  
   - **Evaluation Metrics:** Accuracy, Precision, Recall, F1-score  

---

## **Key Findings** 📌  
- **"Value for Money"** was the **strongest predictor** of customer satisfaction.  
- **"Ground Service"** (check-in, baggage handling) and **"Cabin Staff Service"** significantly impacted overall satisfaction.  
- Features like **"Seat Comfort" and "Inflight Entertainment" contributed moderately**, but maintaining a baseline quality remains essential.  
- **WiFi & Connectivity had minimal impact**, suggesting airlines should prioritize other areas for improvement.  

---

## **Technical Implementation** ⚙️  
- **Machine Learning Models:**  
  - **Decision Tree Classifier** 🌲  
  - **Random Forest Classifier** 🌳🌳🌳  
- **Feature Selection & Engineering:**  
  - Label encoding for categorical features  
  - SMOTE resampling to balance dataset  
  - Hyperparameter tuning for improved model performance  
- **Evaluation Metrics:**  
  - **F1-score:** Improved from **0.93 → 0.96**  
  - **Accuracy:** Increased **by 5% after full preprocessing & tuning**  
- **Visualization Tools:** Matplotlib, Seaborn  

---

## **Results & Performance** 📈  
| Model                 | Accuracy | Precision | Recall | F1-Score |  
|----------------------|----------|----------|--------|---------|  
| **Baseline Decision Tree** | 93.4%  | 92.8%  | 94.1%  | 93.4%  |  
| **Final Decision Tree** | 95.0%  | 94.7%  | 95.2%  | 95.0%  |  
| **Baseline Random Forest** | 94.1%  | 93.5%  | 94.6%  | 94.0%  |  
| **Final Random Forest** | 96.5%  | 96.2%  | 96.7%  | 96.5%  |  

**Key Improvement:** Our **Random Forest model** performed best after **SMOTE resampling and hyperparameter tuning**, achieving a **96.5% accuracy** in predicting whether a customer would recommend an airline.  

---

## **Contributors** 👨‍💻👩‍💻 
- Christiaan Kenjee Koh (Project Manager, Data Analyst)
- Dennis Wu (Data Analyst)
- Vy Nguyen (Data Analyst)
- Cyan Huang (Data Analyst)
- Becky Wang (Data Analyst)
