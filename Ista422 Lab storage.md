# ISTA 422 LAB: Azure storage accounts
## Exercise 1

### Task 1
   1. Login into your azure account
   1. on your dashboard scroll down and select more services
   1. select storage accounts from the list
   1. click the add button 
   1. create a uniqe name for your storage account
   1. select resource manager on deployment model
   1. under account kind select General purpose
   1. make sure that standard is selected on performance
   1. under the replication selection use the read-access geo-redundant storage
   1. make sure the both storage service encryption and secure transfer are disabled
   1. make sure you are using your subscription
   1. and under reasource group create new and input a name of your choosing
   1. select a location close to you
   1. click the pin to dashboard button
   1. click the create button  

   1. once the storage account has deployed from your dashboard select
      the newly created account
	  
### Task 2

   1. from the storage account blade select blobs
    in the new blade click the add contianer button on the top of the page
    create a name for the contianer and select blob from the access type dropdown
   1. select the newly created blob from the blob service blade
   1. click on the contianer properties button and note that container size, 
    block blobs and page blobs all read 0 B.
   1. close container properties
   1. select the upload button on the contianer blade
   1. select a file from you local machine and select upload.
    once your file has uploaded select container properties and note that the
    blob count has increased to 1 and it shows the size
   1. on the container page click delete container
   1. hit yes on the confirmation 
    
   1. under file services select the files button
   1. on the new blade click the file share button


