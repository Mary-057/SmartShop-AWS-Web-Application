# SmartShop AWS Web Application
 Company Web App
 This project documents the pocess of launching an EC2 instance and deploying a web server on it
 ## VPC linking and subnet
 The already created Vpc and public subnet by LITA was chosen to house the AWS resources
 ![Vpc] (/Vpc.png)
 ![Public_subnet] (/Public_subnet.png)
  ### Key Pair Creation
 A key pair was created to secure the EC2 instance and prevent unauthorised access. Below is the image
![Key_Pair] (/Key_Pair.png)
### Security Group Creation
Created security group with inbound rule to allow SSH and HTTP traffic
![Security_group] (/Security_Group.png)
#### Launched EC2 instance
![EC2 instance] (/EC2instance.png)
Deployed Apache web server to the instance
![Apache] (/Apache.png)
