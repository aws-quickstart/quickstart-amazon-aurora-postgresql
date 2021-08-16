# quickstart-amazon-aurora-postgresql
## Modular Architecture for Amazon Aurora PostgreSQL

This Quick Start automatically deploys a modular, highly available environment for Amazon Aurora PostgreSQL on the Amazon Web Services (AWS) Cloud.

Aurora is a fully managed relational database engine that’s compatible with MySQL and PostgreSQL. The code, tools, and applications you use today with your existing PostgreSQL databases can be used with Aurora. With some workloads, Aurora can deliver up to three times the throughput of PostgreSQL without requiring changes to most of your existing applications. Aurora is part of the Amazon Relational Database Service (Amazon RDS) and takes advantage of Amazon RDS features for database management and administration.  

This Quick Start is for users who are looking for a repeatable, customizable reference deployment for Aurora PostgreSQL. You can also use the Quick Start as a building block to set up your own automated deployments. 

The Quick Start offers two deployment options:

- Deploying Aurora PostgreSQL into a new virtual private cloud (VPC) on AWS (use the [aurora_postgres-main.template.yaml template](https://github.com/aws-quickstart/quickstart-amazon-aurora/blob/develop/templates/aurora_postgres-main.template.yaml)).
- Deploying Aurora PostgreSQL into an existing VPC on AWS (use the [aurora_postgres.template.yaml template](https://github.com/aws-quickstart/quickstart-amazon-aurora/blob/develop/templates/aurora_postgres.template.yaml)). This template builds only the Aurora database components and is designed to plug into your existing AWS CloudFormation templates as a drop-in PostgreSQL database replacement.

![Quick Start architecture for Aurora PostgreSQL](https://d0.awsstatic.com/partner-network/QuickStart/datasheets/amazon-aurora-quick-start-architecture.png)

For architectural details, best practices, step-by-step instructions, and customization options, see the 
[deployment guide](https://fwd.aws/jzGyq).

To post feedback, submit feature ideas, or report bugs, use the **Issues** section of this GitHub repo.
If you'd like to submit code for this Quick Start, please review the [AWS Quick Start Contributor's Kit](https://aws-quickstart.github.io/). 
