# Insurance-Analytics-Dashboard-Power-BI-Project
This Power BI project visualizes and analyzes insurance-related data for **PRISM Insurance Pvt. Ltd.** The dashboard offers a comprehensive overview of claim distributions, premium collections, customer segmentation, and policy effectiveness, enabling data-driven decisions in the insurance domain.

---

## 🚀 Objective

The goal of this project is to help insurance companies monitor and improve claim performance, customer engagement, and policy type profitability. The insights provided empower stakeholders to:

- Detect anomalies in claims processing.
- Identify customer demographics driving the most revenue.
- Strategize based on policy types and claim status trends.
- Optimize active customer retention efforts.

---

## 📈 Dashboard Overview

Here’s a breakdown of each visual in the Power BI report and its purpose:

### 1. KPI Tiles

- **Premium Amount (₹5.98M)**: Total premiums collected.
- **Coverage Amount (₹600.55M)**: Total insured sum across policies.
- **Claim Amount (₹16.91M)**: Total amount paid out in claims.

> These KPIs help measure overall profitability and risk exposure.

### 2. Claims by Gender

- **Female**: 5001  
- **Male**: 5003

> This shows a nearly equal gender distribution, indicating balanced insurance coverage and claim activity among males and females.

### 3. Number of Claims by Claim Status

- **Rejected**: 4.4K  
- **Settled**: 3.4K  
- **Pending**: 2.3K

> Useful for tracking claim resolution performance and identifying bottlenecks in the claim process.

### 4. Sum of Premium Amount by Policy Type

- **Travel**: ₹2.5M  
- **Health**: ₹1.2M  
- **Auto**: ₹1.0M  
- **Life**: ₹0.7M  
- **Home**: ₹0.6M

> Identifies which insurance segments bring in the most premium revenue, guiding resource allocation.

### 5. Claim Amount by Age Group

- **Adults**: ₹8.8M  
- **Young Adults**: ₹6.4M  
- **Elderly**: ₹1.7M

> This highlights which age groups file the most expensive claims, useful for underwriting and pricing.

### 6. Customer Status

- **Active**: 74.91% (7.49K customers)  
- **Inactive**: 25.09% (2.51K customers)

> Helps assess retention performance and the proportion of policies at risk.

### 7. Policy Type vs. Claim Status Table

A matrix comparing the claim amounts by status (Pending, Rejected, Settled) across policy types:

Example:  
- **Auto**: ₹20.8M (Pending), ₹40.6M (Rejected), ...  
- **Health**: ₹27.6M (Pending), ₹52.4M (Rejected), ...

> This detailed view supports claims optimization and risk segmentation by product line.

---

## 🧹 Business Problems Solved

✅ **Claim Processing Bottlenecks**  
Visuals help identify how many claims are still pending and rejected, driving efforts to speed up settlements.

✅ **Profitability by Policy Type**  
Breakdown by premium and claims allows analysis of which products are most profitable or risk-heavy.

✅ **Customer Engagement**  
Customer activity status helps drive retention strategies to reduce churn.

✅ **Demographic Risk Exposure**  
Age and gender segmentation helps adjust pricing models and forecast future claim trends.

---

## 🛠️ How to Access the Power BI Project

1. **Clone the Repository**
   ```bash
   git clone https://github.com/vish158/insurance-powerbi-dashboard.git
minimal_readme_content = """
## 🛠️ How to Access the Power BI Project

### Open Power BI Desktop
Download [Power BI Desktop](https://powerbi.microsoft.com/desktop/) if you haven't.
OR
Click the Following link: https://app.powerbi.com/view?r=eyJrIjoiZmY1Njg4ZGUtZjAzNS00ZGE4LWEyY2MtN2I5MjFhYmVmODYwIiwidCI6IjhjZDM2MGMyLTA2OGItNGUzNi04ZGI1LTI3YjM1NzkyZjUzZiIsImMiOjZ9

### Load the Project
Open the `.pbix` file from the cloned folder:
insurance-powerbi-dashboard/InsuranceDashboard.pbix

### Explore the Dashboard
- Use the slicers to filter by Policy Number, Claim Number, or Customer ID.
- Hover over charts and interact with visual elements to get deeper insights.

---

## 📁 Files in This Repository

| File Name               | Description                                  |
|------------------------|----------------------------------------------|
| `InsuranceDashboard.pbix` | Main Power BI dashboard project file         |
| `InsuracePowerB!.pdf`     | Screenshot preview of the Power BI dashboard |
| `README.md`               | Project documentation                        |

---

## 📌 Future Enhancements

- Integration with real-time data sources (SQL/Azure).
- Drill-through pages for customer-level insights.
- Predictive analytics for high-risk claims using ML models.

---

## 👨‍💼 Author

**Vishnu Undhad**  
B.Sc. Computer Science | Data Analytics Enthusiast  
[LinkedIn](https://www.linkedin.com) | [GitHub](https://github.com)
"""
**DISCLAIMER**
It may show a different Author on the file only because the Microsoft Account is under another name however, Im the only Author to Analyse and Generate this Project!

# Save to a README.md file
file_path = "/mnt/data/README.md"
with open(file_path, "w", encoding="utf-8") as f:
    f.write(minimal_readme_content)

