

> [!question] New Hire Request
> *System reported an hour ago (Tue 26 May at 12:34 PM) via Email*
> New Hire Request
> Name: **Jimmy Chan**
> Department: **IT**
> Title: **Senior Software Developer**
> Company Number: **(xxx) xxx-xxx**
> Email: **jchan@kevtech.local**
> Groups: **Add to admin group**
> Special request: ***Share drives none, give him access to his personal drive.***

---
## Microsoft Exchange Server 2016

*Microsoft Exchange Server 2016* is a widely **used email, calendaring, contact management, and collaboration platform.** It is **deployed on Windows Server operating systems** and provides **a centralised solution for managing internal and external communication within an organisation.** 

### Key Features and Functionality:

- **Email:** Enables users to send, receive, and manage email messages. 
- **Calendaring:** Provides a centralised calendar for scheduling meetings, appointments, and events. 
- **Contact Management:** Allows users to store and manage contacts within a shared database. 
- **Collaboration:** Offers features like shared mailboxes, public folders, and task management for enhanced teamwork. 
- **Outlook Web App:** Provides a web-based interface for accessing Exchange services, offering a consistent experience across devices. 
- **Client Access:** Enables secure and reliable access to Exchange services for various clients, including desktop and mobile devices.

> [!warning] End of Support:
> 
> Microsoft will end support for Exchange Server 2016 on October 14, 2025. After this date, Microsoft will no longer provide security updates, bug fixes, or technical support for Exchange Server 2016. Organisations using Exchange Server 2016 should plan for a migration to a supported version of Exchange Server or consider transitioning to Microsoft 365 or another email service.


---

## Troubleshooting Vpn In Depth

### Authentication

- Duo/RSA/Google Authenticator
- ![[Pasted image 20250422175233.png]]

### Common IT Desktop/Support Issues

- Account locked
- Password expired
- Account locked out of Duo or RSA or Google Authenticator
- Wifi needs to work for vpn to work
- Vpn profile missing on the c drive
- Vpn certificate missing
- Duo isn't getting notifications

> [!tip] Cisco Duo
> Cisco Duo is ==a cloud-based identity security solution that provides multi-factor authentication (MFA), single sign-on (SSO), and remote access capabilities==. It helps organizations improve security by verifying user identity and device health, providing a secure connection to applications and networks. 
> 
> ***Key Features of Cisco Duo:***
>- **Multi-Factor Authentication (MFA):**
>        Requires users to verify their identity using a second factor, such as a smartphone or token, in addition to a password. 
>- **Single Sign-On (SSO):**
> 	   Allows users to access multiple applications with a single set of credentials. 
>- **Remote Access:** 
> 	   Enables secure access to corporate resources from remote locations without requiring a VPN. 
>- **Device Trust:**
> 	 Provides visibility into the devices accessing your applications and ensures they meet security requirements. 
>- **Adaptive Policies:**
> 	 Allows you to define and enforce custom access security policies based on user and device characteristics. 
>- **Zero Trust:**
> 	  Employs a "never trust, always verify" approach to security, ensuring that all users and devices are verified before gaining access. 
>
>***How Cisco Duo Works:***
>	Duo works by verifying user identity and device health at every login attempt. It can be integrated with various applications and platforms, including on-premises and cloud applications. When a user attempts to access a protected resource, Duo requires them to complete MFA, such as verifying their identity through a push notification on their smartphone. Additionally, Duo can check the health and compliance of the device being used, ensuring it meets your organization's security standards. 
>
>***Benefits of using Cisco Duo:***
>- **Improved Security:**  
> 	   Reduces the risk of unauthorized access and data breaches by enforcing MFA and device trust checks. 
>- **Enhanced User Experience:**
> 	   Provides a seamless and user-friendly login experience through SSO and clientless remote access. 
>- **Increased Visibility:**
> 	 Offers detailed insights into the devices accessing your applications, allowing you to monitor and manage them effectively. 
>- **Simplified Management:**
 >	Integrates easily with existing technology and provides a centralized platform for managing access policies and user identities.


---

## Understanding Ticket System (Remedy)

![[Pasted image 20250422181807.png]]

### SLA (Service Level Agreement)

- How long can you have a ticket for?

### Creating Tickets

- Get approval if needed
- Attach the approval to the ticket
- Be clear with your information
- Note down everything you did to resolve it

### Closing Tickets

- Don't just close the ticket
- Follow up with the user or client (clients love communication)
- Putting key notes on how to fixed or resolved the issue

### Reassigning The Ticket

- User/Client calling about a ticket because the tech on vacation or sick (make sure you reassign it to someone else)
- Communicate with the other tech that he or she has the ticket now
- Let the point of escalation know that they have the ticket
- Don't just randomly assign tickets to people (be mindful of there queue)
- Make sure the ticket is assigned to the right person

### Having Tickets Stuck In The Queue

- Can't close ticket because your waiting on client (note it)
- Can't close ticket because it's a project (note it)
- Can't close ticket because your waiting for escalation to get back with you (follow up with them or note that it's being worked on)
- If you don't know how to deal with the ticket, check old tickets in the queue. Maybe someone fixed it before. Otherwise ask for help

### Managing Your Queue

- Don't have certain amount of tickets in the queue. Some managers only
- want to see 10-15 tickets max
- Update all your tickets because the manager scans the ticketing system and it tells them when it was last updated
- Take your time, this isn't a race
- Don't take too many tickets or all of them. Everyone needs to work together as a team and manage the queue

---

## Server 2016 Share Drive Access

### What is NTFS?

- NTFS (NT file system; sometimes New Technology File System) is the **file system** that the **Windows NT operating system** uses for storing and retrieving **files** on a hard disk. NTFS is the Windows NT equivalent of the Windows 95 file allocation table (**FAT**) and the **OS/2** High Performance File System (**HPFS**). However, NTFS offers a number of improvements over FAT and HPFS in terms of performance, extendibility, and security.

#### How is it used at work?

- Using security groups to grant access to a folder
- You might grant access to one user with one folder only
- Different companies have different security groups for certain folders in their department

#### How is it used in Desktop Support

- Level 1 might have permission to grant share drive access?
- Do you want the user to inherit the whole folder or just 1 folder?
- Share drive access is almost used in every IT company

>[!important] Helpdesk
>- **Windows 10**
>- **Mac os x**
>- **Active Directory**
>- **Hardware break and fix**
>- **Microsoft suite**
>- **Duo**

