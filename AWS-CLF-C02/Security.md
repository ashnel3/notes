## Shared Responsibility Model ^responsibility-model

> See: [AWS Responsibility Model](https://aws.amazon.com/compliance/shared-responsibility-model/)

Responsibility in the cloud is shared between AWS & the customer. This is often compared to the responsibilities of a home owner vs a construction company.

- **AWS's Responsibility**
  - Software
  - Hardware / Global Infrastructure
- **Customer's Responsibility**
  - Customer Data
  - Platform, Applications, Identity & Access management
  - OS, Networking & Firewall
  - Encryption & data integrity authentication
    - Client-Side
    - Server-Side
    - Network traffic

### Shared Controls ^responsibility-model-shared-controls

Controls which apply to both AWS & Customer but in separate contexts or perspectives.

**Examples:**

- Patch Management
  > AWS is responsible for patching & maintaining the infrastructure, but the customer are responsible for patching their own OS's & applications.
- Configuration
  > AWS maintains the configuration of it's devices, but users are responsible for configuring their own OS's & applications.
- Awareness & training
  > AWS trains it's employees, but a customer must train their own.

## Root User ^root-user

When first creating an AWS account you begin with a root user; The root user can only be accessed w/ the email & password specified. The AWS root user is similar to a concept in Unix, it owns and has complete access to all resources.

It is considered best practice to only use the root user when needed and not as a general purpose account. (See: [[List of Services#^aws-iam|IAM]])

<b class="highlight">! It is recommended to delete all [[List of Terms#^aws-iam-user-access-key|IAM Access Keys]] for the root user</b>
