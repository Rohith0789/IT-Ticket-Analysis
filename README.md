# 🧾 IT Ticket Analysis Project

**Tools Used:** Excel, Pivot Tables, Charts, Correlation Analysis, Data Cleaning  

---

## 📊 Project Overview
This project analyzes **97,000+ IT support tickets** collected over five years (2016–2020) to evaluate workload patterns, agent performance, and system efficiency.  
The goal is to help management make data-driven decisions regarding **hiring, training, and software improvements** in the IT support department.

---

## 📂 Dataset Details
- **Records:** 97,498  
- **Attributes:** 15 columns  
- **Key Fields:**  
  - Agent ID  
  - Request Category  
  - Severity  
  - Priority  
  - Resolution Time  
  - Satisfaction Rate  
- **Source:** Internal IT Ticket Management Data  

---

## 🧹 Data Cleaning
Data preprocessing and standardization steps included:
- Fixed spelling inconsistencies in the **Severity** column (e.g., “Mayor” → “Major”).  
- Standardized **Agent Names** (removed extra punctuation, duplicates).  
- Checked for missing/blank values — none found, ensuring dataset completeness.  

The dataset was finalized as clean and ready for analysis using **Excel Pivot Tables** and **Charts**.

---

## 📈 Key Insights
- **Average Resolution Time:** 4.5 days  
- **Employee Satisfaction:** 4.1 / 5  
- **Main Bottlenecks:** Hardware & System tickets  
- **Fastest Resolutions:** Login issues (resolved within 0.3 days)  
- **Peak Workload:** August–December (highest ticket volume)  
- **Underperforming Agents:** Six identified with low satisfaction scores and high resolution times  

---

## 💡 Recommendations
1. **Training:**  
   Targeted upskilling for underperforming agents to improve resolution efficiency and satisfaction.

2. **Automation:**  
   Automate repetitive requests (e.g., login resets, software installs) to free up time for complex tickets.

3. **AI-Driven Ticketing:**  
   Implement auto-triaging and prioritization to ensure urgent issues are resolved promptly.

4. **Seasonal Staffing:**  
   Deploy temporary or contract agents during high-volume months (Aug–Dec).

---

## 📁 Project Files

| File | Description |
|------|--------------|
| `data/IT_Tickets_Analysis12.xlsx` | Clean dataset used for pivot table and chart analysis |
| `documentation/subjective_and_objective_questions.docx` | Report with objective & subjective analysis, including insights and recommendations |
| `presentation/IT_Ticket_Analysis.pptx` | Summary presentation prepared for management review |

---

## 📸 Dashboard Preview
Here’s a snapshot of the Excel dashboard summarizing ticket trends, resolution times, and agent performance metrics:

![Dashboard Overview](images/dashboard_overview.png)

---

## 🔍 Insights Summary
- **Resolution times** remain stable (~4.5 days) but have plateaued over time.  
- **Satisfaction** remains stagnant at ~4.1, dipping during high workload months.  
- **Hardware and System tickets** cause the longest delays.  
- **Six agents** consistently underperform, needing targeted improvement plans.  
- **AI-based ticket triaging** and **seasonal staffing** can reduce overload and boost satisfaction.

---

## 🧠 Key Takeaway
The IT support system demonstrates **stability but stagnation**.  
By investing in automation, smarter ticket management, and staff training, the organization can reduce resolution time, improve satisfaction, and achieve sustainable operational excellence.

---

## 🏁 Future Enhancements
- Build an **interactive dashboard** using Power BI or Tableau for real-time insights.  
- Use **Python or Pandas** for automated KPI tracking.  
- Integrate **AI-based prioritization models** for predictive ticket routing.

---

## 📬 Contact
For queries or collaboration opportunities, connect with **Salaar** via GitHub or LinkedIn.
