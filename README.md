# 📊 Exploratory Data Analysis (EDA) on AI Workforce Displacement

## 📌 Project Overview
This project performs **Exploratory Data Analysis (EDA)** on a dataset related to **AI adoption, workforce displacement, automation risks, and government policies** across countries, regions, and industries.  
The goal is to uncover insights about how AI impacts economies, industries, and workforce trends globally.

---

## 📂 Dataset
- **Rows:** 20,800  
- **Columns:** 23  
- **Features include:**
  - `country`, `region`, `income_group`
  - `year`, `quarter`, `quarter_label`
  - `industry_sector`
  - `sector_automation_risk_score`
  - `gdp_per_capita_usd`
  - `ai_adoption_index`
  - `pct_sector_workforce_displaced`
  - `pct_sector_workforce_new_roles_created`
  - `net_workforce_change_pct`
  - `ai_skill_wage_premium_pct`
  - `govt_ai_policy_score_1_to_10`
  - `reskilling_programs_count`
  - `ai_tool_adoption_pct`

---

## ⚙️ Tools & Libraries
- **Python 3.x**
- **Libraries:**
  - `pandas` → data manipulation
  - `numpy` → numerical computations
  - `matplotlib` & `seaborn` → visualizations

---

## 🔍 Key Analysis Performed
1. **Dataset Overview**
   - Shape, data types, summary statistics
   - Missing values & duplicates check
   - Unique values per column

2. **Country & Region Insights**
   - Number of unique countries (80)
   - Top countries by **GDP per capita** (Switzerland highest)
   - Top countries by **AI Adoption Index** (Singapore, Israel, USA, etc.)
   - Regional averages for AI adoption and policy scores

3. **Industry Insights**
   - Workforce displacement by industry
   - Highest automation risk (Administrative & Clerical)
   - Net workforce change per industry

4. **Workforce & Policy Trends**
   - Countries where displacement > new roles created
   - Wage premium by income group
   - Reskilling programs by income group
   - AI readiness score (AI adoption + policy score)

5. **Temporal Analysis**
   - AI adoption trends from 2020–2026
   - Year with highest adoption (2026)

6. **Visualizations**
   - Distribution of AI adoption index
   - Workforce displacement distribution
   - Records by region
   - AI adoption by region
   - AI adoption over time (line chart)

---

## 📈 Sample Insights
- **Switzerland** has the highest GDP per capita (~90,747 USD).  
- **Singapore** leads in AI adoption index (0.905).  
- **Administrative & Clerical** jobs face the highest automation risk.  
- **North America** has the strongest government AI policy score (~7.01).  
- Workforce displacement is highest in **Singapore, Denmark, USA, Finland, Sweden**.  
- AI adoption has steadily increased from **0.54 (2020) → 0.81 (2026)**.

---

## 🚀 How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/eda-project.git
   cd eda-project
