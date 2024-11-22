### Load-Balancing

A load balancer acts as an entry point to your scalable resources; spreading the incoming traffic though your dynamic groups.

```mermaid
graph TD;
  Client;
  Client-->|#1|DNS["Route 53 (DNS)"]
  Client-->|#2|CDN["Cloud Front (CDN)"]
  subgraph AWS Cloud
  DNS
  CDN-->Balancer[Load Balancer]
  Balancer-->EC2#1
  Balancer-->EC2#2
  Balancer-->EC2#3
  subgraph group[Auto-Scaling Group]
    EC2#1
    EC2#2
    EC2#3
  end
  end
```
