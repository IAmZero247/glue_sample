
# Database 

Go to Glue Dashboard & Choose Region (N Virginia) 

 ```
   ADD Database >>> Database Name (my_first_glue_db) + Location (\samples\databases\) + Descripition( "First DB") >>> Create
   ************                                                                                                       ******
 ```
 
 # Tables
 
Go to Glue Dashboard & Choose Region (N Virginia)

```
  Databases >>> my_first_glue_db >>> ADD Tables >>> [1. Add Table Using Crawler, 2. Add Table Manually 
                                     **********
  Now     Add Table Manually >>>  5 Step Process 
  
  Step 1 :  Setup Table properties 
            table name -> MyCityData 
            db -> my_first_glue_db
            description -> "something"
  Step 2 :  Add datastore  
            specified path in my account 
            include path -> s3://zero-city-data
  Step 3 :  Choose a data format
            CSV
            Delimiter -> , 
  Step 4 :  Define Schema (Use Add Column Button)   
            Id -> INT
            County -> STRING
            State -> STRING
            City -> STRING
            Amount -> DECIMAL
  Step 5 :  Review And Finish        
       
        
```
