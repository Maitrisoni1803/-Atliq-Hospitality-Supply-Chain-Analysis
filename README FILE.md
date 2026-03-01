## Atliq Hospitality Analysis : Domain: Hospitality,  Function: Revenue

Click below for Powerpoint presentation, Interactive dashboard link and Dashaboard Video

[Atliq Hospitality Ppt](https://github.com/Maitrisoni1803/Atliq-Hospitality-Analysis/blob/main/Atliq%20Hospitality%20Analysis%20PPT.pdf)

[Dashboard](https://github.com/Maitrisoni1803/Atliq-Hospitality-Analysis/blob/main/hospitality%20domain.pbix)



AtliQ Grands owns multiple five-star hotels across India. They have been in the hospitality industry for the past 20 years. Due to strategic moves from other competitors and ineffective decision-making in management, AtliQ Grands are losing its market share and revenue in the luxury/business hotels category. As a strategic move, the managing director of AtliQ Grands wanted to incorporate “Business and Data Intelligence” to regain their market share and revenue. However, they do not have an in-house data analytics team to provide them with these insights.

Their revenue management team had decided to hire a 3rd party service provider to provide them with insights from their historical data.

## Task:  
You are a data analyst who has been provided with sample data and a mock-up dashboard to work on the following task. 

1. Create the metrics according to the metric list.
2. Create a dashboard according to the mock-up provided by stakeholders.
3. Create relevant insights that are not provided in the metric list/mock-up dashboard.



## Data Model 
![image](https://github.com/Maitrisoni1803/Atliq-Hospitality-Analysis/blob/main/data%20model.png)



## Learnings
1. Gained a solid understanding of the Hospitality Domain, including key metrics such as RevPAR, DBRN, DSRN, DURN, ADR, Realization and Occupancy Percentage.
2. Enhanced skills in creating DAX measures for improved data analysis.
3. Used consistent colors across the reports to make them look organized and easier to understand, ensuring that users have a smooth and pleasant experience.

## Key Insights: 

1. Mumbai leads in revenue generation(39.13%), followed by Bangalore, Hyderabad and Delhi.
2. Delhi emerges as the top-performing city in both Occupancy % and average rating. Following closely behind is Hyderabad, Mumbai and Bangalore also demonstrate strong performance.
3. During weekdays, the revenue totals 69.34% of the total revenue. Occupancy stands at 55.99%, with an Average Daily Rate (ADR) of 12,683.18 rupees and Revenue per Available Room (RevPAR) of 7.10 thousand rupees. 
4. Atliq Exotica Hotel leads in revenue with 222 million rupees, while Atliq Seasons Hotel records a comparatively lower revenue of 46 million rupees during weekdays 
5. During weekends see a revenue of 524 million rupees, constituting 30.66% of the total revenue. Occupancy increases to 62.64%, accompanied by a slightly higher ADR of 12,725.49 rupees and an improved RevPAR of 7.97 thousand rupees.
6. Atliq Exotica Hotel maintains its high revenue status with 98 million rupees, while Atliq Seasons Hotel generates 20 million rupees, surpassing other hotels. 
7. Direct offline bookings indicate a lower count and ratings by 8.1K (6.02%), whereas bookings through other platforms showcase higher ratings. Notably, bookings via MakeYourTrip account are 19.9% of the total. 
8. Among room types, Elite rooms secure the highest number of bookings, comprising 49.5K (36.78%). Following Elite rooms are Standard rooms at 28.57%, Premium rooms at 22.71%, and Presidential rooms at 11.94%.
9. AtliQ Blu has the highest occupancy rate at 62%, highlighting significant demand for this property. While, Atliq Seasons records the lowest occupancy rate at 11.31%, indicating potential areas for improvement. 
10. In terms of cancellations, Atliq Palace experiences the highest rate at 14.49%, closely followed by Atliq Gardens and Atliq City. Whereas, Atliq Exotica registers the lowest cancellation rate at 14.02%. 



## Atliq Hospitality Analysis : Domain: Hospitality,  Function: Revenue

Click below for Powerpoint presentation, Interactive dashboard link and Dashaboard Video



[Dashboard](https://github.com/Maitrisoni1803/Atliq-Supply-chain-analysis/blob/main/supply%20chain%20atliq.pbix)



AtliQ Mart is a fast-growing FMCG manufacturer headquartered in Gujarat, India, currently operating in Surat, Ahmedabad, and Vadodara. The company plans to expand into metro and tier-1 cities in the next two years.

However, AtliQ Mart is facing major supply chain service issues, due to which several key customers did not renew their annual contracts. It was observed that essential products were either not delivered on time or not delivered in full over a continued period, resulting in poor customer satisfaction.

As a strategic initiative, the management decided to adopt Business and Data Intelligence to closely monitor supply chain performance and fix these issues before expansion.

## Key Supply Chain Metrics 

OT % (On-Time Delivery %)

IF % (In-Full Delivery %)

OTIF % (On-Time In-Full %)

LIFR (Line Fill Rate %)

VOFR (Volume Order Fill Rate %)

Delayed Orders

Average Delivery Delay (Days)

Total Orders, Delivered Quantity & Undelivered Quantity



## Data Model 
The data model follows a star schema design to ensure efficient analysis and scalability.

Tables Used:
dim_customers
dim_products
dim_date
fact_order_lines
fact_orders_aggregate
dim_targets_orders
Measures supply chain (DAX measures)

![image](https://github.com/Maitrisoni1803/Atliq-Supply-chain-analysis/blob/main/data%20model.png)

## Performace 

Page 1 – Supply Chain Overview
KPI cards: OT%, IF%, OTIF%
Target vs Actual comparison
City-wise service-level performance
Dynamic slicers for city, month, week, customer, and product

Page 2 – Customer & Product Analysis
Customer-wise OT%, IF%, OTIF%, LIFR%, VOFR%
Product-wise delivery performance
Monthly trend analysis to detect consistency issues
Conditional formatting to highlight underperformers

Page 3 – Order & Delay Insights
Total Orders, Delivered Quantity, Delayed Orders
Undelivered quantity by product category
Product-wise and customer-wise delay analysis
Time-based trend visualization

## Learnings


Gained a strong understanding of FMCG supply chain operations and service-level metrics such as OT%, IF%, OTIF%, LIFR, and VOFR.

Improved hands-on experience in DAX by creating complex measures and target comparisons.

Designed an optimized star schema data model for efficient reporting.

Applied consistent color themes and layouts to create business-friendly dashboards.

Enhanced the ability to convert operational data into strategic business insights

## Key Insights: 

All key service metrics are significantly below target, with OTIF at 29.39%, IF at 53.61%, and OT at 65.71%, indicating critical fulfillment gaps.

Due to delayed and incomplete deliveries, multiple key customers failed to renew contracts, posing a serious revenue risk.

Ghee, Curd, and Butter are the most frequently delayed products, impacting customer satisfaction and sales.

Lotus Mart, Coolblue, and Acclaimed Stores receive the highest number of delayed orders.

On average, orders are delivered 0.42 days later than the agreed delivery date.

There is no noticeable improvement trend in OT%, IF%, or OTIF% over recent months.

A significant gap in IF% across customers suggests issues in inventory availability or production planning.

Supply chain inefficiencies pose a high risk to expansion plans if not addressed immediately.
















