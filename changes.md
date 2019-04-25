# sentia
Sentia Assessment
13:00 - Wednesday April 17th, 2019. Started on project:  Created the following resoources in resource group: Acenet: 
An Azure Datalake Gen 2 storage account.
A key vault with a secret
A virtual network
A web app that can access both the datalake storage and the key vault secret
A load balancer that sits between the web app and the internet
Use tags to group the resources. 
Reagrding the keyvault, realized due to the updated Azure policies, export it in the template along with the other deployment information would not be possible right off the bat. 
Currently busy with working on creating and adding custom policy for keyvault access and also working on the load balancer with the address pool and the rules. 
