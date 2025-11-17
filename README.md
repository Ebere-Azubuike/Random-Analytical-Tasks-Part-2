# Heart Disease Risk Analysis: Advanced Data Visualization Project
# Random Data Analysis Tasks (Part 2)

# 📊 Project Overview
This project demonstrates advanced data visualization and machine learning techniques applied to heart disease risk analysis. Using Python's powerful visualization libraries (Matplotlib, Seaborn, Plotly) and machine learning tools (scikit-learn), this analysis explores relationships between various health factors and heart attack outcomes.

# 🎯 Project Objectives
The project is divided into two comprehensive assignments focusing on:

Static visualizations with advanced customization using Matplotlib and Seaborn
Interactive 3D visualizations and dashboards using Plotly and Dash

# 📁 Dataset Features
The heart disease dataset includes the following health-related variables:

Age: Patient age in years
Cholesterol Level: Blood cholesterol levels (mg/dL)
Blood Pressure: Systolic blood pressure (mmHg)
Gender: Male/Female
Smoking Status: Yes/No
Physical Activity: Low/Medium/High
Obesity Index: Body mass index measurement
Heart Attack Outcome: Binary outcome (0 = No, 1 = Yes)


#🔬 TASK 1: Advanced Static Visualizations
**1. Cholesterol Distribution Analysis**
Objective: Analyze the distribution of cholesterol levels in the dataset
Techniques Used:

Combined histogram with Kernel Density Estimation (KDE) curve
Statistical annotations (mean, median, standard deviation)
Custom gridlines and styling

**Key Insights:**

Visualization reveals distribution shape (normal, skewed, or bimodal)
Mean vs. median comparison indicates data symmetry
KDE curve provides smooth probability density visualization

**2. Age vs. Cholesterol Relationship**
Objective: Explore correlation between age and cholesterol levels
Techniques Used:

Overlay scatter plot with trend line
Pearson correlation coefficient calculation
Custom transparency and color coding

**Key Findings:**

Trend line reveals positive/negative relationship
Correlation strength quantified statistically
Individual data points show variability

**3. Multi-Axes Comparative Analysis**
Objective: Compare multiple relationships simultaneously
Visualizations Created:

**Bar Chart: Average cholesterol levels by gender**
**Scatter Plot: Blood pressure vs. age relationship
**
**Techniques:
**
Matplotlib's subplots() function for multi-panel figures
Gender-based color coding
Value labels on bars for clarity

**4. FacetGrid Segmentation Analysis**
Objective: Examine patterns across categorical groups
Implementation:

Seaborn's FacetGrid for categorical segmentation
Multiple subplots by smoking status and gender
Distribution analysis within each category

**Benefits:**

Simultaneous comparison across multiple groups
Pattern identification within subgroups
Statistical reference lines (mean/median)

**5. Advanced Bar Chart with Error Bars**
Objective: Create publication-quality bar charts
Features:

Custom error bars (Standard Error of Mean)
Data labels on bars (mean values + sample sizes)
Adjustable bar width and custom color schemes
Statistical reference lines

**Value:**
1. Professional presentation of group comparisons
2. Uncertainty quantification through error bars
3. Clear communication of sample sizes
