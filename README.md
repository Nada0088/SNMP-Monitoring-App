# SNMP-Monitoring-App

###### A tool to supervise, monitor the network and alert in case of an anomaly 

The SNMP (Simple Network Management Protocol) is a popular monitoring protocol that began with network elements but has since expanded to be used in any hardware or software. 
To graph performance data or send alarms, all monitoring systems support it out of the box (examples are applications like nagios or cacti).
This protocol employs a hierarchical namespace that contains Object IDentifiers (OID), which are represented as a list of numbers (typically 1.3.6.13.6.1...).
Each OID identifies a variable that may be read and/or written using the protocol and represents a real magnitude (for example in a network device the speed negotiated by a port or if this port is connected).
Standardized OIDs are mapped to meaningful names using a MIB (Management information base) that describes each OID. 

It comes with nice HMTL5 UI:
* Dashboard that shows overview of last messages
* Displays messages sent by specific host
* Displays messages per severity
* Displays specific messages received
* Live update of received traps

and more.

You can set severity level for each received message, ignore specific message types, create maintenance periods
for hosts, set per-user quiet hours and more.


Notifications are set per-user/severity, by default aupported are:
* Email notification
* Pushover notification
* SMS notification
* Slack/Mattermost notification

The can be easily extended to any other custom notification type.


## screenshots

Some sample UI screenshots can be found below:
![Screen1](/css/screenshots/Screen1.png?raw=true "Screen1")
![Screen2](/css/screenshots/Screen2.png?raw=true "Screen2")
![Screen3](/css/screenshots/Screen3.png?raw=true "Screen3")
![Screen4](/css/screenshots/Screen4.png?raw=true "Screen4")


## setup




