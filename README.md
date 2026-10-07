# Food Ordering Behaviour and Consumer Trends

A Tableau analysis of 50,000 food delivery orders, built as a capstone project on SkillWallet.

## Problem Statement
The food delivery industry is highly competitive. Businesses hold large volumes of data but find it hard to see which factors drive order demand, customer spending and delivery efficiency. This project turns raw order data into clear, actionable insights using interactive Tableau dashboards.

## Users
- **Rahul Sharma (Business Analyst):** studies demand, order value and customer behaviour across cities, cuisines and meal types.
- **Priya Mehta (Operations Manager):** studies delivery time and order volumes to find delays and improve efficiency.

## Dataset
- 50,000 orders across 6 cities: Mumbai, Pune, Bangalore, Delhi, Chandigarh, Hyderabad
- Key fields: Order Id, City, Cuisine, Meal Type, Company (who the customer ordered with), Restaurant Type, Age, Order Value, Delivery Fee, Rating Given, Time Taken To Order
- Customer ages range from 18 to 44

## Tools
- Tableau Public
- GitHub

## Project Steps
1. Downloaded the dataset and loaded it into Tableau
2. Checked column names and data types
3. Created calculated fields (Age Group) and bins (delivery time, bin size 2)
4. Built 9 visualizations (listed below)
5. Combined them into one interactive dashboard with a City filter
6. Created a Tableau Story that walks from overview to insights to recommendation
7. Published the workbook to Tableau Public

## Visualizations
| # | Visualization | Chart Type |
|---|---------------|------------|
| 1 | KPI Demonstration (Total Orders, Total Order Value, Delivery Fee, Avg Rating) | Text table |
| 2 | Cities by Order Volume | Bar chart |
| 3 | Cuisine Distribution | Pie chart |
| 4 | Flavors Across Cities | Heatmap |
| 5 | Orders by Company Type and Meal Type | Bar chart |
| 6 | Revenue by Meal Type | Bar chart |
| 7 | Customer Rating by Meal Type | Pie chart |
| 8 | Age Group by Restaurant Type | Stacked bar chart |
| 9 | Delivery Time Distribution | Bar chart |

## Key Insights
- **KPIs:** 50,000 orders, about 27.4M in total order value, about 2.98M in delivery fees, and an average rating of 3.
- **Cities:** Mumbai has the most orders, but all six cities are close, so demand is spread evenly rather than depending on one location.
- **Cuisine:** Desserts is the most ordered cuisine, followed closely by Fast Food. North Indian is the lowest, but the gaps are small, so no single cuisine dominates.
- **Flavors across cities:** Order counts per cuisine and city range from about 1,300 to 1,460, which shows consistent demand everywhere.
- **Revenue by meal type:** Breakfast brings in the most revenue (about 6.92M) and Dinner the least (about 6.75M), though the difference is small.
- **Company type:** orders are spread evenly across Alone, Friends, Family and Partner with no group clearly leading.
- **Customer ratings:** Ratings are evenly spread across all meal types
- **Age groups:** millennials leads all of them.
- **Delivery time:** Most deliveries take 2 to 12 minutes and very fast or very slow deliveries are less common.

## Recommendations
1. Keep marketing balanced across all cities, with extra promotion in the top city.
2. Promote Desserts and Fast Food, and run offers on the lower-ordered cuisines to lift them.
3. Create targeted offers for the customer group that orders the most.
4. Monitor delivery times to find and reduce delays.

## Live Dashboard
https://public.tableau.com/app/profile/gunjan.maind/viz/Foodorderingbehaviourandconsumertrends/FoodorderingStory?publish=yes

## Repository Contents
- `.twbx` Tableau workbook
- Dataset (CSV)
- README.md

## Author
Gunjan Maind
