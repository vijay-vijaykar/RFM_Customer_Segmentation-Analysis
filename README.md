# RFM Analysis for Customer Segmentation and profiling using Excel.
RFM Analysis enables businesses to categorize customers into distinct segments, unveiling hidden trends and preferences that might otherwise remain obscured.
 
## Data Source
In this analysis, we’ll employ a dataset sourced from Kaggle, encompassing data on 2,240 customers and their purchasing behavior at a grocery store. The dataset comprises 27 columns, each containing valuable insights about each customers.

## Tool
We’ll utilize Microsoft Excel as our primary data tool for the process of data cleaning, analysis, and visualization.

## Methodology
### Step-by-step for RFM Analysis
**1. Data Cleaning:** This involves imputing missing values, rectifying inaccuracies in spellings, and eliminating duplicate entries from the7 dataset

**2. Data Transformation:** Creating new columns based on existing columns, Calculate the customer’s age based on their year of birth; create a new column for the total number of children; Calculate the total monetary value spent by each customer; and the frequency (number of purchases)for each customer.

**3. Feature Selection:** Selecting the precise data fields from the dataset that hold relevance and significance for the analysis at hand.

**4. Percentrank:** Create a new column for Percentrank for Monetary Value, Frequency, and Recency to normalize these metrics.

**5. Create RFM Score:** Calculate an RFM score based on the Percentrank values, summing the three columns created in the previous step, and create a new column for Percentrank.inc for the RFM score to segment customers based on their combined RFM values.

**6. Customer Segmentation:** Create a new column called “Customer Segment” and segment customers based on the RFM score using VLOOKUP.

**7. Pivot Table:** Create a pivot chart displaying the count of customers in each segment (Top customers, Loyal customers, At-risk, and immediate attention). create a customer profile table that shows all four customer segment and the percentage of customer segment, average age, average income, average number of children, most common Education and Marital status

**8. Visualization:** Create visualizations that explain each segment and add key performance indicators (KPIs). Include demographic values (average age, income, number of children, marital status) for the top customers and the “Immediate Attention” segment to understand customer profiles better.



