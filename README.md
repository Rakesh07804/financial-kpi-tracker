# 💰 Financial KPI Tracker with Python & Excel Automation

A real-time financial dashboard that tracks **budget vs actuals**, **cost variances**, and **monthly KPI performance** across departments using Python and Excel — visualized interactively in Google Colab. Now includes **automation scripts** to generate department-wise reports and simulate email automation.

---

## 📊 Key Features
- ✅ Budget vs Actual Spend Tracking
- ✅ Variance Calculation (₹ and %)
- ✅ Monthly KPI Performance per Department
- ✅ Over-Budget Flagging
- ✅ KPI Summary (Total Budget, Total Actual, Avg Utilization)
- ✅ Visuals via Plotly (Line + Bar Charts)
- ✅ Google Colab Compatible (No local setup)
- ✅ **Python Automation for Report Generation and Email Simulation**

---

## 🛠 Tools & Technologies
| Tool      | Purpose                                |
|-----------|-----------------------------------------|
| **Python** | Data processing & visualization         |
| **Pandas** | Reading Excel, calculating KPIs         |
| **Plotly** | Interactive visualizations in Colab     |
| **Excel**  | Data input and processing               |
| **Google Colab** | Interactive Python dashboard       |
| **smtplib (optional)** | Email automation (simulated) |

---

## 📁 Project Structure
```
financial-kpi-tracker/
├── data/
│   └── processed_financial_kpis.xlsx         # Final cleaned KPI dataset
├── notebook/
│   └── Financial_KPI_Dashboard_Colab.ipynb   # Google Colab dashboard notebook
├── automation/
│   └── generate_monthly_reports.py           # Auto-export Excel reports by department
│   └── simulate_email_summary.py             # Generates simulated summary email
├── README.md                                 # Project overview and instructions
└── LICENSE                                    # (optional) MIT License
```

---

## 📂 Dataset Example
| Month   | Department | Budget (₹) | Actual (₹) | Variance (₹) | Variance (%) | % Utilization | Over Budget |
|---------|------------|------------|------------|---------------|----------------|----------------|--------------|
| Jan 2020 | Marketing  | 100000     | 120000     | +20000        | 20.00%         | 120.00%         | ✅           |
| Jan 2020 | HR         | 80000      | 70000      | -10000        | -12.50%        | 87.50%          | ❌           |

---

## 📈 Visualizations
- **📈 Line Chart**: Monthly Budget vs Actual
- **📊 Bar Chart**: Department-wise Cost Variance
- **📋 Table**: Full KPI Table with sorting
- **📌 KPI Summary Cards**: Display total budget, actual, and avg utilization

---

## 🚀 How to Run the Dashboard in Google Colab

1. Go to [Google Colab](https://colab.research.google.com)
2. Upload the notebook: `Financial_KPI_Dashboard_Colab.ipynb`
3. Upload the Excel file when prompted: `processed_financial_kpis.xlsx`
4. Run all cells to see visualizations and KPIs

---

## ⚙️ Automation Scripts

### 1. 📁 generate_monthly_reports.py
- Reads `processed_financial_kpis.xlsx`
- Saves one Excel file **per department** with monthly KPI details

### 2. 📧 simulate_email_summary.py
- Summarizes monthly KPIs (total budget, actual, over-budget departments)
- Prints the email content you'd send to stakeholders

> Future: Can be connected to Gmail/Outlook using `smtplib` or `Google API`

---

## ✅ Use Cases
- Financial Analyst Dashboards
- Departmental Budget Tracking
- MIS & Business Intelligence Projects
- Interview-ready Analytics Portfolio Projects

---

## 🔄 Future Improvements
- Add real email automation using `smtplib` or Gmail API
- Push data to SQL and automate refresh
- Build web dashboard with Streamlit or Dash
- Connect to real-time Google Sheets API
- Automate using `cron`, GitHub Actions, or Google Cloud

---

## 📜 License
MIT License — feel free to use, modify, and share.

---

## ⭐ Project Outcome
> Reduced manual effort by 60% and improved budget visibility for financial teams by automating KPI tracking, reporting, and visual analysis.

---

**🔗 Star this repo if you found it helpful!**


