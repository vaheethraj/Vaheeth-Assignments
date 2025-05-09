Task Description:

Set up a VPC with an Internet gateway, create a public subnet with 256 IP addresses, a private subnet with 256 IP addresses, make a route table connecting the Internet gateway and the subnets, and launch a Linux EC2 instance by using the above VPC and public subnet.


Solution :

1. Choose a Region and create a VPC with CIDR Block (10.0.0.0/16)
2. Attach an igw to this VPC 
3. Create a public subnet by choosing an AZ 
4. Create a privare subnet by choosing an AZ 
5. Create a route table for Public subnet , edit the routes , add routes to internet gatweay and then associate the route table to the Public subnet
6. Create a route table for Private subnet and associate it to the private subnet

<img width="924" alt="image" src="https://github.com/user-attachments/assets/073238c9-578c-408b-8607-0297f7e9991f" />

![image](https://github.com/user-attachments/assets/483f8410-ad71-4cf4-8a08-f4b86597adfd)

![image](https://github.com/user-attachments/assets/32683846-e694-4357-ac6a-c677583c7f78)

![image](https://github.com/user-attachments/assets/5a4dc7e7-9663-40c5-8cfc-edf44969c3cb)

![image](https://github.com/user-attachments/assets/92166afc-747c-4c73-bd7b-4369dfc5ea7e)




