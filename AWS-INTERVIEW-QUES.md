******Some AWS Interview Question******

1. What is the role of IAM roles and policies?
2. Can you explain the Terraform plan and its purpose?
3. What is AWS Lambda, and how does it work?
4. How do you invoke a Lambda function, and where do you configure it?
5. Can you describe how Lambda handles scaling and event-based invocations?
6. What is Amazon CloudWatch, and have you configured any custom metrics?
7. What metrics are available on your CloudWatch dashboard?
8. How do you configure CPU utilization on your CloudWatch dashboard?
9. How do you attach an SSL certificate to an S3 bucket?
10. What type of encryption have you implemented in your project?
11. If an S3 bucket has a read-only policy, can you modify objects in the bucket?
12. Why did you choose Terraform over Boto3 for infrastructure provisioning?
13. What is a Content Delivery Network (CDN), and how does it work?
14. Have you created a Jenkins pipeline for your project?
15. How do you attach policies to IAM users, either individually or by group?
16. What type of deployment strategies are you using in your project?
17. Have you used any tools to create customized Amazon Machine Images (AMIs)?
18. What is connection draining, and how does it work?
19. How does an Elastic Load Balancer (ELB) distribute traffic?
20. What is auto-scaling, and how does it work?
21. Can you describe the different types of Load Balancers and provide examples?
22. What is the maximum runtime for a Lambda function?
23. What is the maximum memory size for a Lambda function?
24. How can you increase the runtime for a Lambda function?
25. What automations have you performed using Lambda in your project?
26. Why did you choose Terraform over Boto3 for infrastructure provisioning?
27. What modules have you used in your Lambda function?
28. Have you created an SNS topic for your project?
29. If you've exhausted IP addresses in your VPC, how would you provision new resources?
30. What is Groovy, and how is it used in Jenkins?
31. Why do you use Groovy in Jenkins, and where do you save Jenkins files?
32. What is Ansible, and what is its purpose?
33. What language do you use in Ansible?
34. Where do you run Terraform code, remotely or locally?
35. What is the purpose of access keys and secret keys in AWS?
36. What are Terraform modules, and have you used any in your project?
37. What environments have you set up for your project?
38. Do you use the same AWS account for all environments?
39. Do you have separate Jenkins servers for each environment?
40. Where do you write and save your Lambda function code?

    ******AWS VPC Interview Questions******

1. How does VPC peering work?
 VPC peering connects two VPCs for communication using private IPs. Traffic stays within AWS without transiting the internet.

2. What are route tables, and why are they important?
 Route tables define paths for traffic within a VPC and to external destinations (e.g., IGW, NAT).

3. Internet Gateway vs. NAT Gateway: 
 - IGW: Enables internet access for public subnet instances. 
 - NAT Gateway: Provides outbound internet access for private subnet instances.

4. Purpose of Security Groups and NACLs: 
 - Security Groups: Instance-level rules for inbound/outbound traffic. 
 - NACLs: Subnet-level, stateless rules for traffic filtering.

5. Restricting traffic between subnets: 
 Use NACLs or security group rules to limit access based on IP ranges or ports.

6. Designing a multi-region VPC architecture: 
 - Use Transit Gateway or VPC peering for inter-region connectivity. 
 - Ensure redundancy, low latency, and compliance with regulations.

7. AWS Transit Gateway vs. VPC Peering: 
 - Transit Gateway: Central hub for connecting multiple VPCs and on-prem networks. 
 - VPC Peering: One-to-one connection between VPCs.

8. Elastic Load Balancer (ELB) with VPC:
 Distributes incoming traffic across instances in subnets and enhances scalability and fault tolerance.

9. Ensuring high availability in a VPC design: 
 - Deploy resources across multiple Availability Zones. 
 - Use redundant IGWs, NAT Gateways, and load balancers.

10. VPC limits: 
 Default limits: 5 VPCs per region, 200 subnets per VPC. Limits can be increased via AWS Support.

