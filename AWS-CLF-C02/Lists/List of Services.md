## Analytics

- Data Market ^aws-data-market
  > __Third-Party data marketplace.__
- Data Pipeline ^aws-data-pipeline
  > __Data movement & transformation service.__
  >
  > Schedule data tasks & events with a pipeline definition config file.
- Glue ^aws-glue
  > __Serverless data integration service.__ _(third-party data integration)_
- Redshift ^aws-redshift
  > __Managed cloud data warehouse service.__

## Artificial Intelligence

- SageMaker ^aws-sagemaker
  > __Building, Training & deployment platform for AI/ML models__
- Lex ^aws-lex
  > __AI Chat service__
- Textract ^aws-textract
  > Scanned-Document text extraction service.

## Containers

- Elastic Container Registry (ECR) ^aws-ecr
  > __Store, extend & deploy container images on AWS.__
  >
  > like a private AWS docker-hub for container images.
- Elastic Kubernetes (EKS) ^aws-eks
- Elastic Containers (ECS) ^aws-ecs
- Elastic Beanstalk ^aws-elastic-beanstalk
  > Full-Managed web application deployment service.
  >
  > Allows code upload for many languages, and requires minimal to no code changes.

## Databases

- Quantum Ledger DB (QLDB) ^aws-qldb
  > Managed ledger database service.
- Database migration (DMS) ^aws-dms
  > Database conversion service.
- Aurora ^aws-aurora
  > Fully-Managed & scalable relational database service.
- Dynamo DB ^aws-dynamodb
  > Fully-Managed & scalable nosql database service.
- Dynamo DB Accelerator ^aws-dynamodb-accel
  > Memory cache for DynamoDB
- Document DB ^aws-documentdb
  > Managed nosql database service _(w/ MongoDB compatibility)_.
- Relation DB Service (RDS) ^aws-rds
  > Managed relational database service.
- Neptune ^aws-neptune
  > Fully-Managed graph database service.
- ElastiCache ^aws-elasticache
  > Database caching service _(supports: Redis & Memcached)_.

## Networking & CDN

- Direct Connect ^aws-direct-connect
  > __Dedicated VPC connection service.__
- Cloud Front ^aws-cloud-front
  > __Global CDN service.__
  >
  > Uses edge locations to deliver content cross region close to customers.
- Route 53 ^aws-route-53
  > __DNS service.__ (See: [[Networking#Load-Balancing|Load-Balancing]])
- Virtual Private Cloud (VPC) ^aws-vpc
  > __Virtual private cloud service.__
  >
  > A isolated section of AWS cloud w/ a defined network.

## Management & Governance

- Artifact ^aws-artifact
  > __Compliance monitoring & reports service.__
  >
  > Allows for agreement management & compliance review.
- Auto Scaling ^aws-auto-scaling
  > __Automatic resource scaling service.__
- Cloud Formation ^aws-cloud-formation
  > __[[List of Terms#^IaC|IaC]] provisioning service.__
  >
  > Easily configure, template, & provision resources w/ config files _(json,yaml)_.
- Cloud Watch ^aws-cloud-watch
  > __Monitor resources & applications.__
  >
  > Full-stack resource usage events for [[List of Services#^aws-auto-scaling|automated scaling]].
- Cloud Trail ^aws-cloud-trail
  > __Usage audits & logging service.__
  >
  > Track AWS account activity & API usage.
- Organizations ^aws-organizations
  > __Policy based management service for multiple AWS accounts.__
  >
  > Default account limit is 4

## Storage

- Simple Storage Service (S3) ^aws-s3
  > __File storage service.__
  >
  > Each S3 object consists of a file, key, & metadata properties
- Elastic Block Store (EBS) ^aws-ebs
  > __Block storage for EC2 instances.__
  >
  > <b class="highlight">! Single-AZ</b>
  > EBS supports incremental backup w/ ESB snapshot
- Elastic File System (EFS) ^aws-efs
  > __Shared file system service, built for petabyte scale.__
  >
  > <b class="highlight">! Multi-AZ</b>
  > Similar to SAMBA or other attachable network stores.

## Identity, Security & Compliance

- Cognito ^aws-cognito
  > __User Authentication service__
- Macie ^aws-macie
  > __S3 Data security service__
  >
  > Monitors S3 buckets and provides a summary of your data security across all accounts.
- Key Management (KMS) ^aws-kms
  > __Cryptographic key management service.__
  >
  > Allows en/decrypting data.
- Identity and Access Management (IAM) ^aws-iam
  > __User identity service.__
  >
  > Allows you to group & create new users w/ policies & roles. (See: [[List of Terms#^aws-scp|SCP's]])
- Inspector ^aws-inspector
  > __Automated vulnerability monitoring service.__
  >
  > Monitors applications _(ec2, lambda)_ for vulnerabilities & unintended exposure.
- Guard Duty ^aws-guard-duty
  > __Automated security monitoring service.__
  >
  > Monitors incoming vpc traffic & flow logs for threats.
- Detective ^aws-detective
  > __Security data analysis service.__
- Shield ^aws-shield
  > __DoS protection service.__
  >
  > Built in & automatically protects all AWS customers. (See: [[List of Terms#^DoS|DoS]])
  >
  > Shield Advanced has extra attack details & mitigation features.
- Web Application Firewall (WAF) ^aws-waf
  > __Web-Application firewall service.__ (Uses: [[List of Terms#^aws-acl|ACL's]])

# Support

- AWS Trusted Advisor ^aws-trusted-advisor
  > __Real-time advisory service.__
  >
  > Trusted advisor continuously monitors AWS environments to provide best-practice recommendations.
  >
  > Dashboard shows investigations for: cost-optimization, performance, Security, fault-tolerance & service limits
