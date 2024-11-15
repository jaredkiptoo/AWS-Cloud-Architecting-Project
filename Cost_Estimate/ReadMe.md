# Cost Estimate for AWS Academy Cloud Architecting Capstone Project

## Project Overview  
This repository contains the cost estimate for the Cloud Architecting Capstone Project. The goal is to design a scalable, cost-effective cloud architecture using AWS services while adhering to the Well-Architected Framework.

## Estimated Monthly Cost Breakdown  

| **Service**            | **Usage**                       | **Estimated Cost (USD)** |
|-------------------------|----------------------------------|--------------------------|
| Amazon EC2             | 4 t3.micro instances (180 hours)| $10.47                  |
| Amazon ELB             |  1 ALB                          | $7.00                   |
| Amazon RDS             | db.t3.micro instance            | $7.48                  |
| Amazon Secrets Manager      | 1 Secret                   | $0.07                 |                   |
| **Total Estimated Cost** | **N/A**                       | **$35.97/month**       |

## Cost Optimization Considerations  
- Use **Free Tier** wherever possible.  
- Optimize S3 by enabling lifecycle policies for older objects.  
- Leverage **Spot Instances** for non-critical workloads.  
- Enable **AWS Cost Explorer** for real-time monitoring.  

## Disclaimer  
This cost estimate is approximate and may vary based on actual usage and AWS pricing updates. Check the [AWS Pricing Calculator](https://calculator.aws) for detailed calculations.  
