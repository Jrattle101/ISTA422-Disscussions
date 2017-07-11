# Load Balancers

   the Azure Load Balancer is used to provide a relatively    
   even distribution of network traffic across a set of    
   (often similarly configured or related) VMs. Using the    
   load balancer allows you to have multiple VMs work together  
   
   There are two types of load balancers available in Azure: an external    
   load balancer and an internal load balancer The external load balancer 
   is used for distributing traffic from the Internet across one or more VMs. 
   This enables you to expose your application in a highly scalable and highly 
   available manner.       
   
   The internal load balancer is used to distribute traffic from within a virtual 
   network across a set of VMs. For example, this could be traffic to a web API   
   or database cluster that should be available only to front-end web servers,    
   not to the public Internet.   
   
   It's important to understand the differences between the Azure classic and    
   Resource Manager deployment models. Azure Load Balancer is configured 
   differently in each model.   
      
   Virtual machines deployed within a cloud service boundary can be grouped    
   to use a load balancer. In this model a public IP address and a    
   Fully Qualified Domain Name, (FQDN) are assigned to a cloud service.    
   The load balancer does port translation and load balances the network    
   traffic by using the public IP address for the cloud service.   
   
   Load-balanced traffic is defined by endpoints. Port translation endpoints have    
   a one-to-one relationship between the public-assigned port of the public IP    
   address and the local port assigned to the service on a specific virtual machine.    
   Load balancing endpoints have a one-to-many relationship between the public IP    
   address and the local ports assigned to the services on the virtual machines in    
   the cloud service.   
   
## Azure Load Balancer

   Azure Load Balancer uses a hash-based distribution algorithm. By default,   
   it uses a 5-tuple hash composed of source IP, source port, destination IP,   
   destination port, and protocol type to map traffic to available servers. It   
   provides stickiness only within a transport session. Packets in the same TCP    
   or UDP session will be directed to the same instance behind the load-balanced    
   endpoint. When the client closes and reopens the connection or starts a new    
   session from the same source IP, the source port changes. This may cause the   
   traffic to go to a different endpoint in a different datacenter.

### References

   K. (n.d.). Azure Resource Manager support for Load Balancer.    
   Retrieved July 10, 2017, from https://docs.microsoft.com/en-us/azure/load-balancer/load-balancer-arm   

   Collier, M. S., & Shahan, R. E. (2015). Fundamentals of Azure: 
   Microsoft Azure essentials. Redmond, WA: Microsoft Press.





















