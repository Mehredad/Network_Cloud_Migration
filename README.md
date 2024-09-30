# YummyDelight Network and Cloud Migration to AWS

## 📄 Project Overview
This is a Univeristy project involved the migration of YummyDelight’s on-premise infrastructure to AWS, leveraging cloud services to improve scalability, reliability, and cost efficiency. The strategy focused on using various AWS services, including EC2, S3, RDS, IAM, and VPC, to ensure smooth and secure migration while addressing key business needs such as disaster recovery, autoscaling, and security.

## 🚀 Key Features
- **Scalability**: AWS Auto Scaling and Elastic Load Balancing ensure that YummyDelight can handle fluctuations in traffic efficiently.
- **Cost Efficiency**: By adopting a pay-as-you-go model, YummyDelight reduced its infrastructure costs.
- **Disaster Recovery and Backup**: Amazon S3 and RDS provided reliable storage, backup, and recovery solutions.
- **Security**: AWS Identity and Access Management (IAM) and AWS Shield were used to secure sensitive data and protect against attacks.
- **Global Availability**: AWS Availability Zones and Regions allowed YummyDelight to expand globally without requiring new physical data centers.

## 🛠️ Technologies and AWS Services Used
- **AWS EC2**: Virtual servers to replace the on-premise infrastructure.
- **AWS S3**: Scalable storage for static assets and backup.
- **AWS RDS**: Managed MySQL and Oracle databases.
- **AWS IAM**: Access control and security management.
- **AWS CloudFront**: Content delivery for faster website load times globally.
- **AWS CloudWatch**: Monitoring and alert system for EC2 instances.
- **Elastic Load Balancer (ELB)** and **Auto Scaling Groups**: For managing traffic and scaling instances based on demand.
- **AWS Lambda**: Serverless automation for event-driven tasks.

## 🔍 Migration Process
### 1. Assessment and Planning
- Evaluated existing infrastructure, applications, and data for migration readiness.
- Assessed scalability, security, and performance requirements.
  
### 2. Migration Strategy
- Migrated on-premise applications to EC2 instances, with EBS for persistent storage.
- Created S3 buckets for backups and long-term data storage.
- Utilized RDS for migrating MySQL and Oracle databases.
- Set up IAM for access control, and CloudWatch for monitoring.

### 3. Challenges and Solutions
- **Challenge**: EC2 instance sizing limitations due to AWS free tier.
- **Solution**: Resized instances based on load requirements, optimized with Auto Scaling.
  
- **Challenge**: Credential issues while connecting RDS to MySQL Workbench.
- **Solution**: Created new credentials and configured secure access.

## 📊 Architecture Diagrams
![AWS Network Layout](diagrams/cloud_migration.png)

## 📝 Lessons Learned
- Proper planning of security policies (IAM, encryption, multi-factor authentication) is crucial for smooth cloud migration.
- AWS services like S3 Glacier can be very cost-effective for long-term backup storage.
- Auto Scaling and ELB ensure high availability and resilience, even during high-traffic periods.

## 👨‍💻 Author
- **Mehrdad Atariani**  
  [LinkedIn](https://linkedin.com/in/mehrdad-atariani/)

## 📝 License
This project is created for the University of Law (Cloud & Network Management Course)
