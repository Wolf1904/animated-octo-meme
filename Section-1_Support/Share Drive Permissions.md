## IT Technician Interview Task

>[!question] 
>**IT Technician Interview Task**
>
>![[Pasted image 20250209012618.png]]
>
>*What they want?*
>- They want you to **install Active Directory on the server**.
>- Then, they want you to **rename the server** and it could be **done in any order** and they want you to **do NTFS your drive permission**, the <u>way to actually share drive permission a bunch of users and now they only have access to a specific folder</u>, not the other folders.
>  
>  ---
>  
>*Solution:-*
>
>- *Step 1:* Create a bunch of **staff members**.
>- *Step 2:* Give them their title **"Sales, H.R., Finance."**
>- *Step 3:* Give them **scheduled permission**.
>- *Step 4:* **Install active directory domain services on a server 2016** and **renamed the server SVR-01**.
>  
>And that's it.

---

>[!warning]
>If **Client VM does not connect with DC (Domain Controller) VM:**
>- *Step 1:* Check the configurations on both VMs:
>	- IPs should be in the same network
>	- Subnet must match
>	- Default gateway should be same
>	- DNS should be DC's IP address
> 
>- *Step 2:* Check Network Connection
>	- Both VMs connected to Same Network (Bridged, NAT, Host-only)
>	- Test Basic Connectivity (If <u>neither can ping each other</u>, it's a <u>network issue</u>. If the <u>server can ping the client but not or vice versa</u>, it's likely a <u>firewall issue on the DC</u>.)
>
>*If the above doesn't work, then follow further steps*
>- *Step 3:* Disable Firewalls Temporarily
>- *Step 4:* Check Routing & ARP Table
>- *Step 5:* Restart Network Adapters
>- *Step 6:* Reboot Both Machines

>[!tip]
>**When Both VMs Are Connected to the Same Network**
> - If using *Bridged Mode*, both VMs should get *IPs from the same router*.
> - If using *NAT*, ensure they can *communicate internally* (by *NAT Network*).
> - If using *Host-Only*, ensure both are *using the same Virtual Network Adapter*.

