# US_med_insurance_costs_CODCAD

---

# **U.S. Medical Insurance Cost Analysis**  

This project analyzes the **impact of BMI on medical charges** using Python and a dataset from `insurance.csv`. The analysis also explores other influential factors affecting medical insurance costs, such as **age, number of children, and smoking status**.  

## **Project Overview**  
This project includes:  
- **Data Cleaning & Preparation**: Importing and structuring the dataset.  
- **Statistical Analysis**: Calculating mean, median, standard deviation, and correlation coefficients.  
- **Feature Importance Analysis**: Identifying the most influential factors on medical costs.  
- **Bias Exploration**: Investigating potential biases in the dataset.  
- **Data Visualization**: Graphing distributions and relationships between features.  

---

## **Technologies Used**  
- **Python**  
- **Pandas** (for data manipulation)  
- **NumPy** (for statistical analysis)  
- **Matplotlib** (for data visualization)  

---

## **Dataset Information**  
The dataset (`insurance.csv`) contains the following columns:  
- `age`: Age of the policyholder.  
- `sex`: Gender of the policyholder.  
- `bmi`: Body Mass Index (BMI) of the policyholder.  
- `children`: Number of dependents covered under the insurance.  
- `smoker`: Whether the policyholder is a smoker (`yes` or `no`).  
- `region`: Residential region (`northwest`, `northeast`, `southwest`, `southeast`).  
- `charges`: Final medical insurance cost for the policyholder.  

---

## **Key Findings**  
- The correlation between **BMI and medical charges** is **0.198**, indicating a weak positive relationship.  
- **Smoking status** has the highest correlation with medical charges, significantly increasing insurance costs.  
- Age and BMI have **some influence**, but not as strongly as smoking.  
- The dataset contains **gender and regional imbalances**, which could introduce bias in certain analyses.  

---

## **How to Use This Repository**  
### **1. Clone the Repository**  
```bash
git clone https://github.com/FlyingEaglePlays/Medical-Insurance-Analysis.git
cd Medical-Insurance-Analysis
```
### **2. Install Dependencies**  
Ensure you have Python installed, then install the required libraries:  
```bash
pip install pandas numpy matplotlib
```
### **3. Run the Analysis**  
Execute the script using:  
```bash
python medical_insurance_analysis.py
```
or if using Jupyter Notebook:  
```bash
jupyter notebook
```

---

## **Future Improvements**  
- Add **regression models** to predict insurance charges based on BMI and other factors.  
- Implement **interactive visualizations** using `seaborn` or `plotly`.  
- Investigate **regional cost variations** in more detail.  

---

## **Author**  
**FlyingEaglePlayz**  
GitHub: [FlyingEaglePlayz](https://github.com/FlyingEaglePlayz)  

---
