# AWS Certified Data Engineer Associate (DEA-C01)
**Listed Services for AWS Certified Data Engineer - Associate is subject to change in future. This post published in Nov 2023. While studying for Exam go through official exam guide first that is available on official AWS Exam Page. Good Luck for the Exam !!**


<h3 align="center"> Analytics </h3>

**1. Amazon Athena:**
- Amazon Athena is an interactive query service that allows you to analyze data in Amazon S3 using standard SQL.
- It enables you to quickly and easily query data in various file formats stored in S3, making it suitable for ad-hoc data analysis.

**2. Amazon EMR (Elastic MapReduce):**
- Amazon EMR is a cloud-native big data platform that allows you to process vast amounts of data quickly and cost-effectively.
- It simplifies the deployment and management of distributed data processing frameworks like Apache Hadoop, Spark, and more.

**3. AWS Glue:**
- AWS Glue is a managed ETL (Extract, Transform, Load) service that makes it easy to prepare and load data for analytics.
- It automatically generates code for data transformation and integrates with various data sources.

**4. AWS Glue DataBrew:**
- AWS Glue DataBrew is a visual data preparation tool that helps users clean and normalize data for analytics and machine learning.
- It offers a visual interface for data profiling, cleaning, and transformation.

**5. AWS Lake Formation:**
- AWS Lake Formation simplifies the process of building and managing data lakes.
- It provides tools to catalog, secure, and manage data, making it accessible for analytics and machine learning.

**6. Amazon Kinesis Data Analytics:**
- Amazon Kinesis Data Analytics is a real-time data analytics service that allows you to process and analyze streaming data using SQL or Java.
- It's useful for applications such as real-time dashboards and anomaly detection.

**7. Amazon Kinesis Data Firehose:**
- Amazon Kinesis Data Firehose is a service for loading real-time streaming data into AWS data stores, like S3, Redshift, and Elasticsearch.
- It simplifies the data delivery process.

**8. Amazon Kinesis Data Streams:**
- Amazon Kinesis Data Streams is a platform for building custom streaming data applications.
- It allows you to ingest and process real-time data streams at scale.

**9. Amazon Managed Streaming for Apache Kafka (Amazon MSK):**
- Amazon MSK is a managed service for Apache Kafka, a popular distributed data streaming platform.
- It simplifies the deployment and management of Kafka clusters.

**10. Amazon OpenSearch Service:**
- Amazon OpenSearch Service is a managed Elasticsearch service that allows you to search, analyze, and visualize data in real-time.
- It's commonly used for log and event data analysis.

**11. Amazon QuickSight:**
- Amazon QuickSight is a business intelligence and data visualization service.
- It enables users to create interactive dashboards and reports to gain insights from their data.

<h3 align="center"> Application Integration </h3>


**1. Amazon AppFlow:**
- Amazon AppFlow is a fully managed integration service that allows you to securely transfer data between different applications.
- It provides pre-built connectors for various SaaS applications, enabling data flows and automation.

**2. Amazon EventBridge:**
- Amazon EventBridge is a serverless event bus service that makes it easy to connect different AWS services, third-party applications, and custom applications.
- It simplifies event-driven architectures by providing a central event routing system.

**3. Amazon Managed Workflows for Apache Airflow (Amazon MWAA):**
- Amazon MWAA is a managed Apache Airflow service that allows you to orchestrate and automate workflows.
- It provides a platform for scheduling, monitoring, and managing workflows in the cloud.

**4. Amazon Simple Notification Service (Amazon SNS):**
- Amazon SNS is a fully managed messaging service that enables you to send messages or notifications to distributed systems and applications.
- It supports various message formats and delivery protocols.

**5. Amazon Simple Queue Service (Amazon SQS):**
- Amazon SQS is a fully managed message queuing service that allows you to decouple the components of a cloud application.
- It ensures reliable and asynchronous communication between distributed systems.

**6. AWS Step Functions:**
- AWS Step Functions is a serverless orchestration service that enables you to coordinate multiple AWS services into serverless workflows.
- It simplifies the creation of state machines for managing workflows and applications.


<h3 align="center"> Financial Management </h3>

**1. AWS Budgets:**
- AWS Budgets is a service that helps you manage your AWS costs and usage by setting custom cost and usage budgets.
- It allows you to set budget thresholds and receive alerts when your spending or usage exceeds those thresholds.
- AWS Budgets is a valuable tool for cost control and financial planning in AWS environments.

