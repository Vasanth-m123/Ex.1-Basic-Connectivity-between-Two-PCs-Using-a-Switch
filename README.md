## Ex. No 1. 	Basic Connectivity between Two PCs Using a Switch
# Date : 		

# Objective

          “To configure and test basic LAN connectivity between two PCs using a switch.”
________________________________________
# Apparatus/Tools Required
•	Cisco Packet Tracer Software
•	Devices: PCs, Switch, Router, Cables
•	Optional: Wireless Router, Server, Cloud
________________________________________
# Network Topology Diagram

<img width="1920" height="1080" alt="Screenshot 2026-07-23 134445" src="https://github.com/user-attachments/assets/e9fa5aac-cc13-4d2a-a756-a35a103f2818" />

________________________________________
# IP Addressing Table (if applicable)
Device Name	Interface	IP Address	Subnet Mask
PC0	NIC	192.168.1.2	255.255.255.0
PC1	NIC	192.168.1.3	255.255.255.0
Router0	Fa0/0	192.168.1.1	255.255.255.0
________________________________________
# Procedure
Step-by-step commands/configurations.
Example:
1.	Open Cisco Packet Tracer and add two PCs and one Switch.
2.	Connect the PCs to the switch using straight-through cables.
3.	Assign IP addresses to the PCs.
4.	Use the ping command to verify connectivity.
________________________________________
# Commands Used (if any)

For PC IP assignment:<br>
nginx<br>
CopyEdit<br>
Desktop > IP Configuration > Enter IP: 192.168.1.2 / Subnet: 255.255.255.0<br>
For Router Configuration (CLI):<br>

________________________________________
# Output (Screenshots / Ping Results)

<img width="1920" height="1080" alt="Screenshot 2026-07-23 134834" src="https://github.com/user-attachments/assets/f159dc25-20c8-475b-9875-6acea611cca4" />
<img width="1920" height="1080" alt="Screenshot 2026-07-23 134845" src="https://github.com/user-attachments/assets/81285d0c-0ebd-44d4-bead-d59f062228b1" />
<img width="873" height="897" alt="Screenshot 2026-07-23 134408" src="https://github.com/user-attachments/assets/619dd2db-a661-4d18-90f8-2dbbd4466a4f" />
<img width="1920" height="1080" alt="Screenshot 2026-07-23 135820" src="https://github.com/user-attachments/assets/2b39751d-c488-423a-9526-9fcc8350e318" />


________________________________________
# Result
“Successfully configured and verified basic LAN communication between two PCs using a switch in Cisco Packet Tracer.”
	
