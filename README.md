# python-oops-1
keywords
COMPUTER - Consists of three parts 
   
		1. computation
		2. storage
        3. Network

# COMPUTATION 


## CPU - CENTRAL PROCESSING UNIT (also known as a processor).

CPU is reffered to as the brain of the computer and is the most important component of the computer . The fundamental steps or sequence of steps which he Cpu performs are known as the fetch executive cycle or instruction cycle.
STEPS ARE- 1. FETCH 2. DECODE THE INSTRUCTION 3. EXECUTE 4. STORE THE RESULTS

PARTS OF CPU -
ARITHEMATIC LOGIC UNIT (ALU) - Performs all mathematical and arithematic operations.
1. data transfer 2. Arithematic operation 3. Decision making

CONTOLLING UNIT (CU) - It is in- charge of fetch execution cycle. It extracts the instructions from memory and decodes and excutes them calling on the ALU, when neccessary.

REGISTERS - Small and fast storage area inside computers. It is used to immediate calcualtions or instuctions that are needed immediately.


## DPU → Data Processing Unit
 It manages data movement, networking, and storage tasks so the CPU can focus on running programs. It manages data movement, networking, and storage tasks so the CPU can focus on running programs.
 
 ### Purpose

Offloads data-heavy tasks from the CPU (like network packet handling, encryption, compression, etc.). Improves speed for cloud computing, AI, and data centers.

### where is it used ?

NVIDIA BlueField DPU

Intel Infrastructure Processing Unit (IPU — similar concept)

## GPU - Graphics processing unit

A GPU is a special chip in your computer that is really good at doing many small calculations at the same time.

It was originally made for drawing graphics (images, videos, games), but now it’s also used for AI, machine learning, and data processing because of its parallel processing power.

### Purpose

Render images and videos.

Speed up tasks that need massive parallel calculations (AI, simulations, crypto mining).

### Where it’s used

Gaming computers & consoles

AI/ML model training

3D rendering & animation

Data science and deep learning

### Examples

NVIDIA GeForce RTX series (gaming)

NVIDIA Tesla / A100 / H100 (AI & data centers)

AMD Radeon RX series

## TPU - Tensor processing unit 

A TPU is a special chip made by Google that’s designed only to make AI and Machine Learning (especially deep learning) work super fast.

### Purpose

Speed up AI/ML model training and inference.

Optimized for tensor math used in neural networks.

### Where it’s used

Google Cloud servers

AI research (Google Translate, Google Photos, etc.)

Large-scale deep learning projects

# OPERATING SYSTEM 

An operating system is an interface between the user and the computer hardware. It manages computer resources and enables effective operation of hardware by users and applications.



# STORAGE 

### PRIMARY STORAGE 

Primary storage also known as main memory storage.

Examples: RAM (Random Access Memory), Cache memory.

Key Points:

Fast access speed.

Volatile (data is lost when power is off).

Directly accessed by the CPU.

### Secondary Storage 

##### Meaning: 

Permanent storage used to keep data and programs for long-term use.

##### Examples:

Hard Disk Drive (HDD), Solid State Drive (SSD), CD/DVD, Pen drives.

##### Key Points:

Slower than primary storage.

Non-volatile (data remains even when power is off).

Used for storing files, applications, and the operating system.


# 3. NETWORK 

### LAN(LOCAL AREA NETWORK )
A LAN covers a small geographic area, such as a home, office, or campus. It connects devices within this limited area.

### WAN (WIDE AREA NETWORK)
A WAN spans a large geographic area, like multiple cities, countries. WANs can be public, like the internet, or private, like intranet.


## NIC (NETWORK INTERFACE CARD)
A network interface card, also known as NIC or network interface controller, is typically a circuit board installed on the computer to connect to the network. It works as an indispensable component for the network connection of computers.

# OPEN SOURCE VS CLOSED SOURCE 

Open source software refers to computer software whose source is open means the general public can access and use it. In short, it is referred to as OSS.This code can be modified by other users and organizations means that the source code is available for anyone to look at.

Closed Sourcesoftware refers to computer software whose source code is closed means the public is not given access to the source code. In short it is referred as CSS. In closed source software the source code is protected. The only individual or organization who has created the software can only change it.

# CLOUD COMPUTING 


Cloud Computing is a technology that allows users to store, manage, and process data or run applications over the internet using remote servers instead of their own local computers or devices. In simpler terms, Instead of saving files and programs only on your computer, you can use the internet (“the cloud”) to access storage, software, and services anytime, anywhere.

## 1. BARE METAL SYSTEM

A bare metal system is a computer system in which the operating system or application software runs directly on the physical hardware without using any intermediate layer like virtualization or a host operating system.

EG- 1. ATM Machines 

The ATM has its own operating system installed directly on the machine → no virtualization. That’s bare metal.

2. Smartphones 

Your Android or iOS runs directly on the phone’s hardware → also a bare metal system.

## 2. BLOCKCHAIN

A blockchain is a decentralized and distributed digital ledger that stores data in the form of blocks linked together in a chain. Once data is recorded in a block, it cannot be altered easily, which makes blockchain secure, transparent, and tamper-proof. It’s like a digital notebook that is shared among many computers. Everyone has the same copy, and once something is written in it, it cannot be erased or changed.

Eg- 1. Cryptocurrency (like Bitcoin, Ethereum) → Transactions are stored in blockchain.
2.Voting Systems → Some governments are testing blockchain-based voting for security.


## ARM = Advanced RISC Machines

It is both the name of the company and the chip architecture they design.

