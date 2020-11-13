# Azure service compariosn with AWS

https://docs.microsoft.com/en-us/azure/architecture/aws-professional/services

0. Aws Accounts ( Azure Subscriptions)

1. Azure Active Directory - It is a closed source (AWS IAM - open Source) 

2. Computing & Storage : 
    vms, , Functions (Lamda), Azure Storage (EBS), Virtual Machine Scale sets ( Load balancing), Azure VM scaling (auto scaling), Bob Storage (S3), File Storage    (EFS).

3. Secuity: Azure NSG's(security groups) - firewall beytween vms and vnets

4. Networking: Vnets (VPC), Subnets, DNS ( Route53), Express Route, Azure Traffic manager, , Load balancer (Network Load Balancer - Layer 4), Application Gateway (Layer 7), Firewall.

5. Databases: Azure RDS ( Azure SQl, MySQL, PostgreSQL).

# what you did on Azure?
My last assignment was cloud migration moving from premises to azure, My first step for migration was to create pre and post migration tasks. Choosing the best services on the cloud that suits our business requirement and considering cost estimation as our goal as to pay whatever we use (Cost estimation, License issue).


Extensilvely working with Azure  Network & Security  practices utilizing various services such as Virtual Networks (VNets), subnets, Azure network settings, DHCP address blocks, DNS settings, security policies and routing. 


configured Express Routes, Network Security Groups, Peering (Global Vnet and Private Peering), E2E flow for the Hybrid Connectivity, Flow Logs, Network Performance Monitoring (NPM), Service Endpoint, Fast Path, Private link, Network Watcher, Vnet Creation/Deletion, Vnet Injection, UDRs, Application Gateway.

I also worked   on both the Azure Infrastructure & Operations side. where my day-day work involves using Terraform to build the infrastructure as a code  such as provisioning/deprovisioning the services on Azure (computing side, Storage, Networking, Database, Monitoring, Security). Creating functions(SLS - serverless Framework ) using Python to implement serverless architectures. Azure Policies - Azure Policy is a service in Azure which allows you create polices which enforce and “control the properties of a resource”. 
Deny the resource change
Log the change to the resource
Alter the resource before the change
Alter the resource after the change
Deploy related compliant resources



# ARM Templates: (default templates provide by Azure for every service  using the schema for Deployments)
Where I cannot use ansible for deployed/configured. I used ARM templates. Ex: Standard  load balancer, Azure Policies. Where The templates are in a JavaScript Object Notation (JSON) file that defines the infrastructure and configuration for your project.

If I want to deploy  a function app- Storage account every time uploading data , changes in storage account taking snapshot and saving it diff storage account

# 
