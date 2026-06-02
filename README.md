Overview: The primary objective of this project is to design and develop a comprehensive Car Sales Dashboard utilizing Power BI. The focus will be on creating an interactive platform that extracts valuable insights from visual representations of key performance indicators (KPIs) associated with our car sales. Through this dashboard, we aim to provide a user-friendly interface that empowers stakeholders to easily interpret and analyze crucial data, fostering informed decision-making based on a deeper understanding of our sales performance trends.

Requirements:
KPI:
1. Sales Overview:
Year-to-Date (YTD) Total Sales
Month-to-Date (MTD) Total Sales
Year-over-year (YoY) Growth in Total Sales
Difference Between YTD Sales and Previous Year-to-Date (PYTD) Sales
3. Average Price Analysis:
YTD Average Price
MTD Average Price
YoY Growth in Average Price
Difference Between YTD Average Price and PYTD Average Price
4. Cars Sold Metrics:
YTD Cars Sold
MTD Cars Sold
YoY Growth in Cars Sold
Difference Between YTD Cars Sold and PYTD Cars Sold
Charts:
YTD Sales Weekly Trend: Display a line chart illustrating the weekly trend of YTD sales. The X-axis should represent weeks, and the Y-axis should show the total sales amount.
YTD Total Sales by Body Style: Visualize the distribution of YTD total sales across different car body styles using a Pie chart.
YTD Total Sales by Colour: Present the contribution of various car colours to the YTD total sales through a Pie chart.
YTD Cars Sold by Dealer Region: Showcase the YTD sales data based on different dealer regions using a bar chart to visualize the sales distribution geographically.
Company-Wise Sales Trend in Grid Form: Provide a tabular grid that displays the sales trend for each company. The grid should showcase the company name along with their YTD sales figures.
Details Grid Showing All Car Sales Information: Create a detailed grid that presents all relevant information for each car sale, including car model, body style, colour, sales amount, dealer region, date, etc.
Goal: The project goal is to implement an intuitive and dynamic Car Sales Dashboard using Power BI, with a focus on extracting actionable insights from visualized key performance indicators (KPIs). This dashboard aims to provide a centralized platform for stakeholders to comprehensively analyse and interpret critical data related to car sales. By achieving this goal, the project seeks to enhance decision-making processes, enabling the team to make informed and strategic choices based on a real-time understanding of sales performance trends and patterns.

Data Source:
Kaggle Dataset: https://www.kaggle.com/code/eugeniokukes/car-sales-eda-machine-learning
Tools Used:
Excel - Data Cleaning
Power BI – Data Analysis & Visualization
Data Preparation and Modelling Approach:
Data Loading and Inspection.
Handling Missing Values.
Removing Blank Values and Outliers.
Data Cleaning and Formatting.
Creating a Calendar Table.
Establishing Relations for the Data Model.

<img width="1319" height="120" alt="image" src="https://github.com/user-attachments/assets/f1e65a2e-096c-4158-b8c9-07a851dddc54" />

1.Year-to-Date (YTD) Total Sales: A remarkable $371.2 million.
2.Year-over-year (YOY) Growth in Total Sales: An impressive 23.59% increase.
3.YTD Average Price: Stands at $28,000.
4.YOY Growth in Average Price: Slightly down at -0.75%.
5.YTD Cars Sold: An incredible 13,300 units.
6.YOY Growth in Cars Sold: A whopping 24.57% rise.
7.YTD Sales Weekly Trend: Notable peaks in weeks 39, 46, and 50.
8.YTD Total Sales by Body Style: SUVs take the lead.
9.YTD Total Sales by Colour: Pearl White cars stand out with 11.26k sales, followed by black and red cars.
10.YTD Cars Sold by Dealer Region: The Austin region emerges as the top performer with around 4,135 sales

Top 5 Companies by Car Sales
1.Chevrolet leads the way with 1,819 cars sold.
2.Dodge follows closely with 1,671.
3.Ford with 1,614.
4.Volkswagen with 1,333.
5.Mercedes-Benz with 1,285.

<img width="353" height="316" alt="image" src="https://github.com/user-attachments/assets/24b6eee3-7767-4984-a679-cefda66e292b" />

