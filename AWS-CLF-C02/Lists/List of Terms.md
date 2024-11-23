## General

- Infrastructure as code (IaC) ^IaC
  > A method for managing & provisioning physical computer infrastructure using code.
- Software as a service (SaaS) ^SaaS
  > A software pricing model where applications are delivered via subscription.
- Scalability ^scalability
  > Automatically scaling resources to meet demand. (See: [[Networking#Load-Balancing|Load Balancing]])

## Networking

- Denial of Service Attack (DoS) ^DoS
  > A deliberate attempt to make a website or application unusable for end-users.
  > Usually accomplished by flooding a server w/ fake requests.
- Denial of Service Attack (DDoS) ^DDoS
  > A DoS attack from multiple dynamic devices. (See: [[List of Services#^aws-shield|Shield]])
- Domain Name System (DNS) ^DNS
  > Resolves URLs into their IP address's. _Often compared to the internet's phone book_
- Origin ^origin
  > Usually refers to a web server / AWS service.
- Sub Network ^sub-network
  > A section of a VPC containing resources _(such as EC2 instances)_.
- Internet Gateway ^aws-internet-gateway
  > A VPC component that enabled communication w/ the public internet.
- Virtual Private Gateway ^aws-private-gateway
  > A VPC component that enabled secure communication w/ private resources.
  > Often used to connect over a VPN
- Network Access Control List (ACL) ^aws-acl
  > A stateless virtual firewall for a VPC.
  >
  > <b class="highlight">! Defaults: allows all</b>
- Security Group ^aws-security-group
  > A stateful virtual firewall for an instance.
  > Multiple instances inside a VPC can be assigned to a single security group
  >
  > <b class="highlight">! Defaults: ignores incoming & allows outgoing</b>

## Regions

- Availability Zone (AZ) _(Example: us-west-1a)_ ^aws-az
  > One or more redundant data-centers that make up an AWS region.
- Region _(Example: us-west-1)_ ^aws-region
  > A geographic location containing AWS resources.
  >
  > <b class="highlight">! Contains at least 3 AZ's</b>
- Outpost ^aws-outpost
  > On-Prem AWS mini-region.
  > Often used for governance when data must be stored in specific locations
- Point of Presence (POP's) ^aws-pop
  >
- Edge Locations ^aws-edge-location
  > Edge locations are specialized data-centers used for caching close to population centers.
  >
  > They're often used [[List of Services#^aws-cloud-front|CloudFront]] to reduce latency in neighboring regions.
  > They're also often used as on/off ramps for [[List of Services#^aws-route-53|Route 53]]

# Security

- Service Control Policy (SCP) ^aws-scp
  > A type of organization policy that controls the actions users can preform.
  >
  > You can apply a SCP to an AWS user by creating a IAM role.
  >
  > <b class="highlight">! SCP's can only be applied to AWS Accounts & OU's</b>
  ```json
  {
    "Version": "2012-10-17",
    "Statement": {
      "Action": "s3:ListObject",
      "Effect": "Allow",
      "Resource": "arn:aws:s3:::AWSDOC-EXAMPLE-BUCKET"
    }
  }
  ```
