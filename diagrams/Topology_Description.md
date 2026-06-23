# Logical Topology Overview

The TechFusion Enterprise Network follows a hierarchical network design model consisting of an Internet edge, core layer, access layer, server infrastructure, and a remote branch office.

## Headquarters

The headquarters network contains:

* Edge Router for Internet and WAN connectivity
* Cisco 3560 Multilayer Switch for inter-VLAN routing
* Two Cisco 2960 Core Switches connected using LACP EtherChannel
* Department-specific access switches
* Dedicated server infrastructure

## VLAN Segmentation

The network separates departments into individual VLANs:

* Management
* Human Resources
* Finance
* Information Technology
* Sales
* Guest Network
* Server Network

## Branch Office

The branch office is connected to headquarters using a WAN link and dynamic routing through OSPF.

The branch contains:

* Branch Router
* Branch Access Switch
* End-user devices
* Network printer

## Design Goals

* Scalability
* Redundancy
* Security
* Simplified administration
* Enterprise network architecture

