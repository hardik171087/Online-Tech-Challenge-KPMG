This template will deploy:

1. One Virtual Network with four subnets
2. 4 Network Security Groups, one for each subnet
3. External Load Balancer to load balance Web Traffic(HTTP & HTTPS) to web servers
4. Internal Load Balancer to load balance traffic for app VM's
5. 2 Public IPs, one for external Load balancer and other for Jump Host
6. VM Availability Zones for Web Tier, Application Tier and Database tier
7. One Jump Host to faclitate RDP access to all other tier VMs
8. Multiple windows VMs
