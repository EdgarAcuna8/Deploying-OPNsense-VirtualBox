# Deploying an OPNsense NGFW in Virtual Box
<p align="center" width="100%">
    <img src="https://github.com/EdgarAcuna8/Deploying-OPNsense-VirtualBox/assets/146898815/e7973722-5d92-4c41-bc72-b9185f275a76">
</p>

## Introduction

In this project, I deployed an OPNsense firewall on a virtualized environment using Virtual Box. I created a Windows and Kali Linux client connected to the firewall to test out various features. Through this lab, I learned:

- Virtual networking in Virtual Box
- Install and setup OPNsense firewall instance
- Enable IPS mode and configure custom Suricata rules to generate alerts
- Enable web proxy for internal clients
- Configuring Zenarmor for Next-generation firewall (NGFW) capabilites

## Overview
<p align="center" width="100%">
    <img src="https://github.com/EdgarAcuna8/Deploying-OPNsense-VirtualBox/assets/146898815/77e46e38-315b-4136-859a-db211f6a2c58">
</p>

VM Setup:
1. OPNsense Firewall with 2 network adapters - NAT and internal network (serving as LAN)
2. Kali Linux Client with 2 network adapters as above, since I used this machine for initial setup
3. Windows 10 Client with internal network adapter
