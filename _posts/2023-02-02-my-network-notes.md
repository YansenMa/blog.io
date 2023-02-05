---
layout: post
title:  "My Network Note"
tags: network 
mathjax: on
---

# Network
[network command](file:2023-02-01-my-linux-notes.md)


---
**what are Ip address?**

Here is an example of a 32-bit address in binary format: \
11000000 10101000 00000001 00011110\
192        168        1        30


**Use CIDR Notation**

It begins with a starting IP address and is seperated by a forward slash (the '/' character) followed by a number.

``The number at the end specifies how many of the bits of the IP address are fixed.``


---
## Layers (from High to Low)
* Application layer
* Transport layer (TCP/IP)
* Network layer (IP)
* Data link layer (Mac Address)
* Physical layer


### Application layer
The application layer is the group of applicatons requiring network communications\
Generate the data and requests connections

### Transport layer 
The transport layer established the connections between applications on different host\
Establish conncetions between ports. In order to establish communication between applications, needs host + port (`SOCKET`)

`Port` is used to identify process or application

### Network layer
The network layer is responsible for creating the packets that move across the network\
Establish communication between hosts

`network mask` will identify if the ips are in the same local network (LAN)


### Data link layer
The data link layer is responsible for creating the frames that move across the network\
Transfers frames with physical (`MAC`) addresses

request the receiver's MAC address by `broadcasting, broadcasting happens in LAN (local network)`\
Mac address is unique and could be identified by the producer.


```console

# how to find mac address
# format example: 44:38:39:ff:ef:57
ifconfig

```

### Physical layer 
The physical layer is the transceiver that drives the signals on the network\
Transmits and receives bits


