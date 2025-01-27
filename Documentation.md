## Data Visualisation: Empowering Business with Effective Insights

### Internship Introduction:
This is a virtual internship program case study with the company, Accenture North America. This program is hosted through the site called "Forage". This internship helps you to learn data basics such as data cleaning, modelling, visualization and storytelling.

### Internship Company:
![](https://cdn-images-1.medium.com/max/1000/1*CQM2isxyKMptAdH-ByFZCw.jpeg)

Tata Group is a global conglomerate which operates in more than 100 countries across six continents, with a mission 'To improve the quality of life of the communities we serve globally, through long-term stakeholder value creation based on Leadership with Trust'. With a revenue of $128 billion (INR 9.6 trillion) in 2021–22, the companies collectively employ over 935,000 people. There are 29 publicly listed Tata enterprises - many being market leaders in their industries.

### Certificate:
![](https://github.com/KarishmaKolhe51/Data-Visualisation-Empowering-Business-with-Effective-Insights/blob/main/Certificate.jpg)

### Project File:
All the files related to this internship can accessible [here](https://github.com/KarishmaKolhe51/Data-Visualisation-Empowering-Business-with-Effective-Insights)

### Scenario:
An online retail store has hired you as a consultant to review their data and provide insights that would be valuable to the CEO and CMO of the business. The business has been performing well and the management wants to analyse what the major contributing factors are to the revenue so they can strategically plan for next year.
The leadership is interested in viewing the metrics from both an operations and marketing perspective. Management also intends to expand the business and is interested in seeking guidance into areas that are performing well so they can keep a clear focus on what's working. They would also like to view different metrics based on the demographic information that is available in the data.
A meeting with the CEO and CMO has been scheduled for next month and you need to draft the relevant analytics and insights that would help evaluate the current business performance and suggest metrics that would enable them to make the decision on expansion.

#### Dataset Summary:
The client provided one dataset, Online Retail.
The dataset has 9 columns namely,
- InvoiceNo
- StockCode
- Description
- Quantity
- InvoiceDate
- UnitPrice
- CustomerID
- Country
- Revenue

The InvoiceNo column has the invoice number of each purchase made by customers. StockCode has the products stock code. Description has the products description and information. InvoiceDate has dates from when the purchase happened. UnitPrice has the price of the product. CustomerID tells us who purchased the product in numerical form. Country is where the customer resides in. We multiplied UnitPrice and Quantity to make the column Revenue to show insights for the client.

#### Data Preparation:
Before we begin the analysis, we must make sure the data is clean and without errors. We used Excel to clean the dataset with the following steps:
- Removed Rows in the Quantity column showing negative numbers or below 1
- Removed Rows in the UnitPrice column that are below $0
- Removed Rows with blanks
- Added Revenue Column from multipling UnitPrice with Quantity

### Task 1: Framing the Business Scenario
We are tasked with anticipating the business task that the client might ask. We need to draft questions that we think will be important and relevant to the CEO and CMO. The deliverables are 4 relevant questions each to the CEO and CMO that wants to know the answers to with regards to the dataset provided.

**Concerns the CEO may have**
- Which region is producing the most profit, and which region is producing the least?
- What is the trend for revenue on a monthly basis, and which months have seen the highest rise or fall in revenue?
- What quarters had the most revenue? Are sales impacted by the seasons?
- What percentage of overall income are the top customers responsible for? Are these customers essential to the company's success, or is the customers more diverse?

**Concerns the CMO may have**
- How many customers make the same purchases again and over again? Do they place similar orders or do they place distinct orders?
- How long does it take for returning customers to place their next purchase after receiving the first one?
- Which consumers have placed many orders and how much profit is generated by them?
- Who are the consumers who have returned the most frequently? What percentage of the revenue do they contribute?

For more information about Framing the Business Scenario [click here](https://docs.google.com/document/d/1dVPPoY97qXnpMAcx6_d8A4X45S-dhn4keRUtwaUwFgg/edit?usp=sharing).

### Task 2: Choosing the Right Visuals
With this task, we are tested about what different charts and visuals can be appropriate for different kinds of scenarios. Following are quiz questions we need to answer.

**1:** The CEO of the retail store is interested to view the time series of the revenue data for the entire year. The CEO is interested in viewing the seasonal trends and wants to dig deeper into why these trends occur. This analysis will be helpful for the CEO to forecast for the next year.

Which visual would most likely help the CEO analyse the data?

**Ans:** Line Chart

A line chart is used to represent repeated measurements taken over regular time intervals. Time is always displayed on the horizontal axis and values on the vertical axis. The line chart would enable the CEO to see important changes in the data, like seasonality or cyclic behaviour, which will provide a better understanding of the revenue and help forecast better.

**2:** The CMO is interested in viewing the top 10 countries which are generating the highest revenue. Additionally, as a subcomponent, they would also like to see which products are contributing to the total revenue being generated by each country.

Which visual would enable the CMO to view the revenue for each country and the breakdown by products on a single chart?

**Ans:** Stacked Bar Chart

A stacked bar chart would be used here as the chart allows users to compare subcomponent pieces across different categories. The height or length of the bars will represent the total revenue generated by each country. Each bar will be divided into the products sold, where the major portion will be allocated to the products that are generating more revenue. This will allow the CMO to view the total revenue data as well as the revenue for each individual product.

**3:** The CEO of the online retail store wants to see how much average revenue is generated by each country. They are interested in viewing the following metrics on the visual:
- Minimum value
- First quartile value
- Median value
- Third quartile value
- Maximum value

Which chart would you create to show the above metrics for the average revenue generated by each country?

**Ans:** Box Plot

The CEO's request would best be fulfilled using a box plot. The box plot would show the distribution of data based on a five number summary ("minimum", first quartile, median, third quartile, and "maximum"). Boxplots are used to graphically demonstrate the locality, spread and skewness groups of numerical data. Boxplots are used to graphically demonstrate the locality, spread and skewness groups of numerical data. By using the boxplot, we can easily spot outliers and the distribution of the plot.

**4:** The CMO of the online retail store wants to view the information on the top 10 customers by revenue. They are interested in a visual that shows the greatest revenue-generating customer at the start and gradually declines to the lower revenue-generating customers. The CMO wants to target the higher revenue-generating customers and ensure that they remain satisfied with their products.

Which visual would help the CMO understand the data on revenue generated by the top 10 customers?

**Ans:** Column Chart

The CMO's request would best be fulfilled by using a column chart. Column charts are used to display comparisons between different items. Alternatively, you can view a comparison of items over time. In this case, the column chart would display the top 10 customers who are contributing the most to revenue. The first bar on the left would be the longest one and would display information for the customer who bought the most goods from the online store. The revenue contributed by each customer would gradually decline as the bars move to the right.

**5:** The CEO is looking to gain insights on the demand for their products. They want to look at all countries and see which regions have the greatest demand for their products. Once the CEO gets an idea of the regions that have high demand, they will initiate an expansion strategy which will allow the company to target these areas and generate more business from these regions.
He wants to view the entire data on a single view without the need to scroll or hover over the data points to identify the demand.

Which chart would be most useful to provide the CEO information on the demand in each region?

**Ans:** Map Chart

A map chart would be the best option for visuals here as it will allow the CEO to view the demand information on a single view. The map chart will have all the countries on a single map and the demand will be displayed by highlighting the area of each country. Dark highlights would mean that the countries have high demand for products whereas the countries that are highlighted light color are the ones that have low demand. Geographical data is best visualized using map charts as they are very easy to view and the underlying values are also easy to analyse.

### Task 3: Creating Effective Visuals
In this task, the client provided us with the business tasks they need for anaysis. Here are the charts and visualization created with each business task:

**Question 1:** The CEO of the retail store is interested to view the time series of the revenue data for the year 2011 only. He would like to view granular data by looking into revenue for each month. The CEO is interested in viewing the seasonal trends and wants to dig deeper into why these trends occur. This analysis will be helpful for the CEO to forecast for the next year.
![](https://cdn-images-1.medium.com/max/1000/1*2_DNF2J2AgyPdDtUGq40sg.png)

**Question 2:** The CMO is interested in viewing the top 10 countries which are generating the highest revenue. Additionally, the CMO is also interested in viewing the quantity sold along with the revenue generated. The CMO does not want to have the United Kingdom in this visual.
![](https://cdn-images-1.medium.com/max/1000/1*2VHKv0J2deKzV4fUfqgP-Q.png)

**Question 3:** The CMO of the online retail store wants to view the information on the top 10 customers by revenue. He is interested in a visual that shows the greatest revenue generating customer at the start and gradually declines to the lower revenue generating customers. The CMO wants to target the higher revenue generating customers and ensure that they remain satisfied with their products.
![](https://cdn-images-1.medium.com/max/1000/1*XoXgyYMDgFt7cOo3HMmoBg.png)

**Question 4:** The CEO is looking to gain insights on the demand for their products. He wants to look at all countries and see which regions have the greatest demand for their products. Once the CEO gets an idea of the regions that have high demand, he will initiate an expansion strategy which will allow the company to target these areas and generate more business from these regions. He wants to view the entire data on a single view without the need to scroll or hover over the data points to identify the demand. There is no need to show data for the United Kingdom as the CEO is more interested in viewing the countries that have expansion opportunities.
![](https://cdn-images-1.medium.com/max/1000/1*ZdOHK8dDb4i8Z2NhGbe7vQ.png)

### Task 4: Communicating Insights and Analysis
We are tasked to communicate findings to CEO and CMO. I have developed a document regrading insights and analysis.

Good Afternoon,

I'm Karishma Kolhe, and I'm eager to share some information with you regarding your company. I appreciate you giving me the leading questions. Seeing the sorts of insights, you expect to derive from the data was useful. I really believe you will find the analysis convincing and useful as you decide how to proceed with your next business prospects.

I want to start by assuring you that I have given the most accurate and current analysis. I cleaned up any records with negative quantities and unit prices after loading the data into my software, since it was necessary to do so in order to give useful analysis.

**1st**

Regarding your first query, the CEO has asked for a revenue trend to determine whether retail sales are seasonal. According to the data, there are several months of the year that have significant development. According to the statistics, the first eight months of sales from January to August were very stable, with an average of $685K (Six hundred eighty-five thousand US dollars) in revenue per month. The increase in revenue begins in September, when it grows by 40% over the previous month. This pattern persisted up until November, when it rose to 1.5 million US dollars, the largest amount of the whole year. Unfortunately, since the data for December is insufficient, no inferences can be made from it. This research demonstrates how seasonality - which generally happens in the last four months of the year - affects retail store sales.

**2nd**

The top 10 countries with the most potential for growth are represented in the second graph. Since the UK already has a large demand and I understand you are more interested in nations where demand may be boosted, the UK is not included in these statistics. According to the data, sales of units and income are quite high in nations like the Netherlands, Ireland, Germany, and France. To guarantee that steps are taken to further seize these markets, I would propose concentrating on these nations.

**3rd**

The top 10 consumers who have made the most purchases from the business have been the subject of the third study. According to the statistics, there are not many differences between the top 10 consumer purchases. The fact that the highest revenue-producing consumer only spent 17% more than the second highest demonstrates that the company does not rely solely on a small number of consumers to generate income. This demonstrates that consumers' ability to negotiate is limited and that the state of business is positive.

**4th**

The map chart concludes by comparing the places that have produced the greatest revenue to those that have not. Apart from the UK, it is clear that nations like the Netherlands, Ireland, Germany, France, and Australia generate large profits, and the company should invest more in these nations to boost product demand. The map also reveals that the majority of sales occur only in the European zone, with only a small number in the American region. Along with Russia, there is no market for the items in Africa or Asia. Sales revenues and profitability might increase with the implementation of a fresh strategy focused on these areas.

I much appreciate your time. After you've had a chance to process this material, if you have any questions about the analysis or would want to see anything additional, I would be glad to create it for you.

Thank You
