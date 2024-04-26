# ARP-Attack-and-Network-Sniffing
# Explore Network Sniffing and ARP Attacks

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
## OUTPUT:
![image](https://github.com/Gokul0117/ARP-Attack-and-Network-Sniffing/assets/121165938/b7a06166-5085-4d02-a5a8-dc5ce12c75bc)


From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>
## OUTPUT:
![318632000-891aae37-5a0c-42dc-bde0-39a0bd125c1a](https://github.com/Gokul0117/ARP-Attack-and-Network-Sniffing/assets/121165938/90b65a8e-db39-4cf6-868c-40ba5b221734)


 dsniff:




In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
## OUTPUT:
![318632043-430c1bf2-cd8c-41c7-b06b-51c391dae702](https://github.com/Gokul0117/ARP-Attack-and-Network-Sniffing/assets/121165938/f53abe52-1360-4faf-a54d-2eea9c7bde00)




In Kali issue the following commands:
sudo dsnifff
## OUTPUT:
![318632089-fe5cb0d1-aec3-4b29-a6a2-bce5f60011f0](https://github.com/Gokul0117/ARP-Attack-and-Network-Sniffing/assets/121165938/d613ddd8-7fc1-4d3c-96cd-c37222e825b4)



Invoke the wireshark and examine the various menus  and controls of the tool:
![318632114-b51acbd8-7aa5-4d59-bfd5-52c67b3cb6e1](https://github.com/Gokul0117/ARP-Attack-and-Network-Sniffing/assets/121165938/449eb20f-a0bd-4a85-8735-6cee5b7ff51a)


## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
