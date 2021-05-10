
# IAM Policy Setup 

1. GO to IAM dashboard
   
     -  Create Policy 
     
     ```
     Select Polices >>> Create Policy >>> JSON >>>  copy paste [IAM+Permission+Policy.txt] >>>MyNVirginiaGlueServiceRolePolicy >>> Create
     ```
   
     -  Create Role for AWS Service Glue 
     ```
     Select Role >>> Create Role >>> AWS service >>> Select glue >>> Permission  >>> [AWSGlueServiceRole,AmazonS3FullAccess] >>> MyNVirginiaGlueServiceRole >>> Create 
     ```
          
     - Take a note of ROLE ARN 
        
     ```
     arm:aws:iam::xxxxx:role/MyNVirginiaGlueServiceRole
     ```


