## S3 ^s3

### Tiers ^s3-tiers

- Standard
  > designed for frequent access
  > minimum of 3 AZ's
- Standard IA
  > Similar to standard
  > Lower storage prices w/ higher retrieval
- Standard One-Zone IA
  > Lower price than Standard-IA
  > Single AZ
- Intelligent Tiering
  > Automatic tier selection for dynamic access patterns
- Glacier Instant Revival
  > Retrieval in: milliseconds
- Glacier Flexible Revival
  > Retrieval in: 0 - 12hrs
- Glacier Deep Archive
  > Retrieval in: 12 - 28hrs
- Outposts

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
