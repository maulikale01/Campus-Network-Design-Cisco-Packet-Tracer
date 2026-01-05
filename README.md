# Campus Network Design & Wireless Segmentation
**Tool Used:** Cisco Packet Tracer 8.2

## Project Overview
This project simulates a university campus network connecting multiple buildings: Male/Female Hostels, a Library, and an Administrative Office. It demonstrates the ability to manage wireless zones, configure inter-building connectivity, and deploy network services (DNS/HTTP).

## Key Features Implemented
* **Wireless Zoning:** Configured distinct Access Points for 4 separate zones (Male Hostel, Female Hostel, Library, Office) to manage user traffic.
* **Server Integration:** Deployed HTTP and DNS servers (10.0.0.2, 10.0.0.3) to simulate internal web hosting and domain resolution.
* **Network Topology:** Star topology connecting multiple buildings via a central distribution switch (Switch0).
* **Connectivity Verification:** Successful ICMP (Ping) connectivity established between all end devices and servers (as seen in the "Last Status" log).

## Visual Topology
![Network Topology](topology_diagram.png)

## How to Run
1. Download the `.pkt` file.
2. Open with Cisco Packet Tracer (Version 8.2 or newer).
3. Use the simulation mode to observe packet flow between the Hostels and the Library Server.
   
