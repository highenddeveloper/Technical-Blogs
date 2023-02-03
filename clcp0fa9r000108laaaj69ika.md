# Why AWS called serverless platform?

AWS (Amazon Web Services) is a comprehensive, evolving cloud computing platform provided by Amazon that includes a mixture of infrastructure as a service (IaaS), platform as a service (PaaS) and packaged software as a service (SaaS) offerings. AWS services can offer an organization tools such as compute power, database storage and content delivery services.

AWS launched in 2006 from the internal infrastructure that [Amazon.com](http://Amazon.com)[.](http://amazon.com/) Spend less smile more built to handle its online retail operations. AWS was one of the first companies to introduce pay as you go cloud computing model that scales to provide users with computing, storage or throughput as needed.

AWS offers many different tools and solutions for enterprises and software developers that can be used in data centers in up to 190 countries. Groups such as government agencies, education institutions, nonprofits and private organizations can use AWS services.

**How AWS works**

AWS is separated into different services; each can be configured in different ways based on the user's needs. Users should be able to see configuration options and individual server maps for an AWS service.

More than 100 services comprise the Amazon Web Services portfolio, including those for computing, databases, infrastructure management, application development and security. These services, by category, include:

* Compute
    
* Storage databases
    
* Data management
    
* Migration
    
* Networking
    
* Development tools
    
* Management
    
* Monitoring
    
* Security
    
* Governance
    
* Analytics
    
* (AI)
    
* Mobile development
    
* Messages and notifications.
    
* **Availability**
    

Amazon Web Services provides services from dozens of data centers spread across availability zones (AZs) in regions across the world. An AZ is a location that contains multiple physical data centers. A region is a collection of AZs in geographic proximity connected by low-latency network links.

A business will choose one or multiple availability zones for a variety of reasons, such as compliance and proximity to end customers. For example, an AWS customer can spin up virtual machines (VMs) and replicate data in different AZs to achieve a highly reliable infrastructure that is resistant to failures of individual servers or an entire data center.

Amazon Elastic Compute Cloud (EC2) is a service that provides virtual servers -- called EC2 [](https://www.techtarget.com/searchaws/definition/Amazon-EC2-instances)instances -- for computing capacity. The EC2 service offers dozens of instance types with varying capacities and sizes, tailored to specific workload types and applications, such as memory-intensive and accelerated-computing jobs. AWS also provides an Auto Scaling tool to dynamically scale capacity to maintain instance health and performance.

**Storage**

Amazon Simple Storage Service (S3) provides scalable object storage for data backup, collection and analytics. An IT professional stores data and files as S3 objects -- which can range up to 5 gigabytes (GB) -- inside S3 bucket to keep them organized. A business can save money with S3 through its Infrequent Access storage tier or by using Amazon glaciers for long-term cold storage.

Amazon elastic glass provides block-level storage volumes for persistent data storage when using EC2 instances. Amazon Elastic File system offers managed cloud-based file storage.

A business can also migrate data to the cloud via storage transport devices, such as AWS snowball and Snowmobile, or use AWS storage Gateway to enable on-premises apps to access cloud data.

**Databases, data management**

The Amazon relational Database Service -- which includes options for Oracle, SQL Server, PostgreSQL, MySQL, MariaDB and a proprietary high-performance database called Amazon Aurora -- provides a relational database management system for AWS users. AWS also offers managed noSQL databases through Amazon DynamoDB.

An AWS customer can use Amazon ElastiCache and DynamoDB Accelerator as in-memory and real-time data caches for applications. Amazon RedShift offers a data warehouse, which makes it easier for data analysts to perform business intelligence (BI) tasks.

**Migration, hybrid cloud**

AWS includes various tools and services designed to help users migrate applications, databases, servers and data onto its Public Cloud. The AWS Migration Hub provides a location to monitor and manage migrations from on-premises to the cloud. Once in the cloud, EC2 System Manager helps an IT team configure on-premises servers and AWS instances.

Amazon also has partnerships with several technology vendors that ease hybrid cloud deployments. VMware cloud brings software-defined data center technology from VMware to the AWS cloud. Red Hat Enterprise Linux for Amazon EC2 is the product of another partnership, extending Red Hat's operating system to the AWS cloud.

**Networking**

An Amazon Virtual Private Cloud (Amazon VPC) gives an administrator control over a virtual network to use an isolated section of the AWS cloud. AWS automatically provisions new resources within a VPC for extra protection.

Admins can balance network traffic with the Elastic Load Balancing (ELB) service, which includes the Application Load Balancer and Network Load Balancer. AWS also provides a domain name system called amazon Route 53 that routes end users to applications.

An IT professional can establish a dedicated connection from an on-premises data center to the AWS cloud via AWS Direct Connect.

**Developer tools**

A developer can take advantage of AWS command-line tools and software development kits (SDKs) to deploy and manage applications and services. This includes:

* The AWS Command Line Interface is Amazon's proprietary code interface.
    
* A developer can use AWS Tools for PowerShell to manage cloud services from Windows environments.
    
* Developers can use AWS Serverless Application Model to simulate an AWS environment to test Lambda functions.
    

AWS SDKs are available for a variety of platforms and programming languages, including Java, PHP, Python, Node.js, Ruby, C++, Android and iOS.

Amazon API Gateway enables a development team to create, manage and monitor custom application program interfaces (APIs) that let applications access data or functionality from back-end services. API Gateway manages thousands of concurrent API calls at once.

AWS also provides a packaged media transcoding service -- Amazon Elastic Transcoder -- and a service that visualizes workflows for microservices-based applications -- AWS Step Functions.

A development team can also create continuous integration and continuous delivery pipelines with services like:

A developer can also store code in Git repositories with AWS CodeCommit and evaluate the performance of microservices-based applications with AWS X-Ray.

**Management and monitoring**

An admin can manage and track cloud resource configuration via AWS Config and AWS Config Rules. Those tools, along with AWS Trusted Advisor, can help an IT team avoid improperly configured and needlessly expensive cloud resource deployments.

AWS provides several automation tools in its portfolio. An admin can automate infrastructure provisioning via AWS CloudFormation templates, and also use AWS OpsWorks and Chef to automate infrastructure and system configurations.

An AWS customer can monitor resource and application health with Amazon CloudWatch and the AWS Personal Health Dashboard, as well as use AWS CloudTrail to retain user activity and API calls for auditing.

**Security and governance**

AWS provides a range of services for cloud security, including AWS Identity and Access Management, which allows admins to define and manage user access to resources. An admin can also create a user directory with Amazon Cloud Directory, or connect cloud resources to an existing Microsoft Active Directory with the AWS Directory Service. Additionally, the AWS Organizations service enables a business to establish and manage policies for multiple AWS accounts.

Amazon Web Services has also introduced tools that automatically assess potential security risks. Amazon Inspector analyzes an AWS environment for vulnerabilities that might impact security and compliance. Amazon Macie uses machine learning (ML) technology to protect sensitive cloud data.

AWS also includes tools and services that provide software- and hardware-based encryption, protect against DDoS attacks, provision Secure Sockets Layer (SSL) and Transport Layer Security (TLS) certificates and filter potentially harmful traffic to web applications.

The AWS Management Console is a browser-based graphical user interface (GUI) for AWS. The Management Console can be used to manage resources in cloud computing, cloud storage and security credentials. The AWS Console interfaces with all AWS resources.

**Big data management and analytics**

AWS includes a variety of big data analytics and application services. This includes:

* Amazon Elastic MapReduce, which offers a Hadoop framework to process large amounts of data.
    
* Amazon Kinesis provides several tools to process and analyze streaming data.
    
* AWS Glue is a service that handles extracting, transforming and loading jobs.
    
* Amazon Elasticsearch Service enables a team to perform application monitoring, log analysis and other tasks with the open-source Elasticsearch tool.
    
* Amazon Athena for S3, which allows analysts to query data.
    
* Amazon QuickSight, which helps analysts visualize data.
    

**Artificial intelligence**

AWS offers a range of AI model development and delivery platforms, as well as packaged AI-based applications. The Amazon AI suite of tools includes:

* Amazon Lex for voice and text chatbot technology;
    
* Amazon Polly for text-to-speech translation; and
    
* Amazon Rekognition for image and facial analysis.
    

AWS also provides technology for developers to build smart apps that rely on machine learning technology and complex algorithms.

With AWS Deep Learning Amazon Machine Images (AMIs), developers can create and train custom AI models with clusters of graphics processing units (GPUs) or compute-optimized instances. AWS also includes deep learning development frameworks for MXNet and TensorFlow.

On the consumer side, AWS technologies power the Alexa Voice Services, and a developer can use the Alexa Skills Kit to build voice-based apps for Echo devices.

**Mobile development**

The AWS Mobile Hub offers a collection of tools and services for mobile app developers, including the AWS Mobile SDK, which provides code samples and libraries.

A mobile app developer can also use Amazon Cognito to manage user access to mobile apps, as well as Amazon Pinpoint to send push notifications to application end users and then analyze the effectiveness of those communications.

**Messages and notifications**

AWS messaging services provide core communication for users and applications. Amazon Simple Queue Service (SQS) is a managed message queue that sends, stores and receives messages between components of distributed applications to ensure that the parts of an application work as intended.

Amazon Simple Notification Service (SNS) enables a business to send publish/subscribe messages to endpoints, such as end users or services. SNS includes a mobile messaging feature that enables push messaging to mobile devices. Amazon Simple Email Service (SES) provides a platform for IT professionals and marketers to send and receive emails.

**AR & VR (Augmented reality and virtual reality)**

AWS offers augmented reality (AR) and virtual reality (VR) development tools through the Amazon Sumerian service. Amazon Sumerian allows users to create AR and VR applications without needing to know to program or create 3D graphics. The service also enables users to test and publish applications in-browser. Amazon Sumerian can be used in:

* 3D web applications
    
* E-commerce & sales applications
    
* Marketing
    
* Online Education
    
* Manufacturing
    
* Training simulations
    
* Gaming
    

**Game development**

AWS can also be used for game development. Large game-developing companies, such as Ubisoft, will use AWS services for their games, like For Honor. AWS can provide services for each part of a game's lifecycle.

For example, AWS will provide developer back-end services, analytics and developer tools. Developer tools should help aid developers in making their games, while back-end services might be able to help with building, deploying or scaling a developer's platform. Analytics might help developers better know their customers and how they play the game. Developers can also store data, or host game data on AWS servers.

**Internet of Things**

AWS also has a variety of services that enable internet of things (IoT) deployments. The AWS IoT service provides a back-end platform to manage IoT devices and data ingestion to other AWS storage and database services. The AWS IoT Button provides hardware for limited IoT functionality and AWS Greengrass brings AWS to compute capabilities to IoT devices.

**Other services**

Amazon Web Services has a range of business productivity SaaS options, including:

* The Amazon Chime service enables online video meetings, calls and text-based chats across devices.
    
* Amazon WorkDocs, which is a file storage and sharing service
    
* Amazon WorkMail, which is a business email service with calendaring features.
    

Desktop and streaming application services include Amazon WorkSpaces, a remote desktop-as-a-service platform (DaaS), and Amazon AppStream, a service that lets a developer stream a desktop application from AWS to an end user's web browser.

**AWS pricing models and competition**

AWS offers a pay-as-you-go model for its cloud services, either on a per-hour or per-second basis. There is also an option to reserve a set amount of computing capacity at a discounted price for customers who prepay in whole, or who sign up for one- or three-year usage commitments.

If potential customers can’t afford the costs, then AWS Free Tier is another possible avenue for using AWS services. AWS Free Tier allows users to gain first-hand experience with AWS services for free; they can access up to 60 products and start building on the AWS platform. Free Tier is offered in three different options: always free, 12 months free and trials.

AWS competes primarily with Microsoft Azure, Google and IBM in the public IaaS market.

**History**

The AWS platform was originally launched in 2002 with only a few services. In 2003, AWS was re-envisioned to make Amazon's compute infrastructure standardized, automated and web service-focused. This re-envisioning included the thought of selling access to the virtual server as a service platform. One year later, in 2004, the first publicly available AWS service -- Amazon SQS -- was launched.

In 2006, AWS was relaunched to include three services -- including Amazon S3 cloud storage, SQS, and EC2 -- officially making AWS a suite of online core services. In 2009, S3 and EC2 were launched in Europe, and the Elastic Block Store and Amazon CloudFront were released and adopted by AWS. In 2013, AWS started to offer a certification process in AWS services, and 2018 saw the release of an autoscaling service.

Over time, AWS has added plenty of services that helped make it a low-cost infrastructure platform that is highly available and scalable. AWS now has a focus on the cloud, with data centers placed around the world, in places such as the United States, Australia, Europe, Japan and Brazil.

**Acquisitions**

Over time, AWS has acquired multiple organizations, increasing its focus on technologies it wants to further incorporate. Recently AWS' acquisitions haven't concentrated on larger well-established companies, but instead on organizations that could bolster and overall improve the cloud vendor's existing offerings. These acquisitions don't add to AWS, but rather enhance its core services. For example, AWS has acquired TSO Logic, Sqrrl and CloudEndure.

TSO Logic was a cloud migration company that provides analytics, enabling customers to view the state of their current data center and model migration to the cloud.

Sqrrl was a security startup that collects data from points such as gateways, servers and routers, and then puts those findings inside a security dashboard.

Cloud Endure is a company that focuses on workload migrations to the public cloud, disaster recovery and backup.

These acquisitions shouldn't majorly change AWS; they will position it better. For example, the acquisition of CloudEndure should accelerate the movement of on-premises workloads to the AWS cloud.