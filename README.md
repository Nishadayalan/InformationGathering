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


### whois :

### netcat :

### nmap :
<img width="793" height="260" alt="image" src="https://github.com/user-attachments/assets/5b00ee75-7dfe-4151-8bc8-d6a7a2aa52c5" />


### whatweb :
<img width="812" height="152" alt="image" src="https://github.com/user-attachments/assets/d27eb1f0-9d57-452c-977d-2b37e0b955da" />


### httprint :

### TCP traceroute :
![WhatsApp Image 2025-08-21 at 08 27 26_97298e0b](https://github.com/user-attachments/assets/bb87c643-0a2d-481c-9ca1-effda6e584e4)


### UDP traceroute :
![WhatsApp Image 2025-08-21 at 08 28 57_9649ff45](https://github.com/user-attachments/assets/cea22edc-a9ee-4942-8754-79d87c6b64e8)


### ICMP traceroute:
![WhatsApp Image 2025-08-21 at 08 30 11_44aa4e9e](https://github.com/user-attachments/assets/fae77b0e-4c18-496e-8645-1770ea0261ae)


## RESULT:
The information gathering techniques tools/procedure were  identified successfully
