# What is Networking?
Networks are simply things connected. For example, your friendship circle: you are all connected because of similar interests, hobbies, skills and sorts.

**Answer the questions below**

Q-What is the key term for devices that are connected together?
```
Network
```

**Networking** is the practice of connecting devices like computer, server,etc.

## What is Internet?
The Internet is one gigantic network that consists of many, many small networks within itself.

* The first iteration of the Internet was within the **ARPANET** project in the late **1960s**. This project was funded by the "United States Defence Department" and was the first documented network in action.

* However, it wasn't until 1989 when the Internet as we know it was invented by Tim Berners-Lee by the creation of the World Wide Web **(WWW)**

* These small networks are called private networks, where networks connecting these small networks are called public networks -- or the Internet!  
    * A private Network
    * A public Network

**Answer the questions below**  
Q- Who invented the World Wide Web?
```
Tim Berners-Lee
```

## Identifying Devices on network 
Devices also have two means of indetification,with one being permeable -  
* **An IP Address** - It looks like this : **192.168.1.1**
* **A Media Access Control (MAC) Address** -- think of this as being similar to a serial number.

### IP Address or **I**nternet **P**rotocol Address - 
It can be used as a way of identifying a host on a network for a period of time, where that IP address can then be associated with another device without the IP address changing. 

An IP address is a set of numbers that are divided into four octets. The value of each octet will summarise to be the IP address of the device on the network. This number is calculated through a technique known as IP addressing & subnetting

IP Addresses have to follow  set of standards known as protocols. These protocols are the backbone of networking and force many devices to communicate in the same language, which is something that we'll come onto another time.

A public address is used to identify the device on the Internet, whereas a private address is used to identify a device amongst other devices.Public IP addresses are given by your **Internet Service Provider (or ISP)** at a monthly fee (your bill!)

Types of IP's -
* **IPV4** - The Internet Protocol addressing scheme known as IPv4, which uses a numbering system of 2^32 IP addresses (4.29 billion)
* **IPv6** - It is a new iteration of the Internet Protocol addressing scheme. It supports up to 2^128 of IP addresses (340 trillion-plus)


### MAC Addresses
Devices on a network will all have a physical network interface, which is a microchip board found on the device's motherboard  
This network interface is assigned a unique address at the factory it was built at, called a MAC (Media Access Control ) address. The MAC address is a twelve-character hexadecimal number. Split into two's and separated by a colon. These colons are considered separators

For example, **a4:c3:f0:85:ac:2d**. The first six characters represent the company that made the network interface, and the last six is a unique number.

**Warning!!** -
However, an interesting thing with MAC addresses is that they can be faked or "spoofed" in a process known as spoofing. This spoofing occurs when a networked device pretends to identify as another using its MAC address.

When this occurs, it can often break poorly implemented security designs that assume that devices talking on a network are trustworthy. 

**Answer the questions below**

Q- What does the term "IP" stand for?
```
Internet Protocol
```
Q- What is each section of an IP address called?
```
octet
```
Q- How many sections (in digits) does an IPv4 address have? 
```
4
```
Q- What does the term "MAC" stand for?
```
Media Access Contorl
```
Q-  What is the flag?
```
THM{YOU_GOT_ON_TRYHACKME}
```


## PING (ICMP)
**Ping** is one of the most fundamental network tools available to us. Ping uses **ICMP** (**I**nternet **C**ontrol **M**essage **P**rotocol) packets to determine the performance of a connection between devices, for example, if the connection exists or is reliable. The time taken for ICMP packets travelling between devices is measured by ping.

**Answer the questions below**

Q- What protocol does ping use?
```
ICMP
```
Q- What is the syntax to ping 10.10.10.10?
```
ping 10.10.10.10
```

Q- What flag do you get when you ping 8.8.8.8?
```
THM{I_PINGED_THE_SERVER}
```
****
