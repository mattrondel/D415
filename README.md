D415

Flash cards:  https://ankiweb.net/decks

SDN WGU Course notes

## Learning Opportunities

It is highly recommended that you use the following resources to maximize your success:

•	“Introduction to SDN and OpenFlow (3:29:00)” from Udemy (David Bombal) 
https://lrps.wgu.edu/provision/381720354

•	“Introduction to Cisco Automation and Software Defined Networks (1:24:00)” from Pluralsight (Ross Bagurdes)
https://lrps.wgu.edu/provision/303933736

•	“SDN and SD-WAN Fundamentals: Intro to Software-defined Networking (1:12:00)” from Pluralsight (Sean Douglas)
https://lrps.wgu.edu/provision/303938265



Watch the following video to strengthen your knowledge:


"5 SDN Concepts You’ve Gotta Know" (1:56:37) from Kevin Wallace Training, LLC

https://lrps.wgu.edu/provision/308889815

“Cisco Network Security: Core Security Concepts” (1:46) from LinkedIn Learning

https://lrps.wgu.edu/provision/308882104

“Learning Network Troubleshooting” (2:01) from LinkedIn Learning

https://lrps.wgu.edu/provision/308882281

## Course Chatter notes:

"Passed this course a few days ago with about 2 weeks of studying. As others have said STRONGLY recommend watching the 3 videos listed in the course material. The book isn't too long of a read but I do recommend reading that as well to supplement the videos. Know the acronyms NFV, VNF, VNFM, VNFI, CVSS. I also recommend if you have not taken CCNA or have no background in network security(firewalls) brush up on those sections in the book. NIST 800-125B, NIST 800-53 were not explained deeply in the book but I googled on my own to get a better understanding."

"Passed on my first attempt last night. As others have stated, the 3 videos in the beginning are critical as well as the reading material. I switched over from the Cloud Deployment and Operations course after failing twice, and this course was 10000x better in my opinion. I had multiple questions on OpenStack, SDN vs NFV, NIST 800-53 and 800-125b, CVSS, Southbound VS Northbound interface, and firewalls. The PA is a great indicator of how you'll do, so just review the sections you missed and you'll be fine. You got this!!!"

------------------
Secure Virtual Network configuration for VM Protection

This is to secure vm workloads

Section 4.4 makes 4 recommendations for protecting VM workloads with modern architecture

•	VM-FW-R1 – In virtualized environments its best to have delay sensitive items virtualized like firewalls to avoid latency. 

•	VM-FW-R2 – For I/O virtualized sensitive applications kernel based virtual firewalls should be deployed instead of subnet level because kernal based virtual firewalls preform packet processing in the kernel of the hypervisor at native hardware speeds

•	VM-FW-R3 – for subnet and kernel based virtual firewalls it is preferable if the firewall is integrated with a virtual management platform rather than accessible through a stand-alone console. The former with enable easier provisioning of uniform firewall rules to multiple firewall instances, thus reducing the chances of configuration errors.

•	VM-FW-R4 - for subnet and kernel based virtual firewalls it is preferable that the firewall supports rules using higher level components or abstractions in addition to the basic 5 tuple  (source/dest IP address, source/destination ports protocol)

FYI 5 tuple means the five attributes: 


•	Source IP address (the address you're coming from)

•	Source port (usually any, but could be changed if needed)

•	Destination IP address (the address you're going to)

•	Destination port (typically 80, 443 or 25, but could be anything)

• Destination protocol (TCP or UDP)

https://ebookcentral.proquest.com/lib/westerngovernors-ebooks/reader.action?docID=5611487&ppg=152

IPS implementations 

•	Often sit behind a firewall 

•	Inline product

•	Send alarms to the admins

•	Drop the malicious packets

•	Blocking traffic from the source address

•	Reset the connection(s)

•	Uses either signature detection and/or statistical anomaly based detection

•	IDS implementations

•	IDS is passive typically used span or tap done this way because they couldn’t keep up with in real-time, basically a listen only device and can’t take action automatically

•	Detection mechanism is typically signature based and exploit facing signatures.

•	Out of band 

------------------
## Bastion Hosts

The bastion host processes and filters all incoming traffic and prevents malicious traffic from entering the network, acting much like a gateway. The most common examples of bastion hosts are mail, domain name system, Web and File Transfer Protocol (FTP) servers. Firewalls and routers can also become bastion hosts. This hosts are typlcially places in the DMZ

Bastion hosts serve as a main point of contact for incoming connections

Basion hosts define a clear boundry between trusted and untrusted domains

## SDN Planes

Northbound plane - is the link between the applcations and SDN controller

Application plane - was developed for telemetry to communicated behaviors and needed resources to the controller

	think applcations create telemetry data
	
Data Plane - software based and users transmit packets through this plane

Control Plane - consists of one or more controllers and deals with the network toplopgy including the information about the routing table

	this is considered the brain of the system and is the center of SDN achitecture. this is the most important component and controls ass the dta plane devices


Solarwinds NPN - can detect dianose and resolve preformace problems

Network telemetry - refers to a server acting as intermedaiary between a client asking for resources and server with the resources

Open stack make memorable items
https://www.geeksforgeeks.org/introduction-to-openstack/


## EOL 

EOL hardware often comes with high maint costs as the parts become had to find as they are discontinued

EOL hardware has limited ability to adapt to the incresing needs of networks eg 2550 cisco switch - decreased productivity

EOL hardware that no longer receives patches fixes and firmware updates leads to increase security risks/compromised data

EOL hardware can fail and reduce/decrease productivty 

worded oddly but traceroute can trace the router of a packet within a network

The vSAN Ruby vSphere Console (RVC) is a undocumented feature of vSAN that allows you to explore some pretty kick-ass features of vSAN in terms of what-if scenarios, cluster info, and dashboard information from the vCenter server appliance.

VMware vSAN is an enterprise storage virtualization software that supports hyper-converged infrastructure (HCI)

## VNF life cycle

5 stages:

•	Development
•	Instanantiation
•	Operation 
•	Enchancement 
•	Retirement


Service function chaining
