## Sales_Insight_Using_PowerBI_MySQL

#### Dashboard Demo
https://github.com/user-attachments/assets/7fde4a12-9b76-4bf1-b450-ba747b47236d


### PROBLEM STATEMENT: 
XYZ hardware is a company that supplies computer hardware and peripherals to its clients across India. Head office in Delhi and regional offices spread across different regions of India. The Sales Director is facing challenges: Market is growing dynamically and she's facing challenges in tracking insights of her
business. She has regional managers in North India, South India and Central India and whenever she needs insights, she connects with them over call or email. The problem, however, is that the conversations are verbal and it may happen that the conversations may appear rosier than what data would suggest. So, the Sales Director is frustrated with the situation. When asked for numbers, the regional managers gave her 60 big Excel files. She is more interested in an interactive dashboard where she can go and look at the real data.

### PROPOSED SOLUTION:
A picture is worth a thousand words. A Power BI dashboard is based on data and not verbal estimates. This will allow her to get a more factual idea of the business and make data driven business decisions.

Project Planning through AIMS Grid -<br/>
A. PURPOSE: To unlock sales insights that were not visible before for sales team for decision support and automate them to reduce manual time spent in data gathering.<br/>
B. STAKEHOLDERS: Sales Director, Marketing Team, Customer Service Team, Data Analytics Team, IT<br/>
C. END RESULT: An automated dashboard providing quick and latest sales insights in order to support data driven decision making.<br/>
D. SUCCESS CRITERIA<br/>
1. Dashboards uncovering sales order insights with latest data available.
2. Sales team able to take better decisions and prove 10% cost savings of total spend.
3. Sales analysts stop data gathering manually in order to save 20% of their business time.
4. Increase sales by at least 5% by next quarter.

The company has an IT team that has built a Sales Management System already. This software stores records in a MySQL database. The analytics team wants to build an ETL from MySQL to Power BI. Build Dashboard on top of it. 

To make sure that MySQL DB is not affected by queries that are run via Power BI, companies often keep a copy of DB in the Data Warehouse. OLTP -> OLAP <br/>
I don't want any critical systems to slow down or crash. <br/>
Pull data from MySQL(OLTP) -> ETL -> Push data to Data Warehouse(OLAP) (Snowflake) <br/>

END PRODUCT: A powerful dashboard where business manager can track revenue numbers, YoY numbers, 
breakdown by regions, products and identification of trends.  

#### Database Schema
![DB Schema](https://github.com/user-attachments/assets/53369e1e-697e-4e33-88a7-3fda193cddfe)

#### PowerBI Model View
![Model View - Established Relationships](https://github.com/user-attachments/assets/4d17e637-5583-49de-abc3-f115055d8160)




