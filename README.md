# Superstore


Context 


With growing demands and cut-throat competitions in the market, a Superstore Giant is seeking to understanding what works best for them. 
They would like to understand which products, regions, categories and customer segments they should target or avoid.

Go crazy with the dataset, but also make sure to provide some business insights to improve.

•	Building Facts and Dimensions 
•	Relationships 
•	Calculation Groups
•	Build data models
•	Aggregate table

I started from train.csv dataset 
With Power Query Editor I created the tables:

- FactSales;(applied steps:promoted headers;change data type;remove other columns,remove duplicates,change data type,add custom column, change data type)
- FactBuget;(applied steps: promoted headers,change data type,remove other columns,change data type, merge tables, Expanded DimCatSeg,add index column,rename,remove columns,create merged table,remove columns)
- FactAggSales;(applied steps: promoted headers,change data type, remove other columns,remove duplicates,change data type, add custom column, change data type, groupe rows)
- DimProduct;(applied steps: promoted headers, change data type, remove other columns,remove duplicates,sorted rows, add index,rename columns, merge tables, expanded DimCatSeg, rmeove columns)
- DimCustomer(applied steps: promoted headers, change data type, remove columns, remove duplicates, split column by delimiter,change data type, remane columns, remove columns)
- DimGeography;(apllied steps:promoted headers, change data type, remove columns, remove duplicates)
- DimDate;(chage data type)
- DimCatSeg;(applied steps: promoted headers, change type, remove columns, remove duplicate, sorted rows, add index, rename columns)

Manage relationships between tables;
Report:
Build visual:
I used Table for visualizations




