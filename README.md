1. What is AWS and why is it popular?
   
Answer: AWS (Amazon Web Services) is a comprehensive cloud platform offering computing, storage, networking, databases, analytics, and more. It's popular for its global scalability, reliability, cost-effectiveness, and pay-as-you-go model. 


3. What are the types of cloud service models (IaaS, PaaS, SaaS)?


IaaS: Infrastructure managed by users (e.g., EC2, EBS).

PaaS: Platform managed by AWS (e.g., Elastic Beanstalk).

SaaS: Fully managed apps (e.g., WorkMail) .


3. Define cloud computing.

On-demand delivery of IT resources—compute, storage, databases—over the internet, with pay-as-you-go pricing .


5. What are key AWS services?
   
EC2: Scalable virtual servers.

S3: Durable object storage.

RDS: Managed relational databases.

IAM: Access control.

VPC: Private virtual network 


5. What is EC2?
   
Elastic Compute Cloud—virtual machines running on-demand with customizable configurations .


7. What is S3?
   
Scalable object storage with 11-nines durability, used for backups, assets, and analytics. 


9. Describe the difference between S3 and EBS.
    
S3: Object storage over HTTP.
EBS: Block-level persistent storage for EC2 instances 

8. What is an AMI?
   
An Amazon Machine Image—a template (OS, configuration, apps) used to launch EC2 instances .

10. Stop vs terminate EC2 instance?
    
Stop: Shuts down instance; retains EBS volume.
Terminate: Deletes instance and attached volumes 


10. What is IAM?
    
Identity & Access Management—manages users, groups, roles, and policies for secure access control .


12. What is a VPC?
    
Virtual Private Cloud—a logically isolated network, with customizable IP ranges, subnets, and routing .

14. Public vs private subnet?
    
Public: Has Internet Gateway (IGW) access.
Private: No IGW; usually accesses internet via NAT 

13. What is Auto Scaling?
    
Automatically adjusts EC2 capacity based on load metrics, to maintain performance and cost efficiency .


15. Spot vs Reserved vs On-Demand instances?
    
On-Demand: Flexible, pay-as-you-go.
Reserved: Discounted rates in exchange for commitment.
Spot: Cheapest, but may be interrupted .


15. What is ELB—types?
    
Elastic Load Balancing distributes traffic across EC2.

ALB: HTTP/HTTPS.

NLB: TCP/UDP.

Classic ELB: Legacy 


16. What is CloudFront?
    
Global CDN that accelerates content delivery and supports geo-targeting. 


18. What are CloudWatch and CloudTrail?
    
CloudWatch: Monitors metrics, logs, and alarms.
CloudTrail: Logs AWS API calls for audit/debugging . 


18. What is AWS Lambda?
    
Serverless compute service—runs code in response to events; scales automatically; pay per execution .


20. What is CloudFormation?
    
Infrastructure-as-Code—defines and provisions AWS resources as templates, deployed via stacks .


22. What is RDS vs DynamoDB?
    
RDS: Managed relational databases (MySQL, PostgreSQL, etc.).
DynamoDB: Fully managed NoSQL with low latency and auto scaling 


21. What is Snowball?
    
Physical transport appliance for transferring large data sets to/from AWS securely .


23. Name cloud deployment models.
    
Public: AWS-managed infrastructure.
Private: Dedicated on-premises/cloud VPC.
Hybrid: Mix of public and private via VPN/DirectConnect 


23. What is the Shared Responsibility Model?
    
AWS secures the cloud (hardware, facilities); customers secure within the cloud (apps, data, configuration) .

24. How do you secure data at rest and in transit?

Use encryption: S3/KMS/TLS for transport, server-side encryption for storage.
Leverage VPC endpoints, ACM SSL/TLS certs .



25. How to reduce EC2 cost spikes?
    
Monitor with CloudWatch, Cost Explorer.
Right-size instances.
Switch to Reserved/Spot.
Automate schedules.
Tag and report cost
