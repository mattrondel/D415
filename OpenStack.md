OpenStack

**OpenStack Wiki pages:**

https://wiki.openstack.org/wiki/Main_Page

Open-source cloud computing platform, joint project of Rackspace hosting and NASA

READ MORE

https://ebookcentral.proquest.com/lib/westerngovernors-ebooks/reader.action?docID=5611487&ppg=114

### Breakline for new thoughts

https://www.geeksforgeeks.org/introduction-to-openstack/

https://www.techtarget.com/searchstorage/tip/Everything-you-need-to-know-about-OpenStack-modules

School material

https://ebookcentral.proquest.com/lib/westerngovernors-ebooks/reader.action?docID=5611487&ppg=115

### Designate used to point applications in the OpenStack environment to a trusted DNS source. Since it seeks to enhance the security in the environment, it is often Designated as straddling the management and secure functions.




## Core Modules

### Nova 
Compute module used to create and delete compute instances

### Glance
Synchronizes and maintains VM images across the compute cluster. Virtual machine image management THINK: Virtual Machine Images at a Glance

### Keystone
 Authentication for accessing all of openStacks services

### Cinder
 is used for block storage as volumes for VMs

### Swift
 Object Storage used to store large amounts of static data in a cluster. Improve efficacy and scalability of user storage and unstructured data THINK SWIFT STROAGE

### Neutron
 Networking allows compute and storage nodes to communicate with each other THNK: Neutron Star Networking


## Management Modules 

### Horizon
A GUI dashboard and is widely deployed management module - keyword DASHBOARD 

### Heat 
Helps expedite orchestration of applications across multiple compute instances by using templates similar to CloudFormation

### Celiometer monitors the NFVI and helps identify bottlenecks and resource optimization opportunities 

### Ironic 
Provisioning tool for bare metal installs The Ironic module is forked from the Nova bare metal driver

### Congress
A policy management framework for the openstack environment


## Security Modules 

### Barbican

Barbican is a REST API designed for the secure storage, provisioning and management of secrets such as passwords, encryption keys and X.509 Certificates. 

Is the Key manager service it provides secure storage, provisioning and management of secret data, such as password, encryption keys, X509 Certificates and raw binary data

Should be used to improve the storage and management of secure authentication information. Works with Keystone authentication to manage internal application security by behaving as a key manager.

### Murano
 Provides a white list repository of applications


## Service Modules 

### Trove
 it’s a distributed database service and enables users to deploy relational and non-relational database engines

### Sahara
 Used to be called Savanna - Big data services by providing elastic MapReduce and the ability to provision Hadoop

### Maila
 NAS solutions for OpenStack deployment

### Zaqar
 provides a muliti0tenant cloud messaging service

### Magnum
 umbrella project for container assitance. Module is still under development

 Openstack overview notes:

 ![openstack](https://github.com/mattrondel/D415/assets/109989470/869470f4-198e-4600-9e17-e9a8f18c1952)

