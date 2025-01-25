How to Use the Visual Network Traffic Monitoring (VNTM) Software
Below is a step-by-step guide for users to effectively utilize the VNTM software, starting from capturing a PCAP file in Wireshark to generating KML files for visualization:

Step 1: Install Required Tools
Install Wireshark

Download and install Wireshark from its official website.
Ensure you have administrator privileges to capture live traffic.
Install VNTM Software

Download and install the Visual Network Traffic Monitoring (VNTM) software.
Ensure all dependencies, like Python and required libraries, are installed during setup.
Step 2: Capturing PCAP File
Open Wireshark

Launch Wireshark and select the appropriate network interface for traffic capture (e.g., Ethernet, Wi-Fi).
Start Capturing

Click the Start button to begin capturing network packets.
Filter Traffic (Optional)

Use display filters (e.g., ip.addr == 192.168.1.1) to focus on specific traffic types.
Stop Capturing and Save PCAP File

Once the capture is complete, click the Stop button.
Save the captured data by selecting File → Save As, and save it as a .pcap or .pcapng file.
Step 3: Uploading PCAP File to VNTM
Launch VNTM Software

Open the VNTM application on your system.
Import PCAP File

Navigate to the Import PCAP section.
Click on Upload File, browse to the saved PCAP file from Wireshark, and upload it.
Step 4: Analyzing Network Traffic
IP Address Extraction

VNTM will automatically extract source and destination IP addresses from the uploaded PCAP file.
Geolocation Lookup

The software integrates with geolocation services to map IP addresses to geographical locations.
Traffic Details

View detailed statistics, including protocol usage, packet sizes, and traffic flow summaries, in the analysis dashboard.
Step 5: Generating KML File
Convert to KML

In the Export Options, select Generate KML File.
VNTM will create a KML file by mapping the geolocation data to coordinates suitable for geographic visualization.
Save the KML File

Save the generated KML file to your desired location.
Step 6: Visualizing Data on Google Earth
Open Google Earth

Launch Google Earth on your system.
Load KML File

Navigate to File → Open, and select the generated KML file.
The network traffic data will be displayed as points on the map, indicating source and destination locations.
Analyze Visualization

Examine the visual representation of the traffic flow, helping to identify patterns, anomalies, or suspicious activities.
Step 7: Advanced Features (Optional)
Apply Filters

Use VNTM’s filtering options to focus on specific IP ranges, protocols, or time intervals.
Real-Time Monitoring

If supported, use VNTM for real-time packet capture and visualization.
Export Reports

Generate and export detailed reports in various formats like PDF or CSV for documentation or further analysis.
Tips for Effective Use
Regular Updates

Keep both Wireshark and VNTM software up to date for the best performance and compatibility.
System Resources

Ensure your system has adequate resources to handle large PCAP files, especially for high-traffic networks.
Data Privacy

Always handle network data responsibly, ensuring compliance with legal and ethical standards.
By following these steps, users can seamlessly capture network traffic, analyze it, and generate meaningful geographic visualizations with the VNTM software.