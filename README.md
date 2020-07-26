# Home lab Network diagram
This repo shows Network diagram and lists Operating systems and Services that are used to build out my Home Lab. The idea behind building out a home lab is to ensure, the lab is network segmented, use a Firewall, set up scans to identify vulnerabilities etc. This repo also keep tracks of the changes/upgrades that are made to the lab over the period of time.

### Network Diagram
![alt text](images/Home_Lab.jpg)
*[Draw.io](https://app.diagrams.net/) is used to draw Network diagram.*

### Services
- [Pi-hole](https://pi-hole.net/) used for DNS.
- [Bookstack](https://www.bookstackapp.com/) used for organising and storing information.
- [Nextcloud](https://nextcloud.com/) used for home cloud.
- [Starter Page](https://github.com/scurtyhub/startpage) used for hosting home page for Web Browser.
- [Nginx](https://www.nginx.com/) used for Reverse Proxy.
- [Docker](https://www.docker.com/) used for Container platform.
- [Watchtower](https://github.com/containrrr/watchtower) to update running containers.
- [InfluxDB](https://www.influxdata.com/) used as a time series database.
- [Grafana](https://grafana.com/) used for visualization.
- [Anchor Engine](https://anchore.com/) used for container scanning.
- [Nessus](https://www.tenable.com/products/nessus) used to scan hosts on the network.

### Operating systems
- [PfSense](https://www.pfsense.org/) on Protectcli device.
- [Cisco IOS](https://www.cisco.com/c/en/us/products/ios-nx-os-software/index.html) on Cisco Switch.
- [Noobs Lite](https://www.raspberrypi.org/downloads/noobs/) on Raspberry Pi.
- [Ubuntu server](https://ubuntu.com/download/server) on Hypervisor.
- [Proxmox virtualization](https://www.proxmox.com/) on Dell PowerEdge T30.
- [DD-WRT](http://www.dd-wrt.com/) on Netgear Router.