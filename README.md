# Chocolate-Sales-Analysis

 ## 1) What is <a href="https://github.com/Ilaha-Habibova/Chocolate-Sales-Analysis/blob/main/Chocolate_Sales.csv">the dataset</a> about?

### The dataset contains detailed records of chocolate sales, including:

- 📦 Product information (names)

- 👥 Customer segments (sales persons)

- 🌍 Geographic data (countries)

- 📅 Time series data (order dates)

- 📊 Sales metrics (quantity sold,revenue)

### It is designed for:

- 📈 Sales forecasting
- 🛒 Customer behavior analysis
- 📊 Market trend analysis and other business intelligence tasks


### All 6 attributes' meanings:
| Column Name       | Description                                              |
| ----------------- | -------------------------------------------------------- |
| **Sales Person**  | Name of the salesperson responsible for the transaction. |
| **Country**       | Country or sales region where the transaction occurred.  |
| **Product**       | Name of the chocolate product sold.                      |
| **Date**          | Date of the transaction.                                 |
| **Amount**        | Total revenue (in USD) generated from the sale.          |
| **Boxes Shipped** | Number of chocolate boxes shipped in that order.         |



## ▶ Run the Jupyter Notebook file:
Open <a href="https://github.com/Ilaha-Habibova/Chocolate-Sales-Analysis/blob/main/Chocolate_data_analysis.ipynb">the file</a> to explore step-by-step data cleaning, visualization, and insights.

## 2) Data Preprocessing
The dataset required several preprocessing steps to ensure accurate analysis:

 #### Date Conversion:
Converted the Date column from string to datetime format for time-based analysis.

####  Revenue Cleanup:
Cleaned the Amount column by removing dollar signs and commas, converting it to a numeric float for calculations.

####  Missing Values:
Checked and confirmed no missing data across columns.

####  Duplicate Values:
Verified no duplicate rows.

#### Monthly Aggregation:
Created a Month column using the transaction date to analyze trends over time.

## 3) Exploratory Data Analysis (EDA) Summary
> This section presents key insights derived from analyzing the chocolate sales dataset across product types, countries, and time periods.
### 🧾 Revenue by Product
<img width="971" height="584" alt="image" src="https://github.com/user-attachments/assets/f80babc1-93dc-4204-8ab3-2cf1f55b75a7" />

The top 10 revenue-generating products include Smooth Silky Salty, 50% Dark Bites, and White Choc, each contributing between $300,000 and $350,000 in sales.

### 🌍 Revenue by Country
<img width="739" height="429" alt="image" src="https://github.com/user-attachments/assets/e959f26b-7227-4204-9040-314d1ee9f64c" />

Australia, India, the UK and the USA recorded the highest total revenues, each exceeding $1 million in sales.

All six countries in the dataset contributed significantly, highlighting a well-distributed global customer base.

### 📅 Monthly Revenue Trends
<img width="729" height="448" alt="image" src="https://github.com/user-attachments/assets/7705178b-616b-47c7-bf13-c9cbc8121471" />

Sales peaked in January and June, with a noticeable dip in April.

This suggests seasonal demand patterns possibly tied to holidays, gifting occasions, or mid-year campaigns.


### Shipment Volume vs. Revenue (Hexbin Analysis)
<img width="707" height="439" alt="image" src="https://github.com/user-attachments/assets/fcdf8429-8baf-41d8-8d6c-329605870c44" />

Most shipments fall in the range of 0-200 boxes, generating revenue up to $5,000.

The darkest concentration is in the lower left corner, showing that small shipments generating modest revenue are the most common scenario.

## 4) Sales Forecasting & Customer Behavior Insights
This section highlights advanced analytics performed on chocolate sales data, including time series forecasting and behavioral segmentation by country, product, and salesperson.

### 🔮 Sales Forecasting with Holt-Winters
A time series model using Holt-Winters Exponential Smoothing was applied to monthly revenue data.
<img width="856" height="424" alt="image" src="https://github.com/user-attachments/assets/08e8ced0-3035-4abd-bfb3-34c0890a183b" />


#### Key Findings:
Revenue decline forecasted - Next 6 months predict a 26% drop ($735K → $545K). 

Action: Investigate causes and launch retention campaigns.



### 👥 Customer Behavior Analysis
#### 1. Heatmap: Total Revenue by Country & Product
<img width="929" height="568" alt="image" src="https://github.com/user-attachments/assets/59c0bc35-7da5-4813-8628-2aab1adbb474" />

#### Key Findings:
The USA, India, and Australia consistently yield high revenues across multiple products.

Certain products (e.g., 50% Dark Bites, White Choc) perform well in almost all countries.

Action: Tailored product bundles and marketing strategies can be developed for each region based on performance.

#### 2. Heatmap: Purchase Frequency by Country & Product
<img width="911" height="568" alt="image" src="https://github.com/user-attachments/assets/3a626354-72e4-45d2-ac26-11f827b423ca" />

#### Suggestions:
Personalized Promotions: Target high-frequency countries with loyalty programs or bundled offers featuring their top-purchased items.

Demand Stimulation: Conduct localized promotions or campaigns in low-frequency regions to raise product awareness and trial.


### 🧑‍💼 Sales Performance by Salesperson
<img width="622" height="541" alt="image" src="https://github.com/user-attachments/assets/a4f86f20-a3fb-47c9-b50e-d34d30ecbf06" />


Top salesperson: Chess Bonnell with over $320k in sales.

#### Consider:
Implementing incentive programs to reward top-performing salespersons through bonuses or gifts. This can drive higher sales performance.
<br><br>
## Author: [@Ilaha_Habibova](https://github.com/Ilaha-Habibova)
<br>
Unauthorized use, reproduction, modification, or distribution of this project, in whole or in part is strictly prohibited. <br>
Proper reference must be given if any part of this project is used:<br> 
Chocolate Sales Analysis: Ilaha Habibova - https://github.com/Ilaha-Habibova/Chocolate-Sales-Analysis

The dataset link: https://www.kaggle.com/datasets/atharvasoundankar/chocolate-sales/data
