AWS – Concepts
1.	Introduction to Cloud Computing Concepts and AWS (Amazon Web Services):
2.	Introduction to EC2, EBS, EFS and Amazon FSX
3.	Introduction to IAM (Identity and Access management), Cloud Watch, AMI (Amazon Machine Image) 
4.	Elastic Load Balancer and Auto Scaling
5.	VPC (Virtual Private Cloud)
6.	S3 (Simple Storage Service)
7.	Database Services
8.	Cloud Formation and App Services
9.	AWS Lambda, Elastic Beanstalk, AWS Ops work and API (Application Programming Interface) Gateway
10.	SNS (Simple Notification Services)
11.	SQS (Simple Queue Services)
12.	SES (Amazon Simple Email Service)

1.	Cloud Computing
Cloud Computing is sharing a Hardware/Software resource virtually over a network.
Cloud Service Models: 
IaaS – Infrastructure as a Service  Ex: AWS, Rackspace, MS Azure
PasS – Platform as a Service           Ex: AWS Elastic Beanstalk, Heroku etc 
SaaS – Software as a Service           Ex: Google drive, Google docs, MS Office 365 etc 
Cloud deployment Models: 
•	Public Cloud (AWS, MS Azure, Google platform, IBM blue mix etc)
•	Private Cloud (HPE, VM ware, Redhat Open stack, Dell EMC etc)
•	Hybrid Cloud 
Virtualization: 
Virtualization is a process of creating a virtual environment of something. It can be a Hardware or storage device or a network resources.
Advantages of Virtualization: 
•	It saves the space.
•	It saves the operating cost.
•	It enables the easy management of our data center.
Types of Virtualization: 
•	Hardware virtualization   AWS*
•	Application virtualization
•	Server virtualization
•	Network virtualization
•	Desktop virtualization
Hypervisor: 
Hypervisor is a hardware virtualization technique that allows to run multiple operating systems on a single host system at the same time. 
It is also called as virtual machine manager. 
Types of Hypervisor:
We have 2 types of Hypervisors.
Type-1  Bare metal/native hypervisor:  *AWS
It runs directly on the hardware, there is no operating system between hardware and hypervisor. So, it is more efficient due to direct access to the hardware, CPU, memory network and physical storage. However, we should have a dedicated machine to run the instructions.
 
•	Xen – Hypervisor (Type-1) software used by AWS for virtualization.
Type-2  Hosted hypervisor: 
It doesn’t run over the hardware directly, it runs over the application as it has an Operating System.
It is easy to set up.
It is useful for the engineers & Security analysis to check the malware and newly deployed applications. 
 
The below tables shows what are the services that are managed by the customer and the services managed by the CSP (Could Service Provider) in Onsite, IaaS, PaaS, SaaS.
In Onsite, customer has to manager everything as shown. But, in SaaS, CSP manages everything.


 
                                           * Customer manages                                                              * CSP manages 
1. IaaS (Infrastructure as a Service)
Description:
IaaS provides virtualized computing resources over the internet. It allows you to rent IT infrastructure like servers, storage, and networking on a pay-as-you-go basis. This means you don’t have to invest in physical hardware.
Examples:
•	Amazon EC2: You can launch virtual servers and scale them up or down as needed.
•	Google Compute Engine: Offers virtual machines and storage options for your applications.
2. PaaS (Platform as a Service)
Description:
PaaS provides a platform that allows developers to build, deploy, and manage applications without worrying about the underlying infrastructure. It includes tools, middleware, and database management services, making it easier for developers to focus on writing code.
Examples:
•	Google App Engine: A platform for building web applications without managing servers.
•	AWS Elastic Beanstalk: Lets you deploy and manage applications in various languages without worrying about the underlying hardware.
3. SaaS (Software as a Service)
Description:
SaaS delivers software applications over the internet on a subscription basis. Users access these applications through a web browser, eliminating the need to install or maintain software locally.
Examples:
•	Google Workspace (formerly G Suite): Provides applications like Google Docs, Sheets, and Gmail online.
•	Salesforce: A customer relationship management (CRM) tool that runs in the cloud.
4. Onsite Cloud Services (Private Cloud)
Description:

Onsite cloud services refer to private cloud environments hosted on your own premises. This setup allows you to have dedicated resources for your organization, giving you more control over security and compliance.
Examples:
•	OpenStack: An open-source software platform that allows you to create and manage your own private cloud.
•	VMware vSphere: A virtualization platform that enables you to create a private cloud using your own hardware.
Summary
•	IaaS: Rent virtual servers (e.g., EC2).
•	PaaS: Develop applications without managing servers (e.g., Google App Engine).
•	SaaS: Use software online (e.g., Google Workspace).
•	Onsite Cloud Services: Build a private cloud with dedicated resources (e.g., OpenStack).







