## Objective 
- This chapter is to introduce the fundamentals of networks and how technicians support them
- We use [[Network Essentials/Vocabulary#Networks|Networks]] to help connect devices to talk to each other
	- There are different kinds of networks depending on the type and user count but can be from just two computers connected by one cable to complex systems using the internet
		- Other connecting devices: cable, phone lines and wireless links
		- Other connecting types: copper wire, fiber optic cable and radio waves to name a few

## Section 1-1 Network Models
- When we studying networking it's important to understand the difference of two types of [[Network Essentials/Vocabulary#Topology|Topologies]] which are:
	- [[Network Essentials/Vocabulary#Physical Topology|Physical Topology]]
	- [[Network Essentials/Vocabulary#Logical Topology|Logical Topology]]
#### OS connection models
- We control how users and programs access to resources on a network by type of OS used on that network which there are two different types: 
	- ==Peer-to-Peer model== : using any assortment of OS on different devices
	- ==Client-Server Model== : requires a [[Network Essentials/Vocabulary#NOS (network operating system)|NOS]] 
		- Examples are Windows Servers, Ubuntu Servers and Red Hat Enterprise Linux

## Peer-to-Peer model 
- In this model the OS on each computer on the network is responsible for controlling access to its resources without centralized control. 
	- By default no computer on this network has more authority than another
		- They each are their own administration, resource and security
