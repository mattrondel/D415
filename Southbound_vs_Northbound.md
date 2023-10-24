## Southbound vs Northbound

Think of the OSI lay with the highest number at the top with A being application which is the top or north of the stack

API is software talking to software

the controller talks to both north and south APIs

## Northbound

Sometimes called NBI

Whats its purpose?

Application and Control layers are connected to the Norhtbound API




## Southbound

Sometimes called SBI  

Whats its purpose?

The API allows the controller to communicate with the OpenFlow switch and network routers

From the control controller to the device the southbound api its used 2 protocols NETCONF and OpenFlow

##Notes 

1.	Southbound APIs:

a.	Southbound APIs refer to the interfaces and protocols used to communicate between the higher-level control plane and the lower-level data plane in a network architecture. The data plane is responsible for forwarding network traffic (packets) based on predefined rules, while the control plane manages the overall behavior of the network, including traffic routing, quality of service, security policies, and more.

b.	Southbound APIs allow the control plane to instruct the data plane on how to handle network traffic. These APIs enable communication from the higher-level network controller to the physical or virtual networking devices (such as switches, routers, or access points). They are used to configure, manage, and monitor network devices' behaviors, such as setting up routing tables, modifying access control lists, or implementing quality of service policies.

c.	Examples of protocols and technologies commonly used for southbound APIs include OpenFlow, NETCONF, and gRPC.

