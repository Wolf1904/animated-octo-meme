
>[!tip]
>For IT or System Admin --> CompTIA A+

>[!info]
>Active Directory --> Some sort of PhoneBook 

## What is an operating system?

- Operating system is basically an application that runs everything on your pc. For example mac uses ios to run everything on its phone. If you want to get an app, you download it from the apple store. Another example is android. Android uses google play store. 
- To Run and operating system you need hardware.

---

## 32 bit vs 64 bit 

- When it comes to computers, the difference between 32-bit and a 64-bit is all about processing power. **Computers with 32-bit processors are older, slower, and less secure, while a 64-bit processor is newer, faster, and more secure** 
- If you want to upgrade to a 64-bit system, you first need to find out if you have a 64-bit processor. If you don't have the proper hardware, you might be better off buying a new computer. ==Most computers sold since 2011 already have a 64-bit chip, but not every one of them has a 64-bit operating system==.
- Obviously, **most companies may be using 64 bit and other companies don't have money  to get 64 bit because of it they're on 32 bit. That makes sense because some companies, they don't they can't afford licensing and stuff like that.**
- So there's 32 bit, 64 bit. 32 bit is slower and only in the memory when it comes to memory.
- ==You know, 32 where you're going to run four gigs around or less and then 64 bit, you can run more than four gigs around.==
- So when, *when you're working in a job environment, know the difference between 32 bit and 64 bit like maybe you're helping a user/client right now.*

- "*Why is my computer so slow?*" 
	- And then you go and check their memory and they have they have 32 gigs of Ram on a computer and they have a lot of memory where they have the wrong bits. 
	- They have a 32 bit operating system.
	- So it's not going to read all your memory if you have a 32 bit operating system, hence why we install 64 bit so that it reads all the memory on that computer because sometimes that happens.
	- Sometimes what happens is we have 32 bit, 64 bit and that's the same with applications.
	
- Applications are actually they do run some run on 32 bit and some run or 64 bit.

---

#Hardware
## Hardware 
- Memory 
- CPU Hard drive 
- User input/output 
- Motherboard 
- Graphics card

#### Motherboard

![[Pasted image 20250131000830.png]]

>[!note] CMOS
>CMOS Battery --> To change the Date/Time on the Motherboard
>If this incorrect, then this messes up with the System

### Working of the system

![[Pasted image 20250131001349.png]]

#### Ram (Random Access Memory) 

- Computer random access memory is on the most important components in determining your system performance. Ram give applications a place to store and access data on a short-term basis. It stores information your computer is actively using or running. 
- RAM allows your computer to perform many of its everyday tasks, such as loading applications, browsing the internet, editing a spreadsheet, or experiencing the latest game. Memory also allows you to switch quickly among these tasks, remembering where you are in one task when you switch to another task. As a rule, the more memory you have, the better.

	![[Pasted image 20250131001647.png]]

#### CPU

- The CPU is the core component that defines a computing device, and while it is of critical importance, the CPU can only function alongside other hardware. The silicon chip sits in a special socket located on the main circuit board (motherboard or mainboard) inside the device. It is separate from the memory, which is where information is temporarily stored. It is also separate from the graphics card or graphics chip, which renders the video and 3D graphics that are displayed on your screen. 
- AMD VS Intel 
- At its core, a CPU takes instructions from a program or application and performs a calculation. This process breaks down into three key stages: Fetch, decode, and execute. A CPU fetches the instruction from RAM, decodes what the instruction actually is, and then executes the instruction using relevant parts of the CPU.
	
	![[Pasted image 20250131002112.png]]

#### Hard Drive 

- A computer hard drive (or a hard disk or HDD) is one kind of technology that stores the operating system, applications, and data files such a documents, pictures and music that your computer uses. The rest of the components in your computer work together to show you the applications and files stored on your hard drive. 
- The main difference between an SSD vs a hard drive is in how data is stored and accessed. A hard disk drive (HDD) is a traditional storage device that uses mechanical platters and a moving read/write head to access data. A solid state drive (SSD) is a newer, faster type of device that stores data on instantly-accessible memory chips.

	![[Pasted image 20250131002330.png]]

