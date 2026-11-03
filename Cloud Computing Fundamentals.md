# TryHackMe - Cloud Computing Fundamentals

**Platform:** TryHackMe  
**Pathway:** Pre Security  
**Module:** Computer Fundamentals  
**Difficulty:** Beginner  
**Status:** Completed (100%)

---

## Overview

I completed the Cloud Computing Fundamentals room as part of the TryHackMe Pre Security pathway.

This room gave me a better understanding of what cloud computing is, how it works and why so many businesses rely on it today.

I learned about the different cloud deployment models, service models and the advantages of using cloud-based infrastructure instead of relying entirely on traditional physical servers.

I also explored some of the major cloud providers, including AWS, Microsoft Azure and Google Cloud, and looked at how companies use cloud services to support their applications and platforms.

One of the most interesting parts was the practical exercise, where I got to work with a simulated AWS environment. I created virtual machines, selected different instance types, managed running instances and checked how much the environment was costing.

---

## 1. Introduction to Cloud Computing

I started by learning what cloud computing actually means and why it has become such an important part of modern technology.

Before cloud computing became widely available, businesses generally had to purchase and maintain their own physical servers to host applications, store information and manage their IT infrastructure.

This could become expensive and difficult to manage, especially when a business started growing or needed to support users from different parts of the world.

Cloud computing helps solve these problems by allowing organisations to access computing resources over the internet instead of having to own all the physical hardware themselves.

I learned that cloud environments use technologies such as virtualisation and containers to make better use of physical resources. This allows multiple virtual environments and applications to operate on shared infrastructure.

### How Servers Evolved to Cloud

I also learned how server infrastructure has developed over time.

Originally, businesses relied on physical servers that they had to purchase, install, maintain and upgrade themselves.

Virtualisation then made it possible to run multiple virtual machines on a single physical server. This improved resource utilisation and reduced the need for additional hardware.

Cloud computing took this a step further by allowing businesses to access servers, storage and networking resources through the internet.

What I found interesting is how this has changed the way businesses manage their infrastructure. Instead of worrying about purchasing physical hardware every time they need more capacity, they can simply allocate additional cloud resources when required.

---

## 2. Cloud Benefits and Characteristics

Next, I looked at the main benefits of cloud computing and why organisations choose to use it.

### Scalability

One of the biggest advantages I learned about was scalability.

Cloud resources can be increased or decreased depending on how much computing power an application needs.

For example, if an online store experiences a sudden increase in visitors, it can allocate additional resources to handle the extra traffic. Once traffic returns to normal, those resources can be reduced.

This means businesses do not have to permanently pay for infrastructure they only occasionally need.

### On-Demand Self-Service

I learned that cloud platforms allow users to create, configure and remove resources whenever they need them.

Instead of waiting for physical hardware to be ordered and installed, businesses can deploy new virtual machines and other resources through a cloud management interface.

This makes managing infrastructure much quicker and more flexible.

### Pay Only for What You Use

Another important benefit is the pay-as-you-go pricing model.

Cloud providers generally charge customers based on the resources and services they consume.

This means businesses can avoid spending large amounts of money upfront on physical servers and only pay for the cloud resources they actually use.

I also learned why it is important to stop or remove resources that are no longer needed, as leaving unused resources running can lead to unnecessary costs.

### Security

I learned that cloud providers have security measures in place to protect their infrastructure and services.

These include physical security, access controls and different security technologies.

However, something important I took away from this section is that using a cloud provider does not mean security is entirely their responsibility.

Customers still need to secure their own applications, configurations and data, depending on the cloud service they are using.

### High Availability

Cloud environments can be designed to remain available even if individual components experience problems.

This helps businesses keep their applications and services running with minimal disruption.

I learned that this is particularly important for organisations that depend on their online services being available around the clock.

### Global Access

Another benefit is the ability to access cloud-hosted applications and services from different geographical locations.

This makes it easier for businesses to support customers and employees around the world without having to rely on one physical server in a single location.

---

## 3. Types of Cloud

In this section, I learned about the different cloud deployment types and service models.

### Cloud Deployment Types

**Public Cloud**

A public cloud is provided by a third-party company and its infrastructure is shared between multiple customers.

I learned that this is a popular option for businesses because it offers flexibility, scalability and reduced responsibility for maintaining physical infrastructure.

**Private Cloud**

A private cloud is dedicated to a single organisation.

It gives the organisation more control over its infrastructure and how it is configured.

This type of cloud is commonly used by organisations such as banks, healthcare providers and government institutions that have specific security or compliance requirements.

