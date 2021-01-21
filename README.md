# My Introduction to Cloud Computing 
Just teaching myself cloud computing

## Cloud Computing Basics
- Definition: model for enabling convenient,on-demand network access to a shared pool of configurable computing resourcesthat can be rapidly provisioned and released with minimal management effort or service provider interaction. 

- Cloud model: 5 essential characteristics, 3 deployment models and 3 service models.
- 5 Characteristics: 
   - On demand self service 
   - Broad network access (through standard mechanisms)
   - Resource pooling (gives economies of scale making cloud cost-efficient). Dynamically assign resources based on demand.
   - Rapid elasticity: access resources when you need them and kepp them away when you do not.
   - Measued service: if you are not using, you are not paying.
   
- 3 Deployment Models:
  - Public: leverage cloud services over the internet over hardware owned by the provider but usage is shared by others. 
  - Private: infrastructure is for exclusive use by a single organization. Options are run-on-premises or provisioned by a service provider.
  - Hybrid: mix of public and private.
  
- 3 Service Models (based on layers in a computing stack):
  - Infrastructure as a Service (Iaas): access to infrastructure and physical resources such as servers, networking, storage and data centers w/o needing to manage or operate them.
  - Platfrom as a Service (Paas): access to infrastructure and physical hard/soft ware tools needed to deploy applications to users over the internet. 
  - Software App as a Service (SaaS): software licensing and delivery model in which software and apps are centrally hosted and licensed on a subscription basis ("on-demand software")
  
## Emerging Technologies Accelerated by Cloud
These include new era technologies that are disrupting business models and industries while creating unprecendented opportunities for businesses to stand out and create value. 
Some of these technologies include:
- Internet of Things: IoT is a giant network of connected of things and people. Smart devices/sensors are continously tracking and collecting data putting a strain on the identity. The IoT user cna be connected to the cloud for purposes such as device registratio, identity, data storage or enterprise data access. The cloud can store and process IoT data from the devoces servign as a collection point and minimizing latency while providing feedack to the connected devices. Special service can be designed to speed up, support or enable the development of IoT solutions. 
- Artificial Intelligence: AI consime the IoT data and then can predict trends/behaviors for the IoT devices. It powers the insights from the data delivered by IoT devices to provide value for clients and users. Both technologies leverage the cloud's scalability and processing power to deliver value. 
- Blockchain: This refers to a secureimmutable network that allows members to view only thetransactions that are relevant to them. It is a secure, distributed, open technology that can help speed up processes, lower costs and build transparency and traceability in transactional applications. Businesses need to be able to move applications and data across multiple clouds easily and securely. FOr this purpose, blockchain is the technology that provides the trusted, decentralized surce of truth. 

## Cloud Service Models 
- Infrastructure-as-a-service (IaaS): 
Physical data centers which end users do not interact directly with but experience. 
Compute-memory-storage that comes with supporting services liokeauto scaling and load balancing that provide scalability and high performance. 
Networking resources are provided to consumers of the cloud through virtualization or programmatically through APIs
Storage for dtata is of 3 types - object (highly distributive and resilient), file and block.  

- Platform-as-a-Service (PaaS):
Users are only responsible for application code and upgrade while cloud providers are responsible for installation, configuration, operation of application infrastructure. Distinguished by the high level of abstraction they provide including support services and APIs (for distributed caching, queueing, analytics, etc.). They also provie rapid deployment mechanisms and middleware capabilities (dbms, back-end services, rule engines, etc.). Some use cases are APL development and management, IoT, Business analytics/intelligence, business pricess management and Master Data Management.

-------
-------

## Cloud Security 
Cloud security is a shared responsibility between users and cloud providers.This responsibility dependes on which cloud service model (IaaS, PaaS or SaaS) you has a user has chosen. Cloud security can be categorized into 2 based on three stages (User, Application and Data). These are:
   - Data architecture security. Inlcudes data-at-rest encryption, data-in-motion encryption, data-in-memory/use protection and key management (for confidential and/or sensitive data).
   - Scanning for vulnerabilities in application at container level and application level.  
   - In the user section, identity needs to be verified and network access should be monitored by issuing authorization. 

Overall, cloud security comprises of the 2 categories: data protection and access management. 
