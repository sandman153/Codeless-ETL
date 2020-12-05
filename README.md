# Codeless-ETL
This demo is a brief introduction to Azure Data Factory and Mapping Data Flows. The intent of this demo is to show how codeless ETL works with Mapping dataflows  and how it enables development of complex code in a short amount of time.

The source data for this demo is the adventure works database and is available free from https://docs.microsoft.com/en-us/sql/samples/adventureworks-install-configure?view=sql-server-ver15&tabs=ssms

In this demo I will build pipelines using the AdventureWorks database and will be using two tables from that database.

## [Environment Setup: Deploy Codeless-ETL resources to your subscription](./Deploy/Deploy.md)


## 1. Simple Data Flow
For the first demo I will be coping data from a source table in the Adventure Works database to a target table in the Codeless-ETL database with no modifications

## 2. Insert Slowly changed records
In this section of the Demo I will create a more complex scenario where I build in an SCD scenario when loading data.

Import operation for AdventureWorksLT failed.
ErrorCode: BadRequest
ErrorMessage: The ImportExport operation with Request Id '2c8cec24-3f98-4ba6-84b1-c1605d9a7ca2' failed due to 'The Azure SQL Server firewall did not allow the operation to connect. To resolve this, please select the "Allow All Azure"checkbox in the Sql Server's configuration blade.'.