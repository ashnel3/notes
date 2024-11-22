## General

- Origin
  > Usually refers to a web server / AWS service
- Scalability
  > Automatically scaling resources to meet demand.
  >
  > Example: ec2 groups [[List of Services#^auto-scaling]] & [[Load Balancing]]

## Regions

- Availability Zone (AZ) _(Example: us-west-1a)_ ^az
  > One or more redundant data-centers that make up an AWS region.
- Region _(Example: us-west-1)_ ^region
  > A geographic location containing AWS resources.
  > 
  > Contains at least 3 AZ's
- Outpost ^outpost
  > On-Prem AWS mini-region
  >
  > Often used for governance when data must be stored in specific locations
- Point of Presence (POP's)
  >
- Edge Locations
  > Edge locations are specialized data-centers used for caching close to population centers.
  > 
  > They use [[List of Services#^cloud-front|CloudFront]] to reduce latency in neighboring regions.
  > They're also often used as on/off ramps for [[List of Services#^route-53|Route 53]]
