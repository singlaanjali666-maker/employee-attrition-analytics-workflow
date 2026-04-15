# 📊 Employee Attrition Analytics Workflow

This project is an end-to-end Employee Attrition Analysis system that combines workflow automation and data visualization to identify employees at risk of leaving an organization.

It uses n8n for automation and Google Sheets as the data source.

---

## 🚀 Project Overview

The system collects employee survey data, calculates a **risk score**, classifies employees into risk levels, and presents insights through an interactive dashboard.

This helps HR teams:
- Identify high-risk employees
- Understand satisfaction trends
- Make data-driven retention decisions

---

## 🔄 Workflow Architecture

The automation workflow includes the following steps:

1. **Google Sheets Trigger**
   - Captures new employee survey responses

2. **Calculate Risk Score**
   - Computes attrition risk based on:
     - Job satisfaction
     - Manager support
     - Work hours
     - Career growth

3. **Route by Risk Level**
   - Categorizes employees into:
     - Low Risk
     - High Risk
     - ![WhatsApp Image 2026-04-02 at 10 00 17 AM](https://github.com/user-attachments/assets/23731f06-1fb4-4da7-995d-95ad8e907003)


4. **Format Alert Message**
   - Prepares alerts for high-risk employees

5. **Prepare Data for Storage**
   - Structures processed data for reporting/dashboard

---

## 📊 Dashboard Features

The dashboard provides key HR insights:

- Total Responses
- Average Job Satisfaction
- Leave Intent Score
- High-Risk Employee Count
- Average Risk Score
- ![WhatsApp Image 2026-04-02 at 10 00 18 AM](https://github.com/user-attachments/assets/546a0b28-f89f-4a21-93aa-a0f451b6f588)


### 📈 Visualizations:
- Risk Level Distribution (Pie Chart)
- Career Growth vs Risk (Line Chart)
- Risk Score by Job Satisfaction (Bar Chart)
- Employee-level data table

---

## 🗂️ Data Source

Data is collected using Google Sheets with fields such as:
- Email ID
- Job Satisfaction (1–5)
- Manager Support
- Work Hours
- Career Growth Opportunities

---

## ⚙️ Tech Stack

- n8n – Workflow automation  
- Google Sheets – Data storage  
- Power BI / Excel – Dashboard visualization  

---

## 💡 Key Insights

- Employees with low job satisfaction show higher risk scores  
- Lack of career growth strongly correlates with attrition risk  
- Long work hours can increase the likelihood of leaving  

---

## 📌 Use Cases

- HR Analytics Projects  
- Employee Retention Strategies  
- Automation Learning (No-code/Low-code)  
- Academic & Internship Projects  

---

## 🔮 Future Improvements

- Add email/Slack alerts for high-risk employees  
- Integrate machine learning for predictive analytics  
- Connect with HRMS systems  
- Real-time dashboard updates  

---

## 👩‍💻 Author

Anjali singla
