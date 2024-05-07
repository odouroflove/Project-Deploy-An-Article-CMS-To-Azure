TruongTX14
* Table compare app service and virtual machine in azure

| Feature | App Service | Virtual Machine (VM) |
|---|---|---|
| Cost | Pay-per-use based on resource consumption, cost-effective for smaller projects | Fixed cost based on allocated resources, potentially higher for small projects |
| Scalability | Automatically scales up/down based on traffic | Manual scaling required, or use VM scale sets with added complexity |
| Availability | Built-in redundancy and disaster recovery for high availability | Requires configuring availability features like Azure Availability Zones |
| Workflow | Simplified configuration and built-in tools, easier to deploy and manage | Greater control over environment, but requires managing server software, runtime, and deployment |

* I choosing a web app service. 
Cost-wise, this project is small app and low traffic count so use app service would us saving cash. Regarding scalability, this project is small in scale so if traffic increases it will not be significant. Based on the costs, scalability, availability, and workflow analysis I chosed the web app service to deploy for my project article.

* Assess app changes that would change your decision:
I would choose virtual machine when security requirements is for specific compliance needs or highly sensitive data, VM can provide deeper control over security configurations. 