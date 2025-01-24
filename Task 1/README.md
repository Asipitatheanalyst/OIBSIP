# Exploratory Data Analysis (EDA) on Retail Sales Data

## Project Overview
This project performs Exploratory Data Analysis (EDA) on retail sales data to uncover hidden patterns, trends, and valuable insights that can inform business decisions. By analyzing sales data, we aim to understand customer behavior, identify popular products, and discover trends over time.

## Data Source
*   [Dataset Link](https://www.kaggle.com/datasets/mohammadtalib786/retail-sales-dataset)

## Tools
*   *Python:* The primary programming language used for data analysis and visualization.
*   *Pandas:* A powerful library for data manipulation and analysis.
*   *NumPy:* A library for numerical computing in Python.
*   *Matplotlib:* A library for creating static, interactive, and animated visualizations in Python.
*   *Seaborn:* A library based on Matplotlib that provides a high-level interface for creating attractive and informative statistical graphics.

## Exploratory Data Analysis (EDA)
*  Data Loading & Cleaning: Loading and preparing the retail sales datasets.
*  Descriptive Statistics: Calculating basic statistics (mean, median, mode, standard deviation).
*  Time Series Analysis: Analyzing sales trends over time.
*  Customer & Product Analysis: Analyzing customer demographics (if available) and purchasing behavior.

## Findings and Reccomendations
### Daily sales trend overtime

#### Findings:
1. Fluctuations in Daily Sales: The graph shows highly inconsistent sales, with significant peaks and dips throughout the year.
2. Noticeable Sales Peaks in Specific Periods: There are prominent spikes in May and July 2023, indicating exceptionally high sales activity.
3. Lower Sales in Other Periods: Sales appear to be lower and more consistent in the last quarter of the year (October to December).

#### Recommendations

1.  *Replicate Successful Strategies from High-Sales Periods (May/July):*
    *   Identify what caused the sales spikes in these months. For instance:
        *   Promotions or discounts?
        *   Seasonal demand?
        *   New product launches?
    *   Plan similar activities (e.g., promotional campaigns) during low-sales periods (e.g., Q4).
2.  *Address Daily Sales Fluctuations:*
    *   Implement consistent marketing campaigns to stabilize sales. For example:
        *   Weekly discount days to attract recurring customers.
        *   Social media or email marketing to increase daily engagement.
3.  *Focus on Slower Periods (e.g., Q4):*
    *   Since Q4 has lower sales, consider:
        *   Holiday promotions or end-of-year discounts to drive demand.
4.  *Enhance Inventory Planning:*
    *   Prepare for demand during peak months by increasing inventory.
    *   During low-sales periods, reduce stock for less popular items to minimize costs.
5.  *Investigate Root Causes of Sales Dips:*
    *   Review operational challenges or customer feedback during low periods.
    *   Address potential issues such as product availability, pricing, or marketing reach.

### Customer Demographics and Spending Analysis

#### Findings:
1.  *Gender Distribution and Spending:*
    *   The customer base is balanced, with 51% females and 49% males.
    *   Females contribute 232,840 in spending, slightly more than males at 223,160.
2.  *Age Distribution:*
    *   The average customer age is 41.4 years, with most customers aged between 29 and 53 years (the interquartile range).
    *   The youngest customer is 18, while the oldest is 64.
3.  *Category Spending:*
    *   Customers spend the most on Electronics (156,905) and Beauty (143,515), followed by Clothing (155,580).
    *   Spending is relatively evenly distributed across product categories.
4.  *Age-Based Purchase Patterns:*
    *   High spenders are concentrated in specific age brackets. Ages 19, 34, 43, and 61 show peaks in spending, with notable contributions from the 46-60 years bracket.
    *   Younger customers (18-30 years) tend to have moderate-to-low spending compared to older customers.

#### Recommedations
1.  *Leverage Gender-Specific Marketing:*
    *   *For Females:*
        *   Target campaigns on Clothing and Beauty.
        *   Offer personalized deals, discounts, or loyalty programs.
    *   *For Males:*
        *   Emphasize Electronics with tailored promotions and feature highlights.
2.  *Focus on High-Spending Age Groups:*
    *   *Ages 34, 43, and 51 (Peak Spenders):*
        *   Develop age-specific promotions (e.g., "professionals," "mature audiences").
        *   Highlight premium Electronics and Clothing.
    *   *Younger Audiences (18-30):*
        *   Offer budget-friendly options.
        *   Use targeted social media ads.
3.  *Enhance Category-Specific Strategies:*
    *   *Electronics:*
        *   Bundle complementary products (e.g., accessories with gadgets).
        *   Create tech-focused newsletters/ad campaigns.
4.  *Promote Loyalty Among Core Age Groups (30-50):*
    *   Build long-term engagement with loyalty programs, offering:
        *   Cashback or discounts on repeat purchases.
        *   Exclusive early access to new products.
5.  *Improve Customer Segmentation:*
    *   Segment customers by age and gender for personalized experiences and targeted advertising.
    *   For example:
        *   Focus on tech-savvy promotions for males aged 30-45.
        *   Target fashion/beauty trends for females aged 25-40.
6.  *Upsell and Cross-Sell Opportunities:*
    *   Use category spending insights to suggest related products:
        *   Example: Cross-sell beauty accessories with clothing purchases or electronics accessories with gadgets.
7.  *Engage Underperforming Age Groups:*
    *   Younger customers (18-24) and older customers (60-64) have relatively lower spending.
    *   Introduce budget-friendly products and promotions to engage these groups.
    *   Use social media engagement for younger audiences and email marketing for older groups.

### Correlation Heatmap for Total Spending:

#### Findings:
1.  *Price per Unit and Total Amount:*
    *   There is a strong positive correlation (0.85) between the price per unit and the total amount spent.
    *   This indicates that higher-priced items contribute significantly to total spending.
2.  *Quantity and Total Amount:*
    *   A moderate positive correlation (0.37) exists between the quantity purchased and total spending.
    *   While quantity influences spending, its effect is less significant than price per unit.
3.  *Age and Spending:*
    *   A negligible negative correlation (-0.06) suggests age has minimal direct impact on total spending.
4.  *Transaction ID:*
    *   No significant relationship between transaction ID and total spending, as expected.

## Recommendations:
1.  *Focus on High-Value Products:*
    *   Prioritize marketing and inventory for products with higher unit prices, as they significantly drive total revenue.
    *   Use premium pricing strategies to optimize revenue from high-value categories like Electronics.
2.  *Encourage Bulk Purchases:*
    *   Develop promotions encouraging customers to buy more items in a single transaction.
    *   Examples include "Buy More, Save More" campaigns or bundling related products to increase quantity purchased.
3.  *Segment Pricing and Promotions:*
    *   Given the strong influence of price on spending:
        *   Offer tiered pricing strategies, e.g., premium products for higher-income segments.
        *   Target promotions for medium-to-high-priced products where customers perceive value.
4.  *Drive Cross-Selling Strategies:*
    *   For categories with higher correlation to spending (like Electronics and Clothing):
        *   Suggest complementary products to increase both quantity and spending.
        *   For example, pairing electronic gadgets with accessories (e.g., chargers, cases).
5.  *Analyze Product Mix:*
    *   Evaluate if certain high-priced products disproportionately contribute to total spending.
    *   Focus inventory and marketing efforts on top-performing products to maximize revenue.