**Hybrid Cloud**

A hybrid cloud combines public and private cloud environments.

This allows businesses to keep sensitive information within private infrastructure while using public cloud resources when they need additional capacity.

For example, an online store could keep sensitive customer information in a private environment while using public cloud infrastructure to handle increased website traffic during busy periods.

I found this interesting because it shows how organisations can combine different cloud environments depending on their requirements.

### Cloud Service Models

I also learned about the three main cloud service models: IaaS, PaaS and SaaS.

**Infrastructure as a Service (IaaS)**

IaaS provides access to basic computing resources such as virtual machines, storage and networking.

The cloud provider manages the physical hardware, while the customer is responsible for managing the operating system, applications and configurations.

I understood this as essentially renting computing infrastructure from a cloud provider rather than purchasing and maintaining physical servers.

**Platform as a Service (PaaS)**

PaaS provides a managed platform for developing, deploying and running applications.

The provider manages the underlying infrastructure and operating system, allowing developers to focus mainly on building and maintaining their applications.

**Software as a Service (SaaS)**

SaaS provides complete software applications over the internet.

The provider manages the infrastructure, platform and application, while users simply access the software through a browser or application.

Examples include Gmail and Zoom.

The main difference I took away from this section is how much responsibility the customer has depending on which service model they choose.

---

## 4. Major Cloud Vendors

Next, I looked at some of the biggest companies providing cloud computing services.

The room introduced several major cloud providers:

- **Amazon Web Services (AWS):** One of the largest cloud providers, offering a wide range of computing, storage, networking and security services.
- **Microsoft Azure:** A major cloud platform with strong enterprise and hybrid cloud capabilities.
- **Google Cloud Platform (GCP):** Known for its data analytics, artificial intelligence and machine learning services.
- **Alibaba Cloud:** A major provider with a strong presence in Asia and services available internationally.
- **IBM Cloud:** Focuses on enterprise cloud solutions, hybrid environments and AI-driven services.
- **Oracle Cloud:** Provides cloud infrastructure with a particular focus on enterprise applications and database services.

I learned that AWS is one of the leading cloud providers because of its extensive infrastructure, global reach and wide range of available services.

This section helped me become more familiar with the companies I am likely to come across when learning about cloud infrastructure and cybersecurity.

---

## 5. How Companies Are Using the Cloud

This section gave me some examples of how well-known companies use cloud computing to support their platforms and services.

### Netflix

I learned that Netflix uses AWS infrastructure to support its streaming platform.

Cloud computing allows Netflix to support users around the world, handle large numbers of simultaneous connections and maintain reliable streaming during periods of high demand.

### Spotify

Spotify uses cloud infrastructure to support its music platform and millions of users.

Cloud resources help the service handle changes in demand as user activity increases and new content and features become available.

### Instagram

Instagram relies on cloud infrastructure to store and deliver large amounts of photos and videos.

This allows users to upload, view and share content from different geographical locations.

### Online Stores

Online retailers are another good example of how cloud computing is used in practice.

For example, during Black Friday, an online store might experience a massive increase in website traffic.

Instead of having to permanently purchase additional physical servers, the business can scale its cloud infrastructure to handle the increased demand.

What I took away from these examples is that cloud computing is not just something used by technology companies. It plays an important role in everyday services that millions of people use.

---

## 6. Practical Exercise - Deploying a Cloud Environment

After completing the theoretical sections, I moved on to the practical exercise.

The objective was to deploy a simulated cloud environment using an interface similar to the AWS platform.

The scenario involved creating a cloud environment to host a cybersecurity training application.

This gave me the opportunity to work with virtual machines and understand how they can be created, configured, managed and monitored through a cloud management interface.

### Basic Cloud Terminology

Before deploying the environment, I was introduced to two important AWS concepts.

**EC2 (Elastic Compute Cloud)**

EC2 represents a virtual computer or server running in the cloud.

Similar to a physical computer, an EC2 instance has computing resources such as a CPU and RAM and can run applications and services.

I understood that creating an EC2 instance is essentially adding another virtual computer to a cloud environment.

**Instance Type**

Instance types determine the amount of computing resources available to a virtual machine.

Some examples I learned about include:

- **t2:** General-purpose burstable instances.
- **t3:** General-purpose burstable instances.
- **m5:** General-purpose instances designed for a range of workloads.

Larger instances provide more computing power and memory but generally cost more to operate.

Smaller instances use fewer resources and are usually more affordable.

### Deploying the Cloud Environment

