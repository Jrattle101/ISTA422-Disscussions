# AZURE STORAGE ACCOUNTS

   What is Azure storage? To put it simply it is the same as what is on any computer just in the cloud.   
   But, it is much more than that. It provides scalability and elasticity to storage solutions, allowing   
   the user the resources that they need and reduce costs. You can choose a wide range of data types for      
   your storage ranging from SQL to file shares. By being elastic, it can be used to design applications      
   that can scale to meet the requirements that it needs so you pay for what you need and it is cost    
   effective for small business.    
    
   Azure storage can be accessed for anywhere in the world changing the way applications are developed    
   no longer do they need to be developed on premises and launched from a server farm. Anyone from the    
   development team can accesses the storage from anywhere and make the necessary changes and by hosting    
   the app in the cloud it doesn�t require on site servers to run and maintain the app.     
   
   The first type of storage is blob storage, it is an unstructured storage object data, it can be  
   any type of data, text or binary. It is the junk drawer of storage if you need to put it somewhere    
   put it in a blob. Every blob is organized into a container they provide ways to assign security to the objects.   
   A storage account can contain any number of containers and a container can contain any number of blobs,    
   up to 500TB. There are three types of blobs, block blob, append blob, page blob.      
   
   Block blobs are best forcloud objects and are good for documents, media files and so forth.    
   Append blobs are like block blobs but are made for append operations, they can be updated only    
   by adding a new block to the end, they work well where you need to log any changes.    
   Page blobs are for representing IaaS (Information as a Service) disks   
   and may be up to 1TB in size.
      
   Table storage stores structured datasets. It is a NoSQL key-attribute data store making it a schemaless design,   
   so it is different than most traditional databases, which allows for the rapid development and fast access to    
   large quantities of data. It offers scalability with massive amounts of data. It can be used to store flexible    
   datasets and other data that the application needs to operate. It supports a subset of the OData protocol    
   simplifying querying capabilities.     
   
   Queue storage provides workflow processing and communication between cloud services components. It allows   
   communication across application components on the cloud, desktops, mobile device or servers.   
   
   File storage uses the standard SMB (Server Message Block) protocol for legacy applications.    
   With file storage applications running of a virtual machines or cloud services can mount a file share    
   in the cloud so that any number of components can access the file storage at the same time.     


## References 

   Brunetti, R. (2011). Windows Azure step by step. Sebastopol, CA: Published with the authorization of Microsoft Corp. by OReilly Media.   
   Https://docs.microsoft.com/en-us/azure/storage/storage-introduction. (n.d.). Retrieved from https://docs.microsoft.com/en-us/azure/storage/storage-introduction   
