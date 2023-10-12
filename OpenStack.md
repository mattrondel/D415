OpenStack

https://www.geeksforgeeks.org/introduction-to-openstack/

https://www.techtarget.com/searchstorage/tip/Everything-you-need-to-know-about-OpenStack-modules

School material

https://ebookcentral.proquest.com/lib/westerngovernors-ebooks/reader.action?docID=5611487&ppg=115

**Designate** used to point applications in the OpenStack environment to a trusted DNS source. Since it seeks to enhnace the securty in the environment, it is often desinated as straddling the mangement and securt functions.




### Core Modules

### Nova Compute module used to create and delete compute instances

**Glance** Synchronizes and maintains VM images across the compute cluster. Virtual machine image management THINK: Virtual Machine Images at a Glance

**Keystone** authetication for accessing all of openStacks services

**Cinder** is used for block storage as volumes for VMs

**Swift** Object Storage used to store large amounts of statuc data in a cluster. Improve effiececy and scalability of user storage and unstructed data THINK SWIFT STROAGE

**Neutron** networking allows comute and and storage nodes to communicate with each other THNK: NEutron Star Networking


**_Management Modules_**

**Horizon** is a GUI dashboard and is widely deployed management mobule - keyword DASHBOARD 

**Heat** helps expediate orchestration of applications across muliple compute instances by using templates

**Celiometer** monitors the NFVI and helps identify bottlenecks and resource optimization opportunites 

Ironic - provisioning tool for baremetal installs The Ironic module is forked from the Nova baremetal driver

**Congress** is a policy management framework for the openstack environment


**_Securtity Modules_**

**Barbican** should be used to imrove the storage and management of secure authentication information. Works with Keystone authentication to manage internal application secuurty by behaving as a key manager.

**Murano** prodives a white list reposity of applications


**_Service Modules_**

**Trove** its a ditributed database service and enables users to deploy retaional and non-relational database engines

**Sahara** used to be called Savanna - Big data services by providing elastic MapReduce and the abiltiy to provision Hadoop

**Maila** NAS solutions for OpenStack deployment

**Zaqar** provides a muliti0tenant cloud messaging service

**Magnum** umbrella project for container assitance. Module is still under development
