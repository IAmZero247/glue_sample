# Glue Crawler

1. Go to Glue Dashboard & Choose Region (N Virginia)

```
  Databases >>> my_first_glue_db >>> ADD Tables >>> [1. Add Table Using Crawler, 2. Add Table Manually] 
                                     **********
                                     
  Now     Add Table Using Crawler >>>  6 Step Process 
  
  Step1 :  Crawler Info
           Crawler Name -> s3-city-data
           
  Step2 :  Crawler Source Type 
           Data Stores 
           Crawl all folders
           
  Step3 :  Data Store
           DataStore - S3 
           Connection - optional 
           Crawl data in Include path- s3://zero-city-data
           Exclude patterns - optional 
           
  Step4 :  IAM Role
           MyNVirginiaGlueServiceRole
           
  Step5 :  Schedule 
           Run on Demand 
           
  Step6 :  Output
           Database - my_first_glue_db
           Prefix added to tables - optional 
           Grouping behaviour for s3 data - uncheck
           Configuration  options -
                                  *update table definition in the data catalog
                                  *mark the table as deprecated in the data catalog
  Step7 :  Review 
           Finish to Create 
```
2.  Run Crawler From Crawler Dashboard

3.  Go To The table created , Select one and Naviagate to athena    

4.  Run athena query (make sure you have configured output folder in s3 for athena) 



           
           
           