**2. AWS Cost Explorer:**
- AWS Cost Explorer is a tool that provides a comprehensive view of your AWS cost and usage data.
- It offers various cost visualization, filtering, and reporting capabilities to help you understand and analyze your AWS spending.
- With Cost Explorer, you can gain insights into cost patterns, identify cost-saving opportunities, and forecast future expenses.

<h3 align="center"> Compute </h3>

**1. AWS Batch:**
- AWS Batch is a fully managed service that enables you to run batch computing workloads on the AWS Cloud.
- It automatically provisions and scales compute resources, making it easy to process large-scale, batch-oriented workloads.

**2. Amazon EC2 (Elastic Compute Cloud):**
- Amazon EC2 is a web service that provides resizable compute capacity in the cloud.
- It allows you to launch and manage virtual servers (EC2 instances) with a wide range of instance types, operating systems, and configurations.

**3. AWS Lambda:**
- AWS Lambda is a serverless computing service that allows you to run code without provisioning or managing servers.
- You can execute code in response to events, and you only pay for the compute time consumed.

**4. AWS Serverless Application Model (AWS SAM):**
- AWS SAM is an open-source framework for building serverless applications.
- It simplifies the development of serverless applications by providing a template specification for defining serverless resources and their interactions.

<h3 align="center"> Containers </h3>

**1. Amazon Elastic Container Registry (Amazon ECR):**
- Amazon ECR is a fully managed container registry service that makes it easy to store, manage, and deploy Docker container images.
- It integrates seamlessly with other AWS services, like Amazon ECS and Amazon EKS, and provides a secure and scalable container image storage solution.

**2. Amazon Elastic Container Service (Amazon ECS):**
- Amazon ECS is a fully managed container orchestration service that allows you to run and scale containerized applications.
- It simplifies the deployment and management of containers on AWS, supporting both Fargate (serverless) and EC2 launch types.

**3. Amazon Elastic Kubernetes Service (Amazon EKS):**
- Amazon EKS is a managed Kubernetes service that simplifies the deployment and management of Kubernetes clusters.
- It allows you to run containerized applications using Kubernetes, benefiting from the orchestration and scalability features of Kubernetes.

<h3 align="center"> Database </h3>

**1. Amazon DocumentDB (with MongoDB compatibility):**
- Amazon DocumentDB is a fully managed, MongoDB-compatible database service.
- It is designed for applications that require the scalability and flexibility of a NoSQL database with the reliability and performance of a relational database.

**2. Amazon DynamoDB:**
- Amazon DynamoDB is a fully managed NoSQL database service that offers fast and predictable performance at any scale.
- It is suitable for applications that require low-latency, highly available storage for a wide range of data models.

**3. Amazon Keyspaces (for Apache Cassandra):**
- Amazon Keyspaces is a managed Apache Cassandra-compatible database service.
- It enables you to build applications using the Apache Cassandra data model while benefiting from AWS's operational efficiency and scalability.

**4. Amazon MemoryDB for Redis:**
- Amazon MemoryDB for Redis is a fully managed, Redis-compatible, in-memory database service.
- It is designed for applications that require high-performance, low-latency data storage and retrieval.

**5. Amazon Neptune:**
- Amazon Neptune is a fully managed graph database service that supports both the property graph and RDF graph models.
- It is suitable for applications that require efficient querying and analysis of highly connected data.

**6. Amazon RDS (Relational Database Service):**
- Amazon RDS is a managed relational database service that supports multiple database engines, including MySQL, PostgreSQL, Oracle, SQL Server, and MariaDB.
- It simplifies database administration tasks and provides high availability and scalability.

**7. Amazon Redshift:**
- Amazon Redshift is a fully managed data warehousing service designed for analytics and data warehousing workloads.
- It allows you to run complex, high-performance queries on large datasets.

<h3 align="center"> Developer Tools </h3>

**1. AWS CLI (Command Line Interface):**
- The AWS CLI is a command-line tool that provides a unified interface for interacting with various AWS services.
- It allows developers to manage AWS resources, configure services, and automate tasks through scripts and commands.

**2. AWS Cloud9:**
- AWS Cloud9 is a cloud-based integrated development environment (IDE) that simplifies the development and collaboration process.
- It provides a code editor, debugger, and terminal in a browser-based environment, making it easy to build and deploy applications.

**3. AWS Cloud Development Kit (AWS CDK):**
- AWS CDK is an open-source software development framework for defining cloud infrastructure in code.
- It enables developers to define cloud resources using familiar programming languages like TypeScript, Python, and Java, and then deploy them using AWS CloudFormation.

