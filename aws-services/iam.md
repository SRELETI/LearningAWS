# Identity and Access Management

### Global Service



### Roles:



Why Roles? 

One of the reasons why roles were created is because of the security issue with using IAM user on EC2 instance. Without roles, if a application running on EC2 instance wants to access other AWS resources, it should be configured with a IAM user. If these IAM user credentials makes it way to the source code repo of the application, then you are giving away access to your AWS account through the IAM user. With roles, you just attach the roles to the running or new EC2 instance and it works.  

