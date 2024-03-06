# Cloud Computing Basics

## What is Cloud Computing?
Cloud computing refers to the delivery of computing services (such as servers, storage, databases, networking, software, analytics, and intelligence) over the internet ("the cloud") to offer faster innovation, flexible resources, and economies of scale. <br>
This could be simplified to anything that involves delivering services over the internet as opposed to hardware or software installations on devices, it's somewhere else, on-demand and centrally managed.
![img.png](img.png)

## Quick History/Timeline of Cloud Computing:
Cloud computing emerged in the early 2000s when companies began offering virtualized infrastructure and storage services over the internet. Key milestones include the launch of Amazon Web Services (AWS) in 2006, followed by Google Cloud Platform (GCP) and Microsoft Azure in subsequent years.

## What Can You Do with Cloud Computing?
With cloud computing, individuals and businesses can:
- Store and access data from anywhere with an internet connection.
- Host websites and applications without the need for physical servers.
- Scale resources up or down based on demand.
- Run complex computations and analytics.
- Collaborate on projects in real-time.
- Implement disaster recovery and backup solutions.

## What are the 4 Types/Models of Cloud?
![image](https://github.com/Hussainajhar8/tech257_azure_linux/assets/110145960/f2369870-e3e4-4c95-af8f-8f59c83b56ac)

The four types/models of cloud are:
- **Public Cloud**: Cloud services offered by third-party providers over the internet, available to the general public. **Main difference**: Resources are shared among multiple users and accessible via the internet.
- **Private Cloud**: Cloud infrastructure operated solely for a single organization, either on-premises or by a third-party provider. **Main difference**: Offers dedicated resources and greater control over security and compliance.
- **Hybrid Cloud**: Combination of public and private cloud environments, allowing data and applications to be shared between them. **Main difference**: Provides flexibility to leverage the benefits of both public and private clouds while maintaining control over sensitive data.
- **Multi-Cloud**: Strategy of using multiple cloud providers to meet various business needs, reduce dependency on a single provider, and optimize performance and cost. **Main difference**: Involves distributing workloads across multiple cloud environments to avoid vendor lock-in and increase resilience.


## What are the Different Types of Cloud Service?
![image](https://github.com/Hussainajhar8/tech257_azure_linux/assets/110145960/96fcbefa-c63f-4917-916e-c31d18a3ee9f)

The main types of cloud services are:
- **Infrastructure as a Service (IaaS)**: Provides virtualized computing resources over the internet, including virtual machines, storage, and networking. **Main difference**: Offers more control over the infrastructure compared to other services.

- **Platform as a Service (PaaS)**: Offers a platform allowing developers to build, deploy, and manage applications without worrying about infrastructure details. **Main difference**: Focuses on application development and deployment, abstracting away underlying infrastructure concerns.

- **Software as a Service (SaaS)**: Delivers software applications over the internet on a subscription basis, eliminating the need for installation and maintenance. **Main difference**: Provides fully functional software applications accessible via the internet without the need for local installation.


## Advantages/Disadvantages of the Cloud? Specifically for a Business:
## Advantages of Cloud Computing:
- **Cost Savings**: Cloud computing eliminates the need for upfront investments in hardware and infrastructure, reducing capital expenditure.
- **Scalability**: Cloud resources can be scaled up or down quickly and easily to meet changing demand.
- **Flexibility**: Cloud services offer flexibility to access data and applications from anywhere with an internet connection.
- **Accessibility**: Cloud-based applications and data can be accessed from any device with an internet connection, enhancing accessibility and collaboration.

## Disadvantages of Cloud Computing:
- **Security Concerns**: Storing data and applications on third-party servers raises security and privacy concerns, including data breaches and regulatory compliance.
- **Dependence on Internet Connection**: Cloud services rely on internet connectivity, leading to potential downtime and disruptions if internet access is lost.
- **Potential Downtime**: Cloud service outages or maintenance can result in downtime, impacting business operations and productivity.


## What is OpEx vs CapEx?
OpEx (Operational Expenditure) refers to ongoing operational expenses incurred to run a business, while CapEx (Capital Expenditure) refers to one-time investments in physical assets.

## Marketshare - What is the Breakdown?
The cloud computing market is dominated by AWS, followed by Microsoft Azure and Google Cloud Platform (GCP).
![img_1.png](img_1.png)
## What are the 3 Largest Cloud Providers Known for?
- AWS: Vast array of services and global infrastructure.
- Azure: Integration with Microsoft products and services.
- GCP: Expertise in data analytics and machine learning.
  ![image](https://github.com/Hussainajhar8/tech257_azure_linux/assets/110145960/14a2662c-82b6-4e39-b6d9-0406fa346630)


## What are the 4 Pillars of DevOps? How do They Link into the Cloud?
![image](https://github.com/Hussainajhar8/tech257_azure_linux/assets/110145960/a0b8de37-e78d-4fc2-8ad6-349a9a7632e7)

The four pillars of DevOps:
### 1. Communication:
- **Description**: DevOps culture emphasizes collaboration, communication, and shared responsibility among development, operations, and other stakeholders.
- **Importance**: Encourages a cultural shift towards continuous improvement, innovation, and teamwork, fostering a conducive environment for DevOps practices.

### 2. Automation:
- **Description**: Automation involves automating repetitive tasks, processes, and workflows to streamline development, deployment, testing, and operations.
- **Importance**: Reduces manual errors, accelerates delivery, enhances consistency, and frees up human resources for more strategic tasks.

### 3. Monitoring:
- **Description**: Measurement involves collecting, analyzing, and interpreting data to monitor progress, identify bottlenecks, and make informed decisions.
- **Importance**: Provides visibility into the DevOps process, enables continuous feedback and improvement, and helps align efforts with business objectives.

### 4. Communication:
- **Description**: Sharing emphasizes knowledge sharing, collaboration, and transparency across teams, departments, and organizations.
- **Importance**: Facilitates cross-functional collaboration, fosters a culture of learning and innovation, and promotes the reuse of best practices and resources.

These four pillars form the foundation of DevOps practices, guiding organizations towards achieving agility, efficiency, and resilience in software delivery and operations.

## Case Studies Showing Businesses Migrating to or Using the Cloud:
- [Netflix](https://aws.amazon.com/solutions/case-studies/netflix/) - migrated its entire infrastructure to AWS, allowing it to scale globally and handle millions of streaming requests.
- [Airbnb](https://cloud.google.com/customers/airbnb) - leverages Google Cloud Platform to manage its massive data volumes, enabling personalized user experiences and efficient operations.
- [Slack](https://slack.engineering/rebuilding-slack-on-the-desktop-308d6fe94ae4) - moved its desktop application to AWS, resulting in improved performance, reliability, and scalability.

## How Does Cloud Computing Work as a Business Model?
Cloud computing operates on a pay-as-you-go model, where businesses only pay for the resources and services they use, allowing for cost-effective scalability and flexibility.

## What Sorts of Things Do You Usually Need to Pay for When Using the Cloud?
Businesses typically pay for:
- Virtual servers
- Storage space
- Data transfer
- Compute power
- Software licenses
- Support services

## Virtual Machine (VM)

A virtual machine (VM) is like a computer inside your computer. It's a software-based version of a physical computer that runs on your PC or server. Imagine having a computer within your computer that you can use to run different operating systems and software.

### What It Does:
- **Acts Like a Computer**: A VM behaves just like a real computer. It has its own operating system, applications, and settings, but it's all running on your actual computer.
- **Creates Virtual Environments**: With VMs, you can create multiple virtual environments on a single physical machine. Each VM is isolated from the others, so you can run different things without them interfering with each other.
- **Easy to Move Around**: You can easily move a VM from one computer to another. It's like moving a file from one folder to another, but instead, you're moving an entire computer!

### Why It's Useful:
- **Testing and Development**: VMs are great for testing new software or developing apps. You can try things out without worrying about messing up your main computer.
- **Saving Space and Money**: Instead of buying multiple physical computers for different tasks, you can run everything on one machine using VMs. It saves space and money!
- **Backup and Recovery**: VMs make it easy to backup and recover your computer. If something goes wrong, you can quickly restore your VM to a previous state.
- **Using VMs in the Cloud**: In the cloud, VMs are used to create virtual servers. Instead of running on your computer, these virtual servers run on powerful computers in data centres owned by cloud providers like Amazon Web Services (AWS), Microsoft Azure, or Google Cloud Platform (GCP). Using VMs in the cloud allows you to access computing resources on-demand, scale up or down as needed, and pay only for what you use.

### How It Works:
- **Hypervisor**: A hypervisor is like a manager for VMs. It's special software that creates and manages VMs on your computer. Think of it as the boss that oversees all the virtual computers.
- **Types of Hypervisors**: There are two main types of hypervisors: ones that run directly on the hardware (bare-metal) and ones that run on top of an operating system (hosted). Both do the same job but in slightly different ways.

### Advantages:
- **Flexibility**: VMs let you run different operating systems and software on the same computer or the cloud.
- **Saves Time and Money**: You can do more with less hardware, which saves you money and time.
- **Safe Environment**: VMs provide a safe environment for testing and experimenting without risking your main computer.

### Disadvantages:
- **Can Be Slow**: Running VMs can slow down your computer, especially if you're running several at once.
- **Learning Curve**: There's a bit of a learning curve to setting up and managing VMs, especially if you're new to it.
- **Not Always Perfect**: Sometimes VMs can have glitches or compatibility issues, but they're usually fixable with a bit of troubleshooting.

![image](https://github.com/Hussainajhar8/tech257_azure_linux/assets/110145960/0dd73915-bd25-4e9a-bf0c-4327096101a8)

