Dynamic Retail Dashboard:

Introduction:
This project embarks on an exciting journey into Walmart's retail operations, blending exploratory data analysis with interactive dashboard creation to uncover hidden patterns and deliver actionable insights. Leveraging the power of SQL and Excel, the analysis delves into Walmart’s vast data landscape to decode trends, operational efficiencies, and customer behaviors. The dynamic dashboard, meticulously crafted, transforms complex datasets into visually intuitive narratives, offering stakeholders an engaging interface to interact with the data, identify trends, and make informed decisions. By bridging the gap between raw data and strategic decision-making, this project highlights the intricate workings of Walmart's retail ecosystem and empowers stakeholders with insights to drive innovation and operational excellence.

Data description (Meta data):
-	Row Id: Specific unique id for each row.
-	Order Id: Specific unique id depending upon country from which order is placed.
-	Order date: Date on which order was placed.
-	Years: In which year order was placed.
-	Month: In which month order was placed.
-	Quarter: In which quarter of year order was placed.
-	Ship date: On which date order was shipped.
-	Ship mode: What was the ship mode of order e.g. First class, Second Class etc.
-	Customer Id: A unique id assign to each customer.
-	Customer name: Identity of customer.
-	Segment: From which segment customer belong e.g. Consumer, Corporate, Home office.
-	City: Customer residential city.
-	State: Customer residential state.
-	Country: Customer residential country.
-	Postal Code: Pin code as per place of order.
-	Market: Market from which order was placed.
-	Region: Region from which order was placed.
-	Product Id: Unique id for product identification.
-	Category: Category of product e.g. Technology, Office Supplies, Furniture.
-	Sub Category: Deviation of product with multiple category. 
-	Product name: Name of the product.
-	Sales: Sales figure for particular product.
-	Discount: Percentage discount on product price.
-	Profit: Net profit from sales.
-	Shipping Cost: Transportation/ delivery expenses.
-	Order Prior: Priority of order e.g. Critical, Medium, High, Low.


Objectives:

1. Understand Global Retail Trends
2. Market Segmentation Analysis
3. Identify Market-Specific Challenges
4. Create Dynamic Dashboard for Visualization

Steps for EDA and dynamic dashboard creation:

Step 1: Organize Raw Data

Step 2: Dashboard Objectives

Step 3: Choose Visualizations

Step 4: Create Pivot Tables

Step 5: Create Pivot Charts

Step 6: Insert Slicers

Step 7: Use Formulas for Calculations

Step 8: Create Dynamic Charts with Named Ranges

Step 9: Design the Dashboard Layout

Step 10: Conditional Formatting

Worksheet Explanation:

1.	Name of worksheet: Layout

The layout of a dashboard is the strategic arrangement of visual elements and data components to create a user-friendly and informative interface. An effective dashboard layout typically includes key sections such as headers, main content areas, and visualizations. Headers provide a clear title and context for the dashboard. Main content areas house the primary data visualizations, charts, and tables. Format of layout is as follows:

