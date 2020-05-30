# Databricks DataFrame write to Salesforce using BulkLoad
Salesforce Bulk load using Dataframe write using Scala
A Dataframe write into Salesforce using Bulk API with Spark Scala 
PROBLEM : --
Salesforce Bulk load using Dataframe write using Scala
A Dataframe write into Salesforce using Bulk API with Spark Scala 
PROBLEM : --
when you try to write more than 1 million  records into each salesforce using Dataframe write using springML object you will face an Login rate Exceed issue because salesforce default login per an hour is 3000 only and each partition of dataframe will take more than 100 connections, with in one or 2 object load you reach to max limit of 3000 connection, you job can not load all the records.

Solution is uing the bulk load API we can solve the this issue.
@All bulk load examples in the internet mentioned with java code and from java client application,here i am using bulk API in Big data with 
Saprk scala code.
