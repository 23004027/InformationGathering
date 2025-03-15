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
![Screenshot 2025-03-08 134806](https://github.com/user-attachments/assets/00d97c65-f623-4b7d-87e4-bb1bf5273e8c)



## Finding IP address:
ping command is available on Windows as well as on Linux OS. Following is the example to find out the IP address of youtube .com


## OUTPUT:
![Screenshot_2025-03-07_11_41_58](https://github.com/user-attachments/assets/f80fc2ff-ad1b-415d-92f6-8487a60636eb)

## Finding Hosting Company:
get further detail by using ip2location.com website.
## OUTPUT :
![Screenshot 2025-03-15 080828](https://github.com/user-attachments/assets/54db0f47-e8ae-4dfc-93ea-bef27fa5702f)



## History of the website:
## OUTPUT :
![Screenshot 2025-03-15 081035](https://github.com/user-attachments/assets/3e855e86-ada2-47dd-af9c-bfa7ccc85f1c)
![Screenshot 2025-03-15 081047](https://github.com/user-attachments/assets/0c891cfb-7617-4a62-8cf1-cb2d21d0ebdb)
![Screenshot 2025-03-15 081101](https://github.com/user-attachments/assets/c13144ae-8380-48f0-8fc6-9057fdf1b8cd)


## Webserver Fingerprinting:
## Netcat:
nc 172.17.52.118 80

## OUTPUT:
![Screenshot 2025-03-07 224609](https://github.com/user-attachments/assets/eb038a1d-f008-4dd6-9332-1d98173ae2e2)

## nmap:

nmap -p 21 -sV --script=banner ftp.vim.org
## OUTPUT :
![Screenshot_2025-03-08_03_09_18(1)](https://github.com/user-attachments/assets/6f224bf2-8c26-4625-80bb-b89e2f8520ba)


## Whatweb:
## OUTPUT:
![Screenshot 2025-03-07 225006](https://github.com/user-attachments/assets/bf2fc4a9-1142-4e42-aa71-5f5ad311c66a)


## httprint:
httprint -h 172.17.52.201 -s /usr/share/httprint/signatures.txt -P0 |more
## OUTPUT :
![lab2(9)](https://github.com/user-attachments/assets/ab3f61a1-c3f7-4787-8c4a-cc92f2b65b9d)

## Tracing the Location:
## TCP Traceroute:

## OUTPUT :

![Screenshot_2025-03-08_03_49_51](https://github.com/user-attachments/assets/9fa0e8aa-028e-4a87-9500-27ab11ea57d7)

## UDP Traceroute:

## OUTPUT :
![Screenshot_2025-03-08_03_51_52](https://github.com/user-attachments/assets/3314af83-33c5-484a-b0cc-9027bed6469b)

## ICMP Traceroute:

## OUTPUT :
![Screenshot_2025-03-08_03_51_56](https://github.com/user-attachments/assets/762512fb-14ef-4d05-98e2-fba45d171252)


## RESULT:
The information gathering techniques tools/procedure were  identified successfully
