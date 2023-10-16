# networking-notes

## Virtual Private Clouds (VPCs)
Information found at: https://www.cloudflare.com/en-gb/learning/cloud/what-is-a-virtual-private-cloud/

### What is a VPC?
- A VPC is a private cloud hosted on a public cloud.
- Unlike a private cloud, whose infrastructure is built and run by the entity that uses it, VPCs are hosted by a third-party public cloud provider.
- VPCs are kept secure from the rest of the public cloud through IP subnets, virtual local area networks (VLANs) and virtual private networks (VPNs).
- A VPC is like a reserved table in a busy restaurant (public cloud); only those with the reservation can use the table, and the restaurant sets aside some of its space for that table.

### What are the benefits of using a VPC?
- Better performance.
- More scalable; hosting on a public provider such as AWS or Google means it is very easy to add more computing power when needed.
- Easy deployment.
- More secure; the big companies that host VPCs have the resources to continually improve their security. Organisations hosting their own private cloud would have to do this themselves.
- More affordable; money saved on hardware, labor, and other related cloud resources. The cloud provider will be responsible for all maintenance and upkeep for all physical servers and software. (https://www.checkpoint.com/cyber-hub/cloud-security/what-is-vpc-virtual-private-cloud/)
- Less (or, zero) downtime; if you host a private cloud yourself, you have to fix it when it goes down. Conversely, the major platforms that host VPCs have the tools and resources to essentially guarantee that they will back up and running as soon as possible, or even will never experience downtime.

### How do VPCs work?
How do VPCs live on a public cloud and yet remain isolated from everything else in the same space?

- Subnets: private IP adresses within the public cloud network that only the VPC has access to, and which cannot be reached via the public internet.
- VLAN (virtual local area network): a logical overlay network that groups together a subset of devices that share a physical LAN, isolating the traffic for each group. (https://www.techtarget.com/searchnetworking/definition/virtual-LAN)
- VPN (virtual private network): uses encryption to create a private network over the top of a public network. VPN traffic passes through publicly shared Internet infrastructure – routers, switches, etc. – but the traffic is scrambled and not visible to anyone. (https://www.cloudflare.com/en-gb/learning/cloud/what-is-a-virtual-private-cloud/)

