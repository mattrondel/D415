Decent recommended book

https://ebookcentral.proquest.com/lib/westerngovernors-ebooks/reader.action?docID=5611487&ppg=210#

"Know your acronyms (eg: NFV, VNF, VNFM, VNFI, CVSS)"
•	Name

•	What it means

•	Whats it used for 

•	Additonal question to solve


### NFV - 
Network functions virtualization 

(According to red Hat) With NFV, service providers can run network functions on standard hardware instead of dedicated hardware. Also, because network functions are virtualized, multiple functions can be run on a single server. NFV gives providers the flexibility to run VNFs across different servers or move them around as needed when demand changes. This flexibility lets service providers deliver services and apps faster. 

For example, if a customer requests a new network function, they can spin up a new VM to handle that request. If the function is no longer needed, the VM can be decommissioned. This can also be a low-risk way to test the value of a potential new service.

Know any examples? – the CSR vm we have is this.
Virtualing network functions


### VNF 
Virtual Network Functions
**What this means** a software-based implementation of a network function (duh it’s in the name) that would be traditionally preformed by dedicated hardware appliances. VNF run on virtualized infrastructure and can deployed, managed and scaled more dynamically compared to traditional hardware-based solutions.
(According to Red Hat) - are software applications that deliver network functions such as file sharing, directory services and IP configurations

Know any examples? – not at this time

Google quick definition - Common VNFs include virtualized routers, firewalls, WAN optimization, and network address translation (NAT) services. Most VNFs are run in virtual machines (VMs) on common virtualization infrastructure software such as VMWare or KVM. (<- this sounds a lot like NFVs?)
3:20

### Questions to address:

##	NFV vs VNF
NFV converts network processes themselves into software applications, while SDN virtualizes the management of networks so you can gain features like application-based traffic prioritization.

(According to Red Hat) - these are not dependandt on each other but have similaries such as they both rely on virtualization and network abstration
SDN separates network forwarding functions from network control functions with the goal of creating a network that is centrally manageable and programmable. NFV abstracts network functions from hardware. NFV supports SDN by providing the infrastructure on which SDN software can run. 

NFV and SDN can be used together, depending on what you want to accomplish, and both use commodity hardware. With NFV and SDN, you can create a network architecture that is more flexible, programmable, and uses resources efficiently.

###	Benefits and risks of SDN

###	How are NFV and SDNs related?

###	AAA vs RBAC 
Authentication, authorization, and accounting (AAA) is a term for a framework for controlling access to computer resources, enforcing policies and auditing usage. RBAC (Role Based Access Control) is a way that dictates how a subject can access objects.

RBAC - RBAC - Role Based Access Control is used to create differentiated access based on entitlement to administer a network device or controller

Note: There ia second AAA: Abstration Automation and Adjustment
https://ebookcentral.proquest.com/lib/westerngovernors-ebooks/reader.action?docID=5611487&ppg=32


### VNFM 

### VNFI 
(According to Red Hat) - Consists of the the infratructure componets - compute, storage, networking - on a platform to support software such as a hypervisor like KVM or a container management platfor, needed to run network apps.

•	Virtual Network Functions infratructure

### CVSS •	Free and open industry standard for assessing the severity of computer system security vulnerabilities

•	It's a way to evaluate and rank reported vulnerabilities in a standardized and repeatable way.

•	It’s a standard framework used to asset and communicate the severity of vulnerabilities in software and systems. it assigns a numerical score to vulnerabilities based on factors like the impact, exploitability and complexity of the vulnerabilities. The CVSSS score helps organizations prioritize, their response to security vulnerabilities.

•	CVSS is an open-source framework for identifying and defining software vulnerabilities.


### SDS
Software Defined storage - common charaterists of SDS products include the ability to aggregatee storage resouces, scale out the system across a server cluster, manage the shared storage pool and storage services though a single administrative interface and set polices to control storage features and functionality

### SDDC
Software-Defined Data Centers
often reffered to as a data center where al infrastructure is virtualized and delivered as a service. Control of the data center is fully automated by software

### Software defined power SDP
https://ebookcentral.proquest.com/lib/westerngovernors-ebooks/reader.action?docID=5611487&ppg=34



### Network Automation facts
Ansible – written in python



### SDLC

Bonus: not mentioned in material
NFVI

Service chaining - multiple VNFs map together in a process called service chaining for seamless fully functional communication services 

## Attacks and Exploitation 

•	During the reconnaissance phase the attacker gathers information about the target electronically or physically  

•	Vulnerability is the state of being exposed to the possibility of the network being attacked

•	cyber kill chain terms:

•	There are 8 phases:

https://www.crowdstrike.com/cybersecurity-101/cyber-kill-chain/

•	Phase 1: Reconnaissance

•	Phase 2: Weaponization

•	Phase 3: Delivery – happens when the attack is transmitted to the intended victim

•	Phase 4: Exploitation – occurs when an attack actually happens

•	Phase 5: Installation – happens when the attacker installs malware on the system

•	Phase 6: Command and Control – implies that once a system is compromised it has to call home to a command and control system

•	Phase 7: Actions on Objective

•	eighth step: Monetization (added 
