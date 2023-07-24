# implement-the-same-region-disaster-recovery-activepassive-failover-policy
I had done this project in Implement the same region disaster recovery in active passive failover policy
IMPLEMENTING SAME REGION DISASTER         RECOVERY IN ACTIVE PASSIVE FAILOVER POLICY
Project details:
         In this project, I had done backup and restore the primary environment for the AWS cloud infrastructure in same region disaster recovery for active passive failover routing policy and give alert email notification for any ec2 instance state is changed for production environment.
         
Steps to build this project:
Step 1: Create a Secure Socket Layer certificate in amazon certificate manager.
Step 2: Create a hosted zone in Route 53 and attached to the domain.
Step 3: Create a subnet group and database in RDS.
Step 4: Create an IAM role for ec2 instance.
Step 5: To launch an ec2 instance for production and DR server.
Step 6: Create a classic load balancer for production and DR server.
Step 7: Mapping with load balancer in route 53 for create failover records.
Step 8: ACM certificate mapping with load balancer.
Step 9: Create a S3 bucket and Synchronuos the production and DR server.
Step 10: Create alert notification for ec2 instance state change (SNS,AMAZON EVENTBRIDGE RULE).
