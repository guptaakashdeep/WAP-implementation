# WAP-implementation
This repository uses Apache Spark with Iceberg Tables to cover the Write Audit Publish Data Quality Pattern implementation. 

Based on which version of Iceberg you are using. WAP can be implemented in 2 ways:
- Iceberg version > 1.2.0 : Implementation via Branching
- Iceberg version <= 1.2.0 : Implementation via `WAP.id`

## Repository Navigation
- `aws`: contains the notebooks that show the implementation on AWS
- `local`: contains the notebooks that can run WAP on a local workstation.

Code explanation and detailed explanation of implementation can be found on my website [here](https://guptaakashdeep.com/wap-via-apache-iceberg-on-aws).
