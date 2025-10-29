<!-- **📈 Superstore Sales Performance and Profitability Analysis** -->

**Project Overview**

This project is a comprehensive Exploratory Data Analysis (EDA) of four years (2014-2017) of Superstore sales data. The primary goal was to understand overall business performance, identify key sales trends, and diagnose the root causes of significant financial losses present in the dataset.

The analysis led to the finding that the company's profitability is being suppressed by unsustainable deep discounting on specific, high-cost product categories.

**🎯 Key Findings & Business Recommendations**

The analysis provides actionable insights centered on improving profit margins and optimizing inventory strategy.

| **Finding**         | **Insight**                                                                                    | **Recommendation**                                                                                                        |
|-----------------|--------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------|
| **Loss Threshold**  | Any discount of 30% or higher results in an average net loss per transaction.              | Immediately implement a maximum discount cap of 20% to maintain profitability on average.                             |
| **Worst Offenders** | The Tables sub-category alone caused over $17,700 in net losses during the period.         | Stop heavily discounting Tables and Bookcases. Re-evaluate pricing, sourcing, or discontinue these loss-making items. |
| **Strong Growth**   | Sales and Profit are growing consistently year-over-year, confirming business scalability. | Continue current market expansion strategy, but with pricing safeguards in place.                                     |
| **Profit Engines**  | Copiers, Phones, and Accessories are the most reliable profit drivers.                     | Prioritize marketing and inventory investment in these high-margin sub-categories.                                    |****





**🛠️ Technical Stack and Methodology**

**Tools and Libraries**

-**Language:** Python

-**Data Manipulation:** pandas, numpy
 
-**Visualization:** matplotlib, seaborn
 
-**Environment:** Jupyter Notebook / VS Code

**Methodology Summary**

  - **Data Cleaning & Preparation:** Handled data encoding issues (latin1), corrected data types (converting dates to datetime), and dropped redundant columns.
  
- **Feature Engineering:** Calculated key metrics, including Profit Margin ($\%$) and Shipping Duration (Days).
  
- **Exploratory Data Analysis (EDA):** Established annual growth trends and identified strong Q4 (Oct-Dec) seasonality.
- **Deep Dive Analysis:**

    - Quantified the profit at every discount level to precisely locate the $30\%$ loss threshold.
  
    - Aggregated profit by Sub-Category to isolate the exact products (Tables, Bookcases) responsible for the highest total losses.

**📊 Visualizations**

**The analysis was driven by key visualizations:**

- **Monthly Sales and Profit Trend:** Demonstrated consistent growth and the strong recurring seasonal spikes every Q4.
- **Profit vs. Discount Scatter Plot:** Visually confirmed that nearly all points above the $30\%$ discount rate fall below the $0$ profit line.
- **Profit by Sub-Category Bar Chart:** Clearly showed the disproportionate negative impact of the Tables sub-category on overall profit.


**🚀 How to Run the Project**

**Clone the Repository:**

```
Bash

git clone [Your Repository URL Here]

```

**Install Dependencies:**

```
Bash

pip install pandas numpy matplotlib seaborn

```

**Data File:**  Ensure the data file (Sample_Superstore.csv) is present in the root directory.

**Run:**  Open and execute the code cells in the Jupyter Notebook (sales_analysis.ipynb or similar).


**For Reference :  go through below documentation :**

https://docs.google.com/document/d/1UN0oU2mCgDBDT7X469Uv0OhpcsNkdczM4CSb3c5Lk3c/edit?usp=sharing
