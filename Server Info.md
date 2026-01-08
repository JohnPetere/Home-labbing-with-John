# Server Info

## HTPC
**IP:** 192.168.10.84:32400
**DNS:** htpc-plexmedia.com:32400
### Software
 - Plex Media Server
 - Surf Shark: VPN
 - Ubuntu Desktop

## Pi Hole
**IP:** 192.168.10.99
**DNS:** htpc-plexmedia.com:32400
### Software
 - OS: DietPi
 - OpenSSH
 - DietPi
### Pi Hole setup 
 - set Initial Static IP in Router
  - Web Console > System > Settings > DNS > Condtional formatting
    - true,192.168.10.0/24,192.168.10.1,lan.box
### Router setup
 - Settings > Networks > network
  -DNS Server(s)
    - Primary:192.168.10.99 (Pi Hole DNS)
    - Secondary: 8.8.8.8
    - 
    -
## Proxmox Cluster

### Main Node
Name: PVE1
**IP:**  192.168.10.92:8006 /24
**DNS:**  proxmox-cluster-pve1.com:8006

### Secondary Node
Name: PVE2
**IP:**  192.168.10.93:8006 /24
**DNS:**  proxmox-cluster-pve2.com:8006


### Secondary Node
Name: PVE3
**IP:**  192.168.10.94:8006 /24
**DNS:**  proxmox-cluster-pve3.com:8006


