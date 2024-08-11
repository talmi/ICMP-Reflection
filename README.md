# ICMP-Reflection

This repository maintains draft-mh-6man-icmpv6-reflection, an Internet draft that describes the ICMPv6 Reflection utility, which enables a two-way message exchange that can be used for probing and for diagnostic purposes. ICMPv6 Reflection uses a request-response handshake that is similar to ICMPv6 Echo, except that after a request is sent, its corresponding reply includes the request message itself or a subset of its fields as specified in the request. Specifically, the IPv6 header of the request message and its IPv6 extension headers, if they are present, can be included in the reply. Notably, network operators can use ICMPv6 Reflection to determine how IPv6 extension headers have been altered by transit nodes.
