# myRepo
# Creating Pipelines
CICD with Azure devops

Steps to copy data from local computer to ADLS

1.	Create a storage account and resource group
2.	Create a container
3.	Upload the file and give the input folder name
4.	Create a data factory -> go to author and monitor
5.	On the data factory page -> select copy data
6.	Create a pipeline
7.	Create a connection(linked Service)-choose Azure Blob storage(Give Azure Subscription and storage account)
8.	Create source dataset
9.	Create another linked service for ADLS Gen2
10.	Create destination dataset using ADLS linked service
11.	Drag Copy data provide source and sink
12.	Publish and trigger now

