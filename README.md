# ARP-Attack-and-Network-Sniffing
# Explore Network Sniffing and ARP Attacks
# NAME:SANJEV R M
# REG NO:212223040186
# AIM:

To explore network sniffing and ARP Attacks

## STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode

### Step 2:

Investigate on the various categories of tools as follows:


### Step 3:
Open terminal and try execute some kali linux commands

## ARP Attacks:  
ARP spoofing: A hacker sends fake ARP packets that link an attacker's MAC address with an IP of a computer already on the LAN. 
Boot kali and Windows7 virtual machines.
In windows 7 give the command arp -a


From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>
## OUTPUT:
<img width="1013" height="349" alt="image" src="https://github.com/user-attachments/assets/a226dc29-d4e1-4aa6-96bb-dbcb5630dff7" />


 dsniff:

![2](https://github.com/user-attachments/assets/9f7ed5c1-8396-4e0a-9dca-f7ac411e3535)




In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
## OUTPUT:

![3](https://github.com/user-attachments/assets/8c4a86ff-d429-47cd-98c7-5444cef4a946)



In Kali issue the following commands:
sudo dsnifff
## OUTPUT:

![4](https://github.com/user-attachments/assets/ef397cef-be60-47c9-8c91-d0b55d0135b0)



Invoke the wireshark and examine the various menus  and controls of the tool:


## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
