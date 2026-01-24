## Networking : 
How data transfer from one system to other and where it can be attacked? 

## Ports: 
Ports are the door through which services can communicate.

## IP : 
Address of the machine or the server
There are 2 types of IP address IPv4 and IPv6
IPv4 are old so we introduce IPV6

**IP identify the machines and ports identify the services.**

 ## TCP vs UDP
 TCP: 
 It is connection based.
 It is secured.
 No data is being lost.
 It is slow.
 Ex: HTTP, HTPPS, SSH, Database connection.

 UDP:
 It is no connection based. 
 It is not as secure as TCP.
 Data can be lost.
 It is fast.
 Video call, Gaming, Etc

 **Cretical Data is beibg shared over TCP**

## DNS: Domain Name System
It is a name assigned to a server, IP address so that it can be easily accessable by humanbeing. 
For ex. Its is easy to rememebr "www.google.com" rather than "140.x.x.x"

User put request to reccursive DNS resolver and it put request to root DNS server after that to TLD name server and then to Authoratative DNS resolver and then give the required output to the user of the actual address

A attacker can attack and can give the fake address to the the a DNS which will redirect the user to the fake page and over there there is loss chance to loss the data and info.

## HTTP and HTTPS

HTTP:
Plain Text
Anyone can read
Not secure

HTTPS:
Encrypted
Uses TLS
Secure

HTTPS != website
HTTPS = secure transportation

## TLS(Transport Layer Security)

It is a security protocol that helps in keeping the data secure while moving between two system
TLS provides:
Authentication
Encryption
Integrity



 