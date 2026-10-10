**🌐 AWS VPC Peering – Private Network Connectivity**

📌 Project Overview

This project demonstrates how to establish a VPC Peering connection between two Amazon Virtual Private Clouds (VPCs) to enable private communication between resources in different VPCs.

The project includes VPC creation, CIDR block configuration, VPC Peering, route table updates, and network connectivity verification using AWS services.

🎯 Objectives

- Connect two VPCs using VPC Peering.
- Enable private communication between VPC networks.
- Configure route tables for traffic routing.
- Control network access using security groups.
- Understand AWS networking concepts.

🛠️ Technologies Used

- ☁️ Amazon Web Services (AWS)
- 🌐 Amazon VPC
- 🔗 VPC Peering Connection
- 🛣️ Route Tables
- 🔐 Security Groups
- 🖥️ Amazon EC2 (if used for connectivity testing)

🏗️ Project Architecture

VPC 1 — `10.0.0.0/16`  
⬇️  
VPC Peering Connection  
⬇️  
VPC 2 — `192.168.0.0/16`

The two VPCs use different CIDR blocks to avoid IP address overlap. Route tables must be configured on both sides to enable traffic through the peering connection.

✨ Key Features

- 🌐 Two VPCs Connected Using VPC Peering
- 🔗 Private Network Communication
- 🛣️ Route Table Configuration
- 🔐 Secure Network Access Using Security Groups
- 📡 Non-Overlapping CIDR Blocks
- ☁️ AWS Cloud Networking
- ✅ Connectivity Testing Between VPCs

⚙️ Implementation Steps

1. Created two VPCs with non-overlapping CIDR blocks.
2. Configured the required subnets in each VPC.
3. Created a VPC Peering connection between the VPCs.
4. Accepted the peering request.
5. Updated the route tables to direct traffic through the peering connection.
6. Configured security group rules to allow the required traffic.
7. Tested private connectivity between resources, if EC2 instances were configured.


📈 Project Outcome

Established a VPC Peering connection between two VPCs and configured the necessary routing to enable private communication between their networks.

📚 Key Learnings

- AWS VPC and subnet configuration
- CIDR blocks and IP addressing
- VPC Peering setup and acceptance
- Route tables and network routing
- Security group configuration
- Private network connectivity

🏁 Conclusion

This project provided hands-on experience with AWS networking and demonstrated how VPC Peering can connect two separate VPCs for private communication without requiring traffic to pass through the public internet.

👩‍💻 Author

**Ashwini Jankar**

Cloud & DevOps Learning Projects
