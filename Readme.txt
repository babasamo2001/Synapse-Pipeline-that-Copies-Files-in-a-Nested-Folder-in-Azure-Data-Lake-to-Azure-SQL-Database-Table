
 
  Project Title: Synapse ETL Pipeline that Copies All Files in Nested Folder in Azure Data Lake to Azure SQL Database Table

A.  Source Folder Details:
	 Root Folder: 1
	 Nested Folder: 2
	 Each Nested Folder Files: 2
	 File format: CSV


B.  Target Location: Azure SQL database table
	

C.  Business requirments:
    Client (user) needed to copy All Files in Nested Folder in Azure Data Lake to Azure SQL Database Table
	

D.  Solution Steps: 
   	 -create RBAC role assignment for the storage account container 
   	 -create link service, datasets, ETL pipeline and activities
   	 -Copy files from the nested folder to the Azure SQL database table
   	 -check the Azure SQL database table for the copied data to confirm the pipeline runs successfully


E.  Azure Services used: 
   	 -Azure Data Lake
   	 -Azure Data Factory
   	 -Azure SQL Database