The practical exercise required me to create three virtual machines to support the cybersecurity training application.

This followed the Infrastructure as a Service (IaaS) model because I was working directly with virtual machines and their configurations.

The first step was selecting a cloud region.

A region represents the geographical location where cloud resources are hosted, such as Europe or North America.

After selecting the region, I moved to the Create Lab Machine section to configure the virtual machines.

### Creating the Application Interface Machine

The first virtual machine was created to host the application interface.

I used the following configuration:

- **Instance Name:** `application-interface`
- **Instance Type:** `t3.micro`
- **Status:** Running

This machine was intended to host the main application interface used by students.

### Creating the Study Machines

Next, I created two additional virtual machines that would be used as testing computers for students completing cybersecurity exercises.

Both machines were configured with the more powerful `m5.large` instance type.

**Machine 1:**

- **Instance Name:** `study-machine-1`
- **Instance Type:** `m5.large`
- **Status:** Running

**Machine 2:**

- **Instance Name:** `study-machine-2`
- **Instance Type:** `m5.large`
- **Status:** Running

After creating all three machines, I checked the Instances section to make sure the newly deployed machines were displayed.

At this point, my cloud environment consisted of one application interface machine and two study machines.

This practical exercise helped me understand how virtual machines are deployed and managed in a cloud environment.

---

## 7. Billing Analysis

After successfully creating all three virtual machines, I navigated to the Billing section to check how much the cloud environment was costing.

The billing section displayed the monthly cost associated with each instance, along with the total cost of the environment.

With all three instances running, the initial monthly cost was **$170 USD**.

**Initial Billing:**

<img width="1913" height="942" alt="estimate" src="https://github.com/user-attachments/assets/bb5a0255-250c-4ea5-b028-b6f3f179d244" />

At this stage, the application was still under development, meaning the two study machines were not actively being used.

I realised that keeping unnecessary machines running would increase the overall cost without providing any real benefit.

To avoid this, I returned to the Instances section and stopped both `study-machine-1` and `study-machine-2`, leaving the `application-interface` machine running.

After stopping both study machines, I returned to the Billing section to check the updated costs.

The monthly cost had decreased from **$170 USD to $30 USD**.

**Updated Billing:**

<img width="1902" height="993" alt="total" src="https://github.com/user-attachments/assets/e3b35c6c-fe6b-4ad1-ae34-4b2385f4578b" />

I found this particularly useful because it demonstrated how cloud computing allows resources to be managed depending on current requirements.

Rather than paying for machines that were not being used, I could simply stop them and reduce the overall cost.

This exercise reinforced the importance of monitoring cloud usage and managing resources properly.

It also showed me how small decisions, such as stopping unused virtual machines, can make a significant difference to cloud expenditure.

---

## 8. Key Takeaways

After completing this room, I have a much better understanding of cloud computing and how it fits into modern IT infrastructure.

The main things I learned were:

- What cloud computing is and how it differs from traditional physical server infrastructure.
- How virtualisation and containers help support cloud environments.
- The benefits of scalability, on-demand self-service and global accessibility.
- The differences between public, private and hybrid cloud environments.
- The differences between IaaS, PaaS and SaaS.
- The roles of major cloud providers such as AWS, Microsoft Azure and Google Cloud.
- How organisations use cloud infrastructure to support applications and services.
- What EC2 instances are and how instance types affect computing resources.
- How to create and manage virtual machines in a simulated cloud environment.
- Why it is important to stop unused instances to avoid unnecessary cloud costs.

I also gained a better understanding of how cloud infrastructure is managed in practice, rather than just learning the theory behind it.

These concepts will be useful as I continue learning about system administration, cloud security and modern IT infrastructure.

---

## 9. Conclusion

Overall, I found this room a useful introduction to cloud computing.

Before completing it, I had a general idea of what cloud computing was, but I now have a better understanding of how it works, the different service models and why businesses rely on cloud infrastructure.

The practical exercise was particularly helpful because it allowed me to put some of the concepts into practice.

I created three virtual machines in a simulated cloud environment, configured their instance types, managed their running states and reviewed the associated billing costs.

One of the biggest things I took away from the exercise was seeing how stopping two unused study machines reduced the monthly cost from $170 USD to $30 USD.

It demonstrated how flexible cloud infrastructure can be and why managing resources properly is important.

I feel that completing this room has given me a stronger foundation in cloud computing, which will be useful as I continue working through the TryHackMe Pre Security pathway and developing my knowledge of cybersecurity.

---

**Room Status:** Completed  
**Progress:** 100%
