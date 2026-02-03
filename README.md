# Azure-blob-storage-project

A project demonstrating the use and functionality of azure blob storage service

**Project Overview**

This project has been formulaited to demonstrate the use of azure blob storage and potentially other azure storage services in a real world business context. I have chosen to carry on a previous conecpt idea of a Computer marketplace. 

This project includes demonstrations of:

Production of a storage account

Creation of blob storage containers

The enabling of static website intergation into azure blob service(static website paired with storage)

<img width="1919" height="995" alt="image" src="https://github.com/user-attachments/assets/c770bb14-5c88-4dd2-bdbe-5e02ffc684da" />

*Screenshot of the Static Website being enabled(Index.html in azure blob storage*

<img width="1919" height="1079" alt="image" src="https://github.com/user-attachments/assets/711d93e2-5872-469a-914e-81f9733f6ce5" />

*Screenshot of the Uploading of Text and image files to be used on the static website*

This could be useful within this sort of business because it means that the company can keep a log of the devices sold within a given period.

**Architecture/Design decisions**

Due to the nature of the concept either azure tables services or azure blob storage would be the correct services to use. In some cases it could be ideal to use both blob(for web images and text defintions) and azure table(as an archive) services but, in this case I will only be demonstrating blob to avoid confusion and complexity.
Local Redundant Storage was chosen to minimise the cost of the project as a whole. 

**What I learnt**

I learnt how to create a storage account and provide storage solutions for clients.

<img width="1913" height="1011" alt="image" src="https://github.com/user-attachments/assets/dd4d8073-04d7-4adf-9e76-2f6a3aa7e174" />

*Screenshot of storage account being created*

The ideal scenarios in which Azure blob should be used(when nonstructured images and text are involved) and azure tables(for unstructure non sql data essentially allowing you to filter to bigger groups of data together ideal for big archives)

<img width="1915" height="963" alt="image" src="https://github.com/user-attachments/assets/2de6cb1c-5088-47d3-8dcc-0e0a18c775ed" />

*Screenshot of blob storage container being created*

How to manage cloud costs effectively

I also learnt how to include lifecycle managment rules which allow me to auotmate the movement of data to cool or achrive storage(essentially telling azure that this data will not be needed for a prelonged period of time)

<img width="1919" height="845" alt="image" src="https://github.com/user-attachments/assets/d2fc4e36-64c9-4561-9f99-83423cf16572" />

*Screenshot of Lifecycle Management rule being created*

**Cleanup and Cost Management**

After the project was completed I deleted the resources used in this demonstration, this was to avoid any unecessary costs within my subscription and to remain organised.

To progress with this project I would now form a Azure table service to act as an archive of all the computers sold
*For More Screenshots and further information please see the following Document*
[Storage account and .odt](https://github.com/user-attachments/files/25057869/Storage.account.and.odt)
