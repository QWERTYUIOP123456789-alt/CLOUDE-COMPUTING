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

