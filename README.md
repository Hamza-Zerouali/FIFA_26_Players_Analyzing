![sdt_edit](https://github.com/user-attachments/assets/ee98056a-f1ac-4c08-8b5b-71fea780b999)



---

# ⚽ FIFA FC26 Dataset Analysis

## 📊 Overview
Comprehensive exploratory data analysis (EDA) of the FIFA FC26 dataset containing 18,405+ players with 110 features. This project focuses on uncovering insights about player valuations, performance metrics, and market dynamics using Python's data analysis stack.

---

## 🎯 Key Objectives
- Analyze player distribution across leagues, positions, and age groups
- Identify market value drivers and correlations
- Discover young talents and undervalued players
- Visualize skill patterns across different positions
- Create comprehensive dashboards for data storytelling

## 🛠️ Technologies Used
- **pandas** → Data manipulation and analysis
- **NumPy** → Numerical computations
- **Matplotlib** → Core plotting functionality
- **Seaborn** → Statistical data visualization

## 📈 Analysis Highlights
### Dataset Statistics
- **Total Players:** 18,405
- **Features:** 110 (including player attributes, skills, financial data)
- **Leagues Covered:** All major world leagues
- **Age Range:** 16-47 years

### Key Insights Discovered
- **Value Correlations:** Strong correlation between overall rating (0.85), potential (0.82), and market value
- **Position Distribution:** Midfielders (38%), Defenders (31%), Forwards (23%), Goalkeepers (8%)
- **Age Impact:** Peak market value occurs between ages 26-30
- **Skills Analysis:** Position-specific skill patterns clearly identified

---

## 📊 Analysis Components
### **1- Data Cleaning**
- Handled missing values using median imputation for numerical features
- Filled categorical nulls with 'Unknown' placeholder
- Removed duplicate player entries

### **2- Derived Metrics Creation**
- **Age Groups:** Categorized into U21, 22-25, 26-30, 31-35, 35+
- **Potential Growth:** Calculated as (potential - overall rating)
- **Average Skills:** Mean of 6 core skill attributes
- **Position Types:** Grouped into Goalkeeper, Defender, Midfielder, Forward

### **3- Visualization Dashboard**
Created a comprehensive 12-plot dashboard including:
- Overall rating and age distributions
- Position type pie chart
- Market value analysis (log scale)
- Skills comparison by position
- Wage vs value relationships
- Top clubs and nationalities
- Skills correlation heatmap

<img width="1990" height="1229" alt="FC26 Dashboard 1" src="https://github.com/user-attachments/assets/fc26bd61-5774-43d3-959d-22bccf72ed16" />
<img width="1990" height="1229" alt="FC26 Dashboard 2" src="https://github.com/user-attachments/assets/4dece13f-7d91-48ce-948d-b8cce7bbb63c" />

---

## 💡 Key Findings
### **Top Young Talents (U21)**
Identified players under 21 with highest potential ratings for talent scouting

### **Best Value Players**
Found high-rated players (75+) with lowest cost-per-rating ratio

### **Market Insights**
Premier League has highest average player value (€8.2M)
Real Madrid leads in average player rating (81.3)
Strong wage-value correlation (r=0.89) indicates efficient market

---

## ⭐ If you found this analysis helpful, please consider giving it a star!

---
