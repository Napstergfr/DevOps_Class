#  Docker to Kubernetes

# ** Class-01 **

## Topics Discussed

* Linux, Core Linux, Linux CLI
* RCA (Root Cause Analysis)
* IAC (Infrastructure As a Code)
* Cloud Governence

> Note: DevOps = [IAC, CI/CD, Networking, Cloud Computing, Software Engineering knowledge]

* What we will do
	* Docker
	* Kubernetes
	* Microservices Architecture Design
	* Scalability

* Linux Network Namespace
	* User Space
	* Karnel Space
* Socket Binding
* Host Namespace
* Network Namespace
* File Namespace
* ### OSI Layer Model
* ### ARP (Address Resolution Protocol) [ARP Request, ARP Table]
* Route Table
* ### CIDR (Classless Interdomain Network)

> Note: IP4 > [0.0.0.0 = 8 bit 2^32] > IP = Logical Address
> MAC = Physical Address (Unique Hexadecimal Number which is burnt to LAN Card)
> NIC = Network Interface Card 
> VNIC = Virtual Network Interface Card
> 
> ----------------------Package------------------------------------>>
> 
> NIC (Physical Layer) >> Interface/Soft Layer >> Karnel >> Userspace 

* MTU (Maximum Transmission Unit)
> COMMAND: $ tcpdump -i en0 (eth0)
* Loop Back Interface "lo:"
> lo: (Can't Send packet to outside)
* DNS NAME, QUERY (UDP Packet) DNS Resolve
> COMMAND: $ dig facebook.com
> 
> $ nslookup facebook.com (Same as dig)
> 
> $ telnet 152.240.7.35 443 (telnet is a TCP Client)
> 
> $ sudo vi/etc/hosts [Domain Parking]

> Note: TTL = Time to leave
> ### Q. Why it generates random ports (source ports) ? 
> ### [NAT gateways](https://docs.aws.amazon.com/vpc/latest/userguide/vpc-nat-gateway.html)

* Nc NetCat Webserver
* WireShark

> COMMAND: tcpdump -i eth0 dst 69.171.250.35 443 [To see trafic]
> Note: HTTPS is stateless request it closes when it's done
