# 🗽 NYC Taxi Fare Prediction – Automatidata Project

 <img width="1408" height="768" alt="Image" src="https://github.com/user-attachments/assets/17ffa8fe-c8b4-45d4-8175-a3fd115c29c6" />

![Python](https://img.shields.io/badge/Python-3.10%2B-blue?logo=python)  
![License](https://img.shields.io/badge/License-MIT-green)  
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)  
![ML](https://img.shields.io/badge/Machine%20Learning-Regression-orange)  

---

## 📌 Table of Contents
- [Project Description](#-project-description)  
- [Technologies and Tools](#-technologies-and-tools-used)  
- [Data Understanding](#-data-understanding)  
- [Business Problem and Goals](#-business-problem-and-project-goals)  
- [Expected Benefits](#-expected-benefits)  
- [Conclusions](#-conclusions)  
- [Proposed Solutions](#-proposed-solutions)  
- [Key Business Insights](#-key-business-insights)  
- [Model](#-model)  
- [Results](#-results)  
- [How to Run](#-how-to-run)  
- [License](#-license)  

---

## 📄 Project Description
This project was developed as part of the **Google Advanced Data Analytics Professional Certificate**, applying concepts and techniques covered in the program.

The **New York City Taxi and Limousine Commission (TLC)** sought an innovative solution to strategically leverage its operational data, enabling accurate taxi fare predictions **before the trip begins**.

In collaboration with **Automatidata**, a **regression-based predictive model** was developed to estimate trip costs based on variables such as location, time, distance, service type, and other contextual factors.

> This initiative promotes **passenger transparency**, **urban transportation optimization**, and **data-driven decision-making**.

---

## 🛠 Technologies and Tools Used
- **Python**: Pandas, NumPy, Matplotlib, Seaborn, Scikit-Learn, Optuna, XGBoost  
- **Environments**: Jupyter Notebook, Anaconda (terminal), Visual Studio Code  
- **Techniques**: Machine learning algorithms (classification and regression), statistical analysis

---

## 📊 Data Understanding
The dataset, provided by the **TLC**, contains trip records from over **200,000 taxi and limousine licenses**. It includes:  
- Trip duration and distance  
- Pickup and drop-off locations  
- Fare amounts  
- Payment methods  

**Exploratory data analysis** identified relevant patterns and correlations, supporting the understanding of the main factors influencing fare amounts.

> **Note:** This dataset was created for educational purposes and may not reflect the actual behavior of New York City taxi drivers.

---

## 🎯 Business Problem and Project Goals

### **Business Problem**
Urban mobility in New York faces significant challenges, especially regarding fare pricing, where **lack of predictability** can lead to dissatisfaction and disputes between passengers and drivers.

Initial data analysis revealed **anomalies**, such as rides with a reported fare but zero distance. These inconsistencies reduce prediction accuracy and must be addressed — either by adjusting the algorithm or removing such entries.

This project aims to build a reliable predictive system that anticipates fares **before** a ride starts, providing clarity and trust for passengers, drivers, and regulators.

---

### **Goals**
- Extract **strategic insights** from the data  
- Estimate fares before the ride begins  
- Identify passengers likely to tip over 20%  
- Build a **robust machine learning** model for fare prediction  

---

## 💡 Expected Benefits
- **Transparency and trust**: More precise fare estimates to reduce disputes and improve relationships  
- **Regulatory efficiency**: Align fares with actual demand, adjusting prices based on time, region, and seasonality  
- **Data-driven strategic planning**: Support evidence-based public policies and business strategies  
- **Enhanced user experience**: Fairer and more predictable trip costs for both passengers and drivers  
- **Scalability**: Adaptable to other cities and transportation modes  

---

## 📈 Conclusions
The model demonstrated strong potential for accurate fare predictions, identifying key fare determinants through machine learning and statistical methods.

**Next Steps:**
- Refine the model with additional data  
- Deploy in real-world scenarios  
- Gather feedback from stakeholders  

---

## 🧩 Proposed Solutions
- Encourage credit card payments to potentially increase driver revenue  
- Integrate the model into mobile applications for **real-time fare estimation**  
- Conduct **beta testing** to refine predictions  
- Expand dataset and engineer additional features  

---

## 📌 Key Business Insights
- **Ride duration** was the most influential factor in fare prediction  
- Credit card payments are positively associated with higher revenues  
- The model performed reliably in multiple scenarios  

---

## 🤖 Model
This project tested and implemented **multiple regression models**, including **Multiple Linear Regression** and other advanced regression techniques.

**Evaluation Metrics:**
- **Mean Squared Error (MSE)**  
- **Root Mean Squared Error (RMSE)**  
- **R-squared (R²)**  

**Additional Analysis:**
- Hypothesis testing to evaluate variable significance  
- Feature engineering to improve prediction accuracy  

---

## 📊 Results
| Model       | Precision | Recall | F1-Score | Accuracy |
|-------------|-----------|--------|----------|----------|
| RF (CV)     | 0.675     | 0.757  | 0.714    | 0.680    |
| RF (Test)   | 0.675     | 0.779  | 0.723    | 0.687    |
| XGB (CV)    | 0.673     | 0.724  | 0.698    | 0.670    |
| XGB (Test)  | 0.676     | 0.748  | 0.710    | 0.678    |

> 📌 Visualizations, charts, and detailed analysis can be found in the Jupyter notebooks.

---

## 🚀 How to Run
```bash
# Clone repository
git clone https://github.com/yourusername/nyc-taxi-fare-prediction.git

# Navigate to project folder
cd nyc-taxi-fare-prediction

# Install dependencies
pip install -r requirements.txt

# Run Jupyter Notebook
jupyter notebook

