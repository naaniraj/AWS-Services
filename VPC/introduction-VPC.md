##  💼 What is vpc ?
**********************
![vpc](https://github.com/user-attachments/assets/99b22408-b71a-4757-831f-cbff0fc8053e)

VPC is a one of the service in aws  call vartuval private cloude ,

it's like a isolated network inside our server to protect our data ,

user sensitive information from hackers  by secure communicating .

its provide secure communication to our application .

 we configure every thing inside of our VPC 

##  VPC Archetture 
****************************
![vpc](https://github.com/user-attachments/assets/a5771092-66d3-4822-b2da-d779cd2ed613)

##  Components in VPC 
***********************
***✅ 1. Subnets***

subet is like a isolated space in our vpc to keep the data inside of it

  1 . Public Subnet – connected to the internet.
      we can cannact , and access the services that inside

  2 . Private Subnet – isolated from the internet.
       we cant acces from outside ,we keep user sensitive information herelike a data-base
       
***✅ 2. Internet Gateway (IGW)***

Allows communication between  VPC and the internet.

Required for public subnets to access the internet.

***✅ 3. NAT Gateway / NAT Instance***

Lets instances in private subnets access the internet (for updates, etc.) without exposing them directly.

NAT Gateway is a managed service, NAT Instance is a manually configured EC2.

***✅ 4. Route Tables***

Define how traffic is directed in your VPC.Each subnet must be associated with a route table.

***✅ 5. Security Groups***

Virtual firewalls for EC2 instances.Control inbound and outbound traffic at the instance level.

***✅ 6. Network Access Control Lists (NACLs)***

Firewall at the subnet level.Provide an extra layer of security with stateless traffic filtering.

***✅ 7. VPC Peering***

Allows communication between two VPCs (in the same or different accounts) using private IP addresses.

***✅ 8. Elastic IP***

Static public IP you can attach to an EC2 instance in your VPC.

***✅ 9. Endpoints (Interface & Gateway)***

Allow private connections from your VPC to AWS services without needing a NAT or IGW.

***✅ 10. DHCP Option Sets***

Controls DNS resolution within your VPC.

***✅ 11. Carrier Gateway / Transit Gateway***

Carrier Gateway – used for AWS Wavelength.
Transit Gateway – connects multiple VPCs and on-prem networks via a central hub.


