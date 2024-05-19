---
layout: post
title:  "Amazon Cloud Architect Associate"
tags: aws 
---
- [AWS Fundamentals](#aws-fundamentals)
- [(IAM) Identity and Access Management](#iam-identity-and-access-management)
  - [Chapter Summary](#chapter-summary)
- [S3](#s3)
  - [Chapter Summary](#chapter-summary-1)
  - [S3 lifecycles](#s3-lifecycles)
  - [S3 Lock](#s3-lock)
  - [S3 Encryption](#s3-encryption)
  - [Optimizing S3 Performance](#optimizing-s3-performance)
  - [S3 Cross Region Replication](#s3-cross-region-replication)
  - [S3 Transfer Acceleration](#s3-transfer-acceleration)
- [Elastic Compute Cloud (EC2)](#elastic-compute-cloud-ec2)
  - [Chapter Summary](#chapter-summary-2)
  - [Pricing options](#pricing-options)
  - [AWS Commandline](#aws-commandline)
  - [Roles](#roles)
  - [Security Groups and Bootstrap Scripts](#security-groups-and-bootstrap-scripts)
  - [Metadata \& User Data](#metadata--user-data)
  - [Networking with EC2](#networking-with-ec2)
  - [Optimizing with EC2 Placement Groups](#optimizing-with-ec2-placement-groups)
- [Elastic Block Storage (EBS) and Elastic File System (EFS)](#elastic-block-storage-ebs-and-elastic-file-system-efs)
  - [Chatper Summary](#chatper-summary)
  - [EBS](#ebs)
    - [SSD](#ssd)
    - [HDD](#hdd)
    - [Volumnes and Snapshots](#volumnes-and-snapshots)
      - [Keys](#keys)
    - [EBS Ecryption](#ebs-ecryption)
    - [EC2 Hibernation](#ec2-hibernation)
  - [EFS](#efs)
  - [FSx](#fsx)
  - [AMI - Amazon Machine Images](#ami---amazon-machine-images)
- [Databases](#databases)
  - [Chapter Summary](#chapter-summary-3)
  - [Read Replica](#read-replica)
    - [Keys](#keys-1)
  - [DynamoDB](#dynamodb)
    - [DynamoDB Basis](#dynamodb-basis)
    - [DynamoDB Transactions](#dynamodb-transactions)
    - [DynamoDB On-demand backup and restore](#dynamodb-on-demand-backup-and-restore)
    - [Point-in-Time Recovery (PITR)](#point-in-time-recovery-pitr)
    - [Taking your Data Global with DynamoDB Streams and Global Tables](#taking-your-data-global-with-dynamodb-streams-and-global-tables)
  - [Operating MongoDB-Compatible Database in Amazon DocumentDB](#operating-mongodb-compatible-database-in-amazon-documentdb)
  - [Runing Apache Cassandra workloads with Amazon Keyspaces](#runing-apache-cassandra-workloads-with-amazon-keyspaces)
  - [Implementing Graph Databases using Amazon Neptune](#implementing-graph-databases-using-amazon-neptune)
  - [Lerveragubg Amazon Quantum Ledger Database (QLDB) for ledger Databases](#lerveragubg-amazon-quantum-ledger-database-qldb-for-ledger-databases)
    - [Analyzing Time-series Data with Amazon Timestream](#analyzing-time-series-data-with-amazon-timestream)
- [Virtual Private Cloud (VPC) Networking](#virtual-private-cloud-vpc-networking)
  - [Chapter Summary](#chapter-summary-4)
  - [Overview](#overview)
  - [Using NAT GW for Internet Access](#using-nat-gw-for-internet-access)
  - [Protecting your Resources using Security Group](#protecting-your-resources-using-security-group)
  - [Controlling Subnet Traffic with Network ACLs](#controlling-subnet-traffic-with-network-acls)
  - [Private Communication Using VPC Endpoint](#private-communication-using-vpc-endpoint)
  - [Building Solutions across VPCs with Peering](#building-solutions-across-vpcs-with-peering)
  - [Network Privacy with AWS PrivateLink](#network-privacy-with-aws-privatelink)
  - [Securing your Network with VPN Cloudhub](#securing-your-network-with-vpn-cloudhub)
- [Route 53](#route-53)
- [Elastic Load Balancing](#elastic-load-balancing)
  - [Chapter summary](#chapter-summary-5)
  - [Application LB](#application-lb)
  - [Network LB](#network-lb)
  - [Gateway LB](#gateway-lb)
  - [Clasic LB](#clasic-lb)
  - [Deregistration Delay](#deregistration-delay)
- [CloudWatch-·Monitoring](#cloudwatch-monitoring)
  - [Chapter Summary](#chapter-summary-6)
- [High Availability and Scaling](#high-availability-and-scaling)
  - [Chapter Summary](#chapter-summary-7)
  - [Scaling EC2](#scaling-ec2)
  - [Scaling RDB](#scaling-rdb)
  - [Scaling Non-Relational DB](#scaling-non-relational-db)
- [Decoupling Workflows](#decoupling-workflows)
  - [Chapter Summary](#chapter-summary-8)
  - [Simple Queue Service (SQS)](#simple-queue-service-sqs)
  - [Simple Notification Service (SNS)](#simple-notification-service-sns)
  - [API GW](#api-gw)
- [Big Data](#big-data)
  - [Summary](#summary)
  - [Redshift](#redshift)
  - [EMR （Elastic MapReduce）](#emr-elastic-mapreduce)
  - [Kinesis](#kinesis)
  - [Athena](#athena)
  - [Glue](#glue)
  - [QuickSight](#quicksight)
  - [Moving Transformed Data Using AWS Data Pipeline](#moving-transformed-data-using-aws-data-pipeline)
  - [Implementing Amazon Managed Streaming for Apache Kafka (Amazon MSK)](#implementing-amazon-managed-streaming-for-apache-kafka-amazon-msk)
  - [Analyzing Data with Amazon OpenSearch Service](#analyzing-data-with-amazon-opensearch-service)
  - [BigData Exam Tips](#bigdata-exam-tips)
- [Serverless Architecture](#serverless-architecture)
  - [Lambda](#lambda)
  - [Leveraging the AWS Serverless Application Repo](#leveraging-the-aws-serverless-application-repo)
  - [Container](#container)
  - [Running Containers in ECS or EKS](#running-containers-in-ecs-or-eks)
  - [Removing Servers with Fargate](#removing-servers-with-fargate)
  - [Amazon EventBridge (Cloudwatch Evnets)](#amazon-eventbridge-cloudwatch-evnets)
  - [Storing Custom Docker Images in Amazon Elastic Container Registry (Amazon ECR)](#storing-custom-docker-images-in-amazon-elastic-container-registry-amazon-ecr)
  - [\*Using Open-Source Kubernetes in Amazon ELS Distro (EKS-D)](#using-open-source-kubernetes-in-amazon-els-distro-eks-d)
  - [Orchestrating Containers Outside AWS Using Amazon EKS Anywhere and ECS Anywhere](#orchestrating-containers-outside-aws-using-amazon-eks-anywhere-and-ecs-anywhere)
  - [Auto Scaling Database On Demand with Amazon Aurora Serverless](#auto-scaling-database-on-demand-with-amazon-aurora-serverless)
  - [Using AWS X-Rays for Application Insights](#using-aws-x-rays-for-application-insights)
  - [Deploying GraphQL Interfaces in AWS AppSync](#deploying-graphql-interfaces-in-aws-appsync)
- [Security](#security)
  - [DDos](#ddos)
  - [Logging API Calls with cloudtrail](#logging-api-calls-with-cloudtrail)
  - [Shield](#shield)
  - [WAF](#waf)
  - [GuardDuty](#guardduty)
  - [Firewall manager](#firewall-manager)
  - [Macie](#macie)
  - [Inspector](#inspector)
  - [AWS Keymanager (KMS) and CloudHSM](#aws-keymanager-kms-and-cloudhsm)
  - [Secrets Manager](#secrets-manager)
  - [Parameter Store](#parameter-store)
  - [Presigned URLs or Cookies](#presigned-urls-or-cookies)
  - [Certificate Manager](#certificate-manager)
  - [Audit Manager](#audit-manager)
  - [Artifact](#artifact)
  - [Amazon Cognito (important)](#amazon-cognito-important)
  - [Network firewall](#network-firewall)
  - [Secuirty Hub](#secuirty-hub)
- [Automation](#automation)
  - [Summary](#summary-1)
  - [CloudFormation](#cloudformation)
  - [Elasticbeanstalk (high level knowledge)](#elasticbeanstalk-high-level-knowledge)
  - [Systems Manager (Important)](#systems-manager-important)
- [Caching](#caching)
  - [Summary](#summary-2)
  - [CloudFront](#cloudfront)
  - [ElasticCache \& DAX](#elasticcache--dax)
    - [Summary](#summary-3)
  - [Global Accelerator](#global-accelerator)
    - [Summary](#summary-4)
- [Governance](#governance)
  - [Summary](#summary-5)
  - [AWS Organization](#aws-organization)
    - [Summary](#summary-6)
  - [AWS Resource Access Manager (RAM)](#aws-resource-access-manager-ram)
  - [AWS Cross-account role Access](#aws-cross-account-role-access)
  - [AWS Config](#aws-config)
  - [Directory Service](#directory-service)
  - [Cost Explorer](#cost-explorer)
  - [AWS Budgets](#aws-budgets)
  - [AWS Cost and Usage Report (CUR)](#aws-cost-and-usage-report-cur)
  - [AWS Compute Optimizer](#aws-compute-optimizer)
  - [AWS Trusted Advisor](#aws-trusted-advisor)
  - [AWS Control Tower](#aws-control-tower)
    - [Summary](#summary-7)
  - [AWS License manager](#aws-license-manager)
  - [AWS Health dashboard](#aws-health-dashboard)
  - [AWS Service Catalog \& AWS Proton](#aws-service-catalog--aws-proton)
  - [AWS Well-Architected Framewaork (important)](#aws-well-architected-framewaork-important)
    - [Summary](#summary-8)
- [Migration](#migration)
  - [Summary](#summary-9)
  - [Snow family](#snow-family)
    - [Summary](#summary-10)
  - [Storage Gateway](#storage-gateway)
    - [Summary](#summary-11)
  - [Data Sync](#data-sync)
    - [Summary](#summary-12)
  - [AWS Transfer Family](#aws-transfer-family)
    - [Summary](#summary-13)
  - [AWS Migration Hub](#aws-migration-hub)
    - [Summary](#summary-14)
  - [AWS Application Discovery Service \& AWS Application migration Service (MGN)](#aws-application-discovery-service--aws-application-migration-service-mgn)
  - [AWS Database Migration Service (DMS)](#aws-database-migration-service-dms)
    - [Summary](#summary-15)
  - [Migration hub + server migration service (SMS)](#migration-hub--server-migration-service-sms)
- [Front-End Web and Mobile](#front-end-web-and-mobile)
  - [Summary](#summary-16)
  - [AWS Amplify](#aws-amplify)
  - [AWS Device Farm](#aws-device-farm)
  - [Amaaon Pinpoint](#amaaon-pinpoint)
- [Machine Learning](#machine-learning)
  - [Summary](#summary-17)
  - [Analyzing Text using Amazon Comprehend, amazon Kendra, and Amazon Textract](#analyzing-text-using-amazon-comprehend-amazon-kendra-and-amazon-textract)
  - [Predicting Time-series Data using Amazon Forecast](#predicting-time-series-data-using-amazon-forecast)
  - [Protecting Accounts with Amazon Fraud Detector](#protecting-accounts-with-amazon-fraud-detector)
  - [Working with Text and Speed Using Amazon Polly, Amazon Transcribe and Amazon Lex](#working-with-text-and-speed-using-amazon-polly-amazon-transcribe-and-amazon-lex)
  - [Analyzing Images via Amazon Rekognition (important)](#analyzing-images-via-amazon-rekognition-important)
  - [Amazon SageMaker to Train Learning Models](#amazon-sagemaker-to-train-learning-models)
    - [Summary](#summary-18)
  - [Amazon Translate](#amazon-translate)
- [Media (not in the exam yet)](#media-not-in-the-exam-yet)
- [Summary overall](#summary-overall)
- [Load Balancer](#load-balancer)

## AWS Fundamentals
Key Services to Know

**Compute**
1. EC2
2. Lambda
3. Elastic Beanstalk

**Storage**
1. S3
2. EBS - (Elastic Block Store) virtual hard disk we attach to VM
3. EFS
4. FSx
5. Storage GW

**Databases**
1. RDS
2. DynamoDB
3. Redshift - database warehousing tech

**Networking**
1. VPCs
2. Direct Content
3. Route 53
4. API GW
5. AWS Global Accelerator

---
## (IAM) Identity and Access Management 

### Chapter Summary
IAM manages users and their level of access to AWS console. the basics:   

1. IAM Policy Document - should be able to read
2. IAM is Universal - it does not apply to regions at this time
3. Root Account - This is the account created when you 1st setup your AWS account and it has complete admin access. Secure it ASAP and do not use it to log in day to day
4. New User - No permissions when 1st created.
5. IAM Federation 
   1. you can combine your existing user account with AWS, 2 provider type, SAML and OpenID
   2. OpenID, including Activate Directory, Fb, linkedin, etc.
   3. SAML standard, which is Active Directory, 
      * if you want to use the same SSO (Single Sign On) you use to login to your windows environment in order to access to AWS management console, then add identity provider -> select SAML
6. The best practice for users to **inferit permissions** from groups
  * User
  * Group 
  * Roles           
7. ARN - Amazon Resource Name, uniquely identifies any resource in AWS.
User can be organised in Groups of people. Policy is a set of JSON documents with the permissions. Policies can be grouped in **Roles**. We can create new roles as needed. Then either **Users** or **Groups** can be attached to **Policies** or **Roles**

**How to create a Role?**
1. IAM -> Roles -> Create Role
2. Choose the service that will use this role
3. attach policies

* Roles are more secure thant storing your access key and secret access key on individual EC2 instatnces
* Roles are easier to manage
* Roles cane be assigned to an EC2 instance after it is created using both console and command line
* Roles are universal - you can use them in any region

---
## S3
Secure, durable, high-scalable object storage. 

### Chapter Summary
* Object based 
  * Key: An object is a key (the name), 
  * Value (the content of the file in bytes)
  * a version ID (important for versioning)
  * some metadata and other subresources (like access control lists and torrent).
* Files can be from 0 Bytes to 5 TB
* There is unlimited storage
* S3 is universal namespace- all AWS accounts share the S3 namespace. Each S3 bucket names is globally unique.
  * S3 URLs - https://**bucke-name**.s3.region.amazonaws.com/key-name
* Security
  * Buckets are private by default - you have to allow public accesss on both **bucket** and **objects** in order to make the bucket public
  * Object ACLs - you can make **individual objects** public using object ACLs [Controlling Subnet Traffic with Network ACLs](#controlling-subnet-traffic-with-network-acls)
  * Bucket Policies - you can make **entire buckets** public using bucket policies
* Lifecycle Management - it allows to move your object in different tiers depending on the activity and time windows to save up money. It also can be used to configre expiration. e.g., change current vison to different storage tier, or permanently delete noncurrent versions of objects
* S3 can be used as static web hosting**
  1. Static Content - use S3 to host static content only (not dynamic)
  2. Bucket Policies - make entire buckets public using bucket policies 
  3. Automatic Scalling: s3 scales automatically with demand.
* S3 versioning: keep obj save**
  1. All versions - all versions of an object are stored in s3. this includes all writes and even if you delete an object.
  2. Backup - can be a greate backup tool
  3. Cannot be disabled - once enabled, versioning cannot be disabled, only suspended.
  4. Lifecycle Rules - can be integratdd with lifecyle rules
  5. Supports MFA
* S3 storage Classes tires (come up an awful lot in the exam)
  * S3 IA (Infrequent Access) - infrequently accessed but requires rapid access. Lower fee than standard, but you are charged for retrieval fee
  * S3 OZ (One Zone) - Infrequently Accessed and do not require the multiple AZs, lowest option
  * S3 Intelligent Tiering - Use Machine learning to configure the objects around storage classes to the most cost-effective option
  * S3 Glacier - for data archiving. Secure, durable, low-cost storage. Retrieval time configurable from mins to hours
  * S3 Glacier Deep Archive: same as above but retrieval times of 12 hours

| Storage Class                 | Availability and Durability              | AZs | Use Case                                                                                                                   |
|-------------------------------|------------------------------------------|-----|----------------------------------------------------------------------------------------------------------------------------|
| S3 Standard                   | 11 9's Availability and Durability       | >=3 | Suitable for most workloads  e.g., websites, content distribution, mobile, gaming applications and bigdata analytics       |
| S3 Standard-Infrequent Access | 11 9's Availability and Durability       | >=3 | Long-term, infrequently accessed critical data (e.g., backups, data store for disaster recovery files, etc)                |
| S3 One Zone-Infrequent Access | 99.5% Availability and 11 9's Durability | 1   | Long-term, infrequently accessed, non-critical data                                                                        |
| S3 Glacier                    | 11 9's Availability and Durability       | >=3 | Long-term data archiving that occasionally needs to be accessed within a few hours or mins                                 |
| S3 Glacier Deep Archive       | 11 9's Availability and Durability       | >=3 | Rarely accessed data archiving with a default retrieval time of 12 hours (e.g., financial records for regulatory purposes) |
| S3 Intelligent-Tiering        | 11 9's Availability and Durability       | >=3 | Unknown or unpredictable access pattern                                                                                    |

* S3 [Lock](#s3-lock)
* S3 [Encryption](#s3-encryption)
* S3 Performance [Optimization](#optimizing-s3-performance)
* S3 [Replication](#s3-cross-region-replication)
* S3 [Transfer Acceleration](#s3-transfer-acceleration)

**S3 Standard**
1. high avilabiltiy and durability
2. designed for frequent access
3. suitable for most workloads.
   * use case include websites, content distribution, mobile and gaming app, and big data analytics.

**Securing data**
1. Server-side encryption
2. Access control list (ACLs)
3. Bucket Polices


**S3 storage tiers**
1. S3 standard - >=3 AZ(s), suitable for most workloads.
2. S3 standard-infrequent access - >=3 AZ(s) long-term, infrequently accessed critical data, e.g. backups.
3. S3 one zone-infrequent access - 1 AZ, long-term, infrequently accessed, non-critical data.
4. S3 intelligent-tiering - >=3 AZ(s), unknown or unpredictable access partterns.
5. S3 Glacier Instatnt Retrieval - >=3 AZ(s), provides long-term data archiving with instant retriveval time for your data.
6. S3 Glacier Flexible Retrieval - >=3 AZ(s), ideal storage class for archive data that does not require immediate access but need the flexibility to retrieve large sets of data at no cost, such as backups
7. S3 Glacier Deep Archive - >=3 AZ(s) Cheapest storage class and designed for customers that retain data sets for 7-10 years or longer to meet customer needs and regulatory compliance requirements. standard retieval time is 12 hours.

### S3 lifecycles
1. Automates moving objects between different storage tiers.
2. Can be used in conjection with versioing
3. can be applied to current versions and pervious versions.


### S3 Lock
1. **WORM** model, use **S3 Object Lock** to store objects using `write once, read many (WORM)` model
2. Object lock can be on individual objects or applied across the bucket as a whole
3. Object Lock comes into 2 models: `governace mode` and `compliance mode`.  
   1. `Governace mode` - users can't overwrite or delete an object version or aler its lock settings unless they have special permissions.
   2. `Compliance mode` -  a protected object version can't be overwirtten or deleted by any user under `retention period`.
      1. `Retention periods` - protects an object version for a fixed amount of time.

`Glacier Vault Lock` - allows you to easily deploy and enforce compliance controls for individual S3 Glaciers vaults with a vault lock policy. essentially, `Glacier vault lock` is a way of applying a WORM model to Glacier.


### S3 Encryption
* Types of Encryption
  1. Encryption Transit
        1. SSL/TLS
        2. HTTPS
  2. Server-Side Encryption
    1. SSE-S3: S3-manged keys, using AES 256-bit encryption
    2. SSE-KMS (keep in mind the KMS limits)
    3. SSE-C: Customer-provided keys
  3. client-Side Encyption
* Enforcing Server-Side Encryption
  1. console - select the encryption setting on S3 Bucket. 
  2. Bucket Policy - A bucket policy can deny all PUT requests that don't include the `x-amz-server-side-encryption` parameter in the request header.



### Optimizing S3 Performance
1. by spreading reads across different `prefixes` (folders&subfolders under a bucket), in another word, `to create more folders under a bucket`
2. upload - Using `multipart uploads` to increase performance when uploading files to s3, if the file is `over 100MB` and must be used for any file `over 5GB`
3. download - Use `S3 byte-range fechtes` to increase performance when downloading files from S3.


### S3 Cross Region Replication
In order to replicate your data in different regions.

1. Create bucket
2. Go to Management and Replication
3. Enable versioning (it must be enabled in both source and destination)
4. Set Source and Destination
5. Configuration options: select/create the role
Files in an existing bucket and delete markers (or versions) are not replicated automatically (AWS will ask you to create a batch operation job to replicate existing files). It only works for new files.

### S3 Transfer Acceleration
Amazon S3 Transfer Acceleration enables fast, easy, and secure transfer of files over long distances between your end users and an S3 bucket. It takes advantage of Amazon CloudFront’s globally distributed edge locations: as the data arrives at an edge location, data is routed to Amazon S3 over an optimized network path.


---

## Elastic Compute Cloud (EC2) 


### Chapter Summary
1. should know how to select best pricing for your EC2, check [ec2-pricing](#pricing-options)
2. security group? check [here](#security-groups-and-bootstrap-scripts)
3. user data v.s metadata? 
   * user data: are simply bootstrap scripts
   * metadata: is data about your EC2 instances, you can use bootstrap script(user data) to access metadata 
4. choose the correct networking device, ENI v.s EFA v.s Enhanced Networking? check [here](#networking-with-ec2) 
5. placement groups? check [here](#optimizing-with-ec2-placement-groups)

### Pricing options
1. on demand 
   * description: pay by the hour or the second
   * use case: great for flexibility
2. reserved
   * description: reserved capacity for 1 or 3 years, up to 72% discount on the hourly charge  
   * use case: 
     * great if you have known, fixed requirements
     * applications with steady state or predictable usage
     * applications that requires reserved capacity
     * users able to male upfront payments to reduce their total computing costs even further
3. spot 
   * description:  enable you to bid whatever price you want for instance capacity. purchase unused capacity at a discount of up to 90%
   * use case: 
     * stateless, fault-tolerant or flexible applications, such as, big data, containerized workloads, CI/CD, high-performance computing (HPC), and other test and development workloads.
     * applications that have felxible start and end times
     * application that are only feasible at very low compute prices
     * users with urgent computing need for large amounts of additional capacity
4. dedicated
  * most expensive one
  * is a `physical server` with EC2  instance capacity fully dedicated to your use. Deicated Hosts allow you to  `use your existing` per-socket, per-core, or per=VM software `licenses`, including windows server, SQL server and SUSE Linux Enterprise Server.
  * great if you have server-bound licenses to reuse or compliance requirements
  * any question that talks about special licensing requirements, should use dedicated

### AWS Commandline

```console
# list s3 bucket
aws s3 ls

# make s3 bucket 
aws s3 mb s3://${bucket_name}

# s3 upload file to bucket
aws s3 cp ${your_file} s3://${bucket_name}

```
### Roles
1. The preferred Option - Roles are preferred from a security perspective
2. Avoid Hard-Coding your Credentials - Roles allow you to proviede access without the use of access key IDs and secret access keys
3. Policies - Policies control a role's permissions.
4. Updates - You can update a policy attached to a role and it will take immediate effect
5. Attaching and Detaching - you can attach and detech roles to running EC2 instances without having to stop or terminate those instance.


### Security Groups and Bootstrap Scripts

**Security Group** - `vertual firewalls for your EC2 instance`, by default everything is blocked. In order to be able to `communicate to your EC2 instances vis SSH/RDP/HTTP`, you will need to open up the correct ports. 

1. changes to security groups take effect immediantly
2. you can have any number of EC2 instances within a security goup
3. you can have multiple security goups attached to EC2 instances
4. all inbound traffic is blocked by default
5. all outbound traffic is allowed
6. we cannot configure with deny rules, only allows rules (to block IP addresses, we nned to use Network Access Control List (ACL))


**Bootstrap Scripts** - A script that runs when the instance first runs. here is an example

```bash

#!/bin/bash
yum install httpd -y

yum service httpd start

```
paste the scripts under `Advanced Details/User date` As Text.



### Metadata & User Data
* user data is simply bootstrap scripts
* metadata is data about your EC2 instance
* you can use bootstrap scripts (user daa) to access metadata 

here is an example 

```bash

#!/bin/bash
yum update -y
yum install httpd -y


service httpd start
cd /var/www/html
echo "<html><body><h1>IP IS" > index.html
curl http://169.254.169.254/latest/meta-data/public-ipv4 >> index.html
echo "</h1></body></html>"

```


### Networking with EC2

1. ENI - Elastic Network Interface
	> for basic networking, perhaps you need a seperate management network from you production network or a seperate logging network, and you need to do this at a low cost. In this scenario, use multiple ENIs for each network.
2. EN - Enhanced Networking 
	> for when you need speeds between 10 Gbps and 100 Gbps. Anywhere you need reliable, high througput
3. EFA - Elastic Fabric Adapter
	> for when you need to accelerate `high performance computing (HFC)` and machine learning applications or if you need to do an OS-bypass. if you see a scenario quetion mentioning HPC or ML and asking what network adapter you want, choose EFA.
  * keywords: High performance computing (HPC) and Machine learning


### Optimizing with EC2 Placement Groups
placement groups - a logical grouping of EC2 instances.

1. Cluster Placement Group - `Grouping of instances within a single AZ`, Recommended for applications that need low network latency, high network throughput, or both. Fact, only certain instance types can be lauched into a cluster placement group.
	> keys: low network latency , high network throughput.
2. Spread Placement Group - a group of instances that are `each placed on distinct underlying hardware.`, Spread placement groups are recommended for applications that have a small number of critical instances that should be kept seperate from each other, used for individual instances. 
	> keys: individual critical EC2 instances
3. Partition Placement Group - each partition placement group has its own set of racks. Each rack has its own network and power source. No 2 partitions within a placement group share the same racks, allowing you to isolate the impace of hardwre failure within your application. Used for multiple instances.
	> keys: multiple EC2 instances; HDFS, HBase and Cassandra


1. A `cluster placement group` can't span multiple AZs, whereas a spread placement group and partition placement group can.
2. Only  `certain types of instances` can be launched in a placement group (compute optimized, GPU, memory optimized, storage optimized)
3. `AWS recommends homogenous intances` within cluster placement groups
4. you cannot merge placement group
5. you can `move an exiting instance into a placement group`, before you move the instance, the instance must be in the stopped state. you can move or remove an instance using the AWS CLI or AWS SDK, but you cannot do it via the console yet.
   
---

## Elastic Block Storage (EBS) and Elastic File System (EFS)
Storage volumes you can attach to your EC2 intances


### Chatper Summary
* Storage Options Use Caseses (important)
  * S3 - used for serverless object storage
  * Glacier - everytime your seee `Archiving` object, it would be a glacier question 
  * EFS - Network File System (NFS) for Linux instance. Centralized storage solution acrosss multiple AZs
  * FSx for Lustre - File storage for high performance computing Linix file systems
  * EBS Volumes - Persistent storage for EC2 instance
  * Instance Store - Ephemeral storage for EC2 instances.
  * FSx for windows - File storage for Windows instances. Centrialized storage solution across multiple AZs.
* EBS is persistent storage volumes for EC2
* You can create an EBS volume as **encrypted** and then also any `snapshot` taken of that volume will therefore be encrypted as well.
* how to encrypt volumes? (important), [here](#ebs-ecryption)
* Types of EBS
  * ssd - [here](#ssd)
  * hdd - [here](#hdd)
* EBS Volumne and Snapshots
  * volumes exist on EBS, whereas snapshot exits on S3
  * snapshots are point-in-time photographs of volumes and are incremental in nature
  * the 1st snapshot will take some time to create. For consistent snapshots, stop the instance and detach the volume
  * you can share snapshots between AWS accounts as well as between regions. but first you nedd to copy that snapshot to the target region
  * you can resize EBS volumes on the fly as well as changing the volume types.
* EBS v.s Instance Store
  1. Intance store volumes are sometimes called `ephemeral storage` (data only persists for the lifetime of the instance it's attached to)
  2. Instance store volumes `cannot be stopped`, if the underlying host fails, you will lose your data
  3. EBS-backed instance `can be stopped`, you will not lost the data on this instance if it's stopped
  4. you can reboot EBS and instance store volumes and you will `not lose your data`
  5. By default, both root volumes will be **deteted on termination**. However, with EBS volumes, you can tell AWS to keep the root device volume.
  6. An Amazon Machine Image AMI is just a blueprint for an EC2 instance.
* EFS [here](#efs)
  * if you have a scenario-based question around `highly scalable shared storing using NFS`, think EFS
* In the exam you'll be given different scenarios and asked to choose whether you should use `EFS`, `FSx for windows` or `FSx for lusture`
  * EFS - when you need distributed, highly resilient storage for Linux intances and Linux-based applications
  * Amazon FSx for Windows: When you need centralized storage for windows-based applications, such as SharePoint, SQL Server, Workspaces, IIS Web Server or any other native Microsoft application
  * Amazon FSx for Lustre: when you need high-speed, high-capacity distributed storage. This will be for applications that do high performace computing (HPC), financial modeling, etc. Remember that FSx for Lustre can store data directly on S3
* AWS Backup

### EBS
1. production workloads - designed for mission-critical workloads
2. high-available - automatically replicated within a single AZ to protect against hardware failures.
3. scalable - dynamically increase capcacity and change the volumn type with no downtime or performance impact to your live systems.

#### SSD
* General Purpose SSD (GP2) 
  * a balance of price and performance, 
  * suitbale for boot disk, can be used for most workloads
  * up to 16k IOPS (IOPS. IOPS are a unit of measure representing input/output operations per second.)
* General Purpose SSD (GP3) 
  * the top performance of gp3 is 4 times faster than max throughput of gp2 volumns
  * suitbale for high performance application
  * 3000 IOPS
* Provisioned IOPS SSD (IO1) 
  * high performance option and the **most expensive**
  * faster than GP3
  * designed for I/O-intensive applications, large database and latency-sensitive workloads.
  * commonly used for **database**

#### HDD
* Throughput Optimized HDD (ST1) 
  * magnetic storage
  * low-cost hdd volumn, and **cannot be a boot volumne**
  * typically used for **big data, data warehoueses and log processing**
* Cold HDD (sc1) 
  * **lowest-cost** hdd volumn, for apps that need the lowest cost and performance is not a factor. and **cannot be a boot volume.**
  * common use could be for **file server**

#### Volumnes and Snapshots

1. Location - EBS volumes will always be in the same AZ as EC2
2. Resize - resize on fly, do not need to stop or restart the instance
3. Volume Type - switch volume types on fly. 

##### Keys
1. volumes exit on EBS, whereas snapshots exits on S3
2. snapshots are point-in-time photographs of volumes and are incremental in nature.
3. the 1st snapchat take some time to create. for consistent snapshots, stop the instance and detach the volume.
4. you can share the snapshots between AWS accounts as well as between regions. but first you need to copy that snapshot to the target region.
5. you can resize EBS volumes on the fly as well as changing the volume types.


#### EBS Ecryption
how to encrypt volumes
1. `create a snapshot` of the unencrypted root device volume
2. create a `copy` of the snapshot and select the `encrypt option`
3. create an `Amazon Machine Image AMI` from the encrypted snapshot
4. use that AMI to `launch new` encrypted instances


#### EC2 Hibernation
1. ECw hibernation perserves the in-memory RAM on persistent storage (EBS)
2. much faster to boot up because you do not need to reload the operating system
3. Instanct RAM must be less than 150GB
4. Instances can't be hibernated for more than 60 days.
5. Available for on-demand instances and reserved instances.


### EFS
1. supports the network file system version 4 (NFSv4) protocol
2. only pay for the storage you use
3. can scale up to petabytes
4. can support thousands of concurrent NFS conntions
5. data is stored acorss multiple AZs within a region
6. read-after write consistency


### FSx
when you need cnetralized storage for windows-based application, e.g., sharpoint or sql-server.

### AMI - Amazon Machine Images 
provides the information required to launch an instance. you must specify an AMI when you launch an instance.


---
## Databases

### Chapter Summary
* RDS is for `OLTP` (online transaction processinng workloads)
* RDS is not suitable for `OLAP` (online anylytics processing)
* Read Replica [here](#read-replica)
* Read Replica v.s Multi-AZs ? (senario-question)
  * Read Replica
    * a `read-only` copy of your primary database in the same AZ, cross-AZ, or cross-region
    * used to increas or scale read performance
    * great for read-heavy workloads and takes the load off your primary database
  * Multi-AZs 
    * an exact copy of your production database in another AZ
    * used for `disaster recovery`
    * in the event of failure, RDS will automatically failover to the standby instance
* Aurora Serverless Use case - Aurora Serverless provides a relatively simple, cost-effective, option for infrequent, intermittent, or unpredictable workloads.
* DynamoDB [here](#dynamodb)
* DynamoDB Transactions [here](#dynamodb-transactions)
  * if you see any scenario question that mentions ACID requirements, think `DynamoDB transaction`
* DynamoDB Stream
![vpc](https://github.com/YansenMa/image-hosting-repo/raw/main/dynamodb-stream.png)
* if you want to add redundancy to DynamoDB -> turn on global table (in order to turn on global table, you should turn on DynamoDB stream)
* MongoDB to AWS? 
  * MongoDB on-premises -> AWS Database Migration service [here](#aws-database-migration-service-dms) -> Amazon `DocumentDB`
* if you want to migrating big data Cassandra cluster? think of AWS `keyspaces`
* `Naptune` is a distractor, if dont talking about `graph dabatase`
* `QLDB` (Quantum Ledger Database) is a distractor, if don't talk about `immutable database`
* if you see a senario question about where to store large amount of time-series data for analysis? -> `TimeStream`

### Read Replica
* A `read replica` is a read only copy of the primary rdb, and it great for read heavy workloads and takes the load off your primary rdb.
* read replica can be cross AZs or cross-region
* each read replica has it's own DNS endpoint
* read replica can be promoted as its own databases, this breaks the replication
#### Keys 
1. It scaling read performance, `not` for disaster recovery
2. Requires `automatic backup`. - automatic back must be enabled in order to deploy a read replica   
3. Multiple read replica are supported.
  * allow you to add up to 5 read replicas to each DB instance

### DynamoDB
#### DynamoDB Basis 
1. Stored on SSD Storage
2. Spread across 3 geographically distinct data centers
3. eventaully consistent reads (default)
   * consistency across all `copies of data is usually reached within a sec`, repeating a read after a short time should return the updated data. Best read performance.
   * reads are fast but there is no guarantee 
4. Strongly consistent reads
    * A strongly consistent read `returns a result that reflects all writes` that received a successful reponse prior to the read.
    * you have a guarantee of consitency but the trade off is higher latency

#### DynamoDB Transactions
* multiple `all-or-nothing` operations
* 3 options for reads:
  * eventual consistency
  * strong consistency
  * transactional
* 2 options for writes：
  * standard
  * transactional
* DynamoDB transactions provide `atomicity, consistency, isolation and durability (ACID)` across one or more tables within a single AWS account and region

#### DynamoDB On-demand backup and restore
1. full backups at anytime
2. Zero impact on table performance or availability
3. Consistent within seconds and `retained until deleted`
4. Operates within same region as the source table.

#### Point-in-Time Recovery (PITR)
1. protects against accidental writes and deletes
2. Restore to any point in the last 35 days
3. Incremental backups
4. Not enabled by default 
5. Lstest restorable: 5 mins in the past


#### Taking your Data Global with DynamoDB Streams and Global Tables
**Managed multi-master, multi-region replication**
* globally distributed applicatiions
* based on dynamoDB streams (streams should be enabled)
* multi-region redundancy for disaster recovery or high availability
* no application rewrites
* replication latency under 1 sec.

### Operating MongoDB-Compatible Database in Amazon DocumentDB
how to migrating mongoDB from on-premises to AWS
1. MongoDB on-premises
2. AWS Database migration service
3. Amazon DocumentDB

### Runing Apache Cassandra workloads with Amazon Keyspaces
`Canssandra` - a distributed database (it runs on many machines) that uses NoSQL. it's primarily used for bigdata solutions. 

`Keyspaces` - Amazon's Apache Cassandra database service. it allows you to run Cassandra workloads on AWS and it a fully managed database service.


### Implementing Graph Databases using Amazon Neptune
`Graph DB` - a graph database stores nodes and relationships instead of tables or documents.

`Amazon Netpune` - graph database service

### Lerveragubg Amazon Quantum Ledger Database (QLDB) for ledger Databases

`ledger database` - a NoSQL database that is immutable, transparent, and has a cryptographically verifiable transaction log that is owned by on authority. you cannot update a record in a ledger database, instead, an update adds a new record to the database.

`QLDB` - a fully managed ledger database in AWS

#### Analyzing Time-series Data with Amazon Timestream
`Time-Series Data` - data points that are logged over a series of time, allowing you to track your data. Examples could be temperature readings from weather station around the world, on hour every hour for years.

`Amazon timestream` - amazon time-series database 



---
## Virtual Private Cloud (VPC) Networking

### Chapter Summary
* Basics
  * Think of VPC as a logical data center in AWS
  * Consists of  
    * `Internet GW` or `virtual private GW`, 
    * `route tables`, 
    * `network access control lists`, 
    * `subnets`
    * `security group`
  * 1 subnet is always in 1 AZ
* Network Address Translation (NAT) Gateway [here](#using-nat-gw-for-internet-access)
  * how instance in private subnet talk to internet? 
  * automatically assigned public IP address
  * [important] high availability with NAT GW, you can create an AZ independent architecture. 
    * if you have resources in multi-AZs and they share a NAT GW, in the event the NAT GW's AZ is down, resources in the other AZs lose internet access
    * to resolve the above issue and create an availibility zone-independent arch, This can be done by creating a NAT GW in each AZ and then configuring the routing to ensure resources in the same NAT GW are in the same AZ
* Security Group
  *  security goups are stateful = if you send a request from your instance, the response traffic for that request is allowed to flow in regardless of inbound security group rules
* Network ACL [here](#controlling-subnet-traffic-with-network-acls)
  * your vpc automatically comes with a default network ACL, and by default it allows all in-out traffic
  * custom network ACLs, by default, custom ACL denies all in-out traffic until you add rules
  * each subnet in your VPC must be associated with a network ACL
  * block IP addresses: Block IP using network ACLs, not security groups. (could be a senario question)
  * network ACL can be associated with many subnets, but a subnet can **ONLY** have one NACL
  * NACL are **stateless**, meaning they can have separate inbound and outbound rules, unlike with security group.
* Direct Connect
> AWS Direct connect is a cloud service solution that makes it easy to establish a dedicated network connection from your premises to AWS. Therefore, we can establish private connectivity between AWS and your datacenter, office. or colocation environment, which in many cases can reduce your network costs. increase bandwith throughput and provide a more consistent network experience than internet-based connections
  * Direct connect directly connects your data center to AWS
  * useful for high-throughput workloads (e.g, lots of network traffic)
  * help when you need a stable and reliable secure connection
  * ues case:
    * you've got a VPN connection, it keeps dropping out, you need a stable and reliable connection that can handle high-throughput, think Direct Connect.
* VPC Endpoints [here](#private-communication-using-vpc-endpoint)
  * use case? 
  * types?
* VPC Peering [here](#building-solutions-across-vpcs-with-peering)
  * VPC <-> VPC
* AWS PrivateLink [here](#network-privacy-with-aws-privatelink)
* AWS Transit GW - if you see a question about simplifying network topology, or they're talking about IP multicasting, think of Transit GW
* AWS Wavelength - if you see a scenario question about 5G, increasing application speed at edge using mobile networks, think AWS Wavelength
* How to setup your VPC?
  1. create VPC
      1. Go to VPC service in the AWS console, your VPC, create VPC
      2. File IPv4 CIDR block and tanacy and click on create
  > no subnets and internet gateways have been created.

  > route table, network ACLs and security group have been created

  > security group can't span VPCs.
  2. create subnet
    1. go to subnets -> create subnets
    2. name it, select the VPC creted in step 1, select availability zone and IPv4 CIDR block
    3. click on Create
  > By default, no subnet has public IP. in order to do this, select the subnet and click on actions and make it auto apply public IP

  > Amazon always reserve 5 IP addresses with your subnets.

  3. Create Internet GW
     1. Go to internet GW, create internet GW.
     2. Name it and click on create
     3. Select it and with actions, attach the internet GW to the VPC (only VPC can be attached to ONE internet GW)
  > At the moment, all our VPC are public because our routes allow it,  let's fix it.

  4. Create a public subnet
      1. Go to Route tables, select our route table and select `routes`,
      2. Edit Routes
      3. Fill destination (any IP) with target internet GW
      4. Go to subnet Association
      5. Edit subnet associations in order to select the subnet that need to be public  

  > now, we can't ssh-access to our private EC2 intance from our public subnet

  5. create ssh-access to private EC2
     1. Go to EC2 -> Security Groups -> Great Security Group
     2. Select the VPC, type `All ICMP` (protocol ICMP) and the source the public subnet
     3. Select the VPC, type `SSH` and the source the private subnet
     4. Change the security group of our EC2 instance

### Overview
![vpc](https://github.com/YansenMa/image-hosting-repo/raw/main/vpc.png)
![vpc_link](https://github.com/YansenMa/image-hosting-repo/raw/main/vpc_subnets.png)
A VPC is an **isolated network** you create in the AWS cloud, similar to a traditional network in a data center. When you create a VPC, you need to choose three main things.

1. The **name** of your VPC.
2. A **Region** for your VPC to live in. Each VPC spans multiple Availability Zones within the Region you choose.
3. **A IP range** for your VPC in CIDR notation. This determines the size of your network. Each VPC can have up to four /16 IP ranges.

as shown in the pic, a VPC consists of `gateways (or virtual private GWs)`, `route table` , `network acess control lists (ACL)`, `subnets` and `security group`. 

**one subnet is always in 1 AZ**
and 
**one internet GW per VPC**


### Using NAT GW for Internet Access
how the instance in the private subnet talk to internet?

![vpc_link](https://github.com/YansenMa/image-hosting-repo/raw/main/vpc_nat_gateway.png)


### Protecting your Resources using Security Group 

**Security Groups** 
1. are essentially the last line of defense,  
2. are `virtual firewalls for an EC2 instance`. By default, everything is blocked.
3. are `stateful` - if you send a request from your instance, the reponse traffic for that request  is allowed to flow in regardless of the inbound secuirty group rules.


### Controlling Subnet Traffic with Network ACLs
1. are first line of defense.
2. each subnet in your VPC must be associated with a network ACL.
   * default network ACL - allows all outbound and inbound traffic by default.
   * custom network ACL - you add rules, denies all outbound and inbound traffic by default.
3. Block IP Addresses: block IP addresses using network ACLs, not security group.
4. you can associate a network ACL with multiple subnets; however a subnet can be associated with `only 1 network ACL`.
5. Network ACLs are `stateless` - reponses to allowed inbound traffic are subject to the rules for outbound traffic (and vice versa)
6. Network ACLs contain a `numbered list of rules` that are evaluated in order, starting with the `lowest` numbered rule.
7. Network ACLs have `seperate` inbound and outbound rules, and each rule can either `allow or deny traffic`
![vpc_link](https://github.com/YansenMa/image-hosting-repo/raw/main/vpc_link.png)

### Private Communication Using VPC Endpoint
1. Use Case - when you want to connect AWS service without leaving the Amazon internal network
2. 2 Types of VPC Endpoints
   1. Gateway Endpoints: 
      1. similar to NAT GW, a gateway endpoint is a virtual device your provision. `support s3 and DyanmoDB`
   2. Interface Endpoints: 
      1. an elastic network interface with a private IP address that serves as an entry point for traffic headed to a supported service. They support a large number of AWS services. 

### Building Solutions across VPCs with Peering
1. **Allows you to connect** 1 VPC with another via a direct network route using private IP
2. **Transitive peering is not supported** - This must always be in a hub-and-spoke model
3. **you can peer between regions**
4. **No overlapping CIDR addres ranges**

### Network Privacy with AWS PrivateLink
1. if you see a question asking about peering VPS to tens, hundreds, or thousands of customer VPCs, think of AWS PrivateLink
2. Doesn't require VPC peering, no route tables, NAT GW, internet GW, etc.
3. Requires a Network LB on the service VPC and Elastic Network Interface (ENI) on the customer VPC.
VPC link connects API GW to LB


### Securing your Network with VPN Cloudhub
if you have multiple sites, and each with its own VPN connection, you can use AWS VPN Cloudhub to connect those sites together. It's similar to VPC peering in that it works on a hub-and-spoke model.

---
## Route 53
Route 53 is Amazon's DNS Service.

DNS record types:
1. SOA Records
2. CNAME records
3. NS Records (Name server records)
4. A records - fundamental type of DNS record, to translate the name of the domain to an IP address.


CNAME v.s Alias record 
* CCNAME - can be used to resolve one domain name to another. cannot be used for naked domain names.
* Alias Records - work like CNAME, but alias records are used to map resource record in your hosted zone to AWS resources always choose an alias record over a cname.

> ![vpc_link](https://github.com/YansenMa/image-hosting-repo/raw/main/Rout53-simple-routing-policy.png)

1. Simple Routing Policy
   * if you choose the simple routing policy, you can only have `one record with multiple IP addresses`. if you specify `multiple values in a record`, Route 53 retuens all values to the user in a random order.
2. Weighted Routing Policy
     * allows you to split your traffic based on different weights assigned.
3. Failover routing policy  
   * are used when you want to create an primary/secondary setup
4. Geolocation routing policy
   * letts you choose where your traffic will be sent based on the geographic location of your users 
5. Geoproximity routing policy 
   * Traffic Flow only
   * lets Amazon Route 53  route traffic to your resources based on the geographic location of your users and your resources
   * you can also optionally choose to route more traffic or less to a given resource by specifying a value, known as bias.
6. Lantency routing policy
   * allows you to route your traffic based on the lowest network latency for you end user. (i.e., which region will give them the fastest response)
7. Multivalue answer routing
   * lets you configure Amazon Route 53 to return multiple valus. such as IP addresses for your webservers in reponse to DNS queries.
   * simple routing policy + health check

---
## Elastic Load Balancing 

### Chapter summary
1. know the 4 type LB and use case
2. know what is Sticky Sessions, and use case
   1. Sticker sessions enable your users to stick to the same EC2 instance, can be useful if you are storing information locally to that instance
   2. you may see a scenario-based question where you remove an EC2 instance from a pool, but the load balancer continues to direct traffic to that EC2 instance, solution is to disable the sticky sessions
   3. you can enable sticky sessions for ALB as wll, but the traffic will be sent at the target group level.

### Application LB
Best suited for load balancing of HTTP and HTTPS traffic. They operate at layer 7 and are application-aware, and intelligent LB.
* **Listener** - checks for connection request from clients, using the protocol and port you configure.
* **Rules** - Determine how the load balancer routes requests to its registered targets, Each rule consists of a priority, one or more actions, and one or more conditiions
* **Target Group** - each target group routes requests to one or more registered targets, such as EC2 instances, using the protocol and port number you specify.
* **Limitation**: ALBs only support HTTP and HTTPS. 
* **HTTPS** to use an https listener, you must deploy at least one SSL/TLS server certificate on your load balancer. The load balancer uses a server certificate to terminate the frontend connection and then decrypt requests from clients before sending them to the targets.

### Network LB
Operating at the connection level (Layer 4) NLBs are capable of handling millions of requests per second, while maintaining ultra-low latencies. and Perfornace LB.

* **Ports and Protocols** - TCP, TLS, UDP, TCP_UDP, ports range: 1-65535
* **Use case** - are best suited for load balancing of TCP traffic where extreme performance is required. 
* NLB can decrypt traffic, but you will need to install the certificate on the load balancer.

### Gateway LB
watch for any questions about load balancers operating at layer 3 for inline virtual appliances, (don't come to exam much)

### Clasic LB
are the legacy load balancers, you can load balance HTTP/HTTPS applications and use Layer 7 specific featuers, such as X-Forwarded and sticky sessions. You can also use strict Layer 4 load balancing for applications that rely purely on the TCP protocol.
Can be used in test/dev lb

504 error means the gateway has timed out, application is not responding within the idle timeout period

Need the `IPv4 address` of your end user? - Look for the `X-Forwarded-For` header

**Sticky Sessions** - CLB route each request independently to the registered EC2 instance with the smallest load. Sticky sessions allows you to bind a user's session to a specific EC2 instance. This ensures all requests from the user during the session are sent to the same instance.

### Deregistration Delay
* enable deregistration delay: keep exiting connections open if EC2 instance becomes unhealthy
* disable deregistration delay: if you want you load balancer to immediately close connections to the instances that are de-registering or have become unhealthy.

---
## CloudWatch-·Monitoring 

### Chapter Summary
1. 'Cloudwatch is the main tool' for anything alarm related
2. not everything should go through cloudwatch. for example, you may get a senario-based questiont talking about watching for resource changes,use AWS Config
3. 'Know your intervals' the standard metric is delivered every 5 mins, while detailed monitoring delivers data every 1 min
4. cloudwatch logs is the place for logs, EC2, on-premises RDS, Lambda and CloudTrail can all integrate of this service
5. SQL? think about Cloudwatch logs insight. (high-level)
6. Real-time = Kinesis
7. Monitoring Container?
   1. `Grafana` might be best for visulization of container metrics. if you need an AWS-managed service for correlation and visualization of container or loT metrics, this is the best option
   2. `Monitoring container metrics at scala?` Think Amazon Managed Service for `Prometheus`. Leverage this service for any `Kubernetes-based metrics` monitoring at scale. It can be an Amazon EKS cluster or your own self-managed cluster.


there are no default alarms, anything you want to hear about must be created.
standard is 5 mins intervals whereas detailed is 1 min.

**CloudWatch logs**   
1. logs could go to cloudwatch logs if you want to process them and view them in a sort of real time (but not real time)
2. agent based - cloudwatch agent must be install and configured


**Amazon manged Grafana**
1. fully managed AWS service allowing secure data visulaizations for intantly querying, correlating, and visualizing your operational metrics logs and traces from different sources.
2. might be best for visualization of container metrics.

**Amazon manged Prometheus**
1. Serverless, Prometheus-compatible service uesd for securely monitoring container metrics at scale. 'Iot' devices monitoring.
2. monitoring container metrics at scale, leverage this service for any Kubernetes-based metrics monitoring at scale, it can be Amazon EKS cluster or your own self-managed cluster.

---
## High Availability and Scaling

### Chapter Summary
1. `Auto Scaling is ONLY for EC2`. No other service can be scaled using Auto Scaling. Other service might have a built-in option, but they aren't included in Auto Scaling groups.
2. `Get ahead of the workload`, Whenever possible, favor solutions that are predictive rather than reactive.
3. `Bake AMI (Amazon Machine Image) to reduce build time` You can avoid long provisioning times by putting everything in an AMI, This is better than using user data whenever possible
4. `Spread out`, make sure you're spreading your auto scaling over multi-AZs
5. `Steady state groups` allows us to create a situation where the failure of a legacy codebase or resource that can't be scaled can automatically recover from failure.
if you are asked to create a highly avlb solution for that legacy resource where you can't have more than one online at once
6. `ELBs are essentail`. Make sure you enable health checks from load balancers - otherwise, instances won't be terminated and replaced when they fail health check
7. Scaling Database?
   1. RDS has the most database scaling options
   2. horizontal scaling is usally preferred over vertical
   3. [Read replicas](#read-replica) are your frinds
   4. DynamoDB scaling comes down to access patterns.
      1. if you see a scenario-based question where the data is unpredicatable, access pattern spikes up and down, we cannot predict what we need, then we want to pick that on-demand option.

### Scaling EC2 
**What are we going to scaling with?** - A Launch Template, specifies all of the needed settings that go into building out an Ec2 instance. It's a collection of settings that you can configure so you don't have to walk through the EC2 wizard over and over.

**Where are we going to scale?** - Auto Scaling Group, it contains a collection of EC2 intances that are treated as a collective group for purposes of scaling and management
1. `Define your template`
2. `Networking and purchasing`, -using multiple AZs allows for high availability.
3. `ELB Configuration` 
4. `Set Scaling polices`
5. `Notifications` -SNS can act as a notification tool, allowing you to let someone know when a sacliing event occurs.

**When are we going to scale?** - Scale out Aggressively and scale in conservatively

### Scaling RDB
1. Read Rplicas - Read-heavy workload = Read replicas
2. Careful with Storage - RDS storage only scales up -it won't scale back down.
3. Vertical scaling
4. Multi-AZs - Unless it's a dev environment, turn is on.
5. Aurora Everything - Whenever possible, use Aurora if the situation calls for a relational DB.


### Scaling Non-Relational DB
1. provisioned capacity - predictable workload
2. on-demand - sporadic
3. switching between On-demand and Provisioned only once per 24 hours

---
## Decoupling Workflows 

### Chapter Summary
1. SQS
  1. `SQS can duplicate messages`, this is only once in a while, so if it's happening consistently, check for a misconfigured visibility timout or if the developer is failing to make the delete API call.
  2.  `Queues aren't bi-directional`, if you need communication to return to the instance that sent the msg, you'll need a second queue.
  3. `know the defaults`, it's important to understand the standard values for all SQS settings.
  4. `Nothing lasts forever`, messages stored in SQS can only persist up to 14 days.
  5. if the msg ordering important, make sure to select SQS FIFO
2. SNS
   1. proactive notification -> SNS
   2. cloudwatch loves SNS
3. API GW
   1. don't need to have in-depth understanding
   2. only need to know it acts as a secure front door to external communication coming into your env
4. AWS Batch
   1. long-running bacted workloads, anything related to batch workloads that long running (> 15mins, which is lambda limitation), then involve AWS Batch
   2. Queued worklods, if you see a question about batch workloads requiring queues, then think of AWS Batch
   3. On-demand alternative to AWS lambda: Questions regarding an alternative solution to AWS lambda due to runtime requirements could likely to involve the AWS Batch
5. AWS MQ
   1. managed messaging broker, if there is any mention of manged broker service, think of AWS MQ.
   2. RabbitMQ or ActiveMQ, any mention of these 2 tech means you should look for Amazon MQ within the answer
   3. Specific messsaging protocals: if you see messaging protocals like below, select Amazon MQ
      1. JMS
      2. AMQP 0-9-1
      3. AMQP 1.0
      4. MQTT
      5. OpenWire
      6. STOMP
6. Step Functions
   1. Serverless orchestration service: Any questions with this saying will likely involve Step Functions as the answer
   2. Different workflow decision requirements: whenever the solution requires different states or logic during workflows (like, condition checks, failure checks, or wait periods), think of Step Functions
7. AWS AppFlow
   1. for 3rd party SaaS data ingestion with AWS services.
   2. bi-directional

### Simple Queue Service (SQS)
A simple queue service which allows async processing of work
1. delivery delay - default is 0 can be set up to 15 mins
2. message size - messages can be up to 256 kb of text in any format
3. encryption - messages are encrypted in transit by default.
4. message retention - default is 4 days;
5. long v.s short - long polling isn't default, but should be 
6. queue depth - this can be a trigger for autoscaling

**Dead-Letter-Queues** - when a message in SQS queue reachs the retry limits, then the msg will be sent to DLQ (dead-letter-queue)
**FIFO** - gurantee order and no duplicates

**Standard v.s FIFO SQS**  
Standard
  1. best-effort ordering
  2. duplicate message
  3. nearly unlimited transactions per sec

FIFO
  1. guranteed order
  2. no message duplication
  3. 300 msg per sec.


### Simple Notification Service (SNS)
### API GW 

---
## Big Data 
### Summary 
Amazon Athena - data analyzation   
Amazon Redshit - data transformation   
Amazon QuickSight - data visualization 


1. Redshift and EMR
   1. while Redshift is a relational DB, it's not replacement of a traditional RDS
   2. Redshift supports single-AZ and mult-AZs deployment
   3. EMR make up of EC2, so you can employ your Ec2 instance cost-saving measures, like saving plans or reserved instances
2. kinesis is the only service with a !!REAL-time!! Response
3. SQS and kinesis can both be queues, SQS is easier and simpler, and Kinesis is faster and can store data for up to a year
4. `Serverless SQL = Athena`, query data in S3
5. `Glue is serverless ETL service`, it can help to create that schema for your data when paired with Athena
6. kinesis data stream v.s data firehose - key is one is real-time, one is near real time
7. need a dashboard or visualization of your data, go to Quicksight
8. opensearch is primarily used for analyzing log files and various documents or real-timme data like click stream, especially within an ETL process
9. Amazon OpenSearch service extreamly similar with Amazon Elasticsearch service (predecessor), think they are damn same shit
10. Data pipline
    1.  it's a managed ETL service in AWS
    2.  implement automated workflows for movement and transformation of your data
    3.  it itegrates with storages services (RDS, S3) and compute service (EC2, EMR)
    4. perfect for Data-driven and task-dependent ETL workloads 
11. Amazon Managed streaming for Apache Kafka (MSK)
    1.  aws managed apache kafka
    2.  it handles control plane operations (creation, updating and deletion)
    3.  your manage data plane operations
    4. push broker logs to Cloudwatch, S3 or kinese Data Firehose
    5. API calls are all logged to CloudTrail

### Redshift
Redshift - is a fully managed bigdata warehouse service in AWS, it's a very large relational DB traditionally used in big data app.

Redshit Spectrum - Efficiently query and retrieve data from Amazon S3 without having to loda the data into Amazon Redshift tables.

### EMR （Elastic MapReduce）
EMR Storage
1. Hadoop Distributed File System (HDFS)
2. EMR File System (EMRFS)
3. Local File System

### Kinesis
allows you to ingest, process, and analyze `real-time streaming data` 

1. kinesis data streams 
    - real-time streaming for ingesting data, but you're responsible for creating the sonsumer and  scaling the stream
2. kinesis data firehose 
   - data transfer tool to get information to s2, redshift, elasticsearch or splunk 

### Athena
an interactive query service that makes it easy to analyze data in S3 using SQL

### Glue
kinda serverless ETL
wille Athena can wor by itself, Glue can desin a schema for your data.

### QuickSight
Big data visualization service

Example

```bash

[AWS S3] ---> [AWS Glue Crawlers] ---> [AWS Glue Data Catalog] ---> [Athena] ---> [QuickSight]
						|
						|
						v
					[Amazon Redshift Spectrum]
```


`SPICE`: - Robust in-memory engine used to perform advanced calculations

### Moving Transformed Data Using AWS Data Pipeline

`AWS Data Pipeline` - is a managed `Extract, Transform, Load (ETL)` service for automating movement and transformation of your data.

**Popular use cases**
1. processing data in EMR using Hadoop streaming
2. Importing or exporting DynamoDB data
3. Copying CSV files or data between S3 buckets
4. Exporting RDS data to S3
5. Copying data to Redshift


**Exam Tips**
1. Managed ETL - managed AWS service for `ETL workflows` that automates `movements and transformations` of your data
2. Data Driven - Use `data-driven workflows` to create dependencies between tasks and activities
3. Storage Integrations - There are serveral integrations, including `DynamoDB`, `RDS`, `RedShit` and `S3`.
4. Compute Integrations - Easily integrate it with `Ec2` and `EMR` for managed compute needs.
5. Amazon SNS - Leverage `SNS for any failure notifications`. Use it for `sucesses` and `other event-driven workloads` as well.
6. Keywords - Anything related to `managed ETL services` and `automatic retries` for data-driven workflows.


### Implementing Amazon Managed Streaming for Apache Kafka (Amazon MSK)

**Exam Tips**
1. Apache Kafka - `Fully managed AWS service` for running and building Apache Kafka data streaming application
2. Control Plane - Service handles control-plane operations: creation, updating, and deletion of clusters.
3. Data Plane - Leverage the same `Apache Kafka data-plane operations` for producing and consuming data.
4. Automatic Recoveries - Service `detects and automatically mitigates` most of the common ffailures.
5. Encryption - Integrates with `Amazon KMS for SSE` needs. Uses `TLS 1.2 for in-transit` communications.
6. Logging - Push broker logs to `Cloudwatch, S3` or `Kinesis Data Firehose`. API calls are logged to `CloudTrail`

### Analyzing Data with Amazon OpenSearch Service

**Exam Tips**
Amazon OpenSearch Service loves logs
> if you are given a scenario on the exam that talks about creating a logging solution invloving visualization of log file analytics or BI reports, there's a good chance OpenSearch will be included.

### BigData Exam Tips

**Redshift&EMR**
1. `While Redshift is a relational DB` it's not a replacement for RDS in traditional application.
2. `Redshit supports single-AZ and multi-AZ deployment`, you can create multiple clusters in different AZs. Multi-AZ supports 2 AZs at one time. Converting to Multi-AZ requires us of an existing snapshot.
3. `EMR is made of EC2 instances`
4. `EMR for Apche Hadoop and Apache Spark`

**Kinesis, Anthena & Glue**
1. `Kinesis is the only service with a real-time response`. if the question asks for a real-time solution to prcessing or moving data, look for an answer that include Kinesis.
2. `SQS and Kinesis can both be queues`. Each service has its pros and cons. SQS is easier and simpler, and Kinesis is faster and can store data for up to a year.
3. `Serverless SQL means Athena`. Any time serverless SQL or querying data that is stored in S3 comes up, think Athena.
4. `Glue is a serverless ETL service`. It can help create that schema for your data when paired with Athena.

**QuickSight&OpenSearch Service**
1. `Creating Dashboard?` QuickSight is your go-to tool for visualizing data
2. `OpenSearch` is primarily used for analyzing log files and various documents. especially within an ETL process.
3. `Amazon OpenSearch Service` and Amazon Elasticsearch Service (predecessor) are extremely similar, and either may appear on the exam for the time being. They both follow the same concept.


**Data Pipeline**
1. it's a `managed ETL service` with AWS.
2. Implement `automated workflows` for `movement` and `transformation` of your data.
3. It integrates with `storage services (RDS, S3 etc)` and `compute services (EC2, EMR etc)`
4. `Data-driven` and `task-dependent ETL workloads` are perfect use case.

**MSK**
1. It's and `AWS managed` service for building and running Apache Kafka streaming applications.
2. The `service handles` control `plane operations` for you (creation, updating and deletion)
3. `You manage` data plane operations.
4. Push broker logs to `CloudWatch, S3 or Kinesis Data firehouse`
5. `API calls` are all logged to `CloudTrail`.


---
## Serverless Architecture

### Lambda
limitations:
1. 1000 concurrent executions
2. 512 MB - 10 GB disk storage (/tmp)
3. function can run up to 900 seconds
4. Compressed deployment pkg (.zip) size must be <= 50 MB
5. Uncompressed deployment pkg must be <= 250 MB
6. Request and response payload sizes up to 6 MB
7. Streamed reponses up to 20 MB.

lambda can run inside or outside a VPC (default)

### Leveraging the AWS Serverless Application Repo

### Container

**Exam Tips**
Containers are more flexible. On the exam, `containers are generally seen as more flexible.`

They are easier to run on-site and move around to different environments. if you see a senario that talks about any of these situations. pick an answer that includes containers.

### Running Containers in ECS or EKS
`ECS` - Amazon Elastic Container Service
`EKS` - Amazon Elastic Kubernetes Service

**Exam Tips**
1. ECS simple container orchestration service for deploying and managing docker containers
2. if you see container mentioned, you should think ECS
3. Genreally favor using AWS-deigned servers over 3rd parties (just choose the AWS managed one)
4. Anytime you see `open source` or `kubernetes` think EKS.
5. Both ECS and EKS great for long-running apps

### Removing Servers with Fargate
`Fargate` - AWS Fargate is a serverless compute engine for docker containers.
AWS owns and manages the infrastructure.
Requires use of ECS or EKS.

here are some differences between fargate and ec2
1. fargate - no operating sys acdess.
2. pay based on resource allocated an time ran
3. perfect for short-running tasks
4. ioslated environments per container (ec2 multiple containers can share the same host)

**Exam Tips**
1. should to know when to choose Fargate compared to Lambda or EC2
2. Serverless compute option via Amazon ECS
3. ECS or EKS is required, meaning Fargate doesn't work by itself.
4. Fargate can be more expensive, but easier to use, compared to the EC2 launch type.
5. Fargate is for containers and applications that need to run longer
6. You leverage ECS taks Role for assigning IAM permissions to the container.

### Amazon EventBridge (Cloudwatch Evnets)
it allows you to pass events from a source to an endpoint. essentially it's the glue thats holds your serverless application together.

Concepts:
1. Event 
2. Rules - Criteria used to match incomming events
3. Event Bus - A router that receives events and delivers them to targets.

**Exam Tips**
1. Think EventBridge if you want to trigger an action based on something that happened in AWS.
2. Common use case is triggering Lambda functions when AWS aPI call happens.
3. Be familiar with the possible rule configurations at high level.
4. This is Cloudwatch Event successor (tmd就是cloudwatch event 非特么整这么高级 SB)
5. This is the fastest way to repond to things happening in your env
6. Remember you can use a default bus or create a custom bus for cross-account access.

### Storing Custom Docker Images in Amazon Elastic Container Registry (Amazon ECR)
1. registry - A private registry provided to each AWS account; create one or more for image storage
2. Authorization Toke - required to push&pull images to and from registries
3. Repo - Contains all your Docker images, OCI images and OCI artifacts
4. Repo Policy - control all access to repos and images
5. Image

Amazon ECR Public is a similar service for public image repositories.

**Exam Tips** 
1. Container Image Storage - AWS-managed container image registry service
2. Supported Format 
   * Docker Image
   * OCI images
   * OCI-compatible artifacts
3. Lifecycle Policies - Rules defining when to expire and remove unused or older images
4. Image Scanning - Sacn on push repository setting allows for identifying software vunerablilities in your container images
5. Tag Mutability - Helps prevent image tags from being overwrittern
6. Keywords to Look For - Questions related to a manged container image registry, OCI repo or image integration with Amazon ECS and EKS

### *Using Open-Source Kubernetes in Amazon ELS Distro (EKS-D)

**Exam Tips** 
keywords - look out for questions related to `self-managed kubernetes deployments` that are similar to Amazon EKS
Uses - Use EKS-D when you need to run versioned deployment of `clusters outside of AWS-manged services`

this is similiar to EKS, but is fully managed by you, not AWS.

### Orchestrating Containers Outside AWS Using Amazon EKS Anywhere and ECS Anywhere 

**EXam tips**
EKS   
1. EKS Anywhere - not common, this service is not commonly featured on the exam, just fking ignore it.
2. Anywhere - based on the EKS Destro, it allows you to run EKS k8s clusters on-premises.
3. AWS Efficiency - Distro allows customers to maintain similar operational efficiency to Amazon EKS.
4. Managed by you.


ECS
1. Amazon ECS - feature within the Amzon ECS service itself.
2. Anywhere - it allows for AWS-managed container orchestration anywhere on-premises
3. Requirements - you must have SSM Agent, ECS agent and Docker installed
4. Register and Deploy - Execute scripts containing required steps and use the EXTERNAL lauch type.


### Auto Scaling Database On Demand with Amazon Aurora Serverless
**Exam Tips**
1. On demand - auto scaling version of Aurora database service, Capacity adjusted for you 
2. ACU - Aurora Capacity Unit, set min and max ACU for scaling needs. Billed per second for used resources only.
3. Popular Exam Scenarios - Variable workloads, new apps, capacity planning and development/testing needs.
4. Resilient - Data resiliency is the same as Aurora provisioned, 6 copies of data cross 3 AZs
5. Multi-AZ - implement multi-AZ deployment for highly avlb workloads. 

### Using AWS X-Rays for Application Insights
`Segments` - Data containg resource names, request details, and other information
`Subsegments` - Segments providing more granulaar timing information and details
`Service graph` - Graphical representation of interacting services in requests
`Traces`: Trace ID tracks paths of requests and traces collect all segments in a request
`Tracing header` - Extra Http header containing smapling decisions and trace ID

**Exam Tips**
`Application Insights` - Collects data for gaining insights to application request and response
`Important terms` - Traces, tracing headers, and segments
`Integrations` - Many AWS integrations avlb, suc as EC2, Lmabda, and API GW.
`Exam Keywords` - Scenarios involving app request insights, viewing response times of downstream resources, and HTTP reponse anaylysis.


### Deploying GraphQL Interfaces in AWS AppSync
AppSync - Real-Time Data Sync Using GraphQL for Mobile & Web Apps, Online or Offline

**Exam Tips**
1. Scalable GraphQL Interface - Service for scalable GraphQL interface for developers
2. Keywords - GraphQL, fetching app data, declarative coding and frontend app data fetching.

---
## Security
### DDos

***What is a DDos Attack?**   
A distributed Denial of Service (DDos) attack is an attack taht attempts to make your website or applicatiion unavailable to your end users.
This can be achievec by multiple mechanisms, such as large packet floods, by using a combintation of reflection and amplification techniques. or by using large 


***what is a layer 4 ddos attack?**   
A layer 4 DDos attack if often referred  t oas SYN flood. It works at the transport layer (TCP)

***what is a Amplification attack?**   
Amplification /reflection attacks can include things such as NTP, SSDP, DNS, CharGen, SNMP attacks, etc. This is where an attacker may send a 3rd party server (NTP for example) a request using a spoofed Ip address.


***what is a layer 7 attack?**   
a flood of GET / POST requests


### Logging API Calls with cloudtrail
CloudTrail: Auditing

AWS CloudTrail increases visibility into your user and resource activity by recording AWS Management Console actions and API calls. You can identify which users and accounts called AWS, the source IP address from which the calls were made, and when the calls occurred.

### Shield
Shield protects against layer3 (Network) and layer4 (Transport) attacks only

### WAF 
WAF - web application firewall, operates at layer7 (applicaiton layer).
use cases:
* WAF can block layer 7 DDos attacks as well as things like SQL injections and cross-site scripting. 
* if you need to block access to specific countries or IP addresses, you can also achieve this using AWS WAF.

### GuardDuty
is a threat detection service that uses machine learning to continuously monitor for malicious behavior (potenial bad requests or behavoir)

### Firewall manager
is a security management service in a single pane of glass. This allows you to centrally set up and manage firewall rules across multiple AWS accounts and application in AWS org
scenario about multiple AWS accounts and resources that need to be secured centrally.

### Macie
uses machine learning and pattern matching to discover sensitive data in s3, for example detects personally indentifiable information (PII)
macie has macie alerts can be sent to eventbridge.

### Inspector
vulunerability scan tool.
is an automated security assessment service that helps to improve the security and compliance of application deployed on AWS.
1. network assesement - network configs, for example port 22 open? why?
2. host assessment - vulnerable sw.


### AWS Keymanager (KMS) and CloudHSM
AWS Key management system (KMS) is a managed service. literally just a way of maning your encryption keys.

**CMK** - customer master key, is a logical representation of a master key, The CMK includes metadata, such as the key ID, creation date, description and key state.


**CloudHSM** 
AWS CloudHSM is a cloud-based HSM that enables you to easily generate and use your own encryption keys on the AWS Cloud.


**Exam Tips**
1. **AWS KMS** is a managed service that makes it easy for you to create an contral the encryption keys used to encrypt your data.
2. `you start using the service by requesting the creation of a CMK`
3. 3 ways to generate a CMK
  * AWS Creates the CMK for you. The key material for a CMK is generated with HSMs managed by AWS KMS
  > HSM - hardware secuirity module is a physical computing device that safeguards and manges digital keys and performs encryption and decryption functions.
  * import key material from your `own key management infrastructure` and associate it with a CMK.
  * have the key material generated and used in an AWS CloudHSM cluster as part of the custom key store feature in AWS KMS.
4. 3 ways to control permissions
   * key policy
   * IAM policies in combination with the key policy
   * use grants in combination with the key policy



### Secrets Manager
is a service that securely stores, encrypts and rotates your database credentials and other secrets

**important** if you enable rotation, secrets manager immediately rotates the secret once to test configuration

**Exam Tips**
1. Secrets manager can be used to securely store your application secrets: database credentials, API keys, SSH Keys password, etc.
2. Applications use the Secrets manager API
3. Rotating credentials is super easy, but be careful.
4. When enabled, Secrets manager will rotate credentials immediately
5. Make sure all your application instance are configured to use Secrets Manager ~before~ enabling credential rotation.

### Parameter Store
in exam, you will get scenario-based questions aksing if you should use Parameter Store or Secrets Manager, `if you are trying to minimize cost, choose Parameter Store`

if you need more than 10,000 parameters, key rotation, or the ability to generate password using CloudForamtion, use secrete manager.

### Presigned URLs or Cookies
if you see a scenario question where you need to share private file in your S3 bucket, think presigned URLs.

### Certificate Manager
1. in the exam, you will get scenario-based questions around SSL certificates and what services you should use to integrate SSL certificates
2. AWS certificate manager integrates with Elastic load balancing, couldfront, and api gateway
3. free service. automatically renew your ssl certificates and rotate the old certificates with new certificates with supported AWS service.

### Audit Manager
if you have a scenarios question about HIPAA or GDPR compliance that asks about continous auditing automating auditing reports. think AWS Audit Manager.

### Artifact
This comes up in the exam quite a bit and is often used as a distractor. you simply have to know what it is. See a scenario question asking about audits and the need for compliance reports, think AWS artifact.

### Amazon Cognito (important)

`User pools` are directories of users that provide sign-up and sign-in options for your application users.
`Identity pools` allow you to give your users access to other AWS services.

you can use identity pools and user pools either separately or together.

How it works:  
1. device  <-> user pool (Authenitcate and get tokens) 
2. device  <-> identity pool (exchange tokens and get AWS credentials) 
3. device <-> AWS Cloud (access AWS services using credentials)


[<64;60;21M### Amazon Detective (distrctor)
Detective operates across multiple AWS services and analyzes the `root cause` of an event.   
Do not confuse this with Inspector, which is an automated vulnerability management service that continually scans EC2 and container workloads for sw vulnerabilites and unintended network exposure.
Detective can be distractor

no `root cause`, ignore it.

### Network firewall
physical firewall protection across your VPCs

if you have a scenario question about filtering your network traffic bevore it reaches your internet gateway, or if you require intrusion prevention systems or any hadware firewall requirements.
think AWS Network Firewall.

### Secuirty Hub 
a single place to view all your security alerts
if you have a scenario question about a single place to view all your security alerts across multiple AWS secuirty services and accounts, Think Security Hub

---
## Automation
### Summary
1. **Understand Cloudformation sections**: While you don't have to be coding expert, you need to generally know what the parameters, mappings and resource sections of tyhe CloudFormation templates do.
2. **Immutable architecture is preferable**: Gnerally sparking, you'll want to select answers that favor having resources that can be replaced at any time. Stateless is better than stateful on the exam. 
3. **Mappings and Parameter Store**: can be useful to help makke your templates more flexible. Hardcoded IDs (AMI or snapshot ID) are a source of breakage.
4. **Elastic Beanstalk** is a one-stop shot for all things AWS. Questions looking for a simple soluiton to bundle and deploy applications should favor this over CloudFormation. 
5. **Automation Documents** are the primary method used in scenarios asking you to configure the inside of an EC2 instance.
6. **Don't go too Deep** on Systems Manager, While it has a lot of options, this text will focous on Automation document, Parameter Store, and possibley Session Manager.
### CloudFormation
1. cloudformation is perfect for creating immutable architecture
2. know the layout of a cloudformation template and what sections do
3. if it finds an error, cloudformation rolls back based on your configurations
4. cloudformation can easily create and destroy your entire arch
5. hard-coded values and resource IDs can be the reason templates fail to create
6. cloudformation makes the same API calls you make manually.

### Elasticbeanstalk (high level knowledge)
PaaS - Platform as a Service

### Systems Manager (Important)
AWS System manager is a suite of tools designed to let you view, control, and automate both your managed instances in AWS and on-premises

Important - you must be confortable with the AWS System Manager Agent (SSM Agent).

List of important Capabilities
1. Automation: Use predefined or custom playbooks (documents) to enable resource management.
2. Run Command: Remotely execute commands on managed compute without SSH or RDP
3. Patch Manager: Automates patching managed instances (OS patches and applications)
4. Parameter Store: Securely stroe your secrets and[<64;60;21M application configuration information
5. Maintenance Windows 
6. **Session Manager** - Securely connect to your manged compute without needing SSH access.

---
## Caching 

### Summary
1. **CloudFront is the only option** to add HTTPS to a static website being hosted in an S3 bucket.
2. **AWLAYS** favor answers that include caching.
3. **GA (Global Accelerator) is your friend** whenever the scenario talks about IP caching.

for database caching
1. if you see 'in-memory database', 2 solutions, redis and dynamo, if it has dynamo, pick that
2. Redis is the only one support backups, memcached and DAX not a source of truth for your data.

### CloudFront
A fast content delivery network (CDN) service that securely delivers data, videos, applications, and APIs to customers globally, it helps reduce latency and provide higher transfer speed using WAS edge locations.

* edge location - where content will be cached (using a TTL -time to live). we can clear cached objects, but we will be charged
* origin - origin of all the files that CDN will distribute. This can be an S3 bucket, and EC2, and elastic load balancer, or Route53
* distribution - collection of Edge locations
* types
  * web distribution, to route whole web
  * RTMP, use for media streaming.


Example:   
customer -> [CloudFront caches on edge location] -> S3 

1. cloudfront fixes all connection issuess. on the exam every sort of external customer performance issue cane be solved by putting CloudFront in front of your application
   1. slow connectivity from across the globe?
   2. image or videos aren't loading fast enough?
2. Speed - CloudFront main purpose is to cache content at the edge locations to speed up delivery of data.
3. On-site Support - This CDN works for both AWS and on-site arch
4. Blocking Connections - it can be used to block individual countries, but WAF is a better tool for it.
5. All the locations - you cannot pick specific edge locations for your deistributions

### ElasticCache & DAX
**ElasticCache** = `AWS managed version` of `Memcached` + `Redis`
> tips - if you need to pick a no-sql database, dynamo > redis > memcached

**DAX** - DynamoDB Accelerator
1. In-memory Cache, reduce dynamoDB response time **!CRAZYLY!** (milisec -> microsec)
2. Location, location, location - This chache is highly avlb and lives indside the VPC 
3. you re in Control - you determine the node size and count for the cluster, TTL for the data, and maintenance windows for changes and updates.
4. only for Dynamo

#### Summary
1. Always Cache - take the answer with a database caching solution
2. keep it high level
3. Redis can be a standlone database.

### Global Accelerator


short for (GA) is a networking service that sends your users' traffic through AWS's global network infrastructure via accelerators
it can increase performance and help deal with IP caching by leveraging Anycast IP addresses.

Meant for TCP or UDP traffic! major difference from CloudFront

#### Summary
1. any scenarios talking about IP caching, you'll want to think GA.
2. You are provided 2 anycast IP addresses 
3. understand Anycast IP traffic works
4. GA uses edge licaiton to help speed everything up
5. TCP & UDP traffice, e.g., gaming apps, IoT messaging. (different from CloudFront)

---
## Governance

### Summary
1. AWS Organization
   1. service control policies (SCPs) have the ultimate say as whether an API call goes through, The are the **only** way to restrict what the root account can do.
   2. Centralized logs are always the right answer. cloudtrail offers support to log everything into a single AWS account.
   3. Isolating workloads into sperate accounts is a great way to add more layers of secuirty and controls. Avoid answers that lump everything together.
2. AWS Config
   1. Standardizztion - anythime a 'rule' needs to be setup for an account, think about using Config to chekc for compliance.
   2. Automate the response - config offers the ability to automatically remediate problems using automation dcouments.
   3. know what changed - config is the one-stop shop to see what changed. It will provide you with a history of all your arch
3. Authenticaation
   1. user management requires the right tool. Make sure you're using AWS SSO for internal user management and Congito for external.
   2. Active Directory - is a common topic that should immediantely make you think Directory service. if it's a lift and shift, pick the managed Microsoft AD. If AD is staying on-premises, select AD Connector.
   3. Cross-account role access is always a better solution than creating unnecessary IAM credentials.
4. Cost Management
   1. Tracking costs, is a common exam topic. You'll want to use a combination of tags, cost-explorer and AWS budget
   2. Get ahead of problems by creating proactive alerts. When users get too the 80% threshold, tell someone via SNS/
   3. Automate the response. Spending too much money? shut something down. Always think about how you can remove the human interaction
   4. Detailed reports and exploring costs. These questions will usually involve AWS Cost and Usage Reports or Cost Explorer for in-depth reporting purposees.
   5. Use AWS Compute Optimizer to generate recommendations on implementing more accurate compute sizes based on your actual needs. 
5. Trusted Advisor
   1. it's free to use, but you'll need a business or enterprise support plan to get the most useful checks
   2. there are limits to Trusted Advisor. It's **Strictly** an auditing tool, and it **won't** solve the problem for you, This is a common trap the exam will set for you.
   3. Automate the response. Use EventBridge to kick off a lambda function to solve problem for you.
6. Accounts and Licenses
   1. AWS Control Tower can be used to implement compliance and account governance within multi-account environment using automated account setups
   2. Leverage preventive or detective guardrails with AWS Control Tower. They are implemented via SCPs and AWS config (respectively)
   3. AWS License Manager provides a simplified way to manage licenses from supported vendors to prevent license abuse and overcharges. It works in AWS and on-premises (not cloud specific).
7. Infrastructure and Deployments
   1. AWS Service Catalog allows end users to provision pre-apporved products and service vias shared catalog portfolios. These are written in CloudFormation
   2. AWS Proton can empower developers to automate the provisioning of their entire application stack for container-based or serverless architectures.
8. Well-Architected Tool - to document architectural decisions and their measurements against well-established industry best practices
9. AWS Health 
   1.  is a dashbaord and service meant to provide notifications of both public and account -specific within AWS
   2.  Questions about service alerts or notifications of EC2 hardware maintenance reboots will leverage AWS Health in some manner

### AWS Organization
#### Summary
1. Gentrally manage your multi-account AWS designs in a hierarchical manner
2. SCPs are the best way to have th final say in what you can do in your AWS acount
    > Service Control Policies (SCPs), json policies that get applied  to OUs or accounts to restrict actions that are or are not allowed  (important) 

    > SCPs do not affect the management account
3. Consolidated billing can easily roll up to a single account for payment
   > Consolidated billing - rolls all bills up to the payer account, Single payment method
4. RIs and Saving Plans can be shared across accounts within the organization
5. It's important to know you can designate a single AWS account to hold your CloudTrail logs
    > Create a centralized logging account for organizational CloudTrail logs.
6. Konw when to leverage AWS organizations and how OU management works
   > Organizational Unit(OU) - logical grouping of multiple accounts to allow for easy management and speration.


### AWS Resource Access Manager (RAM)
free service allows you to share AWS resources with orther accounts inside or outside your orgnazation.
1. Use AWS RAM to easily share resources across AWS accounts
2. Sharing resources means you do not have to recreate them each time
3. AWS RAM is free to use, but you pay for the resources that are being shared.
4. Remember that RAM easily allows organizations to share componenets
5. knows share VPC resources v.s pering VPCs
6. Rember that participants cannot modify the shared resources. 


### AWS Cross-account role Access
1. this solutions provides a secure method of cross-account access.
2. no need for long-term access keys or IAM users. Instead, we get rolling, temporary credentials that be can be revoked as needed.
3. anytime temp credentials are mentioned, scan the answer looking for roles
4. it's always preferred to create cross-account roles instead of `long-term` IAM users
5. use roles everywhere instead of users
6. you need to know you can set this up and how you can set this up.
7. any temporary employees should get role access only, avoid permanenet credentials (like acess keys)
8. Role assumption is temporary (credentials expire) 

### AWS Config
is a inventory management tool, it allows you to show the `configuration history` of your infrastructure over time. not free service.

1. (important) Configured per Region, results can be aggregated across Regions and AWS accounts.
2. (IMPORTANT) AWS config is NOT preventative, it provides visibility and alerting into resource config changes, it used to detect  non-compliance it can alert you for other deviations, however, it will not prevent configuration changes.
3. AWS Config is the best way to check what standards are applied to your arch
4. you can track previously deleted AWS resources using AWS config
5. You can automation documents and lambda to enforce your standards
6. you can roll up all your results to a single region (aggregation)


### Directory Service
AWS Directory Service is a fully managed version of Active Directory (AD)

1. know the uses - 2 types of Directory Service referenced on the exam, `ManagedMircosoft AD` and `AD Connector`


### Cost Explorer
use tags! tags are one of the most important way to track your spend


### AWS Budgets
1. you can create bugets using AWS buggets


### AWS Cost and Usage Report (CUR)
1. CUR stand for AWS Cost and Usage report
2. integrate with Athena, Redshift and quicksight.
3. Automatic report updates occur at least once a day


### AWS Compute Optimizer
1. Privides recommendations based on collected utilization and configuration metrics
2. Optimizer Resources - EC2, auto Scaling Groups, Lambda, and Amazon EBS.
3. Saving plans -flexible offering for pricing on AWS compute usage; similar to Reserved Instance

### AWS Trusted Advisor
1. used to checking your accounts, includes
   1. cost optimzation
   2. performance
   3. security
   4. service limits
   5. fualt tolerance
2. it works at an account level and makes recommendations based on our entire account
3. basic and develop support comes with limited free checks.
  
### AWS Control Tower
esay way to setup and maintain governacne in multi-AWS account environments
terms 
1. landing zon
2. guardrails
3. account factory
4. cloudformation stackset
5. shared aaccounts

#### Summary
1. Governance - esay way to setup and maintain governance in multi-AWS account Environments
2. Accounts - automate account deployment with preconfigured compliance rules
3. Shared Accounts 
   1. management account
   2. log archive account
   3. audit account
4. preventive Guardrail - leverage service control policies to prevent noncompliant actions
5. Detective Guardrail - leverages AWS config rules to detect and alert on vilating actions or changes
6. Keywords and Scenarios - Automated multi-account governance, guardrails, acoount orchestration, and governed user account provisioning


### AWS License manager 
a service making license management simpler and more efficient  
keywords 
1. Aws-hosted license management
2. Hybrid environment license management
3. Reventing license abuse

### AWS Health dashboard
1. gain visibility into service and resource health of your AWS resources and accounts
2. alerting
3. automate actions basd on events uisng Amazon Eventbridge   

keywords  
look out for questions about checking alerts for service health and automating the reboot EC2 instances for AWS maintenance.


### AWS Service Catalog & AWS Proton
AWS catalog - provides catalogs of preapproved services as CloudFormation templates, which allows end users to deploy the approved services into their own accounts

AWS Proton - offers laC provisioning and deployment of serverless/container archi, which enable developers to move faster with a self-service tool to provision infrastructure and manage code deployment


### AWS Well-Architected Framewaork (important)
the 6 pillars (important)
1. Operational Excellence
2. Reliability
3. Security
4. Performance Efficiency
5. Cost Optimization
6. Sustainability

#### Summary
1. AWS Well-architected tool - tool for measuring current workload againset established AWS best practice
2. Documentation - Aids in Documentation of workload and archi decisions

---
## Migration

### Summary
1. Snow Family
   1. snowcone and snowmobile (ignore)
   2. when to use snowball? - best used in situation where you have slow to no internet. Snowball is faster and more secure in these situations
2. Storage GW
   1. hybrid - anythime on-premises storage is brought up. think "which version of storage GW could complement this"
   2. out of space? - File GW is the perfect solution if you local network attached storage is full.
   3. it's a VM - Storage GW is run locally as VM on-premises  
3. DataSync and Transfer Family
   1. DataSync is an agent-based solution that excels at **one-time** migrations of file shared into AWS.
   2. EFS and FSx - are both viable locations for DataSync to transfer content into (!remober which one you would use for your particular operating system)
   3. Transfer Family - allows you to use legacy file transfer protocols to give older applications the ability to read and write from S3
4. Migration Hub
   1. migration hub - gives you a way to organize all your migration steps, however you will need other tools to complete the migration, migration hub only helps you organize and track
   2. DMS, is go-to tool for any sort of database migration (SCT)
   3. do you have VMs? server migration service is the tool you will want to use to migrate out of data center and into AWS.
5. Application Deiscovery Service
   1. Quickly migrate entire applications to AWS Cloud
   2. Agentless discovery - can be used via OVA file deployment to vSphere
   3. Agent-based discovery collects detailed information of VMs on both linux and windows OS.
6. Application Migration Service
   1. Known as MGN
   2. automated lift-and-shift service for migration infrastructure to AWS
   3. Replicates source servers (VM, physical, or Azure VM) into AWS for non-disruptive cutovers
   4. RTO of mins and RPO of sub-sec

### Snow family
the Snow Family is a set of secure appliances that provide petabyte-scale data (huge data set) and processing solutions at the **edge** and **migrate** large-scale data into and out of AWS.They offer **built-in computing** capabilities, enabling customer to run their operations in remote locations that do not have data center access or reliable network connectivity.

In reality, it's just a sack of hard drives that Amazon ships to you -> load your data -> ship it physically to AWS back.

1. Snowcone - 8TB storage, 4gb of memory and 2 vCPUs
2. Snowball edge - 48 TB to 81 TB in storage.
3. Snowmobile - 100 PB of storage 

#### Summary
if you see a scenarios ask you to pick a solutiion for data migration, they have a large mount of data, very slow internet connection, and very importantly, data needs to be encrypted at rest and in transit, then pick snowball.


### Storage Gateway
1. File Gateway (kinda like a icloud?)
   1. NFS or SMB mount
   2. keep a local copy of recently used files in S3
   3. Use case, Extend on-premises storage, if a user don't have enough on-prem storage space and your solution is going to be setup a cached file GW.
2. Volumne GW
   1. back up drives in S3, and easy method to back up from on-prem to become EBS volumnes inside of AWS.
   2. iSCSI mount
   3. cacehed or stored mode
   4. Create EBS snapshot
3. Tap GW (not comes often, could be a distractor)


#### Summary
Out of space on-premises? emm, which storage GW soluiton solves the issue?  

storage GW is hybrid storage. you'll be given scenarios that ask you to pick a solution for data migration, when this comes up, you need to keep Storage GW in mind.  Anytime on-premises storage is mentioned, you should be thinking about which type of storage GW can complement the existing arch


### Data Sync
is an **agent-based** (an agent need to be installed on the archi on your end) solution for migrating on-premises storage to AWS. it allows you to easily move data between **NFS** and **SMB** shares and AWS storage solutions.

you'll be given scenarios that ask you to pick a solution for data migration.

DataSync v.s Storage?   
1. data sync is great for **one-time migration** (will be shut down after migration done)
2. if you want more continuous setup, choose storage GW, it's ideal for setup hybrid archi

#### Summary
1. difference between data sync and storage GW?
2. agent-based
3. one-time migration
4. always comes as distractor


### AWS Transfer Family
allows you to easily move files in and out of **S3** or **EFS** using Secure File Transfer Protocol (SFTP), File transfer protocol over SSL (FTPS) or File transfer protocal (FTP) (FTP only supported within the VPC and not over public internet) 

#### Summary
1. this excels when you have a colletion of older applications using protocols that cannot be change
2. when you see those protocols above
3. DNS - dns entry stays the same, but the location for the storage becomes S3
4. always be a distractor


### AWS Migration Hub
gives you a single place to **track** the progress of your application migration to AWS. 
it integrates with Server Migration Service (**SMS**) and database migration service (**DMS**)

#### Summary
1. given scenarios that ask you to pick a solution for application migration
2. DMS going to be used to move DB
3. SMS will be the tool of choice for moving servers
4. migration hub will give you the overview you need.
5. keep it high level


### AWS Application Discovery Service & AWS Application migration Service (MGN)
1. Application Discovery Service
   1. Application migration - easily and quickly migrate applications to the AWS Cloud
   2. Agentless Discovery - performed via OVA file in vCenter, Easy migration of VMs
   3. Agent-based Discovery - Installable agent for Windows and Linux to collect detailed information on VMs and physical hosts
2. AWS Application Migration Service
   1. AWS MGN - also known as MGN, it offers automated lift and shift of migrating infrastructure to AWS.
   2. Replication - Replicate source servers (VMs physical, or cloud servers) into AWS for non-disruptive cutovers
   3. RTO and RPO - RTO is measured in mins depending on OS boot time, RPO is measured in sub-seconds

### AWS Database Migration Service (DMS)
it allows for easy imgration of RDB, data warehouses, NoSQL database and other database stores, migration data between AWS and on-premises

Schema Conversion Tool (SCT), leverage SCT for creating some or all of your tables, indexes and more.
> Damn POWERFULL TOOL
> 1. convert- leverage the SCT to convert existing database schemas from one engine to another
> 2. Engine Types - Convert many types of RDB, including both OLAP and OLTP, it even supports data warehouses
> 3. Supported Targets - Conveted Schemas can be used for many supported Amazon RDS engine type, Amazon Aurora or Amazon RedShit
> 4. Amazon EC2 and S3 - you can even use the converted schemas with databases running on EC2 or data stored in S3

you can migrate from&to same engine, e.g., MySQL to MySQL, or different engines. You **MUST** have one endpoint (src/destination) live within an AWS. which meaning you cannot use it from on-premise to on-premise

there are 3 different migration 
1. Full load - all existing data is moved from src to target in parallel
2. Full load + Change Data Capture (CDC) - full load plus CDC, it capture changes to source tables during migration 
3. CDC only - only replicate the data changes from source DB

CDC **Guarantees transactional integrity** of the target database.

You can migrate large dataset using DMS with AWS snowball.


#### Summary
1. what DMS does?
2. how it works? - DMS server runs replication software that execute specified tasks
3. different between full-load, full-load + CDC, and CDC-only migration
4. can you do external-only migration? - nah
5. SCT?
6. Snowball - to migrate massive dataset, snowball + DMS


### Migration hub + server migration service (SMS)
1. scenario-based questions related to tracking and planning migration efforts from either on-premises or another cloud vendor could involve Migration Hub.
2. SMS is perfect for scenario like simplifying migrations of critical VMs from on-premises, easily migrating VMs from other cloud providers and **minimizing downtimes** during cutovers.
---
## Front-End Web and Mobile

### Summary
1. just few of these services are currently on exam
2. focus on Amzon pinpoint
  1. it enables you to engage with customers on large or small scale
  2. pinpoint is geared toward marketing teams, business uers, and sometimes developers.
  3. segments allows for targeted messages and audiences
  4. leverage machine learning modols to predict engagement interactions.


### AWS Amplify
offers tools for front-end web and mobile developers to quickly build full stack application on AWS

### AWS Device Farm
is application testing service for testing and interacting with Android, IOS, and webapps. see a scenario that requires application testing on mobile device in AWS.

### Amaaon Pinpoint
pinpoint enable you to engage with customers through a variety of different messaging channels.

pinpoint is primarily intended for marketers, business users and developers

for questions related to marketing compaigns, user engagements, and sending emails to targeted audiences, or scenarios leveraging machine learning with user engagement preditions



---
## Machine Learning 

### Summary
focus 2 services, Rekognition and Segemaker


### Analyzing Text using Amazon Comprehend, amazon Kendra, and Amazon Textract
Amazon Comprehend - uses natural-language processing (NLP) to help you understand the meaning and sentiment in your test.

Amazon kendra - allows you to create an intelligent **search service** powered by machine learning. 

Amazon Textract - textract uses machine learning to automatically extract text, handwriting and data from scanned docouments.


### Predicting Time-series Data using Amazon Forecast
is a time-series forecasting service that uses machine learning and is built to give you important business insight

### Protecting Accounts with Amazon Fraud Detector
to detect fraud in your data

### Working with Text and Speed Using Amazon Polly, Amazon Transcribe and Amazon Lex 
(not comes in the exam yet)

Transcribe - generate subtiltles
Lex - a natural language model, if you talk to a online bot, you are interacting with the Lax service 
Polly - turns your text into lifelike speech


### Analyzing Images via Amazon Rekognition (important)
100% comes up in the exam
recognition of pics and videos using deep learning and neural networks

if you have a scenario question about content moderation using AI/ML, think Amazon Rekognition

### Amazon SageMaker to Train Learning Models 
comes up in the exam

#### Summary
* Groud Truth (not come up in the exam) - setup and manage labeling jobs for training datasets using active learning and human labeling
* Notebook - jupyter notebook write your python
* Training
* Inference - package and deploy your ML models at scale
  * 2 deployment type, online usage and offline usage, if you need immediate response - online usage deployment, otherwise, offline usage deployment

steps
1. create a model
2. create an endpoint configuration
3. create and endpoint

* SageMaker Neo
  >Tensorflow/mxnet/pytorch/onnx/xgboost -> Amazon SageMaker Neo -> Arch Optimized Binary -> NVIDIA Platform

* Elastic inference - to reduce costs, using CPU-based inferences rather than GPU-based inferences   
* Automatic scaling
* highly available



### Amazon Translate 
not yet comes up in exam
if you have a scenario-based question where you need to translate from on language to another using deep learning/neural netowrk, think of Amazon Translate

---
## Media (not in the exam yet)

**Elatic Trancoder**   
1. not in the exam yet
2. if you see the word 'transcode'or you want to converting your media files to a particular device

**Amazon Kinesis Video Stream**
1. not in the exam yet
2. if you see secnario of video streaming, think it.

---
## Summary overall

Reference Handbooks
* AWS Architecture Center
* AWS Certified Solutions Architect - Associate Exam page (download sample questions)

in exam 
* real-time = kinesis
* logging = cloudwatch logs 
* compute = EC2
* archive = glacier

---
## Load Balancer

**brif overview** 
apiGW -(vpc_link) -> LB -(ports)-> TG(instances) 



