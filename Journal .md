# Journal 

## 1/1/2025
> Orginally planning to build out Windows server domain, but I nee
> Spent last couple of weeks re-working approach when I was able to get 3 Mini PCs hooked up together, and found out about proxmox VE. 
> I built out a multi=node proxmox cluster by creating a single Ubntu VM with apache, confirming locaal and external access, replacing default web page, and registering a domain with working DNS despite some intitial CNAMe and wildcard issues. After cloning the CM across al 3 nodes to work towards reduncacney, I begin settin gup load balancing but stopped when I realised all cloned VM's shared the same IP. I recorded, and set static IP's and domains shortyl after in Server Info. 