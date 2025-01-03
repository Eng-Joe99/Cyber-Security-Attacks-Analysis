# Cybersecurity Attacks Analysis and Dashboard  

This repository contains a data analysis project focused on global cybersecurity incidents. The project aims to uncover patterns and insights using data cleaning, exploration, and visualization techniques. The final deliverable includes a dashboard created in Power BI to effectively communicate the findings.

---


# About Dataset
__Consists of 25 varied metrics and 40,000 records__

Welcome to Incribo's synthetic cyber dataset! Crafted with precision, this dataset offers a realistic representation of travel history, making it an ideal playground for various analytical tasks.

Use the cybersecurity attacks dataset to help you assess the heatmaps, attack signatures, types, and more!

Remember, this is just a sample! If you're intrigued and want access to the complete dataset or have specific requirements, don't hesitate to contact us(info@incribo.com). Happy building!

__Dataset Overview:__

  🌐 Source: __Dataset is taken from [Kaggle](https://www.kaggle.com/datasets/teamincribo/cyber-security-attacks/data)__

  📆 Duration: The dataset chronicles cyber narratives from January 1, 2020, to October 11, 2023.
    
  📊 Shape: Encompassing 40,000 data entries, the records consists of 25 varied metrics.


* __Columns:__
  * Timestamp: The time at which the network activity occurred.
  * Source IP Address: The IP address of the sender or initiator of the network traffic.
  * Destination IP Address: The IP address of the receiver or target of the network traffic.
  * Source Port: The port number used by the source IP address.
  * Destination Port: The port number used by the destination IP address.
  * Protocol: The communication protocol used (e.g., TCP, UDP, ICMP).
  * Packet Length: The size of the packet in bytes.
  * Packet Type: Type of packet (e.g., data packet, control packet).
  * Traffic Type: The type of traffic (e.g., web traffic, email traffic).
  * Payload Data: The actual data transmitted in the packet.
  * Malware Indicators: Indicators of potentially malicious activity or presence of malware.
  * Anomaly Scores: Scores indicating deviations from expected behavior, used for anomaly detection.
  * Alerts/Warnings: Notifications or warnings generated by security systems or monitoring tools.
  * Attack Type: Type of attack detected or suspected (e.g., DDoS, SQL injection).
  * Attack Signature: Specific patterns or signatures associated with known attacks.
  * Action Taken: Actions performed in response to detected threats or anomalies.
  * Severity Level: The level of severity associated with an alert or event (e.g., low, medium, high).
  * User Information: Information about the user involved in the network activity.
  * Device Information: Information about the device involved in the network activity (e.g., device type, operating system).
  * Network Segment: The segment or subnet of the network where the activity occurred.
  * Location: Geographical location information associated with IP addresses.
  * Proxy Information: Information about proxy servers involved in the network communication.
  * Firewall Logs: Logs generated by firewall devices indicating allowed or blocked traffic.
  * IDS/IPS Alerts: Alerts generated by Intrusion Detection Systems (IDS) or Intrusion Prevention Systems (IPS) indicating suspicious or malicious activity.
  * Log Source: The source or origin of the log entry (e.g., name of the logging system or device).



---




## Project Overview  
The primary objective of this project is to analyze cybersecurity attack data, identify trends, and provide actionable insights. The analysis includes:  
- Data cleaning and preprocessing  
- Exploratory data analysis (EDA)  
- Visualization of key metrics and trends
- Data Validation

The final Power BI dashboard showcases insights emphasizing user-friendly and impactful design.

---


## Tools and Technologies  
- **Python**: Used for data cleaning and exploration  
- **Power BI**: Used for creating the final dashboard  
- **Pandas & NumPy**: Libraries for data manipulation and computation
- **Microsoft SQL Server**: Used for data validation

---

## Key Insights  
Some of the insights drawn from the analysis include:  
- The total number of attacks by country can help identify how different regions or cities within the same country compare in terms of attack frequency. A particular city might have vulnerabilities in its cybersecurity infrastructure or might be a frequent target due to political, economic, or technological factors.
 
- User information associated with each attack may reveal patterns such as the types of users or businesses targeted in different cities. For instance, cities with more corporate or government infrastructure might show a higher volume of sophisticated attacks aimed at large organizations.

  
- A correlation between high anomaly scores and malware detection can suggest a strong relationship between the severity of network activity anomalies and the presence of malicious software.

- Analyzing which protocols (e.g., TCP, UDP, ICMP) are most frequently used in attacks can reveal common methods attackers use to penetrate networks. For example, a high prevalence of TCP-based attacks may indicate that attackers exploit specific vulnerabilities in TCP connections.

  
---

## Dashboard  
The final Power BI dashboard is designed to provide a comprehensive data view, with filters and interactive visuals for deeper exploration.
                                              
  **You can explore it through the Power Bi folder**

---


