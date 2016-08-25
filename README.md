# Create 2 Virtual Machines from custom image and configures Load Balancing rules for the VMs

#For this template to work we need the following pre-requisits to be met:
1. Resource group to be created
2. Storage acount created with blob a container to host the custom VM image
3. VM image copied into the blob container via AZcopy


This template allows you to create a Virtual Machines from a custom image. This template also deploys a Virtual Network, Public IP addresses, Network Security Group, loadbalancer, Availability Set and  Network Interface. 
