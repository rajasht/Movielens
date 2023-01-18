Movielens Dataset Analysis:
--------------------------------------

Movielens is a movie recemondation web portal which collects the reviews, ratings, tags etc of various movies and use them to recommend a movie to a user next to watch. It also works on user's previous watch history to recommend the next same genere movie.

The "ml-latest-small" directory contains the dataset files on which we do our analysis and visualisation.

The "Codes" folder contains the "Authorization.ipynb" and "Algorithm.ipynb" files by which we will do the dataset authorization and Analysis Respectively.

---------------------------------------

The Movielens dataset Analysis and visualisation consists of following steps:

1.  Subscription to an Azure Package
2.  Creation of a Resource Group
3.  Creation of Storage Accounts (blob and datalake) in the resource group
4.  Creation of container in Storage Accounts
5.  Uploading the movilens dataset files into the blobcontainer of blob type Storage Account
6.  Creation of Azure Data factory in the resource group
7.  Creation of Copy Pipeline, setting up source and sink, linked services etc. in ADF
8.  Validating the pipeline, Debugging the pipeline, triggering the pipeline and Publishing the Pipeline
9.  Creation of Databricks workspace
10. Creation of cluster into databricks
11. Creating the Notebook
12. Importing the notebook codes
13. Connecting the datalake code with azure databricks file system
14. Creation of Tables from the uploaded dataset
15. Using Algorithm code analysing and visualising the movielens dataset

-----------------------------------------------------------------------------------------------------

Getting Free Trial Package Subscription:

Open Azure Portal:
Click on "Start" of Start with an Azure free trial Account
Click on Start Free
Check the two check boxes and Click on Next
Fill the details and Continue the Verification by Card Process.
It will take a charge of 2 Rupees and an OTP verification of the no. linked with card.AN AMOUNT OF 14500 will be allotted to you for the use for 30 Days.

-------------------------------------------------------------------------------------------------------

CREATION OF RESOURCE GROUP:

-->> Click on the resource group icon:
-->> Click on Create (+) icon
-->> give a name to the resource group. and choose the Region as Central India, then click Review
-->> click Review+Create
-->> The Resource Group is Created Now, Click on blue link of resource group to go into it.
-->> Inside View of Resource Group. ( we can create our required resources here for a specific operation.)

--------------------------------------------------------------------------------------------------------

CREATION OF STORAGE ACCOUNT:

-->> Go to Main Dashboard of your Azure Portal, and click on Storage Account Logo
-->> Click on Create (+) Logo
-->> Fill all the details required
-->> In "Advanced" check the Box of "Enable hierarchical namespace" , then click on Review+Create
-->> It will take some time in creation of Storage Account
--->>> Now we will have an storage account as a resource in our resource group which can be seen by going into the resource group
-->> To Go inside the newly created Storage Account click on the blue link of "samovielens"

------------------------------------------------------------------------------------------------------------

CREATION OF CONTAINER:

-->> Go inside the Storage Account
-->> Click on "Container" inside of "Data Storage" Segment
--->> Click On ( + Container ) symbol, A new side window will appear.
-->> Give the name of your container and click on "Create".
-->> To go inside it click on the name of container

--------------------------------------------------------------------------------------------------------------

Uploading the "ml-latest-small"'s various files into Container

-->> Go inside the container
-->> Click on the Upload
-->> click on the browse folders icon
-->> select the file/s that need to be uploaded.
-->> Click ok.

--------------------------------------------------------------------------------------------------------------