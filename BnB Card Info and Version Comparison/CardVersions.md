# Backdoors and Breaches
### Author:Robin Noyes
## Version Differences: Compare and Contrast 
This section will only call out specific differences between decks.  If the card existed in a prior release version, only the number of new cards will be noted.  Full deck card names are in the Deck List section.

#### Core Deck  
_**_ Initial Compromise
Versions 1-3 have minor differences within the Initial Compromise cards.  Version 3 changes *Trusted Relationship* to *Compromised Trusted Relationship* , *Password Spray* to *External Password Spray* , and *Web Server Compromise* to *Compromised Web server *.  

_**_Pivot and Escalate_**_
No differences in techniques and tactics. 

_**_C2 and Exfil
Version 3 changes *Gmail, Tumblr, SaleseForce, Twitter/X as exfil* to *Cloud-Based Services as Exfil* which could encompass Saas (Zoom, Slack, Google, etc)  , Iaas (AWS, Google, Azure, Akami, IBM Cloud, etc ) , File Sharing and Data storage (Dropbox, Google Drive, OneDrive, Box, etc )  .

_**_Persistance_**_
No differences in techniques and tactics. 

_**_Injects_**_
Version 1 had *Management has Just Approved the Release of a New Procedure* .  Version 2 introduces two new cards, *Memory Analysis* and *Cyber Deception* .  These are also available in ICS/IOT V1.1 Version 3 added two new cards *Permissions Audit* and * Cloud Event Log Analysis * .   Both of these cards are seen again in Trimaran V1, Denscure V1, Cloud Security V1 and V1.2. 

_**_Consultants
There are no consultant cards in the Core decks.

#### Expansion Deck
_**_Initial Compromise:Three new cards
_**_Pivot and Escalate:  Five new cards: 
_**_ C2 and Exfil: One new card 
_**_Persistance: Five new cards
_**_Procedures: Two new cards 
_**_Injects: Ten new cards
_**_Consultants: Introduces Consultants and adds 10 new cards

#### Huntress 
_**_Initial Compromise: Four new cards
_**_Pivot and Escalate: Two new cards: 
_**_ C2 and Exfil: Two new card 
_**_Persistance: Four new cards
_**_Procedures: One new card 
_**_Injects: Fourteen new cards
_**_Consultants: Six new cards

#### Trimarc 
_**_Initial Compromise: Seven new cards
_**_Pivot and Escalate: Seven new cards: 
_**_ C2 and Exfil: Two new card 
_**_Persistance: Two new cards
_**_Procedures: One new card 
_**_Injects: Fourteen new cards
_**_Consultants: Six new cards

#### Red Canary 
_**_Initial Compromise: Five new cards
_**_Pivot and Escalate: Seven new cards: 
_**_ C2 and Exfil: Two new card 
_**_Persistance: Four new cards
_**_Injects: Eight new cards
_**_Consultants: Three new cards

#### Densecure
_**_Initial Compromise: Seven new cards
_**_Pivot and Escalate: Seven new cards: 
_**_ C2 and Exfil: Three new card 
_**_Persistance: Four new cards
_**_Injects: Eight new cards

#### Datadog
_**_Initial Compromise: Eight new cards
_**_Pivot and Escalate: Three new cards: 
_**_ C2 and Exfil: Three new card 
_**_Persistance: Five new cards
_**_Injects: Eight new cards

#### Cloud Security
The major difference between version 1 and 1.1 is the assignment of the tactic.  Version 1 has * Identity and Access Management (IAM) Policy Abuse* as Initial Compromise, whereas Version 1.1 has this as Pivot and Escalate.  

#### ICS/IOT 
_**_Initial Compromise: Seven new card
_**_Pivot and Escalate: Four new cards: 
_**_ C2 and Exfil: Four new card 
_**_Persistance: Four new cards
_**_Procedure: Six new cards
_**_Injects: Nine new cards

#### Bonus
_**_Consultants: Ten new cards

## Deck List
### Core Deck V1
#### Released 2019
_**_ Initial Compromise 
- Credential Stuffing
- Exploitable External Service
- Bring Your Own (Exploited) Device
- Social Engineering
- Trusted Relationship
- Password Spray
- Insider Threat
- Web Server Compromise
- External Cloud Access
- Phish
  
_**_Pivot and Escalate
- Local Privilege Escalation
- New Service Creation/Modification
- Credential Stuffing
- Internal Pasword Spray
- Kerberoasting
- Broadcast/Multicast Protocol Poisoning
- Weaponizing Active Directory

_**_ C2 and Exfil
- HTTP as Exfil
- HTTPS as Exfil
- DNS as C2
- Windows Background Intelligent Transfer Service (BITS)
- Gmail, Tumblr, Salesforce, Twitter/X as C2
- Domain Fronting as C2

_**_Persistance
- Accessibility Features
- Evil Firmware
- Logon Scripts
- Malicious Browser Plugins
- Application Shimming
- New User Added
- Malicious Driver
- DLL Attacks
- Malicious Service/Just Malware

_**_Procedures
- Endpoint Analysis
- User and Entity Behavior Analytics (UEBA)
- Server Analysis
- Firewall Log Review
- Criss Management
- Netflow, Zeek/Bro, Real Intelligence Threat Analytics (RITA) Analysis
- Security Information and Event Management (SIEM) Log Analysis
- Isolation
- Endpoint Security Protection Analysis
- Internal Segmentation

