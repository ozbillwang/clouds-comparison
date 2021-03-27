# clouds-comparison

AWS to Azure services comparison

Notes:
* Reference from https://github.com/ilyas-it83/CloudComparer, and only compare AWS with AZure. 
* Convert to Markdown and flat it for easy updates later
* Category types based on AWS services.

|| Category || Services || AWS | Azure ||
| :-------------: |:-------------:| :---------------------------------------:|:---------------------------------------:|
| Compute | Instances | Amazon EC2  | Azure Virtual Machine |
| Compute | Instances | Launch Templates  |  |
| Compute | Instances | Spot instances  |  |
| Compute | Instances | Reserviced Instances |  |
| Compute | Instances | Dedicated Hosts | Azure Dedicated Host  |
| Compute | Images | AMIs |   |
| Compute | Elastic Block Store (EBS) | Volumes |   |
| Compute | Elastic Block Store (EBS) | Snopshots |   |
| Compute | Elastic Block Store (EBS) | Lifecycle Manager |   |
| Compute | Network & Security | Security Groups|   |
| Compute | Network & Security | Elastic IPs|   |
| Compute | Network & Security | Placement Groups|   |
| Compute | Network & Security | Network Interfaces|   |
| Compute | Load Balancing| Load Balancers |   |
| Compute | Load Balancing| Target Groups |   |
| Compute | Auto scaling| Launch Configurations |   |
| Compute | Auto scaling| Auto Scaling Groups |   |
| Compute | Auto scaling| Auto Scaling Groups |   |
| Compute | | Lightsail |   |
| Compute | | Lambda |   |
| Compute | | Batch |   |
| Compute | | Elastic Beanstalk |   |
| Compute | | Serverless Application Repository |   |
| Compute | | AWS Outposts |   |
| Compute | | EC2 Image Builder |   |
| | | | |
| Containers | Containers | Elastic Container Registry | Azure Container Registry  |
| Containers | Containers | Elastic Container Service (ECS) | |
| Containers | Containers | Elastic Kubernetes Service (EKS) | Azure Kubernetes Service(AKS) |
| * Containers | Containers | Elastic Container Service (ECS) with Fargate | Azure Container Instances |
| Containers | Containers | Red Hat OpenShift Service on AWS | |
AWS Lambda 
Azure Service Fabric 
Azure Functions 
Event Grid 
Google Cloud Functions 
IBM Cloud Code Engine 
IBM Cloud Functions 
Oracle Functions 
Function Compute 
ComputeVirtual Private Servers
Amazon Lightsail 
Azure App Service Environment 
Classic Virtual Server 
Virtual Server for VPC 
Simple Application Server 
ComputeAuto Scaling
Auto Scaling 
Azure Autoscale 
Virtual Machine Scale Sets 
Auto Scaler 
Auto Scaling 
Auto Scaling 
Auto Scaling 
ComputeBatch Jobs 
AWS Batch 
Azure Batch 
Preemptible VMs 
IBM Cloud Code Engine 
IBM Cloud Functions 
Batch Compute 
ComputeApp Development/ Deployment (Java /.Net /PHP /Python) 
AWS Elastic Beanstalk 
Azure Web Apps 
Azure Cloud Services 
Google App engine 
IBM Cloud Code Engine 
Cloud Foundry Apps 
Oracle Application Container Cloud Service 
Java Cloud Service 
Enterprise Distributed Application Service 
ComputeEvent Driven Computing
AWS Lambda
Azure Functions 
Event Grid 
Cloud Functions 
IBM Cloud Code Engine 
IBM Cloud Functions 
Oracle Functions 
Function Compute 
StorageObject Storage 
Amazon Simple Storage Service (S3) 
Azure Blob Storage 
Cloud Storage 
Cloud Object Storage 
Oracle Cloud Infrastructure Object Storage 
Object Storage Service 
StorageVirtual Machine Disk Storage 
Amazon Elastic Block Storage (EBS) 
Azure Page Blobs / Premium Storage 
Managed Disks 
Persistent Disk 
Block Storage 
Block Storage for VPC 
Oracle Cloud Infrastructure Block Volumes 
Block Storage
StorageFile Storage (SMB Compatible) 
Amazon Elastic File System (EFS) 
Azure File Storage 
File Store 
File Storage 
Oracle Cloud Infrastructure File Storage 
NAS File Storage 
StorageLong Term Cold Storage 
Amazon Glacier 
Azure Archive Storage 
Azure Cool Storage 
Cloud Storage 
Archival Storage (NEARLINE & COLDLINE) 
Object Storage-ColdVault 
Archive 
Oracle Cloud Infrastructure Archive Storage 
Oracle Cloud Object Storage Infrequent Access Tier 
Object Storage Archive 
StorageHybrid Storage/Storage Gateway 
AWS Storage Gateway 
Azure Storsimple 
Oracle Cloud Infrastructure Storage Gateway 
Hybrid Cloud Storage Array 
DatabaseRelational Database Management Service 
Amazon Aurora 
Amazon RDS 
Azure SQL Database 
SQL Server Stretch Database 
Azure Database for MySQL 
Azure Database for PostgresSQL 
Azure SQL Database Edge 
Cloud SQL 
Cloud Spanner 
Db2 
Db2 Hosted 
Informix 
Databases for PostgreSQL 
Compose for MySQL(Beta) 
Oracle Database Cloud Service - Virtual Machine 
Oracle Database Cloud Service - Bare Metal 
Oracle Exadata Cloud Service 
Oracle Autonomous Data Warehouse 
Oracle Autonomous Transaction Processing 
MySQL Database Service 
ApsaraDB for RDS MYSQL 
ApsaraDB for RDS SQL Server 
ApsaraDB for RDS PostgreSQL 
Distributed Relational Database Service (DRDS) 
DatabaseNon Relational Database Management Service 
Amazon DynamoDB 
Amazon DocumentDB (with MongoDB compatibility) 
Amazon DynamoDB Accelerator (DAX) 
Amazon Neptune 
Azure CosmosDB 
Table Storage 
Azure Time Series Insights 
Cloud Datastore 
Cloud BigTable 
Cloudant NoSQL DB 
Compose for JanusGraph 
Databases for MongoDB 
Oracle NoSQL Database Cloud Service 
Oracle Autonomous JSON Database 
Apsaradb for Mongodb 
Table Store 
DatabaseTimeseries Database
Amazon DynamoDB 
Azure Time Series Insights 
Cloud BigTable 
Informix 
HiTSDB (High-Performance Time Series Database) 
Time Series Database for InfluxDB 
DatabaseIn-Memory Data Store 
Amazon ElastiCache 
Azure RedisCache 
Cloud MemoryStore (Beta) 
Databases for Redis 
ApsaraDB for Redis 
DatabaseData Warehousing 
Amazon Redshift 
Azure Synapse Analytics 
BigQuery 
Db2 Warehouse on Cloud 
Exadata 
Autonomous Data Warehouse Cloud 
Alibaba MaxCompute ODPS 
Migration ServicesDatabase Migration Services 
AWS Database Migration Service 
Azure Database Migration Service (Preview) 
Lift CLI 
Migrate to the Cloud 
Data Transmission Service 
Migration ServicesServer Migration Services
AWS Server Migration Service 
Site Recovery 
Azure Websites Migration Assistant 
Cloud Migration Tool 
Migration ServicesSmall Scale Data Transfer Service
AWS Import/Export 
Azure Import/Export 
Data Transfer Service 
Aspera High-speed Transfer 
Data Transfer Services - Hard Disk Import 
Migration ServicesLarge Scale Data Transfer Solution (Petabyte Scale)
AWS Snowball 
Mass Data Migration Service 
Data Transfer Services - Storage applicance import 
Data Transport 
Migration ServicesLarge Scale Data Transfer Solution (Terabyte Scale)
AWS Snowball Edge 
Azure Data Box (Preview) 
Transfer Appliance (Beta) 
Mass Data Migration Service 
Data Transfer Services - Storage applicance import 
Data Transport 
Migration ServicesLarge Scale Data Transfer Solution (Exabyte Scale)
AWS Snowmobile 
Data Transfer Services 
Application Discovery ServicesApplication Discovery Services
Application Discovery Service 
Azure Active Directory 
Networking & Content DeliveryVirtual Networking
Amazon VPC 
Azure VNet 
Cloud Virtual Network 
IBM Cloud VPC 
Oracle Virtual Cloud Network 
Virtual Private Cloud 
Networking & Content DeliveryNetwork Gateway
Amazon VPN 
Azure VPN Gateway 
Cloud VPN 
Classic IPSEC-VPN 
VPN gateway for VPC 
Oracle VPN Connect 
VPN Gateway 
Networking & Content DeliveryContent Delivery Network
Amazon CloudFront 
Azure CDN 
Cloud CDN 
Content Delivery Network 
Alibaba Content Delivery Network 
NetworkingNetworking & Content Delivery
Amazon Route 53 
Azure DNS 
Cloud DNS 
Internet Services 
Oracle DNS 
Alibaba Cloud DNS 
NetworkingGlobal Traffic Management
Amazon Route 53 Traffic Flow 
Azure Traffic Manager 
Internet Services 
Oracle Cloud Infrastructure Traffic Management 
Hybrid CloudHybrid Cloud
AWS Outposts 
Azure Arc 
Satellite 
Secure Gateway 
Oracle Exadata Cloud@Customer 
Oracle Roving Edge Infrastructure 
Networking & Content DeliveryPrivate Connectivity 
AWS Direct Connect 
AWS Private Link 
Azure Express Route 
Cloud InterConnect 
Direct Link 
Oracle Cloud Infrastructure FastConnect 
Express Connect 
Networking & Content DeliveryLoad Balancers 
Elastic Load Balancing 
Azure Load Balancer 
Cloud Load Balancing 
IBM Cloud Load Balancers 
IBM Cloud Load Balancer for VPC 
Citrix NetScaler VPX 
Oracle Cloud Infrastructure Load Balancing 
Server Load Balancer 
Developer ToolsCloud Software Development Kit
AWS Cloud9 
AWS Code Star 
AWS CodeCommit 
AWS CodeBuild 
AWS CodeDeploy 
AWS CodePipeline 
AWS X-Ray 
Azure Boards 
Azure Pipelines 
Azure Repos 
Azure Test Plans 
Azure Artifacts 
Cloud Source Repositories 
Continuous Delivery 
DevOps Insights 
Globalization Pipeline 
Oracle Visual Builder Studio 
Developer ToolsCloud Software Development Kit
AWS SDK
Azure SDK Visual Studio 
Cloud SDK Cloud Tools for IntelliJ
Cloud Tools for Android Studio
Cloud Tools for Powershell
Google Plugin for Eclipse
IBM Cloud Developer Tool 
Continuous Delivery 
Oracle API Catalog 
Toolkit for Eclipse 
Oracle Developer Tools for Visual Studio 
Management ToolsServer Management Services 
Amazon EC2 Systems Manager 
Azure Operational Insights 
Oracle Management Cloud 
Management ToolsCloud Deployment Templates/ Infra as Code 
AWS CloudFormation 
Azure Resource Manager 
Azure Building Blocks 
Cloud Resource Manager 
Cloud Deployment Manager 
Schematics 
Oracle Resource Manager 
Resource Orchestration Service 
Management ToolsLogging & Monitoring 
Amazon CloudWatch 
AWS CloudTrail 
Log Analytics 
Azure portal 
Application Insights 
Google StackDriver 
Monitoring 
Logging 
Error Reporting 
Trace 
Debugger 
Monitoring 
IBM Cloud Log Analysis with LogDNA 
IBM Cloud Activity Tracker with LogDNA 
IBM Cloud Monitoring with Sysdig 
Oracle Cloud Infrastructure Logging 
Oracle Logging Analytics 
Oracle Cloud Infrastructure Monitoring 
Application Performance Monitoring (limited availability)
Oracle Service Connector Hub 
Management Cloud
CloudMonitor 
ActionTrail 
Application Real-Time Monitoring Service 
Management ToolsResource / Configuration Inventory
AWS Config 
Azure portal (audit logs)
Cloud Security Scanner
Cloud Data Loss Prevention Api 
Access Transparency (Beta) 
App Configuration 
Oracle Cloud Governance Services 
Alibaba Log Service 
Management ToolsServer Automation
AWS OpsWorks 
Resource Manager 
Azure Automation 
VM Extentions 
Oracle Cloud Infrastructure OS Management 
Oracle Resource Manager 
Resource Orchestration Service 
Management ToolsServer Automation
AWS Service Catalog 
Management ToolsCloud Cost / Performance / Security Advisor
AWS Trusted Advisor 
Azure Advisor 
Azure Cost Management 
Google Cloud Platform Security 
Oracle Cloud Guard 
Oracle Cloud Advisor 
Management ToolsAlerts and Remediation guidance Service
AWS Personal Health Dashboard
Azure Monitor 
Azure Operations Management Suite (OMS) 
Oracle Management Cloud 
Oracle Cloud Guard 
Oracle Security Advisor 
"Cloud monitoring, Notification and Alerts "
Management ToolsCloud Management Tools
AWS Command Line Interface
AWS Management Console
Azure Command Line Interface
Azure Powershell 
Azure Management Console
Azure Cloud Shell 
Cloud Shell 
Cloud Console 
Billing API 
Cloud APIs 
OCI CLI 
Oracle Cloud Shell 
Oracle Management Console
REST API 
Alibaba Cloud CLI 
Management ToolsAutomated Infra Management Services
AWS Managed Services 
Disaster Recovery ServicesAutomated Disaster Recovery Services
AWS Disaster Recovery 
Azure Site Recovery 
Azure Backup 
Oracle Database Backup 
Alibaba Disaster Recovery 
Hybrid Backup Recovery 
"Security & Identity, ComplianceIdentity & Access Management"
AWS Identity and Access Management (IAM) 
Azure Active Directory 
Cloud IAM 
Cloud Identity-Aware Proxy 
Identity & Access Management 
Oracle Identity and Access Management (IAM) 
Oracle Identity Cloud Service 
Resource Access Management 
"Security & Identity, ComplianceCloud Security Assesment Service"
Amazon Inspector 
Gaurd Duty 
Azure Security Center 
Security and Compliance Center 
Oracle Security Advisor 
Oracle Cloud Guard 
"Security & Identity, ComplianceSecured Socket Layer (SSL) Certificates"
AWS Certificate Manager 
App Service Certificate 
Certificate Manager 
SSL Certificates 
"Security & Identity, ComplianceHardware Based Security Module"
AWS CloudHSM 
AWS Secrets Manager 
Azure Key Vault 
Cloud Key Management Service 
Key Protect 
Cloud HSM 
Hyper Protect Crypto Services 
Oracle Cloud Infrastructure Vault 
Key Management Service 
"Security & Identity, ComplianceDirectory Services"
AWS Directory Service 
Azure Active Directory 
Azure Active Directory B2C 
Azure Active Directory Domain Services 
Azure Active Directory Multi Factor Authentication 
Cloud IAM 
Cloud Identity-Aware Proxy 
Security Key Enforcement 
App ID 
Oracle Directory Services 
Resource Access Management 
"Security & Identity, ComplianceKey Management Services"
AWS Key Management Service
Azure Key Vault 
Cloud Key Management Service 
Key Protect 
Cloud HSM 
Hyper Protect Crypto Services 
Oracle Cloud Infrastructure Vault 
Key Management Service 
"Security & Identity, ComplianceConsolidated Management of Multiple Cloud Accounts"
AWS Organizations
Azure Management Groups 
Resource Group 
"Security & Identity, ComplianceDDos Protection Service"
AWS Shield 
Azure DDoS Protection 
Cloud Armor (Beta) 
Internet Services 
Oracle DDoS Protection 
DDOS Pro and Basic 
"Security & Identity, ComplianceWeb Application Firewall"
AWS WAF 
Azure WAF
Internet Services 
Oracle Web Application Firewall 
Web Application Firewall 
"Security & Identity, ComplianceSecurity & Compliance Service"
AWS Firewall Manager
Azure Firewall Manager 
Security and Compliance Center 
"Security & Identity, ComplianceSecurity & Compliance Service"
AWS Artifact 
Azure Security & Compliance 
Cloud Security Command Center (Alpha) 
Security and Compliance Center 
Oracle Cloud Infrastructure Compliance Documents 
Alibaba Truster Center 
Big Data & Advanced AnalyticsBig Data Query as a Service
Amazon Athena 
Azure Data Lake Analytics 
BigQuery 
SQL Query 
Oracle Big Data SQL Cloud Service 
E-MapReduce Service 
Big Data & Advanced AnalyticsBig Data Managed Cluster as a Service
Amazon EMR 
Azure HDInsight 
Cloud DataProc 
Analytics Engine 
Oracle Big Data Service 
E-MapReduce Service 
Big Data & Advanced AnalyticsCloud Search
Amazon CloudSearch 
Amazon Elastic Search Service 
Azure Search
Databases for Elasticsearch 
Big Data & Advanced AnalyticsStreaming Service
Amazon Kinesis 
Amazon Kinesis Video Streams 
Azure Stream Analytics 
Azure Event Hub 
Cloud Dataflow 
Streaming Analytics 
Event Streams 
Oracle Cloud Infrastructure Streaming 
Big Data & Advanced AnalyticsData Warehouse
Amazon Redshift 
Azure SQL Data Warehouse 
BigQuery 
Db2 Warehouse 
Oracle Autonomous Data Warehouse 
Alibaba MaxCompute ODPS 
Big Data & Advanced AnalyticsBusiness Intelligence & Data Visualization
Amazon QuickSight 
PowerBI 
Google Data Studio (Beta) 
Watson studio 
Oracle Analytics Cloud 
Oracle Data Visualization Cloud Service 
Oracle Business Intelligence Cloud Service 
Data IDE 
Big Data & Advanced AnalyticsCloud ETL
AWS Data Pipeline 
AWS Glue 
Amazon Simple Workflow Service (SWF) 
Azure Data Factory 
Azure Data Catalog 
Logic Apps 
Cloud DataPrep (Private Beta) 
Cloud Composer (Beta) 
DataStage 
Watson Knowledge Catalog 
Oracle Cloud Infrastructure Data Flow 
Oracle Integration 
Data Integrator 
DataWorks 
Data Integration 
Artificial IntelligenceLanguage Processing AI
Amazon Lex 
Amazon Comprehend 
LUIS (Language Understanding Intelligent Service) 
Azure Bot Service 
Azure Speech Recognition API 
Natural Language API 
Cloud Text-to-Speech (Beta) 
DialogFlow Enterprise Edition (Beta) 
Natural Language Classifier 
Language Translator 
Watson Assistant 
Watson Discovery 
Watson Knowledge Studio 
Text to Speech 
Personality Insights 
Artificial IntelligenceSpeech Recognition AI
Amazon Polly
Amazon Transcribe 
Amazon Translate 
Bing Speech API
Translation API 
Speech API 
Speech to Text 
Artificial IntelligenceImage Recognition AI
Amazon Rekognition
Emotion API 
Face API 
Computer Vision API
Vision API
Cloud Video Intelligence 
Visual Recognition 
Image Search 
Artificial IntelligenceMachine Learning
Amazon Machine Learning
Amazon Sage​Maker 
Azure Machine Learning 
Azure Machine Learning Workbench 
Azure Machine Learning Model Management 
Cloud DataLab
Cloud AutoML (Alpha) 
Cloud Machine Learning Services
Machine Learning 
Watson OpenScale 
Oracle Machine Learning 
Machine Learning Platform For AI 
Mobile ServicesMobile App Development Services
AWS Mobile Hub
Azure Mobile Apps 
Cloud Mobile App
Mobile Foundation 
Mobile & Chatbots 
Mobile Hub 
Mobile ServicesWeb API Management Service
Amazon API Gateway
Azure API Management
Cloud Endpoints
API Connect 
API Platform 
Apiary 
API Gateway 
Mobile ServicesWeb/Mobile Authentication Services
Amazon Cognito
"Azure Mobile SDK,Offline/Sync"
Firebase Authentication
App ID 
Mobile Cloud Service 
Mobile ServicesConsolidated Mgmt of Multiple Cloud Accounts
Amazon Pinpoint
Azure Mobile Engagement
Mobile Foundation 
Automated Cloud Management ServiceManaged Cloud Services
AWS Managed Services 
Mobile ServicesMobile App Testing Service
AWS Device Farm
Xamarin Test Cloud (Front End)
Azure DevTest Labs (Back End)
Cloud Test Lab 
Mobile ServicesMobile App Software Development Toolkit
AWS Mobile SDK
Azure Mobile SDK
Cloud Tools for Android Studio 
Oracle Visual Builder 
Mobile ServicesApplication Services
AWS Step Functions
Microsoft Flow 
Logic Apps 
Azure Functions 
Event Grid 
Azure App Service WebJobs
App Engine 
IBM Cloud Functions 
IBM Cloud Code Engine 
Oracle Application Express (APEX) 
Oracle Visual Builder 
Oracle Visual Builder Studio 
Mobile ServicesMobile App Analytics
Amazon Mobile Analytics 
Hockey App 
Firebase Analytics 
Mobile Foundation 
Mobile Cloud Service 
Application ServicesAPI Management Service
Amazon API Gateway
Azure API Management
Apigee API Platform 
API Monitization 
API Analytics 
Apigee Sense 
Cloud Endpoints 
API connect 
API Platform 
Apiary 
API Gateway 
Application ServicesMedia Transcoders
Amazon Elastic Transcoder
AWS Elemental MediaConvert 
AWS Elemental MediaLive 
AWS Elemental MediaPackage 
AWS Elemental MediaStore 
AWS Elemental MediaTailor 
Amazon Kinesis Video Streams 
Azure Media Services 
Live On Demand Streaming
Azure Media Player
Content Protection
Media Analytics
Digital Transcoding
ApsaraVideo Live 
Application ServicesQueuing Services
Amazon SQS
Amazon MQ 
Service Bus queues
Queue Storage
Service Bus topics
Service Bus relay
Cloud Pub/Sub
Event Steams 
Integration 
Messaging 
Message Queue 
Application ServicesMobile Analytics
Amazon Pinpoint
Mobile Engagement
Mobile Foundation 
Application ServicesEmail Services
Amazon SES
Sendgrid 
Oracle Cloud Infrastructure Email Delivery 
Direct Mail 
Application ServicesNotification Services
Amazon SNS
Azure Notification Services
Firebase Cloud Messaging 
Push Notifications 
Oracle Cloud Infrastructure Notifications 
Short Message Service (SMS) 
Application ServicesBlockchain Services
Amazon Managed Blockchain 
Amazon Quantum Ledger Database (QLDB) 
Blockchain 
Blockchain Workbench 
Azure Blockchain Tokens 
Blockchain Platform 
Oracle Blockchain 
Blockchain as a Service 
Application ServicesChatbot
Lex Chatbots
Azure Bot Service 
Dialogflow 
Watson Assistant 
Oracle Digital Assistant 
Intelligent Service Robot 
Business ProductivityOffice Document Solutions
Amazon WorkDocs
Amazon WorkMail
Amazon WorkSpaces
Microsoft Office 365
G Suite
Business ProductivityDesktop Application Streaming
Amazon AppStream 2.0
Software MarketPlaceCloud Marketplace
AWS Marketplace
Azure MarketPlace 
Cloud Launcher 
IBM Marketplace 
Oracle Cloud Market Place 
Alibaba Cloud Marketplace 
Internet of ThingsIoT Platform
AWS IoT Platform
Azure IoT Platform 
Azure IoT Hub 
Cloud IoT Core (Beta) 
Google Cloud IoT 
Internet of Things Platform 
Node-Red 
Internet of Things Cloud Service 
IoT Platform 
Internet of ThingsIoT Development Solutions
AWS Greengrass
Azure IoT SDK
Azure IoT Edge 
Internet of Things Platform 
Internet of ThingsIoT Hardware
AWS IoT Button
Azure Sphere 
Game DevelopmentGame Development
Amazon Lumberyard
Visual Studio
Watson Unity SDK 
Robotics DevelopmentRobotics Development
AWS RoboMaker 
Development & TestingDevelopment & Testing
AWS Dev/Test
Azure Dev/Test 
Oracle Visual Builder Studio 
