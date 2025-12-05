# AirFly Insights – Siddhesh Wagh  
_Airline Operations Data Analysis & Dashboard (US Flights 2008–2020)_

## 📖 Project Overview  
This repository contains the complete work done as part of the Infosys Springboard internship project **“AirFly Insights”**. The goal is to analyze large-scale airline flight data to uncover operational trends, delay patterns, and cancellation reasons — and present actionable insights through data visualization and dashboards.

## 🧰 Tools & Technologies  
- **Python** (pandas, numpy, matplotlib, seaborn, plotly) — for data cleaning, preprocessing, and EDA  
- **Power BI Desktop** — for building interactive dashboards and visual analytics  
- **CSV Data** — Original raw data sourced from the publicly available US Flights (2008–2020) dataset  

## 📊 What’s Inside & How to Use  
1. **`EDA.ipynb`** — Open in Jupyter Notebook to reproduce all EDA steps, generate visualizations, and inspect sample data.  
2. **`US Flight Data 2015.pbit`** — Launch in Power BI Desktop to explore the interactive dashboard with filters, slicers, maps, and KPIs.  

## 🎯 Key Features & Insights  
- Comprehensive data cleaning and preprocessing of 5.8M+ flight records (2008–2020)  
- Exploratory Data Analysis covering delay distributions, cancellation patterns, busiest airlines and airports, seasonal trends, route-level analysis, and more  
- Interactive dashboard showing:  
  - Flight volume trends by time and airline  
  - Delay and cancellation statistics and breakdowns    
  - Airline performance and cancellation cause analysis  
- Clear segmentation: Delay analysis, Cancellation analysis— useful for stakeholders like airline operators and airport planners  

## 🔧 How to Reproduce / Extend the Work  
1. Clone this repo to your local machine
2. Download Data From `DataSet Link.txt` file
3. Run `EDA.ipynb` to replicate EDA and charts  
4. Open `US Flight Data 2015.pbit` with Power BI Desktop and explore dashboard or build new visuals  
5. Add new analyses, dashboards or visualizations — and commit to your fork with meaningful commit messages  

## 📝 Note on Data Source & Licensing  
- Original dataset sourced from the **US Flights Dataset (2008–2020)**, publicly available on Kaggle / U.S. Department of Transportation.  
- Data is used for academic/research purposes only — no commercial exploitation.  



---


## 🖼️ Dashboard Overview & Instructions

This repository includes:

* A **dashboard screenshot** for quick preview
* A **Power BI Template (.pbit)** file so users can load the dashboard with their own copy of the dataset

### 📌 **Screenshot Added**

A sample snapshot of the Home Page of the Power BI dashboard has been included here for reference:

**Example:**
![Dashboard Preview](https://github.com/Siddhesh9161/AirFly_--Siddhesh-Wagh-/blob/main/SnapShot%20Of%20HomePage.png)

This image provides a preview of how the final dashboard appears once data is loaded.

---

## 📥 How to Use the `.pbit` Dashboard Template

The file **`US Flight Data 2015.pbit`** uploaded in the repository is a **Power BI Template**, not a full dashboard file.
A `.pbit` file contains all visuals, formatting, measures, relationships, and page layouts — but **requires the data to be imported** manually.

Follow the steps below:

### 🔹 **Step 1: Download the Template**

1. Go to the repository
2. Download the file: **`US Flight Data 2015.pbit`**
3. Open it in **Power BI Desktop**

---

### 🔹 **Step 2: Import the Required Datasets**

When the file opens, Power BI will ask you to provide data sources.

Import the following files (from your system):

1. **`flights_cleaned.csv`**
2. **`airlines.csv`**
3. **`airports.csv`**

You can download these from the link provided in:
➡️ **`Dataset Link.txt`**

---

### 🔹 **Step 3: Confirm Data Types**

Before loading, ensure that:

* Date column is in *Date* format
* Airline/Airport codes are *Text*
* Numeric fields (delay, distance, etc.) are *Whole Number / Decimal*

---

### 🔹 **Step 4: Load the Dashboard**

Click **Load**.
Power BI will automatically:

* Build relationships
* Refresh all visuals
* Update KPIs and filters
* Render maps and charts

Your dashboard will now look exactly like the screenshot provided.

---

### 🔹 **Step 5: Explore or Modify**

You can now:

* Apply slicers and filters
* Explore airline comparison
* Drill down into airport performance
* Add new pages or visuals
* Export PDF reports
* Publish to Power BI Service (optional)

