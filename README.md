# Ex-02 InformationGathering
Information Gathering Techiques

# To perform information gathering techniques

# AIM:

To perform information gathering techniques using kali linux 

## STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode

### Step 2:

Investigate on the various categories of tools as follows:

### Step 3:
Open terminal/browser and try execute necessary commands/use url to perform information gathering

## Architecture Diagram
```
                      +-------------------------+
                      |     Attacker System     |
                      |     (Kali Linux)        |
                      +-----------+-------------+
                                  |
                                  | Terminal / Browser
                                  | Executes Recon Tools
                                  v
      +------------------- Passive Recon --------------------+
      |                                                     |
      |  +----------------+     +------------------------+  |
      |  |   WHOIS Query  | --> |    Domain Registrars    |  |
      |  +----------------+     +------------------------+  |
      |                                                     |
      |  +----------------+     +------------------------+  |
      |  |   DNS Enum     | --> |     Public DNS Servers  |  |
      |  +----------------+     +------------------------+  |
      |                                                     |
      +-----------------------------------------------------+

                                  |
                                  v

      +------------------ Active Recon ----------------------+
      |                                                     |
      |  +----------------+     +------------------------+  |
      |  |   Nmap Scan    | --> |  Target Host/Network    |  |
      |  +----------------+     +------------------------+  |
      |                                                     |
      |  +----------------+     +------------------------+  |
      |  | WhatWeb, Wapp | --> |   Target Web Application |  |
      |  +----------------+     +------------------------+  |
      |                                                     |
      |  +----------------+     +------------------------+  |
      |  | theHarvester   | --> |     Search Engines      |  |
      |  +----------------+     +------------------------+  |
      +-----------------------------------------------------+

                                  |
                                  v
                    +-----------------------------+
                    |     Collected Information   |
                    | - IPs, Subdomains           |
                    | - Open Ports & Services     |
                    | - Technology Stack          |
                    | - Emails, Metadata          |
                    +-----------------------------+
```

## OUTPUT:
### Whois:
![882b7d2a1d734535be81b69eca257bc8](https://github.com/user-attachments/assets/faa0700c-72d1-4927-85f4-5bbba4ec574d)


### Finding Hosting Company :
![9f4a78c877244ab1a4714b5a228c18c3](https://github.com/user-attachments/assets/a08b9892-76cd-4e3c-a621-012427eca740)


### History of the website :
![3ae19a91b189484dab1832e95ac49e4b](https://github.com/user-attachments/assets/f838f5ba-d8c6-4666-aa23-90d6d321b24c)


### ping command :
![4dc47b07a8bd46148650ad426737f95d](https://github.com/user-attachments/assets/7e8d0588-37a3-4531-8e0c-34e603498507)


### netcat :
![45cba155f61247fa8d44c79619e2d5b4](https://github.com/user-attachments/assets/0dfdff82-9bc7-4e65-9d6e-cfc6b020b270)


### nmap :
<img width="793" height="260" alt="image" src="https://github.com/user-attachments/assets/5b00ee75-7dfe-4151-8bc8-d6a7a2aa52c5" />


### whatweb :
<img width="812" height="152" alt="image" src="https://github.com/user-attachments/assets/d27eb1f0-9d57-452c-977d-2b37e0b955da" />


### httprint :
<img width="808" height="292" alt="image" src="https://github.com/user-attachments/assets/b2d5d3cf-9838-4d30-bbc7-11b45775c90c" />


### TCP traceroute :
<img width="801" height="151" alt="image" src="https://github.com/user-attachments/assets/0f20773f-3390-492f-930a-7d851756c599" />


### UDP traceroute :
<img width="812" height="342" alt="image" src="https://github.com/user-attachments/assets/b6972374-7622-457c-aa80-62a738e6f18b" />


### ICMP traceroute:
<img width="803" height="428" alt="image" src="https://github.com/user-attachments/assets/0ef055ba-0673-4058-9919-16af1aaa07ac" />



## RESULT:
The information gathering techniques tools/procedure were  identified successfully
