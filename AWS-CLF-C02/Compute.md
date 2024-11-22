# EC2

## Instance-Stores

> See [Store-Limits](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/instance-store-volumes.html)

A temporary [[List of Services#^aws-ebs|EBS]] device included in the cost of the instance. When the instance is terminated you lose all data in the instance store.

## Instance-Types

- On Demand ^aws-ec2-on-demand
  > Default Type
  >
  > Pay for what you use
- Reserve ^aws-ec2-reserve
  > Discounts for instance commitment
- Spot ^aws-ec2-spot-plan
  > Discounts for interruptible workloads
- Savings Plan ^aws-ec2-savings-plan
  > Discounts for usage commitment (See: [Compute & EC2 Savings Plans](https://aws.amazon.com/savingsplans/compute-pricing/))
  >
  > Requires usage commitment contract for 1 or 3 years
- Dedicated Hosts ^aws-ec2-dedicated
  > Dedicated physical server _(useful for licensing / governance)_