#### Graphic Card

- A graphics card looks like a smaller version of the computer motherboard it's a printed circuit board that has a processor, RAM, and other components. A graphics card is sometimes commonly referred to as a graphics processing unit, or GPU, but in reality the GPU is just a component (albeit the primary, defining component) of the graphics card. 
- **An integrated GPU** is built into the motherboard and cannot be upgraded or replaced. You'll find this in laptops and inexpensive desktop PCs. These graphics typically have modest performance and don't perform well for tasks like games or professional graphics production. 
- **A discrete GPU** is mounted on a graphics card that slips into a computer's expansion slot on the motherboard. This kind of graphics card is replaceable so it can be upgraded as newer graphics cards are developed and helps keep a PC from becoming obsolete.

---

#Server
## Windows 2016 Server

>[!important] Windows Server 2016 Setup
>Installation: Virtualbox (For learning only)
>***Different from Windows OS*** as it has **Server Manager Tools**
>
>==**System Requirements for *Windows 2016 Server***==
>
>**CPU:**
>***Minimum***:
>- 1.4 GHz 64-bit processor
>- Compatible with x64 instruction set
>- Support for NX and DEP
>- Support for CMPXCHG16b, LAHF/SAHF, and PrefetchW instructions
>- Support for Second Level Address Translation (EPT or NPT)
>
>**RAM:**
>***Minimum***:
>- 512 MB for Server Core
>- 2 GB for Server with Desktop Experience
>- ECC (Error Correcting Code) type or similar technology for physical host deployments
>
>**Storage:**
>***Minimum***:
>- 32 GB of space
>
>**Network:**
>***Minimum***:
>- An Ethernet adapter that can achieve a throughput of at least 1 gigabit per second
>- Compliant with the PCI Express architecture specification


>[!info] Folder Sharing
>Folder Sharing on ***Windows Server 2016: up-to 16,777,216 users*** , whereas on ***Windows 10: up-to 20 users***

Set up Windows Server 2016 and Active Directory.

>[!tip]
>If you stuck at something **<u>JUST GOOGLE IT!!</u>** that means **<u>GOOGLE EVERYTHING!! You don't know.</u>**


#Active_Directory
### Active Directory

After *setting up Windows Server 2016*, install and setup **Active Directory** through *Server Manager Tools*.

- Active Directory (AD) is *a database and set of services that connect users with the network resources they need to get their work done.*
- Active Directory (AD) is a*Microsoft service that manages user accounts, devices, and network resources for Windows domain networks*. It's a key part of an organisation's IT infrastructure. 

#### What AD does
- **User management**: AD allows administrators to create, modify, and remove user accounts. 
- **Group management**: AD allows administrators to organize users into groups with different permissions. 
- **Access control**: AD checks user credentials and determines what files and applications they can access. 
- **Security management**: AD provides tools for managing security settings for an organization's IT infrastructure. 

#### How AD works
- **Hierarchical structure**: AD uses a tiered layout structure with domains, trees, and forests. 
- **Partitions**: AD organizes its database into partitions, each containing specific object types. 
- **Trusts**: AD uses trusts to moderate access rights between domains. 
- **Lightweight Directory Access Protocol (LDAP)**: AD uses LDAP to allow applications and clients to interact with DCs. 

#### AD components 
- **Active Directory Domain Services (AD DS)**: The core AD service for managing users and resources.
- **Active Directory Lightweight Directory Services (AD LDS)**: A low-overhead version of AD DS for directory-enabled applications.
- **Active Directory Certificate Services (AD CS)**: For issuing and managing digital security certificates.


>[!info]
> Active Directory **doesn't give access to Whole Servers**.

>[!important] Active Directory 
> #Active_Directory is <u>*very important for IT Support and Related Jobs.*</u>
> So, learn it **separately**
>
>For IT Support L1 (Level 1), you must know the basics of #Active_Directory 

