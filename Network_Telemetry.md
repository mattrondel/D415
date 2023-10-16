*Network Telemetry*

https://cgp-oex.wgu.edu/courses/course-v1:WGUx+OEX0110+v01/courseware/6635185e8f3c4ab99fd1a1b98ceb67db/7410146b8c304748a12f5edd454689b7/2?activate_block_id=block-v1:WGUx+OEX0110+v01+type@vertical+block@2e5308409147451fa2a71956bc697df7

Learning Objectives

At the end of this unit, you will be able to do the following:

define network telemetry data

identify network performance issues

define network availability issues

examine network performance and availability issues by analyzing network telemetry data




### NetFlow

Netflow v5 is most popular

Netflow v9 supports IPv6 and MPLS as well as teplate based results


### sFlow, or sampled flow

 Samples and streaming only 1 out of every n packets to the collector this makes it more scalable than NetFlow for certain applications where real-time traffic visablity is important

### IPFIX

Internet Protocol Flow Information eXport (IPFIX), based on NetFlow v9, is an IETF standard specification that consolidates many of the capabilities of NetFlow. IPFIX is backward-compatible with NetFlow, but extends it with numerous additional data types as well as capabilities such as variable length field support, allowing for significant flexibility and extensibility. 
IPFIX also adds in support for SCTP as the underlying transport, enabling congestion avoidance and bandwidth optimization. IPFIX enjoys wide acceptance in the industry, with support from most major networking vendors.