In the Year-To-Date Sales breakdown by Body Style:
SUVs dominate the landscape, accounting for the largest share at 26.91%, sales of $100M
Hatchbacks follow closely, covering 22.30% of the sales with a revenue of $8M
Sedans secure a significant portion at 19.85%, contributing $74M in sales.
Passenger vehicles claim a share of 17.09%, generating $63M in sales.
Hardtops round out the categories, encompassing 13.85% and $51M in sales.

<img width="350" height="310" alt="image" src="https://github.com/user-attachments/assets/0b4a0449-f184-4035-aa53-e62a758de60d" />

In the Year-To-Date Sales breakdown by Body Color:
The majority of cars sold are in the Pale White color, contributing significantly with sales reaching $17M, representing 47.02% of the total sales across all color categories.
Black-colored cars follow closely, achieving sales of $125M, constituting 33.74% of the overall sales.
Red-colored cars contribute $71M in sales, making up 19.24% of the total sales for the period.

<img width="576" height="319" alt="image" src="https://github.com/user-attachments/assets/6f2ca261-c4d0-4cb0-b493-264780b000cf" />


Observing the Area Chart depicting the Year-to-Date Sales Weekly Trend:
In the 36th week, there is a notable peak, indicating the highest car sales of $14.9 million.
The 47th week maintains a strong sales figure, closely following with $14.7 million in car sales.
During the 45th week, there is a peak at $14 million in sales.
The 52nd week shows a decline in sales, totaling $12.2 million.
In the 29th week, the sales figure reaches $9.7 million.
The 24th week records $9.5 million in car sales etc.

<img width="563" height="310" alt="image" src="https://github.com/user-attachments/assets/aa8a87b6-9255-4cb4-8a2c-a69c4eef3b80" />

The Map Chart highlights Year-To-Date cars sold across different dealer regions: Predominantly, the Austin 2296 and Janesville 2113 regions stand out as key areas for car sales.
In contrast, there is a comparatively lower number of car sales in regions such as Scottsdale 1912, Pasco 1749, and Greenville 1740 among others.
The geographical distribution depicted in the chart offers a clear overview of the varying sales performance across different dealer regions.

<img width="717" height="310" alt="image" src="https://github.com/user-attachments/assets/9915a175-7424-456a-9bc5-5486ef93652a" />

Company Wise Sales Trend:
Chevrolet, Dodge, Ford, Chrysler, BMW, and others are demonstrating strong performance in year-to-date (YTD) sales.
Chevrolet leads the pack with an impressive 1043 cars sold YTD.
Dodge closely follows with 949 cars sold YTD.
Ford maintains a robust sales performance, having sold 886 cars YTD.
Chrysler is performing well with 618 cars sold YTD.
BMW exhibits a solid sales trend, securing 445 cars sold YTD.
These figures showcase the positive sales momentum of these key companies in the current period.

Areas for Business Improvement:
Utilize insights on top-selling colors and body styles to tailor marketing campaigns and meet customer preferences.
Leverage the popularity of SUVs by optimizing inventory to meet customer demand and capitalize on trending styles.
Identify and implement best practices from top-performing dealers to enhance sales strategies and improve overall dealer performance.
Allocate resources to regions with lower sales figures and explore strategies to increase market share.
Analyse the slight dip in the Year-over-Year (YoY) growth in average price. Consider pricing strategies or promotions to boost average transaction values.
Regularly benchmark against competitors, especially the top 5 companies, to identify opportunities for improvement and maintain a competitive edge.  
By focusing on these areas, the business can fine-tune its strategies, improve customer satisfaction, and stay ahead in the dynamic automotive market.

Conclusion:
The Car Sales Dashboard project has successfully achieved its goal of providing a dynamic and intuitive platform for extracting actionable insights from key performance indicators (KPIs) related to our car sales. Through comprehensive data analysis and visualization using Power BI, we've uncovered valuable insights that can significantly impact our decision-making processes.

DASHBOARD:

<img width="1544" height="864" alt="image" src="https://github.com/user-attachments/assets/59cae271-25c1-4711-8853-04216a1ca71d" />

<img width="1543" height="865" alt="image" src="https://github.com/user-attachments/assets/777b8515-4009-4bab-ba76-1471abb9b98b" />


