# Deploy-Azure-Data-Platform-End2End
transfere from an Azure SQL Database to an Azure SQL Data Warehouse database using Azure Data Factory
Use Power BI to visualise collision data from Azure SQL Data Warehouse.

Pipline:
1 Build an Azure Data Factory Pipeline to copy data from an Azure SQL Database table

2	Use Azure Storage as a staging area for Polybase

3	Load data to an Azure SQL Data Warehouse table using Polybase

4	Visualize data from Azure SQL Data Warehouse using Power BI


** : With Virtual machine : install Azure data studio ( like SSMS) to create an empty table with the same columns like an original table in DBB

*new connection with server: mdwsqlvirtualserver-suffix.database.windows.net

And install Power BI 

** Create in azure storage : staging environment for Polybase before data can be copied to Azure SQL Data Warehouse.







