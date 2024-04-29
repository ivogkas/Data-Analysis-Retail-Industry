# Data-Analysis-Retail-Industry

Team project for the course «Business Analytics & Personalization Technologies» (2022). The aim of this project was to analyze data to uncover insights that could assist small retail businesses in discovering unspoiled opportunities. For the purpose of the project we were provided
with two datasets from Intale. Intale is a comapany which offers data management applications to small retail businesses in Greece. 

## Datasets
1. The first one dataset included information about specific transactions (when the transaction occurred, at which store, what product was purchased, the quantity and the revenue).
   
   Columns: StoreId,	DateTime,	InvoiceId,	InvoiceGlobalId,	CategoryId,	Quantity,	Revenue

3. The second one dataset included information about monthly revenues for each store by specific products.

   Columns: Period,	Date_Year,	Date_MonthName,	StoreId,	CategoryId,	Quantity,	Revenue


We also had access to data regarding the geographic location and type (kiosk or mini-market) of each store, as well as the names of the categories for every CategoryId.


## Data Analysis
For the analysis, clustering algorithms (Kmodes, Kmeans and KPrototypes) was conducted on both datasets with the aim of uncovering insights among the clusters (store segments). For more details, please refer to the PDF file.

For data preprocessing, analysis, and visualization, the following tools were utilized: Python, RapidMiner and Excel.
