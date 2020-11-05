---
title: "TR-069 Management Console"
#date: 2019-07-06T15:27:17+06:00
#draft: false
# page title background image
bg_image: "images/backgrounds/page-title.jpg"
# meta description
description : ""
# Research image
image: "images/neuron/PC2.jpg"
# type
#type: "research"
---

### Neuron ACS Console

* Neuron Tr-069 management console provides a unified platform for remote management of CPEs, such as router, modem, ONTs, VOIP, storage devices, IP-Phones, cameras, etc. 
Our Neuron Dashboard is user friendly, have easy access to group info, easy matrix about the estate, easy sidebar navigation, responsive design which will support mobile devices, display of the most recent CPR conatcts. All the different device arecentrally managed though the management console. 


{{<figure src= "/images/neuron/console.png" title="">}} 

#### CPE Stats
* CPE stats displays basic stats based on the running config of the CPE.
Such as, CPE Status, Device Info, WLAN status, LAN Status, LAN Status, WAN Status, Connected Device.

#### CPE Management
* Management console can manage multiple device from a singe user like modems, VOIP device and IP phones. This page shows managed device information, gives real time responce and real time data updates. Search query based on value or parameters, shows quick provisioning widgets, inform history and sessions, RPC history tracking and force connection request. 

#### Device Estate
* Device estate feature used for quick search for device, Search on any of the columns and quick navigation to CPE DEVICE STATS.

#### Policy Engine

The Management Console enables policy management and enforcement. We can defined policy per data model.The following policies can be defined and enforced:

* Communication time intervals: the time interval during which the CPE must notify the ACS and search for updates (Inform Time Interval)
* Polling: the parameter values that the CPE must inform periodically (polling), such as: QoS parameters, bytes sent/received, etc.
* User Updates: whether the CPE should inform the ACS immediately or during the next scheduled Inform if the user changed a value (such as SIP server name).
* Blocking: blocking the user from changing specific parameter values.

### Group Manager
The Management Platform enables remote configuration of a group of devices (mass update). The update may include parameter values, configuration or firmware files, and can be sent to:

CPEs of a specific CPE model type
Customer-defined groups of CPEs
The update can be performed immediately, or scheduled for a certain time and date. The customer can also control the frequency and quantity of updates to reduce ACS server load.

### Data models of TR-069 protocol

Most of the configuration and diagnostics is performed through setting and retrieving the value of the device parameters using Get parameter and Set parameters operations. Device parameters organized in a well-defined hierarchical structure that is mostly common to all device models. The solution supports below [Broadband Forum Technical reports.](https://cwmp-data-models.broadband-forum.org/)
* TR-69 – CPE WAN Management Protocol
* TR-098 – Internet Gateway Device Data Model for TR-69
* TR-104 – DSLHome™ Provisioning Parameters for VoIP CPE
* TR-106 – Data Model Template for TR-069-Enabled Devices
* TR-110 Issue 1.01 – DSLHome™ Reference Models for VoIP Configurations in the DSL Home
* TR-111 - Applying TR-069 to Remote Management of Home Networking Devices
* TR-131 – NBI requirements
* TR-135 – Data Model for a TR-069 Enabled STB
* TR-140 – TR-069 Data Model for Storage Service Enabled Devices
* TR-142 – Framework for TR-069 enabled PON devices
* TR-143 – Enabling Network Throughput Performance Tests and Statistical Monitoring
* TR-156 – Using GPON Access in the context of TR-101
* TR-157 – Component Objects for CWMP
* WT-181 – Device Data Model for TR-69
* TR-196 - Femto Access Point Service Data Model
