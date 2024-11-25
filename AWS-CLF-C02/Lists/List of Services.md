## Analytics

- Data Market ^aws-data-market
  > **Third-Party data marketplace.**
- Data Pipeline ^aws-data-pipeline
  > **Data movement & transformation service.**
  >
  > Schedule data tasks & events with a pipeline definition config file.
- Glue ^aws-glue
  > **Serverless data integration service.** _(third-party data integration)_
- Redshift ^aws-redshift
  > **Managed cloud data warehouse service.**
- Kinesis ^aws-kinesis
  > **Data stream analysis service.**
  >
  > Capable of ingesting real-time data from video, audio, application logs, and website click-streams

## Artificial Intelligence

- Comprehend ^aws-comprehend
  > **Natural language processing service.**
- Polly ^aws-polly
  > **Speech synthesis service.**
- SageMaker ^aws-sagemaker
  > **Building, Training & deployment platform for AI/ML models**
- Lex ^aws-lex
  > **AI Chat service**
- Transcribe ^aws-transcribe
  > **Speech transcription service.**
- Textract ^aws-textract
  > **Scanned document text extraction service.**

## Compute

- FarGate ^aws-fargate
  > **Serverless container service.** (See [[List of Services#^aws-ecs|ECS]])
- LightSail ^aws-lightsail
  > **Managed VPS service.**
- Elastic Beanstalk ^aws-elastic-beanstalk
  > **Fully-Managed web application deployment service.**
  >
  > Allows code upload for many languages, and requires minimal to no code changes.
- Elastic Containers (ECS) ^aws-ecs
  > **Fully-Managed container orchestration service.**
- Elastic Kubernetes (EKS) ^aws-eks
  > **Fully-Managed elastic kubernetes service.**
- EC2
  > **Virtual machine service.** (See: [[Compute#EC2|EC2]])
- EC2 Auto Scaling ^aws-ec2-auto-scaling
  > **Automatic instance scaling service.**

## Containers

- Elastic Container Registry (ECR) ^aws-ecr
  > **Store, extend & deploy container images on AWS.**
  >
  > like a private AWS docker-hub for container images.

## Databases

- Quantum Ledger DB (QLDB) ^aws-qldb
  > Managed ledger database service.
- Database migration (DMS) ^aws-dms
  > Database conversion service.
- Aurora ^aws-aurora
  > Fully-Managed & scalable relational database service.
- Dynamo DB ^aws-dynamodb
  > Fully-Managed & scalable NOSQL database service.
- Dynamo DB Accelerator ^aws-dynamodb-accel
  > Memory cache for DynamoDB
- Document DB ^aws-documentdb
  > Managed NOSQL database service _(w/ MongoDB compatibility)_.
- Relation DB Service (RDS) ^aws-rds
  > Managed relational database service.
- Neptune ^aws-neptune
  > Fully-Managed graph database service.
- ElastiCache ^aws-elasticache
  > Database caching service _(supports: Redis & Memcached)_.

## Networking & CDN

- Client VPN ^aws-client-vpn
  > **Cloud [[List of Terms#^client-to-site|Client-To-Site]] VPN service.**
- Direct Connect ^aws-direct-connect
  > **Dedicated VPC connection service.**
- Cloud Front ^aws-cloud-front
  > **Global CDN service.**
  >
  > Uses edge locations to deliver content cross region close to customers.
- Route 53 ^aws-route-53
  > **DNS service.** (See: [[Networking#Load-Balancing|Load-Balancing]])
  >
  > Route53 supports failover routing *(routeing to healthy resources only)*
- Virtual Private Cloud (VPC) ^aws-vpc
  > **Virtual private cloud service.**
  >
  > A isolated section of AWS cloud w/ a defined network.

## Management & Governance

- Artifact ^aws-artifact
  > **Compliance monitoring & reports service.**
  >
  > Allows for agreement management & compliance review.
- Config ^aws-config
  > **Resource configuration auditing service.**
- Cloud Formation ^aws-cloud-formation
  > **[[List of Terms#^IaC|IaC]] provisioning service.**
  >
  > Easily configure, template, & provision resources w/ config files _(json,yaml)_.
- Cloud Watch ^aws-cloud-watch
  > **Monitor resources & applications.**
  >
  > Full-stack resource usage events for [[List of Terms#^scalability|scalability]].
- Cloud Trail ^aws-cloud-trail
  > **Usage audits & logging service.**
  >
  > Track AWS account activity & API usage.
- Organizations ^aws-organizations
  > **Policy based management service for multiple AWS accounts.**
  >
  > Default account limit is 4

## Storage

- Simple Storage Service (S3) ^aws-s3
  > **File storage service.**
  >
  > Each S3 object consists of a file, key, & metadata properties
- Elastic Block Store (EBS) ^aws-ebs
  > **Block storage for EC2 instances.**
  >
  > <b class="highlight">! Single-AZ</b>
  > EBS supports incremental backup w/ ESB snapshot
- Elastic File System (EFS) ^aws-efs
  > **Shared file system service, built for petabyte scale.**
  >
  > <b class="highlight">! Multi-AZ</b>
  > Similar to SAMBA or other attachable network stores.
- Storage Gateway
  > **On-Prem Hybrid cloud storage service.**
  >
  > Connect On-Prem applications to virtually unlimited cloud storage.

## Identity, Security & Compliance

- Cloud HSM ^cloud-hsm
  > **Single-Tenant hardware security module service.**
  >
  > Manage & access encryption keys on FIPS compliant hardware.
- Cognito ^aws-cognito
  > **User Authentication service**
- Macie ^aws-macie
  > **S3 Data security service**
  >
  > Monitors S3 buckets and provides a summary of your data security across all accounts.
- Key Management (KMS) ^aws-kms
  > **Cryptographic key management service.**
  >
  > Allows en/decrypting data.
- Identity and Access Management (IAM) ^aws-iam
  > **User identity service.**
  >
  > Allows you to group & create new users w/ policies & roles. (See: [[List of Terms#Security|List of Security Terms]])
- Inspector ^aws-inspector
  > **Automated vulnerability monitoring service.**
  >
  > Monitors applications _(ec2, lambda)_ for vulnerabilities & unintended exposure.
- Guard Duty ^aws-guard-duty
  > **Automated security monitoring service.**
  >
  > Monitors incoming vpc traffic & flow logs for threats.
- Detective ^aws-detective
  > **Security data analysis service.**
- Shield ^aws-shield
  > **DoS protection service.**
  >
  > Built in & automatically protects all AWS customers. (See: [[List of Terms#^DoS|DoS]])
  >
  > Shield Advanced has extra attack details & mitigation features.
- Web Application Firewall (WAF) ^aws-waf
  > **Web-Application firewall service.** (Uses: [[List of Terms#^aws-acl|ACL's]])

# Support

- Connect ^aws-connect
  > **AI Contact center service.**
- AWS Trusted Advisor ^aws-trusted-advisor
  > **Real-time advisory service.**
  >
  > Trusted advisor continuously monitors AWS environments to provide best-practice recommendations.
  >
  > Dashboard shows investigations for: cost-optimization, performance, Security, fault-tolerance & service limits
