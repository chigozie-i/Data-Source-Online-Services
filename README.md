![Online Service](https://github.com/chigozie-i/Data-Source-Online-Services/blob/main/Connecting%20Online%20Services.png)

## Introduction:
In today’s data driven world, organizations rely heavily on insights derived from data to drive strategic decision-making and enhance operational efficiency. Microsoft Power BI stands as a powerful tool in this landscape, offering robust capabilities for connecting to various data sources, transforming raw data into meaningful insights, and creating interactive visualizations and reports.


## Overview:

This document focuses on utilizing Microsoft Power BI for data analysis, forming part of a series of documentation projects aimed at exploring various methods for connecting to your data source. This document seeks to underscore the critical significance of selecting an appropriate data source connection method and to offer comprehensive guidance on the diverse approaches available for establishing connectivity to your data source prior to initiating any essential data transformations tailored to your analytical objectives.

The primary goal of this endeavor is to establish a dependable repository for your data, fostering operational efficiency and ensuring the accuracy of reporting in alignment with the business requirements.

The method by which you establish connectivity to your data source holds considerable importance, as it directly influences the efficiency of your analytical tools and shapes the user experience. Moreover, it plays a pivotal role in determining the effectiveness, precision, and trustworthiness of the analytical processes and resulting reports.


## Data Sources:
Sometimes, you may be required to build Microsoft Power BI reports, with data sourced from various databases and files. These data sources vary, with some housed in Microsoft SQL Server and others in Microsoft Excel, yet they are all interconnected.

 ![Data Source](https://github.com/chigozie-i/Data-Source-Online-Services/blob/main/Data%20Sources.png)

Prior to report creation, it's essential to extract data from the various data sources. As the interaction with the sources differ, familiarizing yourself with the intricacies of the source platforms is imperative to report building within Power BI.
Data Sources:

1.	Files
2.	Relational Data Sources | Create Dynamic Reports with Parameters
3.	NoSQL Database 
4.	Online Services
5.	Azure Analysis Services


This documentation project focuses on Online Services as Data Source.

## Connecting To Online Services:
Organizations often utilize a variety of software applications like SharePoint, OneDrive, Dynamics 365, and Google Analytics to support their daily operations, each generating its own set of data. Power BI has the capability to amalgamate data from multiple applications, enabling the creation of more insightful reports.  
  
  
For instance, let's consider Imaginary Inc., which relies on SharePoint for collaboration and sales data storage. At the onset of the new fiscal year, the sales managers need to set new targets for the sales team. The necessary form for this task is housed within SharePoint. Your task is to establish a connection to this data within Power BI Desktop. This will allow the integration of sales goals with other pertinent sales data, facilitating the evaluation of the sales pipeline's health.  
  
To understand how we can achieve this, we will look through how to use the Power BI Desktop Get Data feature to connect to data sources that are produced by external applications. To illustrate this process, we've provided an example that shows how to connect to a SharePoint site and import data from an online list.

## Connecting to Data in An Application
When initiating a connection to data within an application, the process mirrors that of connecting to other data sources. This involves starting with the "Get data" feature in Power BI Desktop, followed by selecting the appropriate option from the Online Services category. In this specific scenario, you would opt for "SharePoint Online List."

![Get Data I](https://github.com/chigozie-i/Data-Source-Online-Services/blob/main/Get%20Data%20I.png)

![Get Data II](https://github.com/chigozie-i/Data-Source-Online-Services/blob/main/Get%20Data%20II.png)







## Reference:  
https://learn.microsoft.com  
https://docs.microsoft.com




## Help and Support

#### Did you find this document helpful? Leave a Star

[![GitHub stars](https://img.shields.io/github/stars/chigozie-i/Data-Source-Online-Services.svg?style=social)](https://github.com/chigozie-i/Data-Source-Online-Services/stargazers)

#### You may make a contribution to help us improve on our documentation by submitting a pull request.
