## Analytics

- Data Market ^aws-data-market
  > **third-party**
- Data Pipeline ^aws-data-pipeline
  > **Data movement & transformation service**
  >
  > Schedule data tasks & events with a pipeline definition config file
- Glue ^aws-glue
  > **Serverless data integration service** (third party data integration)
- Redshift ^aws-redshift
  > Managed cloud data warehouse for large scale data analytics

## Containers

- Elastic Container Registry (ECR) ^aws-ecr
  > Store, extend & deploy container images on AWS
  >
  > like a private AWS docker-hub for container images
- Elastic Kubernetes (EKS) ^aws-eks
- Elastic Containers (ECS) ^aws-ecs

## Databases

- Database migration (DMS) ^aws-dms
  > Database conversion tool
- Aurora ^aws-aurora
  > Fully-Managed & scalable relational database service
- Dynamo DB ^aws-dynamodb
  > Fully-Managed & scalable nosql database service
- Dynamo DB Accelerator ^aws-dynamodb-accel
  > Memory cache for DynamoDB
- Document DB ^aws-documentdb
  > Managed nosql database service (w/ MongoDB compatibility)
- Relation DB Service (RDS) ^aws-rds
  > Managed relational database service
- Neptune ^aws-neptune
  > Fully-Managed graph database service
- ElastiCache ^aws-elasticache
  > Database caching service (supports: Redis & Memcached)

## Networking & CDN

- Direct Connect ^aws-direct-connect
  > Dedicated VPC connection service
- Cloud Front ^aws-cloud-front
  > Global CDN service
  > Uses edge locations to deliver content cross region close to customers
- Route 53 ^aws-route-53
  > DNS service (See: [[Networking#Load-Balancing|Load-Balancing]])
- Virtual Private Cloud (VPC) ^vpc
  > A isolated section of AWS cloud w/ a defined network

## Management & Governance

- Artifact ^aws-artifact
  > Compliance service
  > Allows for agreement management & compliance review
- Auto Scaling ^aws-auto-scaling
  > Scale resources to meet demand
- Cloud Formation ^aws-cloud-formation
  > Easily configure, template, & provision resources w/ config files _(json,yaml)_
- Cloud Watch ^aws-cloud-watch
  > Monitor resources & applications
  >
  > Full-stack resource usage events for automated scaling
- Cloud Trail ^aws-cloud-trail
  > Usage audits & logging service
  > Track AWS account activity & API usage
- Organizations ^aws-organizations
  > Policy based management service for multiple AWS accounts

## Storage

- Simple Storage Service (S3) ^aws-s3
  > File storage service
  >
  > Each S3 object consists of a file, key, & metadata
- Elastic Block Store (EBS) ^aws-ebs
  > Block storage for EC2 instances
  > Single AZ
  >
  > EBS supports incremental backup w/ ESB snapshot
- Elastic File System (EFS) ^aws-efs
  > Shared file system service
  >
  > Built to scale to petabytes

## Identity, Security & Compliance

- Key Management (KMS) ^aws-kms
  > Create & manage cryptographic keys
  > Allows en/decrypting data
- Identity and Access Management (IAM) ^aws-iam
  > User identity service
  > Allows you to group & create new users w/ policies & roles (See: [[List of Terms#^scp|SCP's]])
- Inspector ^aws-inspector
  > Automated vulnerability monitoring service
  > Monitors applications _(ec2, lambda)_ for vulnerabilities & unintended exposure
- Guard Duty ^aws-guard-duty
  > Automated security monitoring service
  > Monitors incoming vpc traffic & flow logs for threats.
- Detective ^aws-detective
  > Security data analysis
- Shield ^aws-shield
  > DoS protection service
  > Built in & automatically protects all AWS customers. (See: [[List of Terms#^DoS|DoS]])
  >
  > Shield Advanced has extra attack details & mitigation features
- Web Application Firewall (WAF) ^aws-waf
  > Web-Application firewall service (Uses: [[List of Terms#^aws-acl|ACL's]])

# Support

- AWS Trusted Advisor ^aws-trusted-advisor
  > Real-time advisory service
  > Trusted advisor continuously monitors AWS environments to provide best-practice recommendations
  >
  > Dashboard shows investigations for: cost-optimization, performance, Security, fault-tolerance & service limits
