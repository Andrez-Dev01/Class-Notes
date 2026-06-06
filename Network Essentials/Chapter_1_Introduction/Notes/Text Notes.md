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
### Note 1-1
- Window Servers and Linux Servers are examples of a specific NOS called [[Network Essentials/Vocabulary#Server Operating Systems|Server Operating Systems]] 
- But there are different kinds of like routers and switches called [[Network Essentials/Vocabulary#Networking Software|Networking Software]] 
	- Examples are IOS (Internetwork OS) on Cisco devices, Junos Os on Juniper devices
- There are also different kinds of software like hypervisor which run virtualized devices or a cloud platform that host cloud-based resources
## Peer-to-Peer model 
- In this model the OS on each computer on the network is responsible for controlling access to its resources without centralized control. 
	- By default no computer on this network has more authority than another
		- They each are their own administration, resource and security
			- [[Figure 1-1 Peer-to-Peer network.png|Figure 1-1]]
### Note 1-2 
- When looking at [[Figure 1-1 Peer-to-Peer network.png|Figure 1-1]] and [[Figure 1-2 Client-Server Network.png|Figure 1-2]] the connecting lines describe the logical arrangement (topology) of the group of computers opposed to the physical arrangement. 
### Resource Sharing 
- When devices are in this network they can share resources through different ways of file sharing or user accounts
	- If all the devices are running windows they can share a folder, file or a Windows work group
		- There is also the option to combine folders and files on the same network and same computers just be aware this can be messy and sticking to separate folders is much better to manage
### When to use this model 
- If the network is support less than 15 computers this model is the recommended type to users for these reasons: 
	- Simple to configure because of environments of which time or technical expertise is missing
	- It's also cost effective to set up and maintain
		- Using something like Windows Servers cost more money than sticking to desktop OS
### Disadvantages
- There are always drawbacks when going with this method:
	- It's not scalable to increasing network growth in users, adding or changing elements of the networks
	- This method is also not very safe in the sense of security is an issue because if an unauthorized user can now access everything on the networks
	- 