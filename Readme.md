# 🧪 A/B Testing Analysis: Mutual Fund Risk Label Impact

This repository contains the full A/B testing analysis project focused on understanding the **impact of visual risk labels** on mutual fund selection behavior. It includes:

- A/B testing design & hypothesis
- Simulated user data (for confidentiality)
- Python analysis notebook
- Visualizations
- PDF report

---
<br></br>
## 📁 Repository Structure

A_B-Testing-Analysis-Mutual-Fund-Risk-Label-Impact/ \
│\
├── mutual_fund_ab_test_data.csv # Synthetic user data\
├── ab_test_analysis_mutual_funds.ipynb # Full Jupyter Notebook for analysis\
├── mutual_fund_ab_test_report.pdf # Auto-generated project summary report\
├── README.md # Project overview & usage instructions

---
<br></br>
## 📌 Project Objective

To evaluate whether adding **risk labels** (e.g., 🔴 High Risk, 🟡 Moderate Risk) to mutual funds influences users to:

- Select fewer high-risk funds
- Explore fund details more often
- Sacrifice potential returns in favor of safety

---
<br></br>
## 📊 A/B Test Setup

| Group       | Description                                     |
| ----------- | ----------------------------------------------- |
| A (Control) | Mutual funds shown with no risk labels          |
| B (Variant) | Mutual funds shown with color-coded risk labels |

Users were asked to select 5 mutual funds for a simulated ₹10 lakh investment portfolio.
<br></br>
### 📈 Key Metrics Analyzed

- % of high-risk funds selected
- Average portfolio return
- Time taken to complete selection
- Click behavior (whether users explored fund details)

---
<br></br>
## 🧪 Statistical Tests Used

| Test                | Purpose                                                |
| ------------------- | ------------------------------------------------------ |
| **T-test**          | Compare average % of high-risk funds selected (A vs B) |
| **T-test**          | Compare average portfolio return                       |
| **Chi-square test** | Analyze categorical difference in click behavior       |

<br></br>
## 🧠 Results Summary

- Users **exposed to risk labels selected significantly fewer high-risk funds**
- These users also had **slightly lower portfolio returns**
- **Click behavior was significantly higher** in the risk label group

These findings suggest risk labels **encourage more cautious and informed decision-making**.

---
<br></br>
## 📜 How to Use:

### 1. **Clone the repository**
   ```
   git clone https://github.com/krithiksharan13/A_B-Testing-Analysis-Mutual-Fund-Risk-Label-Impact.git
   ``` 

### 2. Install dependencies:

```
pip install pandas seaborn matplotlib scipy
```

### 3. Open the notebook:
Use Jupyter Lab or VS Code to run:
```
A/B Testing Analysis: Mutual Fund Risk Label Impact.ipynb
```

### 4. Explore the PDF report
   Open *A_B Testing Project Report.pdf* for a formatted project summary.
<br></br>
## 📢 Disclaimer:
⚠️ The dataset used in this project is completely synthetic.\
It is made-up, randomly generated user behavior data and does not represent any real individuals or investment activity.\
This was done to maintain confidentiality and comply with data privacy best practices.
<br></br>
## 📬 Contact:
If you'd like to contribute, report an issue, or discuss the project, feel free to open an issue or contact me via GitHub.
<br></br>
⭐ Acknowledgements
Python (Pandas, Seaborn, SciPy)\
Radiant Ventures for making me work on this project\
GitHub for hosting this repo
<br></br>
## Made with 💡 by Krithik Sharan S A
