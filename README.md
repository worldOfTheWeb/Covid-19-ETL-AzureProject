# Covid-19-ETL-AzureProject

## Overview

The goal of this project is to build an ETL (Extract, Transform, Load) pipeline for processing and analyzing Covid-19 info data all over the world. The project involves loading data using API or from files, transforming the data using Python and Spark, and then loading the transformed data into a new database or generating reports.


## Project Goals

This project on Covid-19 reporting of all over the world data involved below :

#### Azure Data Factory :

    --> Building a solution architecture for a data engineering solution using Azure Data Engineering 
        technologies such as Azure Data Factory (ADF), Azure Data Lake Gen2, Azure Blob Storage, 
        Azure SQL Database, Azure Databricks, Azure HDInsight and Microsoft PowerBI.

    --> Branching and Chaining activities in Azure Data Factory (ADF) Pipelines using control flow 
        activities such as Get Metadata. If Condition, ForEach, Delete, Validation etc.

    --> Scheduling pipelines using triggers such as Event Trigger, Schedule Trigger and 
        Tumbling Window Trigger in Azure Data Factory (ADF)

    --> Creating Mapping Data Flows to create transformation logic. The course covers all of 
        the transformation steps such as Source, Filter, Select, Pivot, Lookup, Conditional 
        Split, Derived Column, Aggregate, Join and Sink transformation.

    --> Implementing Azure Data Factory pipelines to invoke Mapping Data Flows and 
        executing them.

    --> Creating ADF pipelines to execute HDInsight activities and carry out data 
        transformations.

    --> Creating ADF pipelines to execute Databricks Notebook activities to carry out 
        transformations.

    --> Creating dependency between pipelines to orchestrate the data flow

    --> Creating dependency between triggers to orchestrate the data flow

    --> Monitoring of Data Factory pipelines using Azure Monitor and 
        setting diagnostic setting to be forwarded to Azure Storage Account or Log 
        Analytics Workspace.

    --> Implementing the Azure Data Factory Analytics monitoring tool and how to extend 
        the capability further.


#### Azure Storage Solutions :

    --> Creating Azure Storage Account, Creating containers, Uploading data, Access Control 
       (IAM), Using Azure Storage explorer to interact with the storage account.

    --> Creating Azure Data Lake Gen2, Creating containers, Uploading data, Access Control 
        (IAM), Using Azure Storage explorer to interact with the storage account.

    --> Creating Azure SQL Database, Pricing Tiers, Creating Admin User, Creating Tables, 
        Loading Data and Querying the database.

#### Azure HDInsight & Databricks :

    --> Creating HDInsight Clusters, Interacting with the UI, Using Ambari, Creating Hive tables, 
        Invoking HDInsight activities from Azure Data Factory

    --> Creating Azure Databricks Workspace, Creating Databricks clusters, Mounting storage 
        accounts, Creating Databricks notebooks, performing transformations using Databricks 
        notebooks, Invoking Databricks notebooks from Azure Data Factory.

#### Azure Devops (CI/CD) :

    --> Creating Azure Devops Environment and configuring Azure Devops Git Repository.

    --> CI/ CD process for releasing Azure Data Factory artefacts to higher environments.

    --> Creating build and release pipelines in Azure Devops to release code to higher 
        environments (Test/ Prod).

    --> Configuring/ Parameterise CI/CD pipelines to release ADF pipelines that access 
        Azure Data Lake Storage. 
## Tech Stack

### **Azure Data Engineering Technologies:** 

Azure Data Factory (ADF), 

Azure Data Lake Gen2, 

Azure Blob Storage, 

Azure SQL Database, 

Azure Databricks, 

Azure HDInsight 

and Microsoft PowerBI.

 **Language:** Python

**Framework or Library:** Spark

**Database:** Azure SQL



## Architecture

![Architecture](https://github.com/worldOfTheWeb/Covid-19-ETL-AzureProject/blob/main/Architecture.png?raw=true)


## Copy Activity

![Copy Activity](https://github.com/worldOfTheWeb/Covid-19-ETL-AzureProject/blob/main/Copy_Activity.png?raw=true)


## Git Activity

![Git](https://github.com/worldOfTheWeb/Covid-19-ETL-AzureProject/blob/main/Git.png?raw=true)


## CI/CD Activity

![CI/CD](https://github.com/worldOfTheWeb/Covid-19-ETL-AzureProject/blob/main/CI-CD.png?raw=true)
