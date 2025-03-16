# 📊 RFM Analysis for Customer Segmentation & Profiling using Excel  

## 📌 Project Overview  
RFM (Recency, Frequency, Monetary) Analysis enables businesses to segment customers based on their purchasing behavior. This helps in identifying customer trends, improving marketing strategies, and enhancing customer retention.  

In this project, we analyze customer purchase data from a grocery store to classify customers into different segments such as **Top Customers, Loyal Customers, At-Risk Customers, and Immediate Attention.**  

## 📂 Data Source  
- The dataset is sourced from **Kaggle** and contains **2,240 customers** with **27 features** related to their purchasing behavior.  

## 🛠 Tools Used  
- **Microsoft Excel**: Data cleaning, analysis, and visualization.  

## 🔍 Methodology  

### **1️⃣ Data Cleaning**  
- Handle missing values and remove duplicates.  
- Correct any spelling errors or inconsistencies.  

### **2️⃣ Data Transformation**  
- Compute **customer age** using the year of birth.  
- Calculate **total number of children per customer**.  
- Determine **total monetary value spent** and **purchase frequency** for each customer.  

### **3️⃣ Feature Selection**  
- Extract only relevant columns for RFM analysis.  

### **4️⃣ Percentrank Calculation**  
- Normalize **Monetary Value, Frequency, and Recency** using **Percentrank function**.  

### **5️⃣ RFM Score Calculation**  
- Compute **RFM score** by summing the three Percentrank values.  
- Apply **Percentrank.inc function** to further normalize the RFM score.  

### **6️⃣ Customer Segmentation**  
- Create a **Customer Segment column** using **VLOOKUP** based on RFM scores.  

### **7️⃣ Pivot Table Analysis**  
- Count customers in each segment (**Top Customers, Loyal Customers, At-Risk, Immediate Attention**).  
- Create a **customer profile table** summarizing:  
  - Percentage of each customer segment.  
  - Average **age, income, and number of children**.  
  - Most common **education level and marital status**.  

### **8️⃣ Visualization & Dashboard**  
- Create **pivot charts** to display customer segmentation results.  
- Add **KPIs** to highlight key insights.  
- Provide a **demographic breakdown** of top customers and at-risk customers.  

## 📊 Key Insights  
- **Top Customers** have higher purchase frequency and monetary value.  
- **Loyal Customers** show consistent spending behavior.  
- **At-Risk Customers** show reduced engagement and need targeted marketing.  
- **Immediate Attention** customers may require special offers or re-engagement strategies.  

## 📁 Repository Contents  
- **Excel File**: Contains data, analysis, and pivot tables.  
- **Dashboard Screenshot**: A snapshot of the final analysis.  
- **ReadMe.md**: Documentation of the project.  

 
