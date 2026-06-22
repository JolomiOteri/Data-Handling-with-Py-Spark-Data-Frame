#  Data Handling with PySpark DataFrame (Airline Dataset)

##  Project Overview
This project demonstrates data handling, cleaning, transformation, and analysis using **PySpark DataFrames** on an airline dataset. It focuses on understanding flight delays and extracting meaningful insights using distributed data processing techniques.

---

##  Technologies Used
- Python  
- PySpark  
- Pandas  
- Matplotlib  
- Google Colab  

---

##  Dataset Description
The dataset contains airline flight information, including:

- Airline carrier names  
- Number of flights  
- Arrival delays  
- Delay causes  
- Operational statistics  

This dataset is used to analyse delay patterns and airline performance.

---

##  Project Workflow

### 1. Data Loading
- Imported dataset into PySpark DataFrame  
- Automatically inferred schema  

### 2. Data Exploration
- Viewed data using `.show()`  
- Checked structure with `.printSchema()`  

### 3. Data Cleaning
- Handled missing values:
  - Numerical columns → replaced with `0`  
  - Categorical columns → replaced with `"Unknown"`  
- Removed invalid or inconsistent records  

### 4. Data Transformation
- Applied PySpark functions such as:
  - `groupBy()`  
  - `agg()`  
  - `filter()`  
- Created derived columns for analysis  

### 5. Data Analysis
- Aggregated delays by airline  
- Compared airline performance  
- Identified delay trends  

### 6. Data Visualization
- Converted Spark DataFrames to Pandas  
- Used Matplotlib for visualization:
  - Bar charts  
  - Scatter plots  
  - Trend analysis  

---

##  Key Insights
- Certain airlines experience significantly higher delays  
- Flight volume can influence delay patterns  
- Clear variation exists in airline performance  

---

##  How to Run the Project

1. Open the notebook in Google Colab  
2. Install dependencies:
   ```bash
   pip install pyspark

## 📂 Dataset

The dataset used in this project is available here:

[Download Dataset]
(https://drive.google.com/file/d/1olEseUgBcMwcaSQ2AoK-LQtadEhoI6sL/view?usp=drive_link)

### Usage
1. Download the dataset  
2. Upload it into your Google Colab environment  
3. Ensure the file name matches the one used in the notebook  
