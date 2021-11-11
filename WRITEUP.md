### Analyze of both options ( VM and AppService) for deploying the app

After the analyze of VM and App service, here some points:
- Azure VMs are more expensive to run in comparison to Azure App Service.
- Azure App Service have constraints in comparison to Azure VMs in terms of scalability. Hence, Azure VMs are preferred for apps, which have scope to expand for future.
- Both provide high availability.
- The development of app is much simpler and faster in Azure App Service and can use CI/CD using GitHub, Azure DevOps ...

I choose App Service for the deploying the app cause of the size of this app and thr workflow.

### Assess app changes that would change your decision

I would go for the VM solution if the app has a huge user, need to scalup with Load Balancers. The app has evolve, need more memory and CPU. If the programming languages on Azure App Service is not support. In that case, I will use Azure VM to create environment for the programming language.    
