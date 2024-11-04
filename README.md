# CLOUD-COMPUTING
Concepts of cloud computing, basics, related topics details
![CC](https://github.com/user-attachments/assets/1e6a7492-720a-46b8-8c5e-bcfccce81ef4)
Cloud computing is a way to access computing services, like storage, servers, databases, networking, and software, on-demand. It allows users to store files and applications remotely on servers that are maintained by a cloud computing provider
# KEYWORDS

1. **OPERATING SYSTEM(OS)**: An Operating system is system software that manages computer hardware and software resources and provides common services for computer programs.
it act as an intermediary between users and computer hardware

    these are the famous or commonly used Operating System(OS):

   WINDOWS


   ![image](https://github.com/user-attachments/assets/98ea8da4-cc29-4e4c-b60d-857569a8f998)
   MACos


   ![image](https://github.com/user-attachments/assets/f199f816-d99f-4f7b-acc1-1bf6a8ae014d)
   LINUX



![image](https://github.com/user-attachments/assets/d5743e4b-04cc-432f-af92-47a6c94d9e0d)


3. **BARE METAL**: Bare metal refers to a computer system or servers that runs without a layer of abstraction such as a virtulization layer or operating system.
in this context, "bare metal" means the hardware is directly utilized for a single application or workload, allowing  for maximum performance and control


4. **LINUX KERNEL**: The linux kernal is the core component of the linux operating system. it serves as the fundamental interface between a computer's hardware and its software.
       Here are key aspects of the linux kernal:

   ~kernal functions: it manages hardware resources such as CPU,Memory, and peripheral devices.

   ~modularity: the linux kernal is modular, meaning it can be extended with loadable modules that can be added or removed at runtime.

   ~open source: the linux kernel is open source, released under the GNU General Public License(GPL). this means its source code is freely available for anyone to inspect,
     modify and distribute.

   ~device drivers: the kernel includes drivers for a wide range of hardware devices, enabling the operating system to communicateT with and control peripherals like printers
     network cards, and graphics adapters.
**Devices are mainly divided into three parts:**


 (i) **COMPUTATION**:-

   ~CPU:-The central processing unit (CPU) is the primary component of a computer that performs most of the processing tasks.often
               to referred to as the "brain" of the computer, the CPU executes instruction from proggrams through its control unit, arthmetic logic unit(ALU),and registers.


![image](https://github.com/user-attachments/assets/a5e750ab-d6eb-4472-90f5-ac055006e151)


   ~GPU:-A Gaphics processing unit(GPU) is a specialized processor designed to handle and accelerate the rendering of images, video and animation. unlike a CPU,which is 
               optimised for general-purpose computing task, a GPU is optimized for parllel processing,meaning it can handle many operations simultaneously.

   ~TPU:-A tensor processing unit(TPU) is a specialized type of processor designed by google specifically for accelerating machine learning task,particularly those
               involving tensor computations. Tensor are multimensional arrays used in various machine learning and artificial intelligence models.

   ~QPU:-A quantum processing unit(QPU) is a spcialized type of processor designed to perform quantum computations. unlike classical processor, which use bits to represent 
               data as 0s and 1s, aQPU uses quantum bits or qubits, which can exist in multiple states simultaneously due to quantum superposition.

   ~ASIC:-ASIC stands for Application-Specific integrated circuit. it's a type of integrated circuit designed for a specific application or function, rather than general
                puerpose use. for example, an ASIC designed for cryptocurrency mining is specifically built to perform the hashing calculations required for mining.



  (ii) **STORAGE**:-

   ~primary storage: RAM

   ![image](https://github.com/user-attachments/assets/81817dc9-8cb6-4011-92da-301dedb59c01)


   ~secondary storage: hard disk

  ![image](https://github.com/user-attachments/assets/869694f5-f2a2-49e1-aff0-e36a9906f3ed)

 (iii) **NETWORK**:-

  ~ Local Area Network (LAN): A LAN covers a small geographic area, such as a home, office, or campus. It connects devices within this limited space, typically using Ethernet                               cables or Wi-Fi. LANs are used for sharing resources like files, printers, and internet access.

 

  ~Wide Area Network (WAN): A WAN spans a large geographic area, often covering multiple cities, countries, or even continents. It connects multiple LANs and other types of                             networks. The internet is the largest example of a WAN. WANs can be public, like the internet, or private, like those used by large corporations.

  ![image](https://github.com/user-attachments/assets/a733cd92-453b-4a50-a6b1-4af27b741d96)
  
 5. # OSI MODEL(7 LAYERS) NETWORKING MODEL

  The OSI (Open Systems Interconnection) model is a conceptual framework used to understand and standardize the functions of a    telecommunication or computing system, regardless of its underlying technology. It divides network communication into seven distinct   layers, each with specific functions.

  ![image alt](https://github.com/Gautam-io-dev/Basic-Computer-Science-Keywords/blob/3d5b59e60ab8c2fc4852d69b5fc63b4cf3568ed2/D40E0460-D8DF-4933-9BA6-AB02F9058677.png)

 6. # **BLOCKCHAIN:**

 Blockchain is a decentralized digital ledger technology that securely records transactions across multiple computers in a way that       prevents alteration or tampering. It operates as a chain of blocks, each containing a list of transactions. Once a block is added to   the chain, it is difficult to change any information in that block without altering all subsequent blocks, which requires consensus  from the network. This makes blockchain a transparent and secure method for managing and verifying transactions. It's commonly used in  cryptocurrencies like Bitcoin but also has applications in various other fields, such as supply chain management, voting systems, and   smart contracts.

 ![image alt](https://github.com/Gautam-io-dev/Basic-Computer-Science-Keywords/blob/6393b054257b5e47d8a1d72d2907b6dc8b79c1b9/Image%208.jpeg)

7.**CISC:**

CISC architectures are designed to execute complex instructions with a rich set of addressing modes and operations, often simplifying   programming and achieving high instruction density. However, this complexity can introduce challenges in decoding and execution that    need to be managed effectively.

![image alt](https://github.com/Gautam-io-dev/Basic-Computer-Science-Keywords/blob/4e112c62527ddf180bd8e0c9f09e3b6a7e7b5cb9/Image%209.jpeg)

Examples:-

1️⃣ x86 Architecture: One of the most well-known CISC architectures, used in most personal computers. It includes a wide range of        instructions and addressing modes.

2️⃣ AMD64 (x86-64): An extension of x86 that supports 64-bit computing, maintaining backward compatibility with x86 software.

8.**RISC:**

RISC architectures emphasize a simplified and highly optimized instruction set, with instructions typically executed in a single clock cycle. By relying on a large number of registers and implementing efficient pipelining, RISC processors aim to achieve high performance and efficiency. However, this simplicity can lead to a higher instruction count and potentially lower code density compared to more complex CISC architectures.

![image alt](https://github.com/Gautam-io-dev/Basic-Computer-Science-Keywords/blob/c93a50ea13335a09bf42f637b2b85ba7a93503b1/Image%2010.jpeg)

Examples:-

1️⃣ARM: A widely used RISC architecture, particularly in mobile devices and embedded systems. ARM processors are known for their power efficiency and high performance.

2️⃣MIPS: Another well-known RISC architecture used in various applications, including academic research and embedded systems.

3️⃣RISC-V: An open-source RISC architecture that is gaining popularity due to its flexibility and modular design.

9.**RISC-V**

RISC-V (pronounced "risk-five") is an open-source, RISC (Reduced Instruction Set Computer) architecture designed to be a flexible and extensible instruction set architecture (ISA). Developed at the University of California, Berkeley,its open nature, along with its base instruction set and extensibility, makes it an attractive choice for a wide range of applications, from embedded systems to high-performance computing. The growing community and ecosystem around RISC-V continue to drive innovation and adoption in various field.

![image alt](https://github.com/Gautam-io-dev/Basic-Computer-Science-Keywords/blob/eb2543420ff42659599de408a353b40f74b38f98/Image%2011.jpeg)

10.**ALGORITHM**

An algorithm is a structured procedure or set of rules designed to solve a specific problem or perform a particular task. It involves well-defined, finite steps that take inputs and produce outputs. Algorithms are crucial for efficient computation and problem-solving, and they form the backbone of computer science and various applications in technology.

![image alt](https://github.com/Gautam-io-dev/Basic-Computer-Science-Keywords/blob/ba7d1736b7fd46a89a206f5754ba6c2606cf140d/Image%2012.jpeg)

11.**VIRTUAL MACHINE**

A virtual machine (VM) is a software-based emulation of a physical computer that allows multiple operating systems or instances to run on a single physical machine. VMs provide isolation, encapsulation, and resource efficiency, making them valuable for development, testing, and production environments. They come in two main types: system virtual machines, which emulate entire systems, and process virtual machines, which abstract individual applications. While VMs offer numerous advantages, including flexibility and efficient resource utilization, they also come with performance overhead and management complexity.

![image alt](https://github.com/Gautam-io-dev/Basic-Computer-Science-Keywords/blob/e1f0d5919074b9bd57f2d083dfa2e9007a70a35d/JPEG%20image-4F87-960B-0F-0.jpeg)

12.**IP ADDRESS**

An IP address (Internet Protocol address) is a unique string of numbers separated by periods or colons that identifies each device connected to a network. IP addresses serve two primary functions: identifying the host or network interface and providing the location of the host in the network. They are essential for routing internet traffic and ensuring data reaches the correct destination.

![image alt](https://github.com/Gautam-io-dev/Basic-Computer-Science-Keywords/blob/947a68ef5d4b4142dcddc9c582640da4cbbf1d0c/Image%2013.jpeg)

There are two main versions of IP address:


1️⃣IPv4 (Internet Protocol version 4): This format uses four sets of numbers ranging from 0 to 255, separated by periods 

(e.g., 192.168.1.1). It provides about 4.3 billion unique addresses.

2️⃣IPv6 (Internet Protocol version 6): This format uses eight groups of four hexadecimal digits separated by colons 

(e.g., 2001:0db8:85a3:0000:0000:8a2e:0370:7334). It provides a vastly larger number of addresses to accommodate the growing number of devices on the internet.

![image alt](https://github.com/Gautam-io-dev/Basic-Computer-Science-Keywords/blob/6b8db7da598a230d6aaad055915633906735dec8/Image%2014.jpeg)

13.**ISP(Internet Service Provider)**

An ISP, or Internet Service Provider, is a company or organization that provides individuals and businesses with access to the internet. ISPs offer various types of internet connections, including:

- **DSL (Digital Subscriber Line)**: Uses telephone lines to provide internet access.
- **Cable**: Uses cable television lines for internet service.
- **Fiber-optic**: Uses fiber-optic cables for high-speed internet access.
- **Satellite**: Provides internet access via satellite signals, useful in remote areas.
- **Wireless**: Uses radio signals to connect to the internet, which can include both fixed wireless and mobile broadband.

In addition to providing internet access, ISPs may also offer related services such as email, web hosting, and technical support. When you connect to the internet, you’re usually connecting through an ISP that assigns you an IP address and handles the routing of data between your device and the broader internet.

![image alt](https://github.com/Gautam-io-dev/Basic-Computer-Science-Keywords/blob/f9fec1440bcc59ecad98ababa0c66c49528ea2eb/Image%2015.jpeg)

14.**DNS(Domain Name System)**

DNS stands for Domain Name System. It functions like a phone book for the internet, translating human-friendly domain names (like `www.example.com`) into IP addresses (like `192.0.2.1`) that computers use to identify each other on the network.

Here's a simple breakdown of how DNS works:

1. **Request**: When you type a web address into your browser, a DNS request is made to find the corresponding IP address for that domain name.

2. **Resolution**: The DNS system then looks up the IP address associated with that domain name. This process involves several steps:
   - **Recursive Resolver**: Your request first goes to a DNS resolver, which is often provided by your ISP. This resolver tries to find the IP address for the domain name.
   - **Root Name Servers**: If the resolver doesn't have the address cached, it queries one of the root name servers, which point to the appropriate top-level domain (TLD) name servers (like those for `.com` or `.org`).
   - **TLD Name Servers**: The TLD servers then direct the resolver to the authoritative name servers for the specific domain.
   - **Authoritative Name Servers**: These servers have the actual IP address for the domain and respond to the resolver with this information.

3. **Response**: The DNS resolver returns the IP address to your browser, which then uses it to connect to the web server hosting the website you want to visit.

DNS is crucial for the functionality of the internet, making it easier for people to navigate and access websites without needing to remember complex numerical IP addresses.

![image alt](https://github.com/Gautam-io-dev/Basic-Computer-Science-Keywords/blob/de5ad40f996ec225c98676a971ef020427aa2345/Image%2016.jpeg)

15.**VPN(Virtual Private Network)**

A VPN, or Virtual Private Network, is a service that creates a secure, encrypted connection over a less secure network, such as the internet. It allows you to access the internet as if you were connected to a private network, providing privacy and security. Here's how it works and why you might use it:

1. **Encryption**: When you connect to a VPN, your internet traffic is encrypted, meaning that the data you send and receive is scrambled and unreadable to anyone who might intercept it. This helps protect your data from hackers, especially on public Wi-Fi networks.

2. **IP Masking**: A VPN hides your real IP address and replaces it with one from the VPN server. This can make it harder for websites, advertisers, and other parties to track your online activities and identify your location.

3. **Secure Access**: VPNs provide secure access to your network resources, which can be useful for businesses allowing remote employees to connect to internal systems securely.

4. **Bypassing Restrictions**: VPNs can help you access content that might be restricted or censored in your location by routing your connection through servers in different countries. This is useful for accessing services, websites, or content that might be geo-blocked.

5. **Privacy**: By hiding your IP address and encrypting your data, a VPN enhances your online privacy, making it more difficult for third parties to monitor your browsing activities.

When you use a VPN, your internet traffic is routed through a secure server before reaching its destination, adding a layer of privacy and security. However, it's important to choose a reputable VPN provider to ensure your data is handled securely and your privacy is protected.

![image alt](https://github.com/Gautam-io-dev/Basic-Computer-Science-Keywords/blob/81e44ccdb4ee6295b54576205ad874bb0a4cbad8/Image%2017.jpeg)

16.**FRONTEND,BACKEND AND API(Application Programming Interface)**

In web development, the terms **frontend**, **backend**, and **API** refer to different aspects of building and managing applications. Here’s a breakdown of each:

### **Frontend**

**Frontend** refers to the **client-side** of a web application. It encompasses everything that users interact with directly in their web browsers. This includes:

- **Design and Layout**: The visual aspects of a website or application, including the layout, colors, fonts, and images.
- **User Interface (UI)**: The components that users interact with, such as buttons, forms, and navigation menus.
- **Technologies**: Frontend development primarily involves languages and frameworks like HTML (Hypertext Markup Language), CSS (Cascading Style Sheets), and JavaScript. Frameworks and libraries like React, Angular, and Vue.js are commonly used to build interactive and dynamic user interfaces.

### **Backend**

**Backend** refers to the **server-side** of a web application. It involves everything that happens on the server and is responsible for managing and processing data. Key aspects include:

- **Server**: The hardware or software that provides services, resources, or data to other computers over a network.
- **Database**: Where data is stored, retrieved, and managed. Common databases include MySQL, PostgreSQL, and MongoDB.
- **Server-Side Logic**: The code that runs on the server, handling requests from the frontend, processing data, and sending responses. This includes server-side languages like Python, Ruby, Java, PHP, and Node.js.
- **Authentication**: Managing user login, registration, and security.

### **API**

**API** stands for **Application Programming Interface**. It is a set of rules and protocols that allows different software applications to communicate with each other. APIs can be used to:

- **Connect Frontend and Backend**: APIs often serve as the bridge between the frontend (client-side) and backend (server-side). For instance, when you submit a form on a website, the frontend sends a request to the backend via an API, which processes the request and sends back a response.
- **Access External Services**: APIs enable applications to interact with third-party services or data sources. For example, a weather app might use an API to fetch weather data from an external weather service.
- **Standardize Communication**: APIs provide a standardized way for different software components or systems to interact, regardless of their underlying technology.

**REST (Representational State Transfer)** and **GraphQL** are common API design styles. REST APIs use HTTP requests to interact with resources, while GraphQL allows clients to request specific data and aggregate results from multiple sources.

### **In Summary**

- **Frontend**: The user-facing part of a web application where users interact directly.
- **Backend**: The server-side part that processes data and handles the business logic.
- **API**: A set of rules that allows different software components to communicate and exchange data.

Together, these components work to create a complete web application, with the frontend providing the user experience, the backend managing data and logic, and the API facilitating communication between the two.

![image alt](https://github.com/Gautam-io-dev/Basic-Computer-Science-Keywords/blob/dfdfe91ea07ad09bbc6c54d2e7cedd7269572223/IMAGE%202024-09-08%2002%3A08%3A58.jpg)

17.**HYPERVISIOR**

A hypervisor, also known as a virtual machine monitor (VMM), is software or firmware that creates and manages virtual machines (VMs) on a physical host system. It sits between the hardware and the operating systems, allowing multiple operating systems to run simultaneously on a single physical machine. 

![image alt](https://github.com/Gautam-io-dev/Basic-Computer-Science-Keywords/blob/242e0ad8637badf459f08e03bd2c6d5956dc901d/Image%2020.jpeg)

There are two main types of hypervisors:

1. **Type 1 Hypervisor (Bare-metal)**: This type runs directly on the host's hardware, without an underlying operating system. It manages the hardware resources and allocates them to the virtual machines. Examples include VMware ESXi, Microsoft Hyper-V, and Xen.

2. **Type 2 Hypervisor (Hosted)**: This type runs on top of an existing operating system. It relies on the host OS to manage hardware resources and provides virtual machines with an interface to the host OS. Examples include VMware Workstation, Oracle VirtualBox, and Parallels Desktop.

Hypervisors are used for various purposes, including server virtualization, desktop virtualization, and in development and testing environments, enabling more efficient use of hardware resources and easier management of multiple operating systems.

![image alt](https://github.com/Gautam-io-dev/Basic-Computer-Science-Keywords/blob/d6d385914c1263d3e20993a32d94d47355006c0b/Image%2021.jpeg)

18. **NIC (Network Interface Card)**

    NIC stands for Network Interface Card. It's a hardware component that allows a computer or other devices to connect to a network. Here’s a quick rundown:

Function: NICs facilitate communication between a computer and a network. They handle the process of sending and receiving data packets over the network, 
making it possible for the device to access network resources, such as the internet or shared files.

![image alt](https://github.com/Gautam-io-dev/Basic-Computer-Science-Keywords/blob/bdb368e8d49eaa005144bd8348d7e71257558997/Image%2018.jpeg)

**Types:**

**Wired NICs:** These connect via Ethernet cables and are typically used in local area networks (LANs). They are often built into the motherboard of a computer 
but can also be installed as a separate expansion card.

![image alt](https://github.com/Gautam-io-dev/Basic-Computer-Science-Keywords/blob/94eeee738c61bf01fdae05f9e0d623f3a6a49232/Image.jpeg)

**Wireless NICs:** These connect via Wi-Fi and allow devices to connect to wireless networks. They are commonly found in laptops and some desktop computers, and 
can also be installed as a separate card or USB adapter.

![image alt](https://github.com/Gautam-io-dev/Basic-Computer-Science-Keywords/blob/13d53e808b8b9a414803ed6114ff4140f1337b90/Image%201.jpeg)

**Components:** A NIC typically includes a network port (like an Ethernet port for wired connections), and sometimes LEDs that indicate network activity and 
connection status. Inside, it has a chip that handles data transmission and reception.

**Configuration:** NICs usually come with drivers that need to be installed on the computer. These drivers allow the operating system to communicate with the
NIC and configure it correctly.

**Speed:** NICs come in various speeds, such as 10/100/1000 Mbps (Gigabit Ethernet) for wired connections, and support various Wi-Fi standards for wireless 
connections (e.g., 802.11n, 802.11ac, or the newer 802.11ax).

In essence, the NIC is a crucial component for network connectivity, enabling devices to communicate and share data over a network.

19.**INTERNET PACKET**

An Internet packet, often just called a "packet," is a small unit of data transmitted over a network. When you send or receive information over the Internet, it is broken down into packets to ensure efficient and reliable delivery. Here’s a breakdown of what an Internet packet typically involves:

![image alt](https://github.com/Gautam-io-dev/Basic-Computer-Science-Keywords/blob/d31c99c766f4fb9ba068ecff0b480f4326b77efc/Image%2019.jpeg)

### Components of an Internet Packet

1. **Header**:
   - **Source IP Address**: The address of the device that is sending the packet.
   - **Destination IP Address**: The address of the device that is receiving the packet.
   - **Sequence Number**: This helps in reassembling the packets in the correct order, as packets can arrive out of sequence.
   - **Protocol Information**: Specifies the protocol being used, such as TCP (Transmission Control Protocol) or UDP (User Datagram Protocol).
   - **Checksum**: A value used for error-checking to ensure the data hasn’t been corrupted during transmission.

2. **Payload**:
   - This is the actual data being transmitted, such as part of an email, a webpage, or a file. It’s the content that the packet carries from the sender to the receiver.

3. **Trailer** (Optional):
   - Some protocols include a trailer at the end of the packet that provides additional information for error checking and data integrity.
  
![image alt](https://github.com/Gautam-io-dev/Basic-Computer-Science-Keywords/blob/08a3094982334c138013df03f36dc530ace8908d/Image%202.jpeg)

### Packet Transmission and Reassembly

- **Fragmentation**: Larger messages are divided into smaller packets if they exceed the maximum transmission unit (MTU) size allowed by the network. Each packet is then transmitted independently.
- **Routing**: Packets are sent through various network devices (like routers) to reach their destination. Each router along the path may inspect and forward the packet based on its destination address.
- **Reassembly**: At the destination, packets are reassembled into their original order. This process uses sequence numbers and checksums to ensure that the complete and correct data is reconstructed.

### Protocols Involved

- **TCP (Transmission Control Protocol)**: Provides reliable, ordered, and error-checked delivery of data. TCP packets are often referred to as segments.
- **UDP (User Datagram Protocol)**: Offers a simpler, faster way to send data without the overhead of error-checking and ordering. UDP packets are often used for applications where speed is more critical than reliability, like streaming or gaming.

### Importance

Packets are fundamental to how data is transmitted over the Internet. By breaking data into smaller units, networks can manage traffic more efficiently, handle errors, and deliver data from multiple sources and destinations simultaneously. This packet-switching method is key to the scalability and robustness of Internet communications.

19.**ETHERNET**

Ethernet is a widely used technology for connecting computers and other devices in a local area network (LAN). It was first developed in the 1970s by Xerox PARC and has evolved significantly over the years. Here are some key aspects of Ethernet:

![image alt](https://github.com/Gautam-io-dev/Basic-Computer-Science-Keywords/blob/87fa6f4b285a783c4a417816620a6df8c8ef7420/Image%203.jpeg)

1. **Data Transmission**: Ethernet transmits data in packets over a network. Each packet contains both the data being sent and metadata, including addresses that help route the packet to its destination.

2. **Frame Structure**: Ethernet packets are called frames. An Ethernet frame consists of a header, payload, and a trailer. The header contains source and destination MAC addresses, while the trailer includes error-checking information.

3. **MAC Addresses**: Every Ethernet device has a unique identifier known as a MAC (Media Access Control) address. This address helps in directing packets to the correct device on the network.

4. **Physical Media**: Ethernet can use various types of cables and connectors. The most common are twisted-pair cables (like Cat5e, Cat6, or Cat6a) and fiber optics. Early Ethernet used coaxial cables, but these are less common today.

5. **Speed Variants**: Ethernet has evolved to support various speeds. Initially, it operated at 10 Mbps (10BASE-T), but now it supports higher speeds such as 100 Mbps (Fast Ethernet), 1 Gbps (Gigabit Ethernet), 10 Gbps, 40 Gbps, and even up to 400 Gbps in modern implementations.

6. **Topology**: Ethernet networks traditionally used a bus topology where devices were connected to a single central cable. Modern Ethernet networks use a star topology with switches and hubs, which improves performance and scalability.

7. **Collision Detection and Avoidance**: In the early days, Ethernet used a method called CSMA/CD (Carrier Sense Multiple Access with Collision Detection) to manage data collisions on the network. However, with modern switches, collisions are less of an issue, and this method is not as critical.

8. **Protocols**: Ethernet operates at the Data Link Layer (Layer 2) of the OSI model. It works alongside higher-layer protocols, such as IP (Internet Protocol), to provide end-to-end communication between devices on a network.

Ethernet remains a fundamental technology in networking, known for its reliability, simplicity, and continuous advancements in speed and capability.

20.** CLOUD COMPUTING**:

Cloud computing is a technology that allows individuals and organizations to access and use computing resources—such as servers, storage, databases, networking, software, and analytics—over the internet. Instead of owning and maintaining physical hardware and infrastructure, users can leverage cloud services provided by third-party vendors. Here are some key aspects of cloud computing:

1. **On-Demand Self-Service:** Users can provision and manage computing resources as needed without requiring human intervention from the service provider.

2. **Broad Network Access:** Services are available over the network and can be accessed through various devices, such as smartphones, tablets, and laptops.

3. **Resource Pooling:** Cloud providers use a multi-tenant model to pool resources and serve multiple customers with a single physical infrastructure, optimizing resource usage and efficiency.

4. **Rapid Elasticity:** Resources can be quickly scaled up or down based on demand, providing flexibility and cost-effectiveness.

5. **Measured Service:** Cloud systems automatically control and optimize resource use by leveraging metering capabilities, allowing users to pay only for what they use.

![image alt](https://github.com/Gautam-io-dev/Basic-Computer-Science-Keywords/blob/39b8449eec57cf7dcc896f06fe9fc529244f148e/Image%204.jpeg)

There are several types of cloud computing models:

- **Public Cloud:** Services are offered over the public internet and shared across multiple organizations. Examples include Amazon Web Services (AWS), Microsoft Azure, and Google Cloud Platform (GCP).

- **Private Cloud:** Services are maintained on a private network, providing greater control and security. This can be hosted on-premises or by a third-party provider.

- **Hybrid Cloud:** Combines both public and private clouds, allowing data and applications to be shared between them, offering greater flexibility and optimization.

- **Community Cloud:** Shared by several organizations with common interests or requirements, such as regulatory compliance.

Cloud computing can also be categorized into different service models:

- **Infrastructure as a Service (IaaS):** Provides virtualized computing resources over the internet, including virtual machines, storage, and networks. Examples include AWS EC2 and Google Compute Engine.

- **Platform as a Service (PaaS):** Offers a platform allowing customers to develop, run, and manage applications without dealing with underlying infrastructure. Examples include Google App Engine and Microsoft Azure App Service.

- **Software as a Service (SaaS):** Delivers software applications over the internet, on a subscription basis. Examples include Gmail, Microsoft Office 365, and Salesforce.

Cloud computing enables businesses to be more agile, scale resources according to their needs, and focus on their core activities without worrying about underlying infrastructure management.

21.**AWS (Amazon Web Service)**:

Amazon Web Services (AWS) is a comprehensive and widely adopted cloud computing platform provided by Amazon. It offers a broad range of cloud services, including computing power, storage options, and databases, among others, all delivered over the internet. AWS allows individuals and organizations to use these resources on a pay-as-you-go basis, which means you only pay for what you use.

![image alt](https://github.com/Gautam-io-dev/Basic-Computer-Science-Keywords/blob/7150007f17c5a5947552da8c138ad822dd9c998e/Image%205.jpeg)

Here’s an overview of AWS:

### **Core Services**

1. **Compute Services:**
   - **Amazon EC2 (Elastic Compute Cloud):** Provides resizable virtual servers (instances) that can be used for a variety of applications.
   - **AWS Lambda:** Allows you to run code in response to events without provisioning or managing servers (serverless computing).
   - **Amazon ECS (Elastic Container Service) and EKS (Elastic Kubernetes Service):** Manage containerized applications using Docker and Kubernetes.

2. **Storage Services:**
   - **Amazon S3 (Simple Storage Service):** Scalable object storage for storing and retrieving any amount of data.
   - **Amazon EBS (Elastic Block Store):** Provides block-level storage volumes for use with EC2 instances.
   - **Amazon Glacier:** Low-cost cloud storage service for data archiving and long-term backup.

3. **Database Services:**
   - **Amazon RDS (Relational Database Service):** Managed relational database service supporting multiple database engines (MySQL, PostgreSQL, MariaDB, Oracle, and SQL Server).
   - **Amazon DynamoDB:** Managed NoSQL database service designed for high-performance and scalability.
   - **Amazon Redshift:** Data warehouse service designed for big data analytics.

4. **Networking Services:**
   - **Amazon VPC (Virtual Private Cloud):** Enables you to create a private network within the AWS cloud.
   - **Amazon Route 53:** Scalable DNS and domain name registration service.
   - **AWS Direct Connect:** Provides a dedicated network connection from your premises to AWS.

5. **Management and Monitoring:**
   - **AWS CloudWatch:** Monitors your AWS resources and applications, providing metrics and logs.
   - **AWS CloudTrail:** Tracks user activity and API usage for auditing and compliance.
   - **AWS Config:** Provides a detailed view of the configuration of AWS resources and tracks changes.

6. **Security and Identity:**
   - **AWS IAM (Identity and Access Management):** Manages access to AWS services and resources securely.
   - **AWS KMS (Key Management Service):** Manages cryptographic keys for your applications and data.

7. **Developer Tools:**
   - **AWS CodeBuild, CodeDeploy, and CodePipeline:** Set of tools for building, testing, and deploying applications.
   - **AWS CloudFormation:** Allows you to model and provision AWS resources using templates.

### **Benefits of AWS:**

- **Scalability:** Easily scale resources up or down based on demand.
- **Cost-Effectiveness:** Pay only for what you use, with no upfront costs.
- **Global Reach:** Operates in multiple geographic regions and data centers worldwide.
- **Security:** Provides robust security features and compliance certifications.
- **Flexibility:** Supports a wide range of operating systems, programming languages, and application architectures.

AWS is used by a variety of organizations, from startups to large enterprises, for purposes such as hosting websites, running applications, managing data, and implementing big data analytics.

22.**MICROSOFT AZURE**:

Microsoft Azure, commonly referred to as Azure, is a comprehensive cloud computing platform provided by Microsoft. It offers a wide range of cloud services, including computing, analytics, storage, and networking. Users can choose and configure these services to meet their needs, allowing them to deploy and manage applications and services through Microsoft-managed data centers.

![image alt](https://github.com/Gautam-io-dev/Basic-Computer-Science-Keywords/blob/0c11a810e6b6c2df77ed49495fb4f816a85e7694/Image%206.jpeg)

Here’s an overview of Microsoft Azure:

### **Core Services**

1. **Compute Services:**
   - **Azure Virtual Machines:** Provides scalable virtual servers for running applications and workloads.
   - **Azure App Services:** Enables the deployment of web apps, RESTful APIs, and mobile backends.
   - **Azure Functions:** Allows you to run code in a serverless environment, triggered by events.

2. **Storage Services:**
   - **Azure Blob Storage:** Object storage for large amounts of unstructured data.
   - **Azure Disk Storage:** Managed disks for use with Azure Virtual Machines.
   - **Azure Files:** Managed file shares accessible via the SMB protocol.

3. **Database Services:**
   - **Azure SQL Database:** Managed relational database service for SQL Server.
   - **Azure Cosmos DB:** Globally distributed, multi-model database service for NoSQL and other data types.
   - **Azure Database for MySQL and PostgreSQL:** Managed database services for MySQL and PostgreSQL.

4. **Networking Services:**
   - **Azure Virtual Network:** Creates isolated network environments for your resources.
   - **Azure Load Balancer:** Distributes incoming network traffic across multiple resources.
   - **Azure CDN (Content Delivery Network):** Delivers content to users with low latency by caching it at strategically located edge servers.

5. **Management and Monitoring:**
   - **Azure Monitor:** Provides full-stack monitoring for applications, infrastructure, and networks.
   - **Azure Security Center:** Unified security management and threat protection for your Azure resources.
   - **Azure Resource Manager:** Provides management and deployment services for Azure resources.

6. **Security and Identity:**
   - **Azure Active Directory (AAD):** Identity and access management service for authentication and authorization.
   - **Azure Key Vault:** Manages secrets, encryption keys, and certificates securely.
   - **Azure Sentinel:** Cloud-native security information and event management (SIEM) solution for intelligent security analytics.

7. **Developer Tools:**
   - **Azure DevOps:** Provides a set of tools for planning, developing, delivering, and monitoring applications.
   - **Azure DevTest Labs:** Helps manage and automate development and test environments.
   - **Azure Resource Manager (ARM) Templates:** Defines and deploys infrastructure as code.

### **Benefits of Azure:**

- **Scalability:** Easily scale applications and resources up or down according to demand.
- **Global Reach:** Operates in multiple geographic regions worldwide, providing high availability and redundancy.
- **Cost Efficiency:** Offers a pay-as-you-go pricing model with no upfront costs.
- **Integration:** Works seamlessly with Microsoft products and services like Windows Server, SQL Server, and Active Directory.
- **Security:** Provides built-in security features and compliance with industry standards and regulations.

### **Use Cases:**

- **Hosting Websites and Applications:** Build and deploy web apps and services with high availability and scalability.
- **Data Storage and Backup:** Store and manage large volumes of data with robust backup and disaster recovery options.
- **Big Data and Analytics:** Analyze large datasets and gain insights using Azure's analytics and machine learning services.
- **Development and Testing:** Create and test applications quickly using virtual environments and automation tools.

Azure is widely used across various industries for tasks such as application development, data analytics, AI and machine learning, and hybrid cloud solutions. It competes closely with other major cloud providers like Amazon Web Services (AWS) and Google Cloud Platform (GCP).

23. **GCP(GOOGLE CLOUD PLATFORM)**:

Google Cloud Platform (GCP) is a suite of cloud computing services provided by Google. It offers a range of services for computing, storage, data analytics, machine learning, and more, enabling users to build, deploy, and scale applications and services in the cloud. GCP is known for its strong integration with Google's data infrastructure and innovative technology solutions.

![image alt](https://github.com/Gautam-io-dev/Basic-Computer-Science-Keywords/blob/20a9a1e826eb48feb40ef672a73637727cd89ef8/Image%207.jpeg)

### **Core Services**

1. **Compute Services:**
   - **Google Compute Engine:** Provides scalable virtual machines with various configurations and customizations.
   - **Google Kubernetes Engine (GKE):** Managed Kubernetes service for container orchestration and deployment.
   - **Google App Engine:** Platform-as-a-Service (PaaS) for building and deploying applications without managing the underlying infrastructure.
   - **Google Cloud Functions:** Serverless computing service that lets you run code in response to events without managing servers.

2. **Storage Services:**
   - **Google Cloud Storage:** Object storage service for storing and retrieving any amount of data at any time.
   - **Google Persistent Disk:** Block storage service for use with Google Compute Engine virtual machines.
   - **Google Filestore:** Managed file storage for applications requiring a file system interface and a shared file system.

3. **Database Services:**
   - **Google Cloud SQL:** Managed relational database service for SQL databases like MySQL, PostgreSQL, and SQL Server.
   - **Google Cloud Spanner:** Globally distributed, horizontally scalable relational database service.
   - **Google Firestore:** NoSQL document database for building web and mobile applications.
   - **Google Bigtable:** Managed NoSQL database service designed for large analytical and operational workloads.

4. **Networking Services:**
   - **Google Virtual Private Cloud (VPC):** Creates isolated network environments within GCP.
   - **Google Cloud Load Balancing:** Distributes incoming traffic across multiple virtual machines and regions.
   - **Google Cloud CDN:** Content Delivery Network service for delivering web and video content with low latency.

5. **Management and Monitoring:**
   - **Google Cloud Monitoring:** Provides visibility into your application's performance and availability.
   - **Google Cloud Logging:** Collects and stores logs from applications and services for analysis.
   - **Google Cloud Operations Suite (formerly Stackdriver):** Unified monitoring, logging, and diagnostics platform.

6. **Security and Identity:**
   - **Google Cloud Identity & Access Management (IAM):** Manages access control and permissions for resources.
   - **Google Cloud Key Management Service (KMS):** Manages cryptographic keys for data encryption.
   - **Google Cloud Security Command Center:** Provides security and risk management for your GCP resources.

7. **Machine Learning and AI:**
   - **Google AI Platform:** Tools and services for building, training, and deploying machine learning models.
   - **AutoML:** Allows users to build custom machine learning models with minimal coding.
   - **BigQuery:** Fully-managed data warehouse designed for large-scale data analytics.

### **Benefits of GCP:**

- **Innovation:** Access to advanced technologies such as artificial intelligence, machine learning, and big data analytics, leveraging Google’s expertise.
- **Scalability:** Easily scale applications and services based on demand with high availability.
- **Global Infrastructure:** Operates in multiple regions around the world, providing low-latency access and disaster recovery options.
- **Cost Efficiency:** Offers competitive pricing with a pay-as-you-go model and various discounts.
- **Integration:** Seamlessly integrates with other Google services and products, including G Suite and Google Ads.

### **Use Cases:**

- **Application Development:** Build, deploy, and manage applications with various tools and platforms.
- **Data Analytics:** Perform large-scale data processing and analytics with tools like BigQuery.
- **Machine Learning:** Develop and deploy machine learning models and leverage pre-trained models for various tasks.
- **Storage and Backup:** Store and protect data with scalable and reliable storage solutions.

GCP is used by a wide range of organizations, from startups to large enterprises, for various purposes including data processing, application development, and leveraging advanced analytics and AI capabilities. It competes with other major cloud providers like Amazon Web Services (AWS) and Microsoft Azure.

23.**DSA(DATA STRUCTURE ALGORITHMS)**:

DSA stands for Data Structures and Algorithms. It’s a foundational concept in computer science that focuses on organizing and manipulating data efficiently. Here’s a breakdown:

![image alt](https://github.com/Gautam-io-dev/Basic-Computer-Science-Keywords/blob/a151e1aeb906fcbf771accb267a987784c506aac/Image%208.jpeg)

### Data Structures
Data structures are ways to store and organize data so that it can be accessed and modified efficiently. Common data structures include:

- **Arrays**: A collection of elements identified by index or key.
- **Linked Lists**: A collection of elements where each element points to the next one.
- **Stacks**: A collection of elements that follows Last In, First Out (LIFO) principle.
- **Queues**: A collection of elements that follows First In, First Out (FIFO) principle.
- **Trees**: A hierarchical structure with a root element and sub-elements (nodes), like binary trees and binary search trees.
- **Graphs**: A set of nodes connected by edges, useful for representing networks.
- **Hash Tables**: A data structure that maps keys to values for fast retrieval.

### Algorithms
Algorithms are step-by-step procedures or formulas for solving problems. They operate on data structures to perform tasks such as:

- **Sorting**: Organizing data in a specific order (e.g., Quick Sort, Merge Sort).
- **Searching**: Finding specific data within a structure (e.g., Binary Search, Depth-First Search).
- **Traversal**: Visiting all nodes or elements in a structure (e.g., Breadth-First Search).
- **Dynamic Programming**: Solving complex problems by breaking them into simpler subproblems (e.g., Fibonacci sequence).

Understanding DSA is crucial for writing efficient code and solving complex computational problems. It also plays a significant role in coding interviews and competitive programming.

24.**DBMS(DATABASE MANAGMENT SYSTEM)**:

DBMS stands for Database Management System. It is software designed to manage databases, which are collections of data organized in a way that facilitates easy access, management, and updating. Here’s a breakdown of its key components and functions:

1### Key Components of DBMS:

1. **Database Engine**: The core service for accessing and managing data. It handles the storage, retrieval, and update of data in the database.

2. **Database Schema**: Defines the structure of the database, including tables, columns, data types, and the relationships between tables.

3. **Query Processor**: Interprets and executes queries, often written in SQL (Structured Query Language). It translates user requests into database operations.

4. **Transaction Manager**: Ensures that database transactions are processed reliably and ensures that data remains consistent and correct even in the case of errors or failures.

5. **Database Administrator (DBA) Tools**: Provides tools for database management, such as performance monitoring, backup, and recovery tools.

6. **Security Manager**: Manages user access and permissions, ensuring that only authorized users can access or modify the data.

### Functions of a DBMS:

1. **Data Storage Management**: Efficiently stores and organizes data on disk or other storage media.

2. **Data Retrieval**: Allows users to query and retrieve data efficiently, often through query languages like SQL.

3. **Data Manipulation**: Supports operations like inserting, updating, and deleting data.

4. **Data Integrity and Validation**: Ensures that data adheres to defined rules and constraints, maintaining accuracy and consistency.

5. **Concurrency Control**: Manages simultaneous data access by multiple users, ensuring that transactions do not interfere with each other and that data remains consistent.

6. **Backup and Recovery**: Provides mechanisms to back up data and recover it in case of system failure or data corruption.

   ![image alt](https://github.com/Gautam-io-dev/Basic-Computer-Science-Keywords/blob/fd0d901442f73b0df18f354d8307d89c2ee0b335/Image%209.jpeg)

### Types of DBMS:

1. **Relational DBMS (RDBMS)**: Organizes data into tables with rows and columns. Examples include MySQL, PostgreSQL, and Oracle Database.

2. **NoSQL DBMS**: Designed for unstructured or semi-structured data and often used in big data applications. Examples include MongoDB, Cassandra, and Redis.

3. **Object-Oriented DBMS (OODBMS)**: Stores data in objects, similar to object-oriented programming. Examples include db4o and ObjectDB.

4. **Hierarchical DBMS**: Data is organized in a tree-like structure. Examples include IBM’s Information Management System (IMS).

5. **Network DBMS**: Uses a graph structure where entities can have multiple relationships. Examples include Integrated Data Store (IDS).

DBMSs are essential for managing large volumes of data and are used in various applications, from enterprise systems to web applications.

25.**GITHUB**

GitHub is a platform for version control and collaborative software development. It uses Git, a version control system created by Linus Torvalds, to track changes in code and facilitate collaboration among developers. 

![image alt](https://github.com/Gautam-io-dev/Basic-Computer-Science-Keywords/blob/ec5a2160d08791a8960aaf3200f85b93c19f7480/Image%2010.jpeg)

Here's a quick rundown of what GitHub offers:

1. **Version Control**: GitHub allows you to track changes to your code over time, making it easy to manage different versions and collaborate with others.

2. **Repositories**: Projects are organized into repositories (or repos), where you can store your code, track issues, and manage documentation.

3. **Collaboration**: Multiple people can work on a project simultaneously. GitHub provides tools for reviewing code, merging changes, and managing contributions.

4. **Issue Tracking**: You can create and track issues (bugs, feature requests, etc.) related to your project.

5. **Pull Requests**: This feature lets you propose changes to a repository, review code, and discuss modifications before integrating them into the main project.

6. **GitHub Actions**: You can automate workflows like testing and deployment directly within GitHub.

7. **GitHub Pages**: Host static websites directly from your repositories.

It's widely used in the software development community for open-source projects, personal projects, and enterprise-level applications.

27.**GiTOps**

GitOps is a set of practices for managing and deploying applications using Git as the single source of truth for both infrastructure and application code. It extends the principles of DevOps and Infrastructure as Code (IaC) by using Git repositories to define, store, and manage the desired state of your infrastructure and applications. Here’s how GitOps typically works:

![image alt](https://github.com/Gautam-io-dev/Basic-Computer-Science-Keywords/blob/4487df7379739e111fd4b68c75f6a9a44121ad15/Image%2011.jpeg)

1. **Declarative Configuration**: All configurations for infrastructure and applications are stored in Git repositories in a declarative manner. This means you define the desired state of your system in configuration files (e.g., YAML files) and commit these files to the repository.

2. **Automated Deployment**: Tools that support GitOps monitor your Git repository for changes. When a change is detected, these tools automatically apply the updates to your infrastructure or application environment. This is often done through continuous deployment pipelines.

3. **Version Control**: Since all configurations and application states are stored in Git, you benefit from version control, audit trails, and rollback capabilities. You can track changes, review history, and revert to previous states if needed.

4. **Consistency and Reconciliation**: GitOps tools continuously reconcile the current state of your system with the desired state defined in Git. If there are any discrepancies, these tools will attempt to correct them automatically, ensuring consistency between your configuration and your actual deployment.

5. **Security and Compliance**: Using Git as a source of truth provides a clear, auditable history of changes. Access controls and code reviews in Git can help ensure that only authorized and reviewed changes are applied to your infrastructure and applications.

**Common Tools Used in GitOps:**

- **ArgoCD**: A declarative, GitOps continuous delivery tool for Kubernetes.
- **Flux**: Another popular tool for GitOps, which integrates with Kubernetes and automates the deployment process based on Git changes.
- **Terraform**: Often used for managing infrastructure as code, it can be part of a GitOps workflow when combined with other GitOps tools.

GitOps is particularly popular in Kubernetes environments, but the principles can be applied to other types of infrastructure and applications as well.

28.**GITLab**

GitLab is a web-based DevOps platform that provides a range of tools for managing the entire software development lifecycle. It integrates source code management, CI/CD (Continuous Integration/Continuous Deployment), and various other DevOps practices into a single application. 

![image alt](https://github.com/Gautam-io-dev/Basic-Computer-Science-Keywords/blob/87662fe3f9f8d62d586bd3de145dd1fa56d9317e/Image%2012.jpeg)

Here’s an overview of GitLab’s core features:

1. **Source Code Management (SCM)**: GitLab provides Git-based repositories for version control. You can host, manage, and collaborate on code with features such as branching, merging, and pull requests (or "merge requests" in GitLab terminology).

2. **Continuous Integration/Continuous Deployment (CI/CD)**: GitLab offers built-in CI/CD pipelines that automate the process of building, testing, and deploying code. You can define your build and deployment processes in a file called `.gitlab-ci.yml` and GitLab will execute these pipelines based on your configuration.
