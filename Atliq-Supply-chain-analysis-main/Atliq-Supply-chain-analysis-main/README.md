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








