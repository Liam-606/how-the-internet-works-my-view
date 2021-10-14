# How The Internet Works - My View

Before we cover what the internet is, we have to define what a "network" is. A network is a group of connected computers that are able to send data to each other. A computer network is much like a social circle, which is a group of people who all know each other, regularly exchanging information and coordinating activities together.

The internet is a vast collection of networks that connect to each other. the word "internet" could be said to originate from this concept *inter*connected *net*works. since computers connect with each other within a network and these networks also connect to each other, one computer can talk to another in a faraway network thanks to the internet. This makes it possible to rapidly exchange information between computers across the world. 

To understand the internet, it helps to look at it as a system of two main components. the first of those components is **hardware**. This includes everything from the cables that carry terabits of information every second to the computer. Other types of hardware that support the internet include routers, servers, cell phone towers, satellites, radios, smart phones and other devices. All these devices together create a network of networks.

Computers connect to each other and the internet through wires, cables, radio waves and other types of networking devices. All data sent over the internet is translated into bits and then interpreted by the receiving computer. The wires, cables and radio waves conduct these bits at the speed of light. The more bits that can pass through these wires and cables at once, the faster the internet works.

All of this hardware would not create a network without the second component of the internet: **the protocols**. Protocols are set of rules that machines follow to complete tasks. without a common set of protocols that all machines connected to the internet must follow, communication between devices would not happen. The various machines will be unable to understand each other or send information in a meaningful way. The protocols provide the method and a common language for machines to use to transmit data.

 PACKETS and PROTOCOLS

In networking, a packet is a small segment of a larger message. Each packet contains both data and information about that data. The information about the packets contents in known as the header and it goes at the front of the packet so that the receiving machine knows what to do with the packet. When data gets sent over the internet, it is first broken down into smaller packets which are then translated into bits. The packets get routed to their destination by various networking devices such as routers and switches. When the packets arrive at their destination, the receiving device reassembles the packets in order and can then use or display the data. Packets are sent across the internet using a technique called packet switching.  Intermediary routers and switches are able to process packets independently from each other without accounting for their source or destination. this is by design so that no single connection dominates the network. If data was sent between computers all at once with no packet switching, a connection between two computers could occupy multiple cables,, routers and switches for minutes at a time making it possible for only two people to be able to use the internet at a time instead of an unlimited number of people as is the case in reality.

Connecting two computers both of which may use different hardware and run different  software is one  of the main challenges that the creators of the internet had to solve. It requires the use of communication techniques that are understandable by all connected computers. These problem is solved with standardized way of doing certain actions and formatting data so that two or more devices are able to communicate with and understand each other.

There are protocols for sending packets between devices on the same network(Ethernet), for sending packets from network to network(IP), for ensuring those packets successfully arrive in order(TCP), and for formatting data for websites and applications(HTTP). In addition to these foundational protocols, there are also protocols for routing, testing and encryption.

# What is Internet Protocol (IP)?

Internet Protocol (IP) is the method or protocol by which data is sent from one computer to another on the internet. Each computer known as a **host** on the internet has at least one IP address that uniquely identifies it from all other computers on the internet.

# What is an IP address?  
IP provides mechanisms that enable different systems to connect to each other to transfer data. Identifying each machine in an IP network is enabled with an IP address.

Similar to the way a street address identifies the location of a home or business, an IP address provides an address that identifies a specific system so data can be sent to it or received from it.

An IP address is typically assigned via the DHCP (Dynamic Host Configuration Protocol). DHCP can be run at an internet service provider, which will assign a public IP address to a particular device. A public IP address is one that is accessible via the public internet.

A local IP address can be generated via DHCP running on a local network router, providing an address that can only be accessed by users on the same local area network.

# Differences between IPv4 and IPv6  
The most widely used version of IP for most of the internet's existence has been Internet Protocol Version 4 (IPv4).

IPv4 provides a 32-bit IP addressing system that has four sections. For example, a sample IPv4 address might look like 192.168.0.1, which coincidentally is also commonly the default IPv4 address for a consumer router. IPv4 supports a total of 4,294,967,296 addresses.  In contrast, IPv6 defines a 128-bit address space, which provides substantially more space than IPv4, with 340 trillion IP addresses. An IPv6 address has eight sections. The text form of the IPv6 address is xxxx:xxxx:xxxx:xxxx:xxxx:xxxx:xxxx:xxxx, where each x is a hexadecimal digit, representing 4 bits.

# Encryption

