## General

- Rightsizing
  > The process of restructuring a company to improve efficiency & meet updated objectives.
- Infrastructure as code (IaC) ^IaC
  > A method for managing & provisioning physical computer infrastructure using code.
- Managed Services ^managed
  > Services where AWS takes more responsibility
  >
  > <b class="highlight">! Companies generally save money by using managed services.</b> 
  > <b class="highlight">! Reduces staff overhead.</b>

- Scalability ^scalability
  > Automatically scaling resources to meet demand. (See: [[Networking#Load-Balancing|Load Balancing]])

## Networking

- Classless Inter-Domain Routing (CIDR) ^CIDR
  > CIDR notation allows you to express a range of ip address's. (See: [How Does CIDR Work?](https://aws.amazon.com/what-is/cidr/#seo-faq-pairs#how-does-cidr-work))
  >
  > **Example: `10.0.0.0/24`:**
  > IP Address's contains 32-bits, using CIDR notation we can allow dynamic trailing bits by using a slash _(`/24` allows the last bit)_.
  >
  > <b class="highlight">! Range between `/16` _(65,536)_ to `/28` _(16)_</b>
- Client-To-Site ^client-to-site
  > A device accessing a remote network through a VPN.
- Site-To-Site ^site-to-site
  > Multiple networks communicating together through a VPN.
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
- Route Tables ^route-tables
  > A set of routes that direct traffic flow from a subnet / gateway.
- Internet Gateway ^aws-internet-gateway
  > A VPC component that enabled communication w/ the public internet.
- Virtual Private Gateway ^aws-private-gateway
  > A VPC component that enabled secure communication w/ private resources.
  >
  > Often used to connect over a VPN
- Network Access Control List (ACL) ^aws-acl
  > A stateless virtual firewall for a VPC.
  >
  > <b class="highlight">! Defaults: allows all</b>
- Security Group ^aws-security-group
  > A stateful virtual firewall for an instance.
  >
  > Multiple instances inside a VPC can be assigned to a single security group
  >
  > <b class="highlight">! Defaults: ignores incoming & allows outgoing</b>

## Regions

- Availability Zone (AZ) _(Example: us-west-1a)_ ^aws-az
  > One or more redundant data-centers that make up an AWS region.
- Region _(Example: us-west-1)_ ^aws-region
  > A geographic location containing AWS resources.
  >
  > <b class="highlight">! Best practice to host in two regions for high-availability</b>
  > <b class="highlight">! Contains at least 3 AZ's</b>
- Outpost ^aws-outpost
  > On-Prem AWS mini-region.
  >
  > Allows AWS services to be run On-Premise hardware.
- Point of Presence (POP's) ^aws-pop
  >
- Edge Locations ^aws-edge-location
  > Edge locations are specialized data-centers used for caching close to population centers.
  >
  > They're often used [[List of Services#^aws-cloud-front|CloudFront]] to reduce latency in neighboring regions.
  >
  > They're also often used as on/off ramps for [[List of Services#^aws-route-53|Route 53]]

## Pricing

- Software as a service (SaaS) ^SaaS
  > A software pricing model where applications are delivered via subscription.
- Operation expenses (OpEx) ^OpEx
  > Day to day operating expenses.
- Capital Expenses (CapEx) ^CapEx
  > One time upfront investments.

## Security

- IAM user access-keys ^aws-iam-user-access-key
  > Long term credentials for an IAM user / AWS account.
  >
  > <b class="highlight">! It's best practice to use temporary security credentials like roles.</b>
- IAM Roles ^aws-iam-role
  > You can use [[List of Services#^aws-iam|IAM]] roles to associate certain permissions to AWS users.
  >
  > You can also apply roles to EC2 instances using [[Compute#Instance-profiles|Instance-Profiles]].
- Service Control Policy (SCP) ^aws-scp
  > A type of organization policy that controls the actions users can preform.
  >
  > You can apply SCP's to a user by assigning an [[List of Terms#^aws-iam-role|IAM role]] w/ the policy.
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