**4. AWS CodeBuild:**
- AWS CodeBuild is a fully managed build service that compiles source code, runs tests, and produces deployable software packages.
- It supports a variety of build environments and integrates with other AWS services and source code repositories.

**5. AWS CodeCommit:**
- AWS CodeCommit is a fully managed source code control service that makes it easy for teams to host secure and scalable Git repositories.
- It provides a secure and highly available platform for version control.

**6. AWS CodeDeploy:**
- AWS CodeDeploy is a deployment service that automates code deployments to a variety of compute services, including EC2 instances, Lambda functions, and on-premises servers.
- It simplifies application deployments and ensures reliability and consistency.

**7. AWS CodePipeline:**
- AWS CodePipeline is a continuous integration and continuous delivery (CI/CD) service that automates the building, testing, and deployment of applications.
- It allows you to create and manage end-to-end software release workflows.

<h3 align="center"> Frontend Web and Mobile </h3>

**1. Amazon API Gateway:**
- Amazon API Gateway is a fully managed service that makes it easy for developers to create, publish, maintain, monitor, and secure APIs at any scale.
- It acts as a front-end for your backend services, enabling you to build and expose APIs to the internet or other services. It supports RESTful and WebSocket APIs.

<h3 align="center"> Machine Learning </h3>

**1. Amazon SageMaker:**
- Amazon SageMaker is a fully managed service that simplifies the process of building, training, and deploying machine learning models.
- It provides a complete set of tools and infrastructure for data scientists and developers to experiment with and deploy machine learning models at scale.

<h3 align="center"> Management and Governance </h3>

**1. AWS CloudFormation:**
- AWS CloudFormation is an infrastructure-as-code service that allows you to define and provision AWS infrastructure and resources using templates.
- It enables you to automate the deployment and management of your AWS infrastructure in a consistent and repeatable manner.

**2. AWS CloudTrail:**
- AWS CloudTrail is a logging service that records API calls and events made within your AWS account.
- It provides an audit trail for actions taken by users, services, or resources, helping with security, compliance, and troubleshooting.

**3. Amazon CloudWatch:**
- Amazon CloudWatch is a monitoring and observability service that allows you to collect and track metrics, collect and monitor log files, and set alarms.
- It helps you gain insights into the performance and health of your AWS resources and applications.

**4. Amazon CloudWatch Logs:**
- Amazon CloudWatch Logs is a service for ingesting and storing log data generated by your applications and AWS resources.
- It provides the ability to search, analyze, and monitor log data to troubleshoot issues and gain operational insights.

**5. AWS Config:**
- AWS Config is a service that helps you assess, audit, and evaluate the configurations of your AWS resources.
- It continuously monitors your AWS infrastructure for compliance and changes and provides a historical record of resource configurations.

**6. Amazon Managed Grafana:**
- Amazon Managed Grafana is a fully managed service for creating, visualizing, and sharing operational dashboards using Grafana.
- It simplifies the setup and management of Grafana, a popular open-source monitoring and observability platform.

**7. AWS Systems Manager:**
- AWS Systems Manager is a management service that helps you automate operational tasks across your AWS resources.
- It provides capabilities for patch management, configuration management, automation, and other tasks.

**8. AWS Well-Architected Tool:**
- The AWS Well-Architected Tool is a service that provides guidance and best practices for building and optimizing workloads in the cloud.
- It helps organizations evaluate their architecture against the AWS Well-Architected Framework and provides recommendations for improvements.

<h3 align="center"> Migration and Transfer </h3>

**1. AWS Application Discovery Service:**
- AWS Application Discovery Service helps organizations plan their migration to the cloud by discovering and assessing on-premises applications.
- It collects data about on-premises environments, including application dependencies and resource utilization, to inform migration decisions.

**2. AWS Application Migration Service:**
- AWS Application Migration Service is designed to assist in migrating on-premises applications to AWS.
- It provides automation and orchestration capabilities to simplify the migration process, making it easier to transition applications to the cloud.

**3. AWS Database Migration Service (AWS DMS):**
- AWS Database Migration Service is a fully managed service that helps migrate databases to AWS easily and securely.
- It supports a wide range of source and target database platforms, facilitating database migration, replication, and continuous data integration.

**4. AWS DataSync:**
- AWS DataSync is a data transfer service designed to simplify data migration and transfer between on-premises environments and AWS.
- It offers high-speed data transfer, data validation, and automatic encryption to ensure secure and efficient data synchronization.

