# Project Overview
The aim of this project is to build a simple interactive report in Power BI to monitor key business metrics and trends for a Toy store chain in Mexico. The dataset comprises 829,262 transactions recorded from January 2022 to September 2023, aggregated from four store locations across Mexico. The objective of this analysis is to give product recommendations in each of the four store locations based on analysis of historical data.
  
## Data Source
The data used in this analysis is provided by Maven Analytics and can be [found here](https://www.mavenanalytics.io/data-playground.)

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
   ![Dashboard]![toy store- final dashboard](https://github.com/mwang-cmn/Toy-Store-Dashboard/assets/73072045/955a52e6-a6b3-43bf-a768-0e70a1b4038e)


## Insights
Key findings from the analysis:
- The toy store chain recorded a profit of USD 4 million during the entire period.
- Revenue exhibited a fluctuating pattern, peaking in early 2023 (likely during the holiday season) and declining afterward.
- Downtown and Commercial locations contributed over 50% of total profit.
- Airport stores experienced a sharp decline in revenue and orders in August 2023.
- Mexico City was the most profitable city.
- Best-selling product categories were Toys and Art and Crafts.
- Most profitable product: Colorbuds.

##Recommendations
The following is a summary of product performance in each of the 4 Store locations, key trends in revenue and suitable product recommendations based on this analysis
| Location    | Description                                                                                                                |
|-------------|----------------------------------------------------------------------------------------------------------------------------|
| Airport     | The sales trend in this location remains relatively flat with minor fluctuations. Electronics and Toys contribute the highest revenue percentages. Since these locations are duty-free zones, travelers often purchase art and crafts as souvenirs, along with electronic companions that provide comfort during long flights and seamless connectivity across borders. Curate an enticing blend of artistic crafts and cutting-edge electronics to appeal to the modern traveler. |
| Commercial  | These locations experienced a significant peak in June but declined thereafter. Sport and Outdoors sales are relatively increasing compared to other locations. Focus on these categories to cater to the corporate crowd, who may buy last-minute gifts, seal deals, express gratitude, or purchase functional gadgets like smartwatches. |
| Residential | Electronics are the biggest driver of revenue in these locations. Situated within residential areas, where children and families seek birthday gifts and toys, consider cross-promotions or family-themed sales events to promote the sale of toys and sports & outdoor items. Nurturing community bonds is essential for success in these locations. |
| Downtown    | Toys perform exceptionally in these city-center locations. Conveniently accessible to a larger consumer base, highlight arts and crafts in these locations to celebrate local craftsmanship and drive additional revenue. |



Full Solution in PowerBI >> [PowerBI file](https://drive.google.com/file/d/1qvDiXe2lQMgscY-UqlMW6T1kZa_s2JFS/view?usp=sharing)


