# Mental-health-Analysis
Mental health Analysis using Power BI


# 📚 Citations

- https://datasetcatalog.nlm.nih.gov/dataset?q=0002430533  
- https://data.mendeley.com/datasets/xppzm3kv9g/2  

---

# 🧠 Depression Risk & Early Warning Dashboard

## 🎯 Objective

Identify **high-risk individuals** based on:

- Depression score  
- Behaviours  
- Sleep  
- Social media usage  
- Self-harm indicators  

### This project focuses on:

- Risk segmentation  
- Early warning patterns  
- Suicide attempt predictors  

---

## 📊 Key KPIs 

- Average Depression Score  
- % High Depression (Score > threshold)  
- % With Suicide Attempts  
- % With Self Harm  
- Avg Sleep Hours  
- Avg Social Media Hours  

---

## 📄 Dashboard Pages

### 📌 Page 1: Depression Overview

#### 📈 Visuals

1. **Clustered Column Chart**
   - Axis: Gender  
   - Values: Avg Depression Score  

2. **Bar Chart**
   - Axis: Age Group (Create bins)  
   - Values: Avg Depression Score  

3. **Donut Chart**
   - Depression Type distribution  

4. **Heatmap Matrix**
   - Rows: Education Level  
   - Columns: Employment Status  
   - Values: Avg Depression Score  

### 📌 Page 2: Suicide & Self-Harm Risk Analysis

#### 📈 Visuals
1. **Stacked Column Chart**
   - Axis: Depression Type
	- Values: Suicide Attempts
2. **Bar Chart**
   - Axis: Sleep Hours (grouped)
	- Values: Avg Depression Score
3. **Scatter Plot**
   - X: SocialMedia_Hours
	- Y: Suicide_Attempts
	- Size: Depression_Score
	- Legend: Gender
4. **Table (High Risk Individuals)**
   - Filters:
			- Depression Score > 7
		   - Self Harm = Yes OR Suicide Attempts > 0


