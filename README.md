# VPC-Peering
Virtual-Private-Cloud-Peering-Connection
A VPC peering connection is a networking connection between two VPCs that enables you to route traffic between them using private IPv4 addresses or IPv6 addresses. Instances in either VPC can communicate with each other as if they are within the same network.



## VPC Peering Configurations

1. Create two VPCs.
2. Create & attach two Internet gateway to the VPC.
3. Create Subnets under both the VPCs.
4. Create Route Tables, edit routes and associate them with the appropriate subnets.
5. Create Resources(EC2 instance) under both the subnets. 


## Peering Connection:

1. Select the option Peering connection in the VPC dashboard.
2. Click on Create peering connection 



1. Give a name to the peering connection and create the connection

1. Accept VPC peering connection request, Click on Actions, and select Accept request.


1. In the route tables, edit routes, add the peering connection in the routes.



1. We can access the machine created in the second VPC(Demo vpc-2).


## Summary

You can establish VPC peering connections to enable private communication between VPCs within your AWS infrastructure.