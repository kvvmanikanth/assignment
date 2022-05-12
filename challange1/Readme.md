3 TIER ARCHITECTURE IN AWS
--------------------------

1. Creating vpc in us-east-1 

2. Creating two availiabilty zones (us-east-1a & us-east-1b) for HA

3. Creating 2 public subnets for web & application, 1 private subnet for db in both zones

4. Creating Internet Gateway for internet to reach instances in public subnet 

5. Creating Route Table for routing the traffic to hit web instance

6. Creating ec2 instance for web server, application server in public subnet and instaling Apache in web server in it for other zone aswell

7. Creating security group for the web servers, application servers

8. Creating ec2 instance for db (RDS) & configuring security groups

9. Creating Application level load balancer & configuring it, which will forward traffic to public subnets
