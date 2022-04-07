# cloudformation_rds_template
aws cloud formation template for rds postgres aurora with public access
This Repository provides cloudformation template for rds postgres aurora 11.9 and can be upgraded to any version.
The Template stack creates vpc,2 public subnets,igw,gatewayattachment,routetables for both subnetsand security groups, rds cluster postgres aurora instances on the mentioned vpc.
