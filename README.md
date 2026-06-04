# HR_Hotel-Attrition
Exploratory Data Analysis (EDA) of employee attrition using Google Sheets to identify key drivers of employee turnover such as income, experience, and overtime.
## 🔑 Key Insights & Analytics Summary

### 1. The Overtime Impact (High Attrition Risk)
> 💡 **Core Finding:** Employees who work overtime are **nearly 3 times more likely to leave** the company compared to those who do not. This indicates a strong correlation between workload/burnout and staff turnover.

| Overtime Status | Employees Stayed | Employees Left | Total Employees | Attrition Rate |
| :--- | :---: | :---: | :---: | :---: |
| 🚫 **No Overtime** | 944 | 110 | 1,054 | **10.44%** |
| ⚠️ **Works Overtime** | 289 | 127 | 416 | **30.53%** |

---

### 2. Income Disparity & Compensation Analysis
> 📊 **Core Finding:** Financial compensation plays a critical role in employee retention. The data shows a significant drop-off in average monthly income for employees who choose to leave the organization.

| Attrition Status | Average Monthly Income | Pay Gap (Difference) |
| :--- | :---: | :---: |
| 🟢 **Retained Staff (No)** | `$6,832.74` | *Baseline* |
| 🔴 **Departed Staff (Yes)** | `$4,787.09` | **-$2,045.65 (-30%)** |

---

### 🛠️ Strategic Recommendations based on EDA
* **Implement Overtime Caps:** Review departments with high overtime metrics to redistribute workloads or scale up hiring, directly targeting the 30.53% attrition rate.
* **Compensation Review:** Conduct structural salary benchmarks for roles falling below the `$5,000` monthly income threshold, as this represents the primary turnover risk window.
