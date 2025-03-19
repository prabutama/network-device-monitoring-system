# Network Device Monitoring System Using ThingsBoard

This repository contains the development of a **Network Device Monitoring System** leveraging the **ThingsBoard IoT platform**. The system is designed to monitor and manage network devices (such as routers, switches, and servers) in real-time using the **SNMP (Simple Network Management Protocol)** protocol. The project integrates ThingsBoard's powerful IoT capabilities with custom gateway configurations to collect, visualize, and analyze network performance metrics.

## Key Features

1. **Real-Time Monitoring**:
   - Collects real-time data from network devices using SNMP, including CPU usage, memory utilization, bandwidth, and interface status.
   - Provides live dashboards for visualizing network health and performance.

2. **ThingsBoard Integration**:
   - Utilizes ThingsBoard as the central IoT platform for data storage, processing, and visualization.
   - Custom dashboards and widgets are created to display network metrics in an intuitive and user-friendly manner.

3. **Custom SNMP Gateway**:
   - A custom **ThingsBoard Gateway** is implemented to bridge SNMP-enabled devices with the ThingsBoard platform.
   - Supports multiple SNMP devices and allows for easy configuration through JSON files.

4. **Alerting and Notifications**:
   - Configurable alerts are set up to notify administrators of critical events, such as high CPU usage, link failures, or unusual traffic patterns.
   - Notifications can be sent via email, SMS, or other integrated messaging platforms.

5. **Scalable and Modular Architecture**:
   - The system is designed to be scalable, allowing for the addition of new devices and metrics with minimal configuration.
   - Docker containers are used for easy deployment and management of the ThingsBoard server, gateway, and database.

6. **Data Visualization**:
   - Interactive dashboards provide insights into network performance trends, device status, and historical data.
   - Customizable widgets allow users to tailor the monitoring experience to their specific needs.

## Technologies Used

- **ThingsBoard**: Open-source IoT platform for data collection, processing, and visualization.
- **SNMP**: Protocol used for monitoring and managing network devices.
- **Docker**: Containerization for easy deployment and scalability.