_**_Injects
- Honeypots Deployed
- It was a Pentest
- Data Uploaded to Pastebin
- SIEM Analyst Returns from Splunk Training
- Take One Procedure Card Away
- Give the Defenders a Random Procedure Card
- Lead Handler Has a Baby, Takes FMLA Leave
- Bobby the Intern Kills the System You Are Reviewing
- Legal Takes Your Only Skilled Handler Into a Meeting to Explain the Incident
- Management has Just Approved the Release of a New Procedure

_**_Consultants
There are no consultant cards in the Core Decks

### Core Deck V2
#### Released 2021
_**_ C2 and Exfil
-  Removed Internal Segmentation
- Memory Analysis
- Cyber Deception
_**_Injects
- Removed *Management has Just Approved the Release of a New Procedure*

### Core Deck V2.2
#### Released 2022
No changes from V2.2

### Core Deck V3
#### Released 2025
_**_ Initial Compromise 
- Same as V1 with minor renames
- Compromised Trusted Relationship
- External Password Spray
- Compromised Web Server 

_**_ C2 and Exfil
- Cloud-Based Services as Exfil

_**_Procedures
- Same as V2 plus
- Permissions Audit
- Cloud Event Log Analysis
  
_**_Injects
- Removed *Honeypots Deployed*, *Take One Procedure Card Away*, 
*Give the Defenders a Random Procedure Card*, and *Lead Handler Has a Baby, Takes FMLA Leave* . 
- Analyst Returns from IR Training
- Policy?  What Policy?
- Luck of the Soc

### Expansion Deck V1.2
#### Released 2021
_**_ Initial Compromise 
- Physical Access
- Supply Chain Attack
- Missing HTTP Strict Transport Security (HSTS) Protection

_**_Pivot and Escalate
- AccesssToken Manipulation
- SMB WEAKNESS
- Internal Spearphishing
- Cleartext Passwords in Files
- Stale Network Address Configuration (SNAC) Attack

_**_ C2 and Exfil
- Exfil over Physical Medium

_**_Persistance
- Malware Injection Into Client Software
- Malicious Email Rules
- Windows Recovery Service
- Registry Key Peristance
- Evenet Triggered Malware
  
_**_Procedures
- Physical Security Review
- Call a Consultant
  
_**_Injects
- It was a Pentest
- Data Uploaded to Pastebin
- Analyst Returns from IR Training
- Bobby the Intern Kills the System You Are Reviewing
- Legal Takes Your Only Skilled Handler Into a Meeting to Explain the Incident
- Policy?  What Policy?
- Luck of the Soc

_**_Consultants
- Chris Brenton
- Jorge Orchilles
- Robert M. Lee
- Alethe Denis
- Eric Conrad
- Cloe Messdaghi
- Marcus J. Carey
- Tim Medin
- Alissa Torres
- Deter Smith

### Huntress V1
#### Released 2021
_**_ Initial Compromise 
- Public Facing Database Compromise
- Fake Software Update
- Exchange Zero-Day Vulnerability Exploit
- Embedded Remote Trojan (RAT)

_**_Pivot and Escalate
- Unpatched Critical Security Update
- Malware Propagation

_**_ C2 and Exfil
- Clipboard Scrape
- Rotating C2 Server Location

_**_Persistance
- Hiding in Plain Sight
- Registry Modification
- Living off the Land
- WMI Events

_**_Procedures
- Call a Consultant

_**_Injects
-  Major Failure Alert
- Lets Rock
- Read to the End
- That Was a Bad Idea
- Back to Basics
- Ignore Those Pesky Open Ports
- Rookie Mistake
- Risk Accepted
- A Little Help From My Friends
- Knowledge Is Power
- Haste Makes Waste
- A Bad Day Made Worse
- Alert Fatigue Is Real
- Security Training For The Win

_**_Consultants
- Jamie Levy
- John Hammond
- Harlan Carvey
- Cat Contillo
- Mathew Brennan
- Kyle Hanslovan

### Densecure V1 
#### Released 2021
_**_ Initial Compromise 
- Publicly Exposed Secret Key
- Trojan Mail
- HTML Smuggling
- Vendor Default Credentials Attack
- Wi-Fi Guest Network Escape
- Microsoft Direct Send Phishing
- Vishing

_**_Pivot and Escalate  
_**_ C2 and Exfil
_**_Persistance
_**_Procedures  
_**_Injects  
_**_Consultants  

### Red Canary V1
#### Released 2023
_**_ Initial Compromise   
_**_Pivot and Escalate  
_**_ C2 and Exfil
_**_Persistance
_**_Procedures  
_**_Injects  
_**_Consultants

### Trimarc V1
#### Released 2024
_**_ Initial Compromise   
_**_Pivot and Escalate  
_**_ C2 and Exfil
_**_Persistance
_**_Procedures  
_**_Injects  
_**_Consultants

### Datadog V1
#### Released 2025
_**_ Initial Compromise   
_**_Pivot and Escalate  
_**_ C2 and Exfil
_**_Persistance
_**_Procedures  
_**_Injects  
_**_Consultants

### Cloud Security V1
#### Released 2021
_**_ Initial Compromise   
_**_Pivot and Escalate  
_**_ C2 and Exfil
_**_Persistance
_**_Procedures  
_**_Injects  
_**_Consultants

### Cloud Security V1.1
#### Released 2023
_**_ Initial Compromise   
_**_Pivot and Escalate  
_**_ C2 and Exfil
_**_Persistance
_**_Procedures  
_**_Injects  
_**_Consultants

### ICS/IOT (Dragos) V1
#### Released 2022
_**_ Initial Compromise   
_**_Pivot and Escalate  
_**_ C2 and Exfil
_**_Persistance
_**_Procedures  
_**_Injects  
_**_Consultants

### Bonus
_**_Consultants