Encryption is a process that encodes a message or file so that it can be only be read by certain people. Encryption uses an algorithm to scramble, or encrypt, data and then uses a key for the receiving party to unscramble, or decrypt, the information. The message contained in an encrypted message is referred to as plaintext. In its encrypted, unreadable form it is referred to as ciphertext.

# How Encryption Works   
Encryption uses algorithms to scramble your information. It is then transmitted to the receiving party, who is able to decode the message with a key. There are many types of algorithms, which all involve different ways of scrambling and then decrypting information.

# Search Encrypt Terms

Key: Random string of bits created specifically for scrambling and unscrambling data. These are used to encrypt and/or decrypt data. Each key is unique and created via algorithm to make sure it is unpredictable. Longer keys are harder to crack. Common key lengths are 128 bits for symmetric key algorithms and 2048 bits for public-key algorithms.   
Private Key (or Symmetric Key): This means that the encryption and decryption keys are the same. The two parties must have the same key before they can achieve secure communication.       
Public Key: This means that the encryption key is published and available for anyone to use. Only the receiving party has access to the decryption key that enables them to read the message.  
   Cipher: An algorithm used for encryption or decryption. It is a set of steps that are followed as a procedure to encrypt information. There are two main types of ciphers, block ciphers and stream ciphers.   
Algorithm: An algorithm is the procedure that the encryption process follows. The specific algorithm is called the cipher, or code. There are many types of encryption algorithms. The encryption’s goal and level of security determines the most effective solution. Triple DES, RSA and Blowfish are some examples of encryption algorithms, or ciphers.    
Decryption: The process of switching unreadable cipher text to readable information.
  
# What physical infrastructure makes the internet work?

A lot of different kinds of hardware and infrastructure go into making the internet work for everyone. Some of the most important types include:


1.  Routers: forwards packets to different computer networks based on their destination. Routers are like the traffic  cops of the internet making sure the internet traffic goes to the right networks.

2.  Switches: connect devices that share a single network . they use packet switching to forward packets to the correct devices. they also receive outbound packets from those devices and pass them along to the right destination.

3. Servers: Web servers are specialized high-powered computers that store and serve content (webpages, images, videos) to users, in addition to hosting applications and  databases. servers also respond to DNS (Domain Name Server) queries and perform other important tasks to keep the internet up and running. Most servers are kept in large data centers which are located around the world.

# What is DNS?

The Domain Name System (DNS) is the phonebook of the Internet. Humans access information online through domain names, like www.codeclannigeria.dev or espn.com. Web browsers interact through Internet Protocol (IP) addresses. DNS translates domain names to IP addresses so browsers can load Internet resources.

Each device connected to the Internet has a unique IP address which other machines use to find the device. DNS servers eliminate the need for humans to memorize IP addresses such as 192.168.1.1 (in IPv4), or more complex newer alphanumeric IP addresses such as 2400:cb00:2048:1::c629:d7a2 (in IPv6).

# How does DNS work?   
The process of DNS resolution involves converting a hostname (such as www.codeclannigeria.dev) into a computer-friendly IP address (such as 192.168.1.1). An IP address is given to each device on the Internet, and that address is necessary to find the appropriate Internet device - like a street address is used to find a particular home. When a user wants to load a webpage, a translation must occur between what a user types into their web browser (codeclannigeria.dev) and the machine-friendly address necessary to locate the codeclannigeria.dev webpage. 

# What are the steps in a DNS lookup?  
For most situations, DNS is concerned with a domain name being translated into the appropriate IP address. To learn how this process works, it helps to follow the path of a DNS lookup as it travels from a web browser, through the DNS lookup process, and back again. Let's take a look at the steps.

# The 8 steps in a DNS lookup:
1. A user types ‘codeclannigeria.dev’ into a web browser and the query travels into the Internet and is received by a DNS recursive resolver.
2. The resolver then queries a DNS root nameserver (.).
3. The root server then responds to the resolver with the address of a Top Level Domain (TLD) DNS server (such as .com or .net or .dev), which stores the information for its domains. When searching for codeclannigeria.dev, our request is pointed toward the .dev TLD.
4. The resolver then makes a request to the .dev TLD.
5. The TLD server then responds with the IP address of the domain’s nameserver, codeclannigeria.dev.
6. Lastly, the recursive resolver sends a query to the domain’s nameserver.
7. The IP address for codeclannigeria.dev is then returned to the resolver from the nameserver.
8. The DNS resolver then responds to the web browser with the IP address of the domain requested initially.
Once the 8 steps of the DNS lookup have returned the IP address for codeclannigeria.dev, the browser is able to make the request for the web page:

9. The browser makes a HTTP request to the IP address.
10. The server at that IP returns the webpage to be rendered in the browser (step 10).
