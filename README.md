# Sales Data Analysis and Network Visualization

## Project Overview

This project conducts a comprehensive analysis of sales data to identify key trends, customer behaviors, product relationships, and profitability drivers. The analysis leverages a suite of business intelligence and data visualization tools, including Tableau Prep for data cleaning and transformation, Tableau Desktop for interactive dashboarding and insight generation, and Gephi for network analysis of product co-purchases.

The primary goals were to:
*   Understand sales performance and identify trends.
*   Analyze profitability across different dimensions (products, categories, regions).
*   Investigate the impact of discounts and shipping on sales and customer experience.
*   Uncover relationships between products through network visualization to identify potential bundles or cross-selling opportunities.

## Tools Used

*   **Tableau Prep:** For data cleaning, transformation, aggregation, and preparation for analysis.
*   **Tableau Desktop:** For creating interactive visualizations, dashboards, and deriving analytical insights.
*   **Gephi:** For network graph construction and analysis of product co-purchase relationships.

## Methodology

The project followed a structured analytical approach:

1.  **Data Preparation (Tableau Prep):**
    *   Raw sales data was processed and transformed.
    *   Key operations included:
        *   Aggregating sales and profit figures.
        *   Calculating profit margins.
        *   Grouping products by category and order frequency.
        *   Converting data types.
        *   Performing data joins to enrich the dataset for network analysis.
        
    ![Screenshot 2024-11-23 215002](https://github.com/user-attachments/assets/199958de-f296-4644-b07a-bd532b632b9d)
          

3.  **Visualization and Analysis (Tableau Desktop):**
    *   A comprehensive dashboard was created to summarize key findings and explore sales trends and patterns.
    *   Visualizations included:
        *   Time series analysis of sales trends (identifying seasonality).
        *   Correlation analysis (e.g., discounts vs. sales).
        *   Profit analysis by product category, sub-category, and region.
        *   Geographic analysis of profit and orders.
        *   Analysis of average shipping times by shipping mode and category.
        *   Identification of top-selling and most profitable products.
        *   Profit/Loss analysis by individual product.
  
    ![Dashboard 1](https://github.com/user-attachments/assets/11861d13-4bd9-4511-94eb-6631d2707547)

5.  **Network Analysis (Gephi):**
    *   Gephi was used to construct a network graph where:
        *   **Nodes:** Represent individual product IDs.
        *   **Edges:** Indicate products purchased together in the same order and across orders.
    *   Analysis focused on:
        *   **Graph Clustering:** Visualizing communities of frequently co-purchased products.
      
            ![image](https://github.com/user-attachments/assets/71796b0c-6a77-493d-b83c-d0000249d3d1)
            ![Screenshot 2024-11-25 192516](https://github.com/user-attachments/assets/afe7f36e-6462-482a-91fb-f6db7769638e)
            ![Screenshot 2024-11-25 193137](https://github.com/user-attachments/assets/3617638f-3a00-4bd0-8593-bee8ca8fae9a)

            *   Node size was based on degree (number of connections).
            *   Node color represented purchase frequency (darker = more frequent).
            *   Interesting finding: Some large, light-colored nodes indicated products not bought often on their own but frequently in combination with others.
        *   **Querying with Filters:**
            *   Filtering nodes by minimum purchase frequency (e.g., >=12 purchases) to identify consistently popular products.
                ![g1](https://github.com/user-attachments/assets/5b827de1-0908-474d-bf8c-1813737dcb44)

            *   Filtering nodes by degree range to identify products with high co-purchase rates (versatile/core products) versus those with low co-purchase rates (niche/specific products).
                ![g2](https://github.com/user-attachments/assets/babf157c-5930-430d-8a8d-d6a9bf571b49)

    
