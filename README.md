# 🩺 Analyzing Cancer Incidence in Canada

## 📌 Introduction  
Cancer is a leading public health challenge, affecting individuals and communities across Canada. This project explores cancer incidence data to uncover critical insights into its prevalence across:  
- **Geographic regions**  
- **Demographic groups**  
- **Cancer types**  

Using data from [Open Canada’s dataset](https://open.canada.ca/data/en/dataset/e667992c-5f2e-425a-8a44-a880930d82d8), I aim to transform raw numbers into actionable knowledge to drive public health policies and research.  

### Dataset Dimensions  
The dataset offers insights into:  
- **📅 Time**: Year-over-year trends in cancer incidence.  
- **🗺️ Geography**: Data from provinces and nationwide.  
- **👥 Demographics**: Age groups, sex, and other characteristics.  
- **🏷️ Cancer Types**: Classified using ICD-O-3 standards.  

Each data point includes essential metrics like the number of cases, incidence rates per 100,000 population, and confidence intervals, making it rich yet challenging for structured analysis.  

---

## 🎯 Objectives  
- **🧹 Data Cleaning**: Handle missing values, duplicates, and inconsistencies to ensure data reliability.  
- **📊 Data Analysis**: Identify trends in cancer incidence by type, demographic, and geography.  
- **📈 Insights for Public Health**: Provide actionable recommendations for policies and interventions.  
- **🔄 Reusable Framework**: Develop a scalable methodology for analyzing public health datasets.  

This project bridges the gap between raw data and actionable strategies, empowering policymakers and researchers to combat cancer more effectively.  

---

## 🌟 Potential North Star Metrics  

### Key Metrics Tracked:  
- **📉 Annual Cancer Incidence Rate**:  
  - **Why**: Reflects the yearly burden of cancer.  
  - **How**: Analyzed trends to inform risk policies.  

- **🌍 Cancer Incidence Rate per 100,000 Population (Demographics)**:  
  - **Why**: Highlights disparities across regions, age groups, and sexes.  
  - **How**: Identified high-risk populations for interventions.  

- **🔬 Number of New Cancer Cases (Total/By Type)**:  
  - **Why**: Tracks growth or decline of specific cancers.  
  - **How**: Assessed prevention and early detection efforts.  

- **📅 Change in Incidence Rate Over Time**:  
  - **Why**: Evaluates the effectiveness of interventions.  
  - **How**: Year-over-year comparisons.  

- **🏆 Top 5 Most Prevalent Cancer Types**:  
  - **Why**: Guides resource allocation and research priorities.  
  - **How**: Focused action on the most common cancers.  

---

## 🔍 1. Data Exploration and Cleaning  

To ensure the dataset was ready for analysis, I:  
- **📥 Loaded Data**: Imported the dataset using Pandas for initial exploration.  
- **🔎 Inspected Data**: Reviewed missing values, inconsistencies, and outliers.  
- **🛠️ Handled Missing/Duplicates**: Addressed missing values contextually and removed duplicates.  
- **✂️ Dropped Unwanted Columns**: Streamlined the dataset by removing irrelevant columns.  
- **🔧 Adjusted Data Types**: Reformatted dates and categorical variables for proper analysis.  

---

## 📊 2. Data Analysis Framework  

### A. Cancer Types  
- **📈 Visualized Trends**: Used line and bar graphs to analyze prevalence over time.  
- **❌ Excluded Duplicates**: Removed cumulative records (*"Total, all primary sites of cancer [C00.0-C80.9]"*).  
- **🔑 Key Insights**:  
  - Identified top 5 cancer types by year and calculated growth rates.  
  - Aggregated total incidence rates to measure the annual cancer burden.  

### B. Demographic Analysis  
#### 1. Age Groups  
- Identified high-risk age groups and tracked their trends over time.  
- Conducted cross-analyses:  
  - **Top 10 cancer types vs. top 5 age groups**.  
  - **Top 3 cancer types vs. top 5 age groups**.  
- Applied **K-Means Clustering** to group similar age patterns.  
- Performed **ANOVA** to identify statistically significant differences.  

#### 2. Sex  
- Compared cancer incidence rates between males and females using **T-tests**.  
- Summarized trends with descriptive statistics.  
- Highlighted top 10 cancer types for each gender over time.  

### C. Geographic Analysis  
- Differentiated between *"Canada"* and *"Canada (excluding Quebec)"* for nuanced insights.  
- Conducted **geospatial mapping** to uncover regional disparities.  

---

## 📐 3. Statistical and Analytical Techniques  

### Techniques Used and Why:  
- **🧮 EDA**: Uncovered patterns, relationships, and anomalies.  
- **📊 Visualization**: Created intuitive graphs, charts, and maps.  
- **📈 Descriptive Statistics**: Quantified trends with mean, median, and standard deviation.  
- **🧪 Hypothesis Testing (T-tests/ANOVA)**: Validated demographic differences.  
- **📍 Clustering (K-Means)**: Grouped similar age patterns.  
- **🌍 Geospatial Analysis**: Mapped incidence rates across regions.  

---

## 📦 4. Deliverables  

### 📌 Insights  
- Trends by cancer type, demographics, and geography.  
- Identified high-risk groups and regions.  

### 📊 Visualizations  
- Informative graphs, charts, and interactive maps.  

### 📑 Recommendations  
- **Targeted Interventions**: Focus on high-risk groups.  
- **Prevention & Detection**: Enhance screening and public health campaigns.  
- **Resource Allocation**: Address regional disparities in healthcare access.  

---

## 🌍 Impact  
This project delivers a comprehensive package of insights, visual tools, and recommendations. It empowers stakeholders to design strategies that reduce cancer incidence and improve health outcomes across Canada.  
