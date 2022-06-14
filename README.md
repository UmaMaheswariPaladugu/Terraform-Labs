# Terraform-Labs

## Task Details :

1. We need to use terraform to do this. Create a module called private hosted zone, which accepts a input domain name.

2. Create a first VPC. (only vpc, no need of subnets, RT, NATGW, IGW)

3. Create a secondary VPC (only vpc, no need of subnets, RT, NATGW, IGW)

4. Create Private hosted zone for VPC1. (use input hosted zone)

5. Associate Private hosted zone with VPC2.

6. Delete VPC1 after private hosted zone is connected with VPC2. (This may require customization)
