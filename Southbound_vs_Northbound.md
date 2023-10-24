## Southbound vs Northbound

Think of the OSI lay with the highest number at the top with A being application which is the top or north of the stack

API is software talking to software

the controller talks to both north and south APIs

### Northbound

Sometimes called NBI

Whats its purpose?

Application and Control layers are connected to the Norhtbound API

**Notes**

2.	Northbound APIs:

a.	Northbound APIs, on the other hand, refer to the interfaces and protocols used to communicate between the control plane and higher-level applications or management systems. These APIs allow applications and management systems to interact with and control the underlying network infrastructure.

b.	Northbound APIs provide a way for external applications, services, or orchestrators to request network services, retrieve network status, and manipulate network behavior without needing to have detailed knowledge of the underlying network's internal workings. These APIs enable the creation of network applications, network automation, and integration of networking functions into larger software ecosystems.

c.	Examples of protocols and technologies commonly used for northbound APIs include RESTful APIs, WebSockets, and custom application-specific APIs.


### Southbound

Sometimes called SBI  

Whats its purpose?

The API allows the controller to communicate with the OpenFlow switch and network routers

From the control controller to the device the southbound api its used 2 protocols NETCONF and OpenFlow

OpenFlow is an API that gives direct access to and management of the forwarding plane on virtual and physical switches and routers

Netconf - network management prototocol used to install, manipulate and delte the configuration of network devices via RPC messagges are encoded in XML

REST allows controllers to montior and manage infrastrutcture through HTTP and HTTPS verbs ( GET, PUT, DELETE etc)

RESTCONF - 

OpFlex - controller is not the brains

**Notes**

1.	Southbound APIs:

a.	Southbound APIs refer to the interfaces and protocols used to communicate between the higher-level control plane and the lower-level data plane in a network architecture. The data plane is responsible for forwarding network traffic (packets) based on predefined rules, while the control plane manages the overall behavior of the network, including traffic routing, quality of service, security policies, and more.

b.	Southbound APIs allow the control plane to instruct the data plane on how to handle network traffic. These APIs enable communication from the higher-level network controller to the physical or virtual networking devices (such as switches, routers, or access points). They are used to configure, manage, and monitor network devices' behaviors, such as setting up routing tables, modifying access control lists, or implementing quality of service policies.

c.	Examples of protocols and technologies commonly used for southbound APIs include OpenFlow, NETCONF, and gRPC.

