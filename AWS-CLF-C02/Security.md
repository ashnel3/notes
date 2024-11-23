## Shared Responsibility Model ^responsibility-model

Responsibility in the cloud is shared between AWS & the customer. This is often compared to the responsibilities of a home owner vs a construction company.

```mermaid
classDiagram
class Customer["Customer Responsibility"]
Customer : Customer Data
Customer : Platform | Identity | Access Management
Customer : Operating systems | Applications | Networking & Firewall
Customer : Traffic-protection | Encryption(Client-Side, Server-Side)

Customer <|--|> AWS

class AWS["AWS Responsibility"]
AWS : Software
AWS : Compute | Storage | Database | Networking
AWS : Hardware / Infrastructure(Regions, Availability-Zones, Edge-Locations)
```

## Root User ^root-user

When first creating an AWS account you begin with a root user; The root user can only be accessed w/ the email & password specified. The AWS root user is similar to a concept in Unix, it owns and has complete access to all resources.

It is considered best practice to only use the root user when needed and not as a general purpose account. (See: [[List of Services#^aws-iam|IAM]])
