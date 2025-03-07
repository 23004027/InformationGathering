# InformationGathering
Information Gathering Techiques

# To perform information gathering techniques

# AIM:

To perform information gathering techniques using kali linux 

## STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode

### Step 2:

Investigate on the various categories of tools as follows:

### Step 3:
Open terminal/browser and try execute necessary commands/use url to perform information gathering

## Pen Test Tools Categories:
Following Categories of pen test tools are identified for information gathering:

Footprinting is a part of the reconnaissance process which is used for gathering possible information about a target computer system or network.

http://www.whois.com/whois website to get detailed information about a domain name information including its owner, its registrar, date of registration, expiry, name server, owner's contact information, etc.

## OUTPUT:
![Screenshot 2025-03-07 223424](https://github.com/user-attachments/assets/b276a405-65af-42b2-bd24-c49819a068f7)

## Finding IP address:
ping command is available on Windows as well as on Linux OS. Following is the example to find out the IP address of youtube .com


## OUTPUT:
![Screenshot_2025-03-07_11_41_58](https://github.com/user-attachments/assets/f80fc2ff-ad1b-415d-92f6-8487a60636eb)

## Finding Hosting Company:
get further detail by using ip2location.com website.
## OUTPUT :
![Screenshot 2025-03-07 223524](https://github.com/user-attachments/assets/e99ac3bd-5675-4b9e-bd39-2ff39b83a420)

## History of the website:
## OUTPUT :
![lab2(4)](https://github.com/user-attachments/assets/e4e12ae6-3543-4c00-920a-bc7f0174ae9c)
![lab2(5)](https://github.com/user-attachments/assets/c4d933a9-87b6-444f-b8ff-a4d08a2a5841)

## Webserver Fingerprinting:
## Netcat:
nc 172.17.52.118 80

## OUTPUT:
![Screenshot 2025-03-07 224609](https://github.com/user-attachments/assets/eb038a1d-f008-4dd6-9332-1d98173ae2e2)

## nmap:

nmap -p 21 -sV --script=banner ftp.vim.org
## OUTPUT :
![Screenshot 2025-03-07 224753](https://github.com/user-attachments/assets/4e92fb33-5be1-4150-b824-251d872d0706)


## Whatweb:
## OUTPUT:
![Screenshot 2025-03-07 225006](https://github.com/user-attachments/assets/bf2fc4a9-1142-4e42-aa71-5f5ad311c66a)


## httprint:
httprint -h 172.17.52.201 -s /usr/share/httprint/signatures.txt -P0 |more
## OUTPUT :
![lab2(9)](https://github.com/user-attachments/assets/ab3f61a1-c3f7-4787-8c4a-cc92f2b65b9d)

## Tracing the Location:
## TCP Traceroute:
sudo traceroute -T www.instagram.com
## OUTPUT :
![lab2(10)](https://github.com/user-attachments/assets/f9d38703-0eae-42b6-b0b0-02a6b909fa6a)

## UDP Traceroute:
sudo traceroute -U www.instagram.com
## OUTPUT :
![lab2(11)](https://github.com/user-attachments/assets/8a4b99b0-e2ea-41a0-944e-3508707777ca)
## ICMP Traceroute:
sudo traceroute  www.facebook.com
## OUTPUT :
![lab2(12)](https://github.com/user-attachments/assets/85f3b2bb-ef9f-441e-8af3-85392624d266)
## RESULT:
The information gathering techniques tools/procedure were  identified successfully
