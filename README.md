# DevOps Network Lab With Raspberry Pi 5

![Cover Image](./cover/cover.jpg)

## Table of Contents

- [Project Overview](#project-overview)

- [Architecture](#)

- [Technologies Used](#)

- [Folder Structure](#)

- [Setup Instructions](#)

    - [Step 1: Raspberry Pi Setup](#)

    - [Step 2: Pi-hole DNS and DHCP](#)

    - [Step 3: WireGuard VPN](#)

    - [Step 4: SSH Tunnel Proxy](#)

    - [Step 5: Monitoring Stack](#)

- [Challenges & Fixes](#)
- [Screenshots](#)
- [Lessons Learned](#)
- [Future Improvements](#)

## Project Overview

This DevOps-oriented network lab was designed using a **Raspberry Pi 5** as a core network server. The objective was to build a fully automated, observable, and secure home lab implementing:

- DNS and ad-blocking via **Pi-hole**

- VPN gateway using **WireGuard**

- Network traffic monitoring via **Prometheus + Grafana**

- SSH tunneling for secure remote browsing

## Components:

- Pi-hole (DNS + Ad-blocking)
- Dnsmasq (DHCP)
- Unbound (Recursive DNS Resolver)
- WireGuard (VPN)
- Prometheus + Grafana (Monitoring)

> Built as part of a DevOps lab environment to simulate real-world infrastructure with automation, observability, and security in mind.
