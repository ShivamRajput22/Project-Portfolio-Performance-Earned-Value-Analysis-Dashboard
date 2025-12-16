# 📊 Project Portfolio Performance & Earned Value Analysis Dashboard

## 🎯 Project Objective
This project focuses on building a comprehensive **Project Portfolio Performance Dashboard** using Earned Value Management (EVM) principles to provide clear visibility into schedule health, cost efficiency, and delivery risk across a multi-project construction portfolio.

The primary objective was to move beyond surface-level budget tracking and expose the true relationship between **planned work, actual spend, and value delivered**, enabling early identification of execution risk, inefficiencies, and misaligned resource deployment.

## 🧭 Business Context
The portfolio consists of two active projects:
- **Saratoga Senior Community**
- **Nesbid Building Expansion**

Despite significant financial outlay, leadership lacked a consolidated, data-driven view of:
- Whether spending was translating into progress
- Where schedule slippage was occurring
- Which projects and work packages posed the highest delivery risk

This dashboard was designed to close that gap.

## 🖼️ Dashboard Preview

### 🏠 Portfolio Overview
![Portfolio Overview](image/Portfolio Overview.png)

### 📊 Variance Analysis
![Variance Analysis](image/variance_analysis.png)

### 📈 Progress & Cost Analysis
![Progress & Cost Analysis](image/progress_cost_analysis.png)

### 💡 Key Insights
![Key Insights](image/executive-analysis.png)

---

## 📌 Key Metrics Tracked
The dashboard is built around core Earned Value and delivery performance indicators:
- Schedule Performance Index (SPI)
- Cost Performance Index (CPI)
- Schedule Variance (Days)
- Cost Variance (£)
- Earned Value (EV) vs Actual Cost (AC)
- Activity status distribution (Not Started, In Progress, Completed)
- WBS-level progress and stagnation analysis

These metrics provide a fact-based view of execution health rather than relying on budget consumption alone.

## 🔍 Key Insights & Findings
Several critical issues emerged from the analysis:

- **Severe schedule and cost underperformance**  
  SPI (0.06) and CPI (0.07) are both far below the acceptable threshold of 1.0, indicating that the portfolio is significantly behind schedule and over budget relative to value delivered.

- **Minimal progress despite substantial spend**  
  Over **£875K** has already been spent, yet average progress across the portfolio stands at only **6.1%**, highlighting inefficient resource utilisation.

- **Major execution backlog**  
  Out of 335 total activities, **304 (91%) have not started**, with only 19 completed and 12 in progress.

- **Project-level concentration risk**  
  Saratoga Senior Community accounts for **93% (£816.3K)** of total spend and exhibits the greatest schedule slippage at **14 days**, while Nesbid Building Expansion contributes only **7% (£59.1K)** of costs with a smaller delay of **6 days**.

- **Misleading budget position**  
  Although the portfolio appears **£97K (10%) under budget**, this is driven by slow execution rather than efficiency gains. Planned resources are not being deployed as scheduled.

- **Earned Value lagging Actual Cost**  
  Earned Value consistently trails Actual Cost, most notably in March where **£239.7K** was spent for only **£16.2K EV**, signalling poor conversion of spend into deliverables.

- **WBS-level stagnation**  
  Several critical work packages, including Roof, Windows, Carpentry, Lifts, and Mechanical Systems, remain **100% not started**, increasing the risk of late-stage schedule compression and rework.

## 🧠 Analytical Approach
- Cleaned and validated schedule, cost, and progress datasets across multiple reporting snapshots
- Applied Earned Value Management logic to calculate SPI, CPI, EV, and variance metrics
- Built a relational data model enabling drill-down from portfolio to project and WBS levels
- Designed visuals to highlight risk concentration, progress gaps, and cost-to-value misalignment
- Interpreted results through a delivery risk and execution control lens rather than purely financial reporting

## 🛠️ Tools & Techniques
- **Power BI** for data modelling, DAX calculations, and interactive dashboard design
- **DAX** for dynamic performance metrics and variance analysis
- **Earned Value Management (EVM)** methodology
- Portfolio-level performance analysis and insight storytelling

## ✅ Outcome & Value Delivered
The final dashboard provides leadership with a transparent, objective view of portfolio health. It exposes hidden delivery risks that would not be visible through traditional budget tracking alone and enables:
- Early intervention in high-risk projects
- Better alignment between spending and execution
- Improved planning for resource deployment and recovery strategies
- Stronger governance over schedule and cost performance

This solution supports informed decision-making, reduces the likelihood of late-stage surprises, and strengthens overall portfolio control.

---