“RISC” means Reduced Instruction Set Computing → a processor design that uses simple instructions so that chips work faster and with less power.

In simpler terms, ARM chips = Smart, low-power processors used in mobiles, tablets, and smart devices.

## CISC (Complex Instruction Set Computing) 

It is a type of processor design where the chip can understand and execute many complex instructions in a single command.

Most Intel and AMD laptops/desktops use CISC processors.

They can run complicated software easily because the chip handles complex tasks.

## RISC ( REDUCED INSTRUCTION SET COMPUTER )

RISC (Reduced Instruction Set Computing) → It is a type of processor design where the chip uses simple and small instructions to perform tasks.Each instruction does less work, but the processor can execute instructions very fast and efficiently.

Uses less power, which is why it’s popular in mobiles, tablets, and embedded devices.

## RISC-V

RISC-V is an open-source processor design based on RISC principles, allowing anyone to build fast and efficient chips.It is based on RISC principles and develop in 2023 and which is a free open source. it also have a project called SHAKTI.


## ASIC

ASIC (Application-Specific Integrated Circuit) → A type of custom-made chip designed to do one specific task really efficiently.

# VIRTUAL MACHINE

A virtual machine (VM) is a software-based emulation of a physical computer that allows multiple operating systems or instances to run on a single physical machine. VMs provide isolation, encapsulation, and resource efficiency, making them valuable for development, testing, and production environments. 

In simpler terms, It is a software-based computer that acts like a real computer but runs inside another computer.

### KERNEL
The kernel is a computer program at the core of a computer's operating system and generally has complete control over everything in the system. The kernel is also responsible for preventing and mitigating conflicts between different processes.	

The kernel is like the bridge between the hardware and software.

It controls CPU, memory, devices, and programs so they work together smoothly.

Without the kernel, the operating system cannot function.

### IP ADDRESS

An IP address (Internet Protocol address) is a unique string of numbers separated by periods or colons that identifies each device connected to a network. IP addresses serve two primary functions: identifying the host or network interface and providing the location of the host in the network. They are essential for routing internet traffic and ensuring data reaches the correct destination.

### Port No. 

It is a number assigned to a specific process or service on a computer to help send and receive data over a network. a way to identify a specific process to which an internet or other network message is to be forwarded when it arrives at a server. • [for http - 80 • SSH(Secure Shell) - 22 • SMTP - 25 • Telnet - 23 • https - 443 • DNS - 53

### SSL( Secure Socket Layer )

It is a security technology that protects the data sent between a user’s browser and a website.

SSL encrypts information so hackers cannot read it while it travels over the internet. You can see it as the lock icon (🔒) in your browser address bar when visiting a secure website.

### ISP(Internet Service Provider)
An ISP, or Internet Service Provider, is a company or organization that provides individuals and businesses with access to the internet.

### Digital Subscriber Line (DSL) 
It is a technology that provides high-speed internet over regular telephone lines.

### Cable:
Uses cable television lines for internet service.

### Fiber-optic:
Uses fiber-optic cables for high-speed internet access.

### Satellite:
Provides internet access via satellite signals, useful in remote areas.

### Wireless:
Uses radio signals to connect to the internet, which can include both fixed wireless and mobile broadband.

### DNS(Domain Name System)
DNS stands for Domain Name System. It functions like a phone book for the internet, translating human-friendly domain names (like www.example.com) into IP addresses (like 192.0.2.1) that computers use to identify each other on the network.

### VPN(Virtual Private Network)
A VPN, or Virtual Private Network, is a service that creates a secure, encrypted connection over a less secure network, such as the internet. It allows you to access the internet as if you were connected to a private network, providing privacy and security.

# FRONTEND,BACKEND AND API(Application Programming Interface)
In web development, the terms frontend, backend, and API refer to different aspects of building and managing applications. Here’s a breakdown of each:

### 1.Frontend
Frontend refers to the client-side of a web application. It encompasses everything that users interact with directly in their web browsers. This includes:

### 2.Backend
Backend refers to the server-side of a web application. It involves everything that happens on the server and is responsible for managing and processing data. Key aspects include:

### 3.API
API stands for Application Programming Interface. It is a set of rules and protocols that allows different software applications to communicate with each other. APIs can be used to connect Frontend and Backend

#### Together, these components work to create a complete web application, with the frontend providing the user experience, the backend managing data and logic, and the API facilitating communication between the two.

# The 7 layers of OSI model:-
### :-Layer 7 : (Application Layer) - The application layer is used by end-user software such as web browsers and email clients.

### :-Layer 6 : (Presentation Layer )- The presentation layer prepares data for the application layer. It defines how two devices should encode, encrypt, and compresses data so it is received correctly on the other end.

### :-Layer 5 : (Session Layer )- The session layer creates communication channels, called sessions, between devices.

### :-Layer 4 : (Transport Layer )- The transport layer takes data transferred in the session layer and breaks it into “segments” on the transmitting end.

### :-Layer 3 : ((Networking Layer) - The network layer has two main functions. One is breaking up segments into network packets, and reassembling the packets on the receiving end.

### :-Layer 2 : (Data-Link-Layer) - The data link layer establishes and terminates a connection between two physically-connected nodes on a network.

### :-Layer 1 :( Physical Layer) - The physical layer is responsible for the physical cable or wireless connection between network nodes.

# Hypervisor :-
A hypervisor is a software layer that allows multiple virtual machines (VMs) to run on the same physical machine. It's also known as a virtual machine monitor (VMM)

















		
