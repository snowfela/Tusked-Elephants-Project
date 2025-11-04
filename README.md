# 🐘 Tusked Elephants — Evolutionary Impact of Poaching  

## Overview  
This project investigates how the **illegal ivory trade** of the 1970s and 1980s affected the **tusk size and genetic traits** of African elephants.  
By comparing tusk size data from elephants born **before** and **after** the poaching crisis, it explores how human-driven selection pressures can lead to measurable evolutionary changes in wildlife populations.  

---

## Objectives  
- Analyze **tusk size variations** in elephants across two time periods.  
- Understand the **evolutionary impact** of poaching on genetic traits.  
- Identify potential **correlations between age, tusk length, and height**.  
- Use data visualization to communicate biological and conservation insights.  

---

## Dataset  
**File:** `male-elephant-tusk-size.csv`  

This dataset includes tusk and physical measurements of male elephants from East Africa, collected across two different periods:  
- **1966–1968:** Before the peak of the ivory poaching crisis.  
- **2005–2013:** After conservation and recovery efforts began.  

| Column Name | Description |
|--------------|-------------|
| `year_observed` | Period when data was recorded |
| `shoulder_height` | Shoulder height of the elephant (in cm) |
| `tusk_length` | Length of the elephant’s tusk (in cm) |
| `age` | Age of the elephant (in years) |
| `period` | Categorization — “pre_poaching” or “post_recovery” |

---

## Key Steps and Analysis  

### 1. Data Loading and Exploration  
- Loaded the dataset using **pandas** and reviewed structure and statistics.  
- Inspected the columns and units (tusk length and height in centimeters).  
- Split data into two subsets: **pre_poaching** and **post_recovery** cohorts.  

### 2. Comparative Analysis  
- Calculated **average tusk lengths** for both periods.  
- Found that post-recovery elephants had **smaller average tusk sizes**.  
- Identified **age** as a confounding variable that may influence tusk size.  

### 3. Controlling for Age  
- Analyzed the relationship between **age** and **tusk length**.  
- Created scatter plots to visualize tusk growth patterns.  
- Compared **tusk length-to-height ratios** to account for overall size differences.  

### 4. Visualization  
Used **Matplotlib** and **Seaborn** to create:  
- **Histograms** comparing tusk lengths across time periods.  
- **Scatter plots** of tusk length vs. shoulder height for each cohort.  
- **Trend lines** to show correlations and changes in distribution.  

---

## Key Insights  
- Elephants born after the poaching period tend to have **shorter tusks**, suggesting a **genetic shift** due to selective poaching of large-tusked individuals.  
- The findings illustrate **human-induced natural selection**, where traits linked to survival change in response to hunting pressures.  
- Data emphasizes the **long-term biological consequences** of illegal wildlife trade.  

---

## Tools & Libraries  
- **Python**  
- **Pandas** – for data handling and analysis  
- **Matplotlib** – for visualization  
- **Jupyter Notebook** – for exploration and reporting  
---

## Author  
Developed as a **data analysis and conservation biology project**, highlighting how statistical methods can reveal evolutionary effects of human activities on wildlife populations.
