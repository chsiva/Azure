# Azure service compariosn with AWS

https://docs.microsoft.com/en-us/azure/architecture/aws-professional/services

Computing & Storage : 
vms, , Functions (Lamda), Azure Storage (EBS), Virtual Machine Scale sets ( Load balancing), Azure VM scaling (auto scaling), Bob Storage (S3), File Storage (EFS).

Secuity: Azure NSG's(security groups) - firewall beytween vms and vnets

Networking: Vnets (VPC), Subnets, DNS ( Route53), Express Route, Azure Traffic manager, , Load balancer (Network Load Balancer - Layer 4), Application Gateway (Layer 7), Firewall.

Databases: Azure RDS ( Azure SQl, MySQL, PostgreSQL).




# ARM Templates: (default templates provide by Azure for every service  using the schema for Deployments)
Where I cannot use ansible for deployed/configured. I used ARM templates. Ex: Standard  load balancer, Azure Policies. Where The templates are in a JavaScript Object Notation (JSON) file that defines the infrastructure and configuration for your project.

If I want to deploy  a function app- Storage account every time uploading data , changes in storage account taking snapshot and saving it diff storage account

# 
