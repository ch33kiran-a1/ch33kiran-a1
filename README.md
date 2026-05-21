# Azure Linux High Availability Infrastructure

## Overview

Built a highly available Linux infrastructure environment in Microsoft Azure using Ubuntu virtual machines, Azure Load Balancer, NSG-based traffic filtering, Nginx web hosting, HTTPS, and SSH hardening.

---

## Architecture

Internet
   ↓
Azure Load Balancer
   ↓
vm-web-01
vm-web-02

---

## Technologies Used

- Ubuntu 24.04
- Azure Virtual Machines
- Azure Load Balancer
- Azure NSG
- Azure VNet
- Nginx
- Certbot SSL
- SSH Key Authentication
- Azure Monitor

---

## Features

- High availability web deployment
- Load balancer failover testing
- HTTPS-enabled custom domain
- SSH key-based authentication
- NSG traffic filtering
- Linux troubleshooting practice
- Monitoring and incident simulation

---

## Troubleshooting Scenarios Practiced

- SSH connection failures
- NSG rule misconfiguration
- Nginx service outages
- DNS resolution issues
- Disk space exhaustion
- High CPU utilization
- SSL certificate troubleshooting

---

## Linux Commands Used

```bash
df -h
du -sh /*
top
ps -ef
journalctl -xe
systemctl status nginx
ss -tulnp
curl
