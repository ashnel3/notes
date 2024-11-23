## EC2 ^ec2

### Instance-Stores ^ec2-instance-stores

> See [Store-Limits](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/instance-store-volumes.html)

A temporary [[List of Services#^aws-ebs|EBS]] device included in the cost of the instance. When the instance is terminated you lose all data in the instance store.

### Instance-Types ^ec2-instance-types

- On Demand ^aws-ec2-on-demand
  > Default Type (See: [[Pricing#^pricing-concepts-on-demand|On-Demand Pricing]])
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

## SnowBall ^aws-snowball

- Snowcone _(Thin-Client sized)_
  - 2 CPUs, 4GB Memory
  - Up-To 14TB Storage
- Snowball _(Desktop sized)_
  - SnowBall-Edge **(Storage optimized)**
    - 40 vCPUs, 80GiB Memory
    - 80TB HDD + 1TB SDD
    - Equivalent w/ sbe1 instances
  - SnowBall-Edge **(Compute optimized)**
    - 104 vCPUs, 416GiB Memory
    - 80TB HDD + 28TB NVME SSD
    - Optional NVidia Tesla v100 GPU
    - Equivalent w/ sbe-c & sbe-g instances
- Snowmobile _(Semi-Truck sized)_
  - Up-To 100PiB per snowmobile.