**5. AWS Schema Conversion Tool (AWS SCT):**
- AWS Schema Conversion Tool is a service that helps convert database schemas between different database engines.
- It is valuable when migrating applications that use one database engine to another, ensuring a smooth transition.

**6. AWS Snow Family:**
- The AWS Snow Family comprises physical devices designed for data transfer and migration in challenging or offline environments.
- Snowball, Snowball Edge, and Snowmobile are part of this family and provide secure, scalable, and efficient ways to transfer large datasets to AWS.

**7. AWS Transfer Family:**
- AWS Transfer Family includes AWS Transfer for SFTP (Secure File Transfer Protocol) and AWS Transfer for FTP (File Transfer Protocol).
- These services allow you to set up fully managed SFTP and FTP servers in AWS to securely transfer files.

<h3 align="center"> Networking and Content Delivery </h3>

**1. Amazon CloudFront:**
- Amazon CloudFront is a content delivery service that accelerates the distribution of web content to end-users globally.
- It uses a network of edge locations to cache and serve content, reducing latency and improving website performance.

**2. AWS PrivateLink:**
- AWS PrivateLink is a service that enables private connectivity between VPCs (Virtual Private Clouds) and supported AWS services over the AWS network, without using public IPs.
- It enhances security and compliance by allowing private, direct connections to AWS services.

**3. Amazon Route 53:**
- Amazon Route 53 is a scalable and highly available Domain Name System (DNS) web service.
- It provides DNS and domain registration services, making it easy to route traffic to AWS resources and external endpoints.

**4. Amazon VPC (Virtual Private Cloud):**
- Amazon VPC is a service that allows you to create isolated, virtualized networks in the AWS cloud.
- It gives you control over network architecture, IP addressing, subnets, security groups, and routing to build secure and scalable infrastructure.

<h3 align="center"> Security, Identity, and Compliance </h3>

**1. AWS Identity and Access Management (IAM):**
- AWS Identity and Access Management (IAM) is a service that allows you to control access to AWS resources securely.
- It enables you to create and manage users, groups, roles, and policies to define permissions and access control in your AWS environment.

**2. AWS Key Management Service (AWS KMS):**
- AWS Key Management Service (AWS KMS) is a managed encryption service that makes it easy to create and control the encryption keys used to secure data.
- It helps protect data at rest and in transit by providing a central location for key management.

**3. Amazon Macie:**
- Amazon Macie is a security service that uses machine learning to discover, classify, and protect sensitive data in AWS.
- It helps organizations identify and secure their data, ensuring compliance with security and privacy requirements.

**4. AWS Secrets Manager:**
- AWS Secrets Manager is a service for managing and rotating sensitive information, such as database credentials, API keys, and other secrets.
- It simplifies the process of securely storing and accessing sensitive data.

**5. AWS Shield:**
- AWS Shield is a managed Distributed Denial of Service (DDoS) protection service that safeguards applications and websites against DDoS attacks.
- It provides both standard and advanced protection tiers to meet the security needs of different applications.

**6. AWS WAF (Web Application Firewall):**
- AWS WAF is a web application firewall service that helps protect web applications from common web exploits and attacks.
- It allows you to create rules to filter and monitor incoming traffic, enhancing the security of your web applications.

<h3 align="center"> Storage </h3>

**1. AWS Backup:**
- AWS Backup is a fully managed backup service that centralizes and automates the backup of your AWS resources, including Amazon EBS volumes, RDS databases, and more.
- It simplifies the backup and recovery process, helping you meet data retention and compliance requirements.

**2. Amazon Elastic Block Store (Amazon EBS):**
- Amazon Elastic Block Store (Amazon EBS) provides block-level storage volumes that can be attached to Amazon EC2 instances.
- It offers durable and high-performance storage for EC2 workloads and is commonly used for databases and application data.

**3. Amazon Elastic File System (Amazon EFS):**
- Amazon Elastic File System (Amazon EFS) is a scalable, fully managed file storage service that can be shared across multiple EC2 instances.
- It is designed for use cases requiring shared access to files and data.

**4. Amazon S3 (Simple Storage Service):**
- Amazon S3 is an object storage service that allows you to store and retrieve data, including documents, images, videos, and backups.
- It offers scalable, durable, and highly available storage with various storage classes and features for data management.

**5. Amazon S3 Glacier:**
- Amazon S3 Glacier is a storage service for data archiving and long-term backup at a lower cost.
- It is designed for infrequently accessed data that needs to be stored securely and durably
