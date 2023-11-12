# Azure-Fundamental-AZ-900

It includes fundamental of cloud services provided with azure. It comprises of 3 main components:
1) Cloud concepts (25-30%)
2) Azure architect & services (35-40%)
3) Management & governance (30-35%)

Cloud : Renting computing resources on demand.
Computer Resources can be :
1) Servers
2) Storage
3) Databases
4) Msg Queues
5) CDN (content delivery network)
6) Batch processing jobs


### Public, private and hybrid clouds


### Pricing
```https://azure.microsoft.com/en-us/pricing/calculator/```
You can go to different category add services, add qty to it & can also save/share it 
![9-pricing](https://github.com/Gurudutt-Goswami/Azure-Fundamental-AZ-900/assets/86184439/6a3bb0e7-b6b0-4e9d-a2d5-bdc3597f7489)
![8-costing vm](https://github.com/Gurudutt-Goswami/Azure-Fundamental-AZ-900/assets/86184439/64bc7d9e-0d52-4695-9799-0235410f1b93)


### Benefits of cloud computing 
1) High availability : Make up/available both in planned(patches,updates,maintainance,migration,hardware replacement)/unplanned(hardware failure,network disruptions,power outages,natural distasters,cyber attacks) outages
2) Scalability : adding/removing resources as needed (helps to handle traffic without change in app/code)
   -- Vertical scaling (scaling up/down) adding more resource(memory or cpu) to a single server (limited)
   -- horizontal (scaling out/in) adding more server to a system (no limit thus need load balancers as well)
3) Elasticity: Quickly & Easily scaling & includes some sort of automation. Like if limits exceeds then only add resources to avoid waste.
4) Reliability: perform its intended function with interruption & with high accuracy.
5) Predictability: Ability to forecast & control performance, behavior & future cost of a system.
6) Security: Platform security, Microsoft security response center (MSRC), Role based access control (RBAC), azure active directory, ecryption, firewall
7) Governance: Process of defining, implementing & monitoring framework of policies that guides org cloud operations. (auditing & reporting)
  -- GDPR : General data protection regulation
	-- HIPAA: Health Insurance Portability and Accountability Act
	-- PCC: Pharmaceutical Compliance Congress
8) Manageability: Web portal, cli,Rest api, scripts , cloudshell


### Cloud Service Types
As a service: renting service not buying it just like a car
1) IAAS: Computing, storage, networking CSN Eg: Server or VM pay by second, choices to set cpu speed ram etc, Azure storage (like blob : binary large object & many other formats), virtual network
2) PAAS: Azure app services , Azure sql db, load balancer, firewall ,azure front door
3) SAAS: Cloud apps like office 365, one drive, skype its ready to use kind of thing 

#### Serverless
paying for service not renting hardware. The best example would be a simple sql db with 0 vcore where we are not paying for the hardware as it might be only queried only for sometime, function, container apps, kubernetes, cosmos db.


### Shared responsibility model 
#### On premise 
![3a-On premise responsibility](https://github.com/Gurudutt-Goswami/Azure-Fundamental-AZ-900/assets/86184439/e4a5c1d1-6f33-4186-b3c1-b912ca7a41fb)
#### Cloud VM
![4-cloud VM responsibilty](https://github.com/Gurudutt-Goswami/Azure-Fundamental-AZ-900/assets/86184439/2291e7b1-6c88-4e36-b696-30e33cd58a2f)
#### Cloud app service 
![5-cloud-app service responsibility](https://github.com/Gurudutt-Goswami/Azure-Fundamental-AZ-900/assets/86184439/c3f5fd2b-46a6-4cee-ac9a-ecb79cfd1a07)
#### SaaS responsibility
![6-SAAS responsibility](https://github.com/Gurudutt-Goswami/Azure-Fundamental-AZ-900/assets/86184439/fcf9ed60-6798-444c-bbd7-0d5bfe8e7bfa)
#### Shared Responsibilities
![7-shared responsibility](https://github.com/Gurudutt-Goswami/Azure-Fundamental-AZ-900/assets/86184439/6cf9b527-8dcd-41ed-b697-f68c1b3ab21b)



### Screenshot
#### HomePage
![1-HomePage](https://github.com/Gurudutt-Goswami/Azure-Fundamental-AZ-900/assets/86184439/496cc441-b28a-4bce-b157-aec3fa7e7768)
#### Services
![2-someservices](https://github.com/Gurudutt-Goswami/Azure-Fundamental-AZ-900/assets/86184439/bcd0a3b3-e345-4fb5-a741-6f17e8768a31)
#### Marketplace
Type 'marketplace' in search & you can see services offered by other companies.
![3-marketplace](https://github.com/Gurudutt-Goswami/Azure-Fundamental-AZ-900/assets/86184439/3c11f486-9d30-45e0-bce4-3987d0339613)
