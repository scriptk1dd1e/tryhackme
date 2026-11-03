TryHackMe - Cloud Computing Fundamentals

Platform: TryHackMe
Pathway: Pre Security
Module: Computer Fundamentals
Difficulty: Beginner
Status: Completed (100%)

Overview

I completed the Cloud Computing Fundamentals room as part of the TryHackMe Pre Security pathway.

The room covers the fundamentals of cloud computing, including how cloud infrastructure works, the different cloud deployment and service models, and the benefits of using cloud-based resources.

The focus was on understanding how cloud computing has evolved from traditional physical servers, the advantages it provides to businesses, the major cloud service providers and how organisations use cloud infrastructure to support their applications.

The room also included practical exercises involving the deployment of virtual machines in a simulated cloud environment, configuring instance types, managing running instances and reviewing billing costs.

1. Introduction to Cloud Computing

The first section introduced cloud computing and explained how it helps overcome the limitations of running applications on a single physical computer.

Traditional setups can experience problems when applications need to support users across different geographical locations, handle increased traffic or remain available continuously.

Cloud computing addresses these challenges by providing computing resources over the internet.

Instead of hosting an application on a single physical computer, businesses can use cloud infrastructure to access servers, storage and networking resources whenever required.

The cloud is built on technologies such as virtualisation and containers, which allow multiple applications and environments to operate efficiently on shared infrastructure.

How Servers Evolved to Cloud

The room explained how server infrastructure has evolved over time.

Businesses originally relied on physical servers, which required organisations to purchase, maintain and manage their own hardware.

As technology developed, virtualisation allowed multiple virtual machines to operate on a single physical server, improving resource utilisation and reducing hardware requirements.

Cloud computing took this further by allowing organisations to access computing resources over the internet without having to own and maintain the underlying physical infrastructure.

This evolution has made it easier for businesses to deploy applications, increase capacity and manage resources as their requirements change.

2. Cloud Benefits and Characteristics

The next section covered the main benefits and characteristics of cloud computing and why it has become widely used by businesses.

Scalability

Cloud environments allow computing resources to scale up or down depending on application requirements.

For example, an online application experiencing increased traffic can allocate additional resources to handle the demand.

When traffic decreases, those resources can be reduced again.

On-Demand Self-Service

Cloud platforms allow users to create, configure and remove resources whenever needed.

This means businesses do not have to wait for physical hardware to be purchased and installed before expanding their infrastructure.

Pay Only for What You Use

Cloud providers generally charge customers based on the resources and services they consume.

This reduces the need for large upfront investments in physical infrastructure.

Businesses can also reduce costs by stopping resources that are no longer required.

Security

Cloud providers implement security measures to protect their infrastructure and services.

These include physical security, access controls and various security technologies.

However, customers are still responsible for securing the resources and applications they deploy, depending on the cloud service model.

High Availability

Cloud environments can be designed to remain operational even when individual components experience failures.

This helps businesses maintain access to applications and services.

Global Access

Cloud infrastructure allows applications and services to be accessed by users from different geographical locations.

This makes it easier for businesses to support international users without relying on a single local server.

3. Types of Cloud

The next section covered the different cloud deployment types and service models.

Cloud Deployment Types

Public Cloud

Public cloud infrastructure is provided by third-party cloud providers and shared between multiple customers.

It is commonly used by startups, websites and businesses because it offers flexibility, scalability and reduced infrastructure management.

Private Cloud

A private cloud is dedicated to a single organisation.

It provides greater control and customisation over the infrastructure and is commonly used by organisations such as banks, healthcare providers and government institutions that have specific security or compliance requirements.

Hybrid Cloud

A hybrid cloud combines public and private cloud environments.

This allows organisations to keep sensitive information within private infrastructure while using public cloud resources for additional capacity and scalability.

For example, an e-commerce business could keep sensitive data in a private environment while using public cloud infrastructure to handle increased traffic during busy periods.

Cloud Service Models

The room also introduced three main cloud service models.

Infrastructure as a Service (IaaS)

IaaS provides access to basic computing resources such as virtual machines, storage and networking.

The cloud provider manages the physical hardware, while the customer is responsible for managing the operating system, applications and configurations.

Platform as a Service (PaaS)

PaaS provides a managed platform for developing, deploying and running applications.

The provider manages the underlying infrastructure and operating system, allowing developers to focus primarily on building and maintaining their applications.

Software as a Service (SaaS)

SaaS provides complete software applications over the internet.

The cloud provider manages the infrastructure, platform and application, while users simply access the software through a browser or application.

Examples include Gmail and Zoom.

4. Major Cloud Vendors

The next section introduced some of the major companies providing cloud computing services.

The room covered the following cloud providers:

Amazon Web Services (AWS): The industry-leading cloud platform, offering a wide range of computing, storage, networking and security services.
Microsoft Azure: A major cloud provider with strong enterprise and hybrid cloud capabilities.
Google Cloud Platform (GCP): Known for its data analytics, artificial intelligence and machine learning services.
Alibaba Cloud: A major cloud provider with a strong presence in Asia and services available internationally.
IBM Cloud: Focuses on enterprise cloud solutions, hybrid environments and AI-driven services.
Oracle Cloud: Provides cloud infrastructure with a particular focus on enterprise applications and database services.

The room highlighted AWS as the industry leader due to its extensive infrastructure, global reach and wide range of available services.

5. How Companies Are Using the Cloud

The room provided examples of how major companies use cloud computing to support their platforms and services.

Netflix

Netflix uses AWS infrastructure to support its streaming platform.

Cloud computing allows the service to scale globally, handle large numbers of simultaneous users and maintain reliable streaming during periods of high demand.

