# Project Overview
The aim of this project is to build a simple interactive report in Power BI to monitor key business metrics and trends for a toy store chain in Mexico. The dataset comprises 829,262 transactions recorded from January 2022 to September 2023, aggregated from four store locations across Mexico.

## Data Cleaning and Transformation
The dataset consists of four tables:
- **Product Table**: Contains information about the products.
- **Sales Table**: Used as the fact table, with calculated columns for revenue and profit.
- **Calendar Table**: Provides date-related information.
- **Stores Table**: Contains details about the store locations.
  
I established many-to-one relationships between these tables to create a relational model. 
1. Created calculated columns for revenue and profit.
2. Defined three new measures: total orders, total revenue, and total profit.
3. Created a date hierarchy (date, start of month, start of week).

## Insights
Key findings from the analysis:
- The toy store chain recorded a profit of USD 4 million during the entire period.
- Revenue exhibited a fluctuating pattern, peaking in early 2023 (likely during the holiday season) and declining afterward.
- Downtown and Commercial locations contributed over 50% of total profit.
- Airport stores experienced a sharp decline in revenue and orders in August 2023.
- Mexico City was the most profitable city.
- Best-selling product categories: Toys and Art and Crafts.
- Most profitable product: Colorbuds.

## Disclaimer
The data used in this analysis is provided by Maven Analytics and can be found here.
Feel free to customize this information for your GitHub readme! 😊🚀
