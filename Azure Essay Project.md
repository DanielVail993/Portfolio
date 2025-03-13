# Project outline
## ![image](https://github.com/user-attachments/assets/c63db28e-4a42-41c3-95ef-bfb9bfdbeec0)

# My Project
## Data Laws and Regulations

First of all, when looking into analysing people’s data we must be very careful as to not cross any data laws and that we are absolutely clear to the customers what we are doing with their data. 

### GDPR and DPA
GDPR and the Data Protection Act exist in order to protect the personal information of individuals and must be followed else legal action could be taken again the business.

*	Customers must give the business clear consent to collect their personal data using a clear consent form and they must be able to take back that consent at any time.

*	Customers should be able to access and edit their data to correct any mistakes and ask for their data to be deleted at their will, as well as have the right to restrict their data from being processed.

*	Only the minimum amount of data should be collected and stored by the business. For example, if their only goal was to track sales of customers in different age groups, records of customer information like medical conditions, religious beliefs and race are irrelevant and should not be stored if there is no use for it.

*	If sensitive data like health or financial data on a customer must be stored, extra measures must be taken to ensure that data is secure. This should include being encrypted and being protected by anti-virus software and firewalls.

### Consumer Rights Act 2015
This is another important act that must be followed.

*	In this case the business must be transparent with their pricing, deliver on the products they promise and comply with return policies.

Personal data an employer can keep about an employee
https://www.gov.uk/personal-data-my-employer-can-keep-about-me 

Consumer Rights Act 2015
https://www.gov.uk/government/publications/consumer-rights-act-2015/consumer-rights-act-2015 

The UK's data protection legislation
https://www.gov.uk/data-protection 





## Azure Service Recommendations

### Data Storage and Analysis

#### Azure Blob Storage

*	Azure blob storage is amazing at storing large amount of unstructured data and is extremely flexible using pay-as-you-go

*	In this scenario I think this type of storage is unnecessary as the data bring stored is customer information and sales so they will fit nicely into a structured format. But depending on the sheer size of the data and if there are future plans to expand massively again this sort of solution may still be a good option

Azure Blob Storage Overview
https://azure.microsoft.com/en-us/products/storage/blobs/ 

#### Azure SQL Database

*	An Azure SQL Database seems like the obvious choice here for a number of reasons

*	The main reason is that the SQL database is ideal for structured data which customer information, sales and inventory all fit into nicely. This will make SQL queries easy, allowing for better access to and analysis of any sales trends, changing customer profiles, etc.

*	These databases also have integration with Azure Synapse Analytics (note: Azure Blob Storage also has this) Making it extremely easy to get analytics using this tool which will analyse sales trends, predict demand based on customer sales activity and find ways to optimize inventory. These are all very common use cases for analytic software so it will be very good at spotting common trends and no doubt get the analysis the business is looking for

Azure SQL Database Overview
https://azure.microsoft.com/en-us/products/azure-sql/database/ 
Azure Synapse Analytics Overview
https://azure.microsoft.com/en-us/products/synapse-analytics/ 

### Data Collection

#### Azure Data Factory

*	This feature of azure will make data collection and movement extremely easy 
