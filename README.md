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

<img width="1920" height="1080" alt="Screenshot 2026-07-23 134445" src="https://github.com/user-attachments/assets/0261008a-9738-4547-af4f-8a4f79b446a1" />

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
<img width="1920" height="1080" alt="Screenshot 2026-07-23 134834" src="https://github.com/user-attachments/assets/054a2583-2560-4400-b2a4-e9c56740a7b8" />
<img width="1920" height="1080" alt="Screenshot 2026-07-23 134845" src="https://github.com/user-attachments/assets/5e0ce1d4-5974-4647-9fb5-2e64a70907d1" />
<img width="873" height="897" alt="Screenshot 2026-07-23 134408" src="https://github.com/user-attachments/assets/35a0769c-9095-4d9c-8e2b-04213892644e" />
<img width="1920" height="1080" alt="Screenshot 2026-07-23 134941" src="https://github.com/user-attachments/assets/93fc6b72-1c34-4b24-8d21-fc8089184d60" />

________________________________________
# Result
“Successfully configured and verified basic LAN communication between two PCs using a switch in Cisco Packet Tracer.”
	