Spotify

Spotify uses cloud infrastructure to manage its music platform and support millions of users.

Cloud resources allow the service to scale when new music, features or increased user activity generate additional demand.

Instagram

Instagram relies on cloud infrastructure to store and deliver large amounts of photos and videos.

This allows content to be accessed quickly by users across different geographical locations.

Online Stores

Online retailers use cloud computing to handle sudden increases in website traffic.

For example, during Black Friday, an online store can scale its infrastructure to support additional customers without having to permanently purchase extra physical servers.

These examples demonstrate how cloud computing helps organisations improve scalability, reduce infrastructure costs and maintain reliable services.

6. Practical Exercise - Deploying a Cloud Environment

After completing the theoretical sections, I moved on to the practical exercise.

The objective was to deploy a simulated cloud environment using an interface similar to the AWS platform.

The scenario involved creating a cloud environment to host a cybersecurity training application.

The exercise demonstrated how virtual machines can be created, configured, managed and monitored through a cloud management interface.

Basic Cloud Terminology

Before deploying the environment, the room introduced two important AWS concepts.

EC2 (Elastic Compute Cloud)

EC2 represents a virtual computer or server running in the cloud.

Similar to a physical computer, an EC2 instance has computing resources such as a CPU and RAM and can run applications and services.

Creating an EC2 instance is essentially adding another virtual computer to the cloud environment.

Instance Type

Instance types determine the amount of computing resources available to a virtual machine.

Examples include:

t2: General-purpose burstable instances.
t3: General-purpose burstable instances.
m5: General-purpose instances designed for a range of workloads.

Larger instances provide more computing power and memory but generally cost more to operate.

Smaller instances use fewer resources and are usually more affordable.

Deploying the Cloud Environment

The exercise required creating three virtual machines to support the cybersecurity training application.

This followed the Infrastructure as a Service (IaaS) model because the environment provided direct access to virtual machines and their operating systems.

The first step was selecting a cloud region.

A region represents the geographical location where cloud resources are hosted, such as Europe or North America.

After selecting the region, I moved to the Create Lab Machine section to configure the virtual machines.

Creating the Application Interface Machine

The first virtual machine was created to host the application interface.

The following configuration was used:

Instance Name: application-interface
Instance Type: t3.micro
Status: Running

This machine was intended to host the main application interface used by students.

Creating the Study Machines

Next, I created two additional virtual machines that would be used as testing computers for students completing cybersecurity exercises.

Both machines were configured with the more powerful m5.large instance type.

Machine 1:

Instance Name: study-machine-1
Instance Type: m5.large
Status: Running

Machine 2:

Instance Name: study-machine-2
Instance Type: m5.large
Status: Running

After creating all three machines, the Instances section displayed the newly deployed cloud environment.

The setup consisted of one application interface machine and two study machines.

7. Billing Analysis

After successfully creating all three virtual machines, I navigated to the Billing section to review the cost of the cloud environment.

The billing section displayed the monthly cost associated with each instance, along with the total cost of the environment.

With all three instances running, the initial monthly cost was $170 USD.

Initial Billing:

<img width="1913" height="942" alt="estimate" src="https://github.com/user-attachments/assets/35e73dd6-6dee-45a7-80fb-dc87bbf25d8f" />

At this stage, the application was still under development, meaning the two study machines were not actively being used.

To avoid unnecessary costs, I returned to the Instances section and stopped both study-machine-1 and study-machine-2, leaving the application-interface machine running.

After stopping both study machines, I returned to the Billing section to review the updated costs.

The monthly cost had decreased from $170 USD to $30 USD.

Updated Billing:

<img width="1902" height="993" alt="total" src="https://github.com/user-attachments/assets/8318251a-bd71-4949-85be-56267278c31d" />

This exercise demonstrated one of the key benefits of cloud computing: resources can be started and stopped whenever required, allowing businesses to reduce costs by avoiding charges for unnecessary running resources.

It also reinforced the importance of monitoring cloud usage and managing resources efficiently to prevent unnecessary expenditure.

8. Key Takeaways

This room covered several important areas of cloud computing and how it is used in modern IT environments.

The main points covered were:

What cloud computing is and how it differs from traditional physical server infrastructure.
How virtualisation and containers support cloud environments.
The benefits of scalability, on-demand self-service and global accessibility.
The differences between public, private and hybrid cloud environments.
The differences between IaaS, PaaS and SaaS.
The roles of major cloud providers such as AWS, Microsoft Azure and Google Cloud.
How organisations use cloud infrastructure to support applications and services.
The purpose of EC2 instances and instance types.
How to create and manage virtual machines in a simulated cloud environment.
How stopping unused instances can significantly reduce cloud costs.

These concepts are particularly relevant to understanding modern infrastructure, cloud security, system administration and the technologies used to deploy and maintain applications.

9. Conclusion

This room provided a useful introduction to cloud computing and its importance in modern IT environments.

The theoretical sections covered the different cloud deployment and service models, the benefits of cloud infrastructure and how major organisations use cloud services to support their applications.

The practical exercise reinforced these concepts by allowing me to deploy three virtual machines in a simulated cloud environment, configure their instance types and review the associated billing costs.

One of the most useful parts of the exercise was seeing how stopping two unused study machines reduced the monthly cost from $170 USD to $30 USD.

This demonstrated how flexible cloud infrastructure can be and why resource management is important when working with cloud environments.

Having a solid understanding of cloud computing provides useful context as I continue working through the TryHackMe Pre Security pathway and developing my cybersecurity knowledge.

Room Status: Completed
Progress: 100%