![image](https://github.com/user-attachments/assets/c2f01278-b8e6-434b-86f0-699a9b490ce9)


2.	Name of worksheet: Slicers 

In Excel, a slicer is a visual filtering tool that allows users to easily filter and interact with data in a pivot table or pivot chart. For this EDA I have used market, segment, category, year these types of slicers.

![image](https://github.com/user-attachments/assets/5bbfbd65-1e9a-463f-9247-c958bf469e3a)


3.	Name of worksheet: Major category analysis
 
Categorical analysis involves the examination and interpretation of data based on distinct categories or groups. In the context of market and segment categories, this type of analysis focuses on understanding and comparing data patterns within different markets and segments.

![image](https://github.com/user-attachments/assets/5596e7e0-94e6-4fa0-9d1b-0243a86cf0b4)


4 .Name of worksheet: Growth analysis

Growth analysis involves the examination of changes in key financial metrics, such as sales and profit, from one period to another, typically from the previous year to the current year. This analysis provides insights into the performance and trajectory of a business over time.

![image](https://github.com/user-attachments/assets/88371540-f1c2-4b7e-99b1-85c58be9e6d7)


5.	Name of worksheet: Quantitative analysis

Quantitative analysis involves the systematic examination of numerical data to derive meaningful insights and make informed decisions. In the context of sales, profit, and orders related to order IDs, quantitative analysis would focus on numerical measures and relationships within these variables. For example, analysts may calculate key performance indicators (KPIs) such as average sales per order, profit margins, or trends in order quantities over time.

![image](https://github.com/user-attachments/assets/37a31fc0-9ee2-4664-9bfa-f714153f0e07)


6.	Name of worksheet: Time Series

 Time series analysis involves the examination of data points collected over successive time intervals to uncover patterns, trends, and dependencies. In the context of total orders over the year and their distribution across quarters, time series analysis would focus on understanding how order quantities vary over time.

![image](https://github.com/user-attachments/assets/20637c64-ea0a-4133-a975-17bfcb76e480)


7.	Name of worksheet: Dashboard

 A dynamic dashboard is created based on retail data analysis of Walmart from 2019 to 2022, is an interactive and visually engaging platform that automatically updates to reflect real-time changes in the underlying dataset. Leveraging features like pivot tables, charts, and slicers, the dynamic dashboard provides users with the flexibility to explore key retail metrics such as sales, profit, and order data across different categories, segments, and time periods. Users can interactively filter data based on specific criteria, drill down into details, and observe trends over the four-year period. This dynamic approach enhances the user experience, allowing stakeholders to gain actionable insights from Walmart's retail data dynamically, facilitating better decision-making and strategic planning based on the evolving trends observed over the specified timeframe.
 
![image](https://github.com/user-attachments/assets/a3ffddcb-e0e5-4096-aa51-9e334a44d38e) 

Exploratoty Data Analysis:

For Africa Market:

 A visual analysis of Walmart's retail data for the African market from 2019 to 2022 reveals a consistent and robust growth trend across key metrics, including orders, sales, profit, and quantities. The graph showcases a steady upward trajectory, indicating a positive and sustained expansion of Walmart's presence in the African market. The consistent rise in orders reflects increasing customer demand, while escalating sales and profit figures underscore the effectiveness of Walmart's strategies in this region. Concurrently, the growth in quantities suggests a successful alignment of product offerings with consumer preferences. This visual representation of Walmart's retail data underscores the company's successful market penetration and sustained growth in Africa over the analysed period.

![image](https://github.com/user-attachments/assets/7ae26ab2-ae5c-432d-b836-6612ab3beaa8)


For APAC Market:
 
A visual analysis of Walmart's retail data for the Asia-Pacific (APAC) market spanning the years 2019 to 2022 illustrates a consistent and remarkable growth pattern across key metrics, including orders, sales, profit, and quantities. The graph showcases a persistent upward trend, indicating substantial expansion and success for Walmart in the APAC region. The continuous increase in orders reflects a growing customer base and heightened market demand. The parallel growth in sales and profit metrics underscores the effectiveness of Walmart's strategies in capturing and capitalizing on opportunities in the APAC market. Concurrently, the rising quantities signify a successful alignment of product offerings with the preferences of APAC consumers. This visual representation of Walmart's retail data underscores the company's sustained growth and thriving presence in the dynamic and diverse APAC market throughout the analysed period.

![image](https://github.com/user-attachments/assets/a51e58f8-ab4b-4b65-85c1-69dbf9816551)

For Canada Market:
 
 The retail data analysis for Walmart in the Canadian market reveals a distinctive trend from the fourth quarter of 2019 to 2022. The graph illustrates a decline in orders, sales, profit, and quantities during the fourth quarter of 2019, followed by a steady and consistent growth trajectory in the subsequent years. The decline in the fourth quarter of 2019 might be attributed to various factors, such as economic fluctuations, seasonal challenges, or specific market dynamics during that period.
However, the subsequent years' steady growth signals Walmart's ability to adapt, implement effective strategies, and recover from the challenges experienced in 2019. The upward trend in orders, sales, profit, and quantities from 2020 to 2022 reflects the success of Walmart's initiatives, resilience in the face of challenges, and an overall positive performance in the Canadian market.

![image](https://github.com/user-attachments/assets/09972110-772d-4cb2-9b0b-b9463a463bab)


For EMEA Market:
 
The retail data analysis for Walmart in the Europe, Middle East, and Africa (EMEA) market from 2019 to 2022 reveals a compelling and consistent growth pattern across various key metrics, including orders, sales, profit, and quantities. The graph illustrates a sustained upward trajectory, indicating a positive and steady expansion of Walmart's operations and success in the EMEA market over the analysed period. The continuous increase in orders reflects a growing customer base and heightened market demand.
The parallel growth in sales and profit metrics underscores the effectiveness of Walmart's strategies in navigating the EMEA market dynamics, capturing consumer attention, and translating it into profitable outcomes. Simultaneously, the rising quantities signify a successful alignment of product offerings with the preferences and needs of consumers in the region.

![image](https://github.com/user-attachments/assets/8dc5849f-033b-4f1b-a681-58096fdb6fd3)

For EU Market:
 
 The retail data analysis for Walmart in the European Union (EU) market from 2019 to 2022 indicates a remarkable and consistent growth pattern across key metrics, including orders, sales, profit, and quantities. The graph illustrates a sustained upward trajectory, signifying a positive and steady expansion of Walmart's presence and success in the EU market throughout the analysed period. Notably, the EU market stands out with the steadiest growth among all the markets analysed.
The continuous increase in orders reflects a growing customer base and heightened market demand in the EU region. This growth is further mirrored in sales and profit metrics, emphasizing the effectiveness of Walmart's strategies in navigating the EU market dynamics and capitalizing on consumer preferences. Simultaneously, the rising quantities suggest a successful alignment of product offerings with the diverse needs of consumers in the EU.

![image](https://github.com/user-attachments/assets/5d52ec1c-94de-420b-8af3-d2ce1aa3c460)

For LATHAM Market: 
 
The retail data analysis for Walmart in the Latin America and the Caribbean (LATHAM) market from 2019 to 2022 reveals a consistent growth pattern marked by constant fluctuations in orders, sales, profit, and quantities. The graph illustrates a general upward trend, indicating overall market expansion over the analysed period. However, the presence of fluctuations suggests that the market experiences dynamic conditions, possibly influenced by factors such as economic variations, regional events, or shifts in consumer behaviour.
The continuous growth in orders, sales, profit, and quantities implies that Walmart has been successful in navigating the challenges and leveraging opportunities in the LATHAM market. The fluctuations observed may be attributed to the inherent complexities and variability of the market, requiring adaptability and strategic responses from Walmart to maintain growth momentum.
This dynamic retail data underscores Walmart's resilience and effectiveness in managing a market characterized by fluctuations, showcasing the company's ability to adjust strategies and operations to suit the unique demands and uncertainties within the Latin America and Caribbean region.

![image](https://github.com/user-attachments/assets/d035a1b7-62f6-4efc-abbb-22bc993549e8)


For US Market:
 
The retail data analysis for Walmart in the United States from 2019 to 2022 unveils a story of collective growth and resilience, characterized by consistent expansion and a unique quarterly pattern. The graph showcases a steady upward trajectory throughout each year, with a distinctive quarterly growth pattern. From the first quarter to the fourth quarter, the graph consistently rises, underscoring a shared journey of progress.
This collective growth pattern signifies not only the success of Walmart but also the shared prosperity of communities and individuals across the United States. The constant fluctuations in orders, sales, profit, and quantities are emblematic of the dynamic nature of the market and the adaptability of both Walmart and its community of shoppers to changing circumstances.

![image](https://github.com/user-attachments/assets/42e0e508-0316-473d-bb78-dec8a215c52b)

Market Composition
 
The retail market composition of Walmart illustrates a global presence with diverse geographical allocations. In this breakdown, the United States holds a significant share at 23%, showcasing Walmart's strong footprint in its home market. Africa occupies 4%, indicating a presence and market share in the African continent. The Asia-Pacific (APAC) region holds a substantial 26%, reflecting Walmart's strategic positioning and growth in this dynamic market.
The Europe, Middle East, and Africa (EMEA) region occupy 5%, while the European Union (EU) holds 17%, showcasing Walmart's presence and market share in these regions. Latin America and the Caribbean (LATHAM) hold a significant share at 25%, highlighting Walmart's influence in this diverse market. Canada occupies 0.8%, signifying a presence in the North American market.
This market composition emphasizes Walmart's global reach and its ability to navigate and cater to diverse consumer markets across continents. Each region's share reflects Walmart's strategic approach to adapt and succeed in various market landscapes, contributing to its overall position as a leading global retailer.

![image](https://github.com/user-attachments/assets/7c14f4b2-97be-45ec-b8f5-91375b7e4a1e)

 

FINDINGS:
 
By observing 5.2.4 Analysis for EMEA Market following conclusion and patterns are formed:
The exploratory data analysis of Walmart's retail data spanning 2019 to 2022 revealed a notable trend. Among the major markets, including Africa, APAC, Canada, EMES, EU, LATHAM, US, and EMEA, it was consistently observed that EMEA was the only market experiencing quarterly losses in at least one quarter each year from 2019 to 2021. In contrast, all other markets, including Africa, APAC, Canada, EMES, EU, LATHAM, and US, demonstrated steady growth in both sales and profits throughout this period. This finding underscores the need for targeted strategies in the EMEA market to address the recurring losses and emphasizes the overall positive trajectory of Walmart's retail operations in most other regions.

![image](https://github.com/user-attachments/assets/9a113412-44e1-4f46-9bde-f64b24850fb7)


SUGGESTION

Given the consistent occurrence of quarterly losses in the EMEA market from 2019 to 2021, a targeted approach is crucial to enhance profitability. Here are specific suggestions:

1. Market-Specific Analysis   

2. Product and Pricing Optimization
   
3. Operational Efficiency
   
4. Customer Engagement and Loyalty Programs
      
8.	Collaboration with Local Partners








