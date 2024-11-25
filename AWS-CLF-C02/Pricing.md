### Concepts ^pricing-concepts

- On-Demand pricing ^pricing-concepts-on-demand
  > Only pay for exactly what you use.
- Pay less w/ reservations ^pricing-concepts-reservations
  > Some services offer reservation options that drastically reduce cost (See: [[Compute#^aws-ec2-savings-plan|EC2 Savings Plan]])
- Pay less w/ high volume ^pricing-concepts-bulk
  > Some services offer tiered pricing to lower cost per-unit at scale.
  >
  > Example: cost per GB is lowered based on storage space used w/ S3 (See: [[Storage#Tiers s3-tiers|S3-Tiers]])

### Free-Tier ^pricing-free-tier

| Name        | Description                                                                                                                  |
| ----------- | ---------------------------------------------------------------------------------------------------------------------------- |
| Always-Free | Some service's free-tier offerings do no expire.<br><br>Example: 1mil requests + 3.2mil seconds of compute a month w/ lambda |
| 12-Months   | These offers are available for 12 months after sign-up<br><br>Examples: S3 Storage, EC2 compute & CloudFront transfer        |
| Trials      | Short-Term offers started when you activate a service.<br><br>Examples: AWS Lightsail 90-day free trail                      |

### Budgets ^pricing-budgets

You can create budgets to plan your service costs and reservations. Budgets can also be configured to send alerts for specific usage or cost thresholds.

Budgets are updated 3 times a day.

### Calculator ^pricing-calculator

> See: [Pricing-Calculator](https://calculator.aws/#/)

Allows you to calculate and forecast service costs beforehand.

### Dashboard ^pricing-dashboard

Where you pay your AWS bills, has a ton of features related to monitoring & controlling cost.

- Compare current months usage w/ last for easy forecasting
- View current send by service
- View [[Pricing#Free-Tier pricing-free-tier|Free-Tier]] usage by service
- Access Cost-Explorer & budget creation
- Access & manage savings-plans
- Publish AWS Cost & Usage Reports (CUR) ^aws-cur
  > See: [AWS Cost & Usage Reports](https://docs.aws.amazon.com/cur/latest/userguide/what-is-cur.html)

### Cost-Explorer ^pricing-cost-explorer

A tool to help visualize and manage AWS costs and usage over time.

Include a default report of costs and usage for your top-5 accruing services.

### Consolidation ^pricing-consolidation

Consolidated billing allows you to receive a single bill for all AWS accounts in an [[List of Services#^aws-organizations|Organization]]. With consolidation you can easily track the combined cost of all linked accounts.

Another benefit is the ability to share discount pricing (savings plans, reserved instances) across your organization.
