Basic Terms
====================================

Before delving into how a network works, let's define some of the key term with
basic definition to help comprehension.

## networking
In computing, networking is the practice of connecting devices (computers)
together for the exchange of data.

A computer network is made of *networking devices* (switches, routers, etc)
and *nodes* (computers, printers, phones, etc).

> The Telex messaging system (1933) is probably the earliest form of computer 
> network.[^1]

## switch
A device through which computers connect to the network. Switches are also 
inter-connected with other switches to extend the network to other physical 
areas. A switch has basic *intelligence*. When a data unit is transmitted 
through it, the switch reads the begining of the data unit to see where it 
goes and passes the data unit only to the recipient.

## hub
A hub is basically like a switch, except it has no *intelligence*. All data unit
received are passed on to all devices connected to it, regardless of destination.
Nowaday, hubs are rarely used.

## port
A port is a connector on a network device where a cable can be connected.

## protocol
In computing, protocols are sets of rules or standards for transmitting 
information - be it networking or transmitting data between two components of 
a computer. For exapmle, a networking protocol would dictate how two devices
discover each other, how they establish a communication channel and how they
signify the end of a transmission.

## ethernet
Ethernet is a set of technologies, protocols and standards for networking. There
are other networking technologies, but Ethernet today is the most common. The 
key aspect of Ethernet is that multiple devices can be connected through a
switch or hub to form a network and thus able to exchange information.

## router
A router connects one network to another. This is an advanced networking concept. 
Computers on a network are able to communicate with each other through switches, 
however, they aren’t able to connect to another network without a router. For 
example, multiple computers in a house are inter-connected with a switch. A 
router is then used to connect the switch to the Internet. The computers then 
can communicate with other computers on the Internet by going through the router 
as the router knows how to route the data over the Internet.

## IP address
IP stands for *Internet Protocol* - a set of standards which defines a way for 
computers to communicate over a network and how data is exchanged between 
computer networks.

An IP address then is simply the identifier (address) of a computer in an 
IP-based network. In the human form, it is made of 4 sets of 1 to 3 digits (to
the computer, this is all 0s or 1s), for example, `192.168.1.1`.

## host
Another word for a computer or server, generally referring to a physical machine.

## packet
A packet is a unit of information sent through the network. It contains various
parts such as the source, destination and the data. If a file, for example, is
copied from one computer to another via the network, it will be broken up into
multiple packets which will be sent through the network.

## bandwidth
The bandwidth of a network link is how much data can travel on it in one second
(*bps*). It is calculated in terms of bits per second. It can be said to be the 
maximum speed of a network - its capacity. With no other factors involved, if a 
network has a 100 Mbps (*Mega-bits per second*) bandwidth, it means that a movie
of 700MB (*Mega-bytes*) will take 56 seconds to be transmitted.

Speed is often used interchangeably with bandwidth. It is more correct to use 
speed to qualify a data transmission (a download, etc) and bandwidth for the
capacity of a line.

## latency
While the bandwdith represents how many bits per second can pass through the 
network, latency is how long it takes for a packet to be transmitted. Latency 
does affect the actual speed of a link - a long latency reduces the speed.

> Today (2016), latency is measured in milliseconds (ms). On a local network, it 
> is usually below 2ms. On the Internet, one commonly finds less than 100ms. [^3]

## network
The word network can be used in multiple ways - it is often used to mean a 
*computer network* which is a system of inter-connected hosts, switches, routers, 
etc.

However, network engineers often use the term to refer to an abstract concept
relating to how hosts on a computer network are addressed. On a network, 
computers can communicate with each other through switches, but they can't 
communicate to computers which are connected to another network - a router is
needed to route the packets between networks.

A network, in that sense, is defined by the IP addresses. For example, a network
can be defined such that any IP address between `192.168.1.1` and `192.168.1.254`
can communicate directly, but to get to other addresses, such as `192.168.2.1`,
the devices need to send the traffic to a router (also know as gateway).

This matters in networking because this is how security constraints can be 
enforced. It also shows how two different corporate networks can be 
inter-connected and be able to exchange information. There are other benefits 
but they won't be covered here.


-------------

[^1]: [Timeline of Computer History, www.computerhistory.org](http://www.computerhistory.org/timeline/1933/)
[^2]: [Optical fiber, wikipedia](https://en.wikipedia.org/wiki/Optical_fiber)
[^3]: [Latency Numbers Everyone Should Know](https://dzone.com/articles/latency-numbers-everyone-should-know)