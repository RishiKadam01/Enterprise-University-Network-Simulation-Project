Enterprise University Network Simulation


📘 Introduction

This project simulates a scalable and secure enterprise network for a university consisting of two campuses separated by 20 miles.
It is designed in Cisco Packet Tracer and includes departments such as Health & Science, Business, Engineering & Computing, and Arts & Design.
The goal is to provide efficient communication, logical segmentation, and secure access for staff and students.


🎯 Objectives

Design and implement a complete university network topology in Cisco Packet Tracer.

Create and configure VLANs for departmental segmentation.

Implement RIP v2 for internal dynamic routing.

Configure Static Routes for external communication.

Set up router-based DHCP for automatic IP assignment.

Ensure secure and reliable communication between both campuses.

Document configuration, testing, and results for verification.



🧩 Project Scope

This project provides a full enterprise-level simulation with:

VLAN-based logical separation for all departments.

Dynamic and static routing between multiple campuses.

DHCP services for simplified IP management.

Inter-VLAN routing and trunk port configuration.

Security features including password protection and VLAN isolation.

Scalable design for future expansion.




🛠️ Network Components & Technologies

Cisco Packet Tracer (Simulation Environment)

Routers & Layer 3 Switches – Routing and VLAN communication

Layer 2 Switches – VLAN segmentation

RIP v2 – Dynamic internal routing
Static Routes – External connectivity

DHCP – Automated IP allocation

ACLs & Security – Controlled access and password protection




⚙️ Implementation Overview
VLAN Configuration

Each department is assigned a unique VLAN ID and subnet.
Example:

Department	VLAN ID	Subnet
Admin	10	192.168.1.0/24
HR	20	192.168.2.0/24
Finance	30	192.168.3.0/24
Engineering & Computing	50	192.168.5.0/24
Arts & Design	60	192.168.6.0/24
Routing

RIP v2 is used for dynamic routing within campuses.

Static Routes connect the network to external (cloud/internet) networks.

DHCP

A router-based DHCP server dynamically assigns IP addresses, gateways, and DNS settings for clients in Building A.

Inter-Campus Communication

Campuses are connected via Serial Interfaces with IP links (10.10.10.x/30). RIP v2 ensures automatic route learning between campuses.




🧪 Testing & Verification

Performed tests include:

✅ VLAN configuration verification using show vlan brief

✅ DHCP allocation verification with show ip dhcp binding

✅ Routing table inspection using show ip route

✅ Ping and traceroute tests for inter-campus communication

✅ Security and ACL validation




🚀 Results

Successful VLAN segmentation and inter-VLAN communication.

RIP v2 dynamic routing established between campuses.

DHCP successfully assigning IPs automatically.

Static routes properly configured for external communication.

Network performance verified through testing.





🔮 Future Scope

Upgrade to OSPF or EIGRP for faster convergence.

Add wireless networking with access points.

Implement firewalls and IDS/IPS for advanced security.

Introduce VPN tunnels for remote connectivity.

Use QoS policies to prioritize real-time traffic.

Explore network automation using Python or Ansible.




