# customer-segmentation-rfm
This project uses RFM analysis to segment customers based on their purchasing behavior. By calculating RFM scores and applying clustering techniques (e.g., K-Means), it identifies distinct customer segments such as loyal, at-risk, and high-value customers. The goal is to support targeted marketing and personalized customer strategies. 


🧠 Project Objective
1. to perform customer segmentation using RFM (Recency, Frequency, Monetary) analysis
2. to identify distinct customer groups based on their purchasing behavior.
3. to reveal valuable insights leads to data-driven marketing strategies that will enhance customer retention, and increase overall business profitability.

Steps performed
*  import python libraries
*  Load and merge retail data from 2 years
*  Removed duplicates, null values and missing values
*  Created TotalSales 
*  Create RFM metrics and calculate RFM scores
*  Scaled data using StandardScaler
*  Applied KMeans (k=3) clustering on RFM scores
*  Analyzed RFM clusters based on their mean, median and mode values
*  Recommendations and insights


💡  Key insights
1. High-Value Customers Identified = The loyal and profitable customers are identified who scored high across all RFM metrics—recency, frequency, and monetary.
2. At-Risk Customers Detected - Customers who haven’t purchased recently, are identified based on their low recency scores.
3. Potential Loyalists Emerging - Customers having potential to become high-value if nurtured properly can be assessed. They showed high frequency but moderate monetary value and recency.
4. New Customers Segment - Customers with high recency but low frequency and spending were found.


🎯 Recommendations
✅ The loyal and profitable customers should be prioritized for retention campaigns.
✅ At risk detected customers may need re-engagement strategies like special offers, availability etc.
✅ Execute active campaigns or promotional campaigns with deep discounts (if profitable) for the lost customers.


🚀 Tools and libraries used
🔹 Python - Numpy, Pandas, Seaborn, Matplotlib, Scikit-learn (StandardScaler, KMeans)
🔹 Jupyter Notebook

➕ Internship 
    Project Title: Customer Segmentation using clustering analysis
    Task 1 – Data Analysis Role
    Company: indolike

🔗 Author
    Purabi Banerjee
    LinkedIn Profile - https://www.linkedin.com/in/purabi-banerjee-784929351
