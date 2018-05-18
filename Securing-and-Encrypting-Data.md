
One of the keys to data protection in the cloud is accounting for the possible states in which your data may occur, and what controls are available for that state.  


 


For the purpose of Azure data security and encryption, the following guidance will illustrate the information you need around the following data’s states: 
 

Data Encryption-At-rest: This includes all information storage objects, containers, and types that exist statically on physical media, be it magnetic or optical disk. 


Data Encryption-In-Transit: When data is being transferred between components, locations or programs, such as over the network, across a service bus (from on-premises to cloud and vice-versa, including hybrid connections such as ExpressRoute), or during an input/output process, it is thought of as being in-motion. 



 


 


Guidance 

Enable and enforce Multi-Factor Authentication (MFA) as a second layer of security to user sign-ins and transactions. This will help safeguard access to data and applications while meeting user demand for a simple sign-in process. 


Enable and enforce Azure Role-Based Access Controls to ensure that you grant only the amount of access that users need to perform their jobs 


Encrypt your Azure Virtual Machines to help protect and safeguard your data to meet your organizational security and compliance requirements.  


Use secret keys to encrypt your data. Azure disk encryption uses Azure Key Vault to help you control and manage disk encryption keys and secrets in your key vault subscription, while ensuring that all data in the virtual machine disks are encrypted at rest in your Azure storage. 


Use a Privileged Access Workstations (PAW) to reduce risk of data loss or any attacks to workstations for your lines of businesses and more specifically its end users. 


If you are using SQL databases, ensure you enable SQL Data Encryption 


Protect your data in transit by isolating the entire communication channel between your on-premises and cloud infrastructure by using a virtual private network (VPN) such as Site-to-Site VPN 


Enforce file level data encryption using Azure Rights Managements (RMS) to help secure your files and email themselves as an added layer of security. 



 


Next Steps 


Operationalizing Security 