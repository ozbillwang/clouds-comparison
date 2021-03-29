# clouds-comparison

AWS to Azure services comparison

### Clarifications

AWS and Azure are different public cloud providers, services between them are not same. So it is hard to match the services between them. 

This page gives some simple comparisions for AWSers who want to know Azure services easily.

### Notes
* Only compare AWS with Azure. 
* Markdown for easy updates later
* Category types based on AWS services.
* Service with * in front need be reviewed.
* Only list as similar services

### Comparision

| Category | Services | AWS | Azure |
| ---------- |:-------------:| :---------------------------------------:|:---------------------------------------:|
| Compute | Instances | Amazon EC2  | Azure Virtual Machine |
| Compute | Instances | Launch Templates  |  |
| Compute | Instances | Spot instances  | Azure Spot Virtual Machines |
| Compute | Instances | Reserviced Instances | Azure Reserved Virtual Machine Instances |
| Compute | Instances | Dedicated Hosts | Azure Dedicated Host  |
| Compute | * Images | AMIs |  Sysprep <br> Azure Images |
| Compute | Elastic Block Store (EBS) | Volumes | Disk Storage  |
| Compute | Elastic Block Store (EBS) | Snopshots | Snopshots  |
| Compute | Elastic Block Store (EBS) | Lifecycle Manager |   |
| Compute | Network & Security | Security Groups| Network Security Groups  |
| Compute | Network & Security | Elastic IPs| Public IP addresses  |
| Compute | Network & Security | Placement Groups| Proximity placement groups  |
| Compute | Network & Security | Network Interfaces| Network interfaces  |
| Compute | Load Balancing| Load Balancers | Load balancers  |
| Compute | Load Balancing| Target Groups |   |
| Compute | Auto scaling| Launch Configurations |   |
| Compute | Auto scaling| Auto Scaling Groups | Virtual machine scale sets (VMSS)  |
| Compute | | Lightsail | App Service  |
| Compute | | Lambda | Functions  |
| Compute | | Batch | Batch |
| Compute | | Elastic Beanstalk | App Service   |
| Compute | | Serverless Application Repository |   |
| Compute | | AWS Outposts | Stack  |
| Compute | | EC2 Image Builder | Images  |
| | | | |
| Containers | Containers | Elastic Container Registry | Azure Container Registry  |
| Containers | Containers | Elastic Container Service (ECS) | Container Instances |
| Containers | Containers | Elastic Kubernetes Service (EKS) | Azure Kubernetes Service(AKS) |
| Containers | * Containers <br> (Serverless Compute Engine) | Elastic Container Service (ECS) with Fargate | Azure Container Instances |
| Containers | Containers | Red Hat OpenShift Service on AWS | |
| | | | |
| Storage |  | Simple Storage Services (S3) | Blob Storage |
| Storage |  | EFS | File storage |
| Storage |  | FSx | |
| Storage |  | S3 Glacier | |
| Storage |  | Storage Gateway | |
| Storage |  | AWS Backup | Azure Backup Center |
| | | | |
| Network & <br> Content Delivery | Virtual Private Cloud | Virtual Private Cloud (VPC) | Virtual Network (vNet) |
| Network & <br> Content Delivery | Virtual Private Cloud | Subnets | Subnets |
| Network & <br> Content Delivery | Virtual Private Cloud | Route Tables | Route Table |
| Network & <br> Content Delivery | Virtual Private Cloud | Internet Gateway | |
| Network & <br> Content Delivery | Virtual Private Cloud | Egress Only Internete Gateway  | |
| Network & <br> Content Delivery | Virtual Private Cloud | Elastic IPs  | |
| Network & <br> Content Delivery | Virtual Private Cloud | Mangaged Prefix Lists  | |
| Network & <br> Content Delivery | Virtual Private Cloud | Endpoint Services  | |
| Network & <br> Content Delivery | Virtual Private Cloud | NAT Gateway  | |
| Network & <br> Content Delivery | Virtual Private Cloud | Peering Connections  | |
| Network & <br> Content Delivery | Security | Network ACLS (NACL)  | |
| Network & <br> Content Delivery | Security | Security Groups| |
| Network & <br> Content Delivery | Reachability | Reachability Analyzer  | |
| Network & <br> Content Delivery | AWS Network Firewall | Firewalls  | |
| Network & <br> Content Delivery | AWS Network Firewall | Firewall policies  | |
| Network & <br> Content Delivery | AWS Network Firewall | Network Firewall rule groups  | |
| Network & <br> Content Delivery | Virtual Private Network (VPN) | Customer Gateways  | |
| Network & <br> Content Delivery | Virtual Private Network (VPN) | Virtual Private Gateways (VPG)| |
| Network & <br> Content Delivery | Virtual Private Network (VPN) | Site-to-Site VPN Connections  | |
| Network & <br> Content Delivery | Virtual Private Network (VPN) | Client VPN Connections  | |
| Network & <br> Content Delivery | Transit Gateways | Transit Gateways | Virtual WAN |
| Network & <br> Content Delivery | Transit Gateways | Transit Gateway Attachments | Virtual Hub <br> Transit vNet |
| Network & <br> Content Delivery | Transit Gateways | Transit Gateway Route Tables |  |
| Network & <br> Content Delivery | Transit Gateways | Transit Gateway Route Multicast |  |
| Network & <br> Content Delivery | Transit Gateways | Network Manager |  |
| Network & <br> Content Delivery | Traffic Mirroring | Mirror Sessions |  |
| Network & <br> Content Delivery | Traffic Mirroring | Mirror Targets |  |
| Network & <br> Content Delivery | Traffic Mirroring | Mirror Filters |  |
| Network & <br> Content Delivery |  | CloudFront | |
| Network & <br> Content Delivery |  | Route 53 | |
| Network & <br> Content Delivery |  | API Gateway | |
| Network & <br> Content Delivery |  | Direct Connect | ExpressRoute Circuit |
| Network & <br> Content Delivery |  | AWS App Mesh | |
| Network & <br> Content Delivery |  | AWS Cloud Map | |
| Network & <br> Content Delivery |  | Clobal Accelerator | |



### Reference:

https://docs.microsoft.com/en-us/azure/architecture/aws-professional/services

http://comparecloud.in/


