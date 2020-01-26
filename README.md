# CoMon

 The primary goal of the Project CoMon is to secure, enhance and control the data flow of a mesh network with multiple gateways and multiple clients. The use of the data flow statistics, monitored in real time, will be necessary for easier bug fixing and general network maintenance in the future.


 Data flow monitoring and analysis structure for the whole system:
 - Top-to-Bottom OSI-Layer monitoring
 - Each interface in each layer will be monitored
 - interfaces are globally 'weighed' by certain parameters of the network system
 - the weigh must be a normalized value, to be comparable in every layer
 with every kind of interface
 - Anomalies in the course of the monitoring process must be categorized for the whole system
 - Connection problems in the system can be then narrowed down easily at a certain layer between 2 interfaces

 Analysis/Monitoring for each interface:
 - Data packages should be 'weighed' by size and transport speed
 - Statistical analysis of the weighed data flow at each interface
