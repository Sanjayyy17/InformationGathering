# InformationGathering
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
<img width="1036" height="845" alt="Screenshot 2025-09-19 135656" src="https://github.com/user-attachments/assets/a1486d02-29a0-4760-9012-be77853458a5" />



### Finding hosting company:
<img width="803" height="648" alt="488735909-c3d50300-13bd-4126-953a-18474cf689ab" src="https://github.com/user-attachments/assets/156fef06-e249-4fa7-ac91-71b39dcd406b" />

### History of the website:
<img width="1624" height="912" alt="488736190-58f8cce0-ba3a-4546-9d93-b09be950bc2a" src="https://github.com/user-attachments/assets/42c2e3a1-dc82-417a-a4ab-06dedfda835f" />



<img width="1920" height="1009" alt="kali linux  Running  - Oracle VirtualBox 19-09-2025 14_07_36" src="https://github.com/user-attachments/assets/c23895da-b99d-4274-8328-909622095915" />
<img width="1920" height="1009" alt="kali linux  Running  - Oracle VirtualBox 19-09-2025 14_08_00" src="https://github.com/user-attachments/assets/e96d451c-ecbe-4a6e-8f41-fbfc738ae714" />

<img width="1920" height="1009" alt="kali linux  Running  - Oracle VirtualBox 19-09-2025 14_08_07" src="https://github.com/user-attachments/assets/3b9956a5-f3c6-4ce3-9443-328215957190" />

### Finding Hosting Company :
<img width="1920" height="1009" alt="kali linux  Running  - Oracle VirtualBox 19-09-2025 14_12_39" src="https://github.com/user-attachments/assets/02951086-6e50-457d-8181-f7efa9605f8d" />
<img width="1920" height="1009" alt="kali linux  Running  - Oracle VirtualBox 19-09-2025 14_12_43" src="https://github.com/user-attachments/assets/d7476e08-0ad2-4bcb-a05f-ec4a1eb7937a" />

### nmap:
<img width="1920" height="1009" alt="kali linux  Running  - Oracle VirtualBox 19-09-2025 14_21_06" src="https://github.com/user-attachments/assets/aa1c686a-0fdc-4d62-bfa7-88a38bd45018" />

### whatweb :
<img width="1920" height="1009" alt="Captures - File Explorer 19-09-2025 14_32_05" src="https://github.com/user-attachments/assets/e2ce6d7e-c09a-4ef7-82fc-793e3e8fc5bf" />

### TCP traceroute :
<img width="1920" height="1009" alt="madhanraj67_InformationGathering _ Information Gathering Techiques - Google Chrome 19-09-2025 14_24_02" src="https://github.com/user-attachments/assets/5fe39656-8592-455a-9414-67566654a30c" />

### UDP traceroute :
<img width="1920" height="1009" alt="InformationGathering_README md at main · YendluriChandana_InformationGathering - Google Chrome 19-09-2025 14_26_08" src="https://github.com/user-attachments/assets/8db43724-6841-4adb-8f0a-7b9da8a55d9a" />



## RESULT:
The information gathering techniques tools/procedure were  identified successfully
