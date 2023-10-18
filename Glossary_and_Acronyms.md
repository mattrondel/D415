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

Virtualization offers carriers the ability to offer pay-as-you-go services without huge up-front investment. Avoiding proprietary hardware empowers adminisators with a strealined provisioning process

If a service providers customeer requests a new funtion for example, NFV enabes the service prover to more easily add that service in the form of a VM without upgrading or buying new hardware.

### VNF 
Virtual Network Functions
**What this means** a software-based implementation of a network function (duh it’s in the name) that would be traditionally preformed by dedicated hardware appliances. VNF run on virtualized infrastructure and can deployed, managed and scaled more dynamically compared to traditional hardware-based solutions.
(According to Red Hat) - are software applications that deliver network functions such as file sharing, directory services and IP configurations

Know any examples? – not at this time

Google quick definition - Common VNFs include virtualized routers, firewalls, WAN optimization, and network address translation (NAT) services. Most VNFs are run in virtual machines (VMs) on common virtualization infrastructure software such as VMWare or KVM. (<- this sounds a lot like NFVs?)
3:20

### Questions to address:



##	NFV vs VNF ##
NFV converts network processes themselves into software applications, while SDN virtualizes the management of networks so you can gain features like application-based traffic prioritization.

An** SDN** can be considered a series of networking entites such as switches, routers and firewalls that are deployed in a highly automated manner.

**NFV** is the process of moving services like load balancing, firewalls an intrusion prevention systems away from dedicated hardware

(According to Red Hat) - these are not dependandt on each other but have similaries such as they both rely on virtualization and network abstration
SDN separates network forwarding functions from network control functions with the goal of creating a network that is centrally manageable and programmable. NFV abstracts network functions from hardware. NFV supports SDN by providing the infrastructure on which SDN software can run. 

NFV and SDN can be used together, depending on what you want to accomplish, and both use commodity hardware. With NFV and SDN, you can create a network architecture that is more flexible, programmable, and uses resources efficiently.

## OPENFV
Open Platform for NFV - a collaborative open-source platform that seeks to develop NFV and shape its evolution created by the linux foundation in 2014. It looks to reduce the time to market for NFV products and solutions.


###	Benefits and risks of SDN

###	How are NFV and SDNs related?

###	AAA vs RBAC 
Authentication, authorization, and accounting (AAA) is a term for a framework for controlling access to computer resources, enforcing policies and auditing usage. RBAC (Role Based Access Control) is a way that dictates how a subject can access objects.

RBAC - RBAC - Role Based Access Control is used to create differentiated access based on entitlement to administer a network device or controller

Note: There ia second AAA: Abstration Automation and Adjustment
https://ebookcentral.proquest.com/lib/westerngovernors-ebooks/reader.action?docID=5611487&ppg=32


### VNFM 
Virtual Network Functions Manager 
Manages the life-cycle of a Virtual Network Fucntion (VNF)
They are resposible for basic lifecyle management operations such as CRUD platform aware NFV load optimization, health monitoring, auto-scaling and VNF configuration management operation

### NFVO 
NFV Orchestrator is resposible for VIM resource check and allocation, SFC management using VNF forwarding graph descriptor, VNF placement policy, network service deployment using decomposed VNFs

### NFV-MANO 
Network Function Virtualization Management and Orchestration

Consists of all functional blocks, data repositories, reference points, and interfaces that are used for managing and orchestrating VNFs and the NFVI


### VIM 
Virtualized Infrastructure Manager 
this does what: 

### WICM
Wan Infrastructure connection manager 
this does what: 

### T-NOVA

### TeNOR
A store of all published VNFs. The design goal for TeNOR is lifecycle management of distributed and virtualized NFVI

### VNFI 

Virtual Network Function Infrastructure refers to the virtualized resources required to support the execution of Virtual Network Functions (VNFs). This infrastructure includes the compute, storage, and networking resources that VNFs need to operate effectivley.

(According to Red Hat) - Consists of the infrastructure components - compute, storage, networking - on a platform to support software such as a hypervisor like KVM or a container management platform, needed to run network apps.

• Virtual Network Functions infrastructure

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
