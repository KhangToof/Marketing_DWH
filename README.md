![image](https://github.com/KhangToof/Marketing_DWH/assets/93634247/30fcbcf2-2359-4905-8186-5bb09f3b1025)# Marketing_DWH
 **Market Analysis Data Warehouse**
## 1. Dataset
- Data: [Marketing Campaign](https://github.com/YuehHanChen/Marketing_Analytics/blob/main/marketing_data.csv)
- The data on marketing campaigns is collected for 2 years and published in 12/2020 (2012-2014).
- Throughout the dataset, we can claim customers' information, the money spent for each kind of products, the purchases of different ways, customers' responses,...
- The dataset includes 28 columns, 2240 rows.
--------------------------------------
## 2. Dimension and Fact tables
### a. DimDate table
- Contains information about recorded timestamps.
- Includes attributes such as year, quarter, day, and month.
- Primary key of this table is "DateKey".
### b. DimCustomer table
- Contains information about recorded customers.
- Includes attributes such as income, marital status, amount paid for each type of prods,...
- Primary key of this table is "CustomerKey".
### c. Fact_MarketingAnalytic table
- Contains information about customer influences on Marketing campaigns.
- Includes attributes such as complaints, total approved campaigns, total spent,...
- This table will refer to the previous two Dimension tables to establish relationships.
There will be foreign key references to ensure data integrity.
--------------------------------------
## 3. Schema
![Schema](https://github.com/KhangToof/Marketing_DWH/assets/93634247/a8dfc778-441e-4c36-9b2e-5226c67bc0ea)
--------------------------------------
## 4. ETL Process
![ETL](https://github.com/KhangToof/Marketing_DWH/assets/93634247/55b2b546-eba9-4ee0-9acf-caf606ab2960)
--------------------------------------
## 5. SSAS
### a. Data Cube
![DataCube](https://github.com/KhangToof/Marketing_DWH/assets/93634247/57a4808f-1255-4dac-9dbe-5b3e253d20b9)


**_Calculated member and Some of the Named Sets_**
- Calculated member:
![image](https://github.com/KhangToof/Marketing_DWH/assets/93634247/7c6a287d-3636-4630-bdce-c14d39e1f662)
- Some of the Named Sets:\
<img src="https://github.com/KhangToof/Marketing_DWH/assets/93634247/5ced2a84-d113-4b1a-b7b3-179bf79ce618" width="350" height="150"> <img src="https://github.com/KhangToof/Marketing_DWH/assets/93634247/7986e44f-e4d9-4e34-b26d-a55cb9ba41b0" width="450" height="150"> <img src="https://github.com/KhangToof/Marketing_DWH/assets/93634247/77e2482a-c625-483b-8384-7084b7208c25" width="500" height="150"> <img src="https://github.com/KhangToof/Marketing_DWH/assets/93634247/5548f753-18f2-4c61-9cc2-4f3d9644fdcb" width="450" height="150">

## 6. Dashboard with Power BI
![Screenshot 2024-06-22 195805](https://github.com/KhangToof/Marketing_DWH/assets/93634247/a24ab8f1-012b-49a3-b913-312a83a38c41)





**If you have any questions about the assignment, please contact me via the following email:** 
💬︎ ntk29072003@gmail.com
