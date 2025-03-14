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
![Screenshot 2025-03-14 134550](https://github.com/user-attachments/assets/e8be7548-b8f5-41a4-94ed-92c211a832c3)


## Finding IP address:
ping command is available on Windows as well as on Linux OS. Following is the example to find out the IP address of saveetha.ac.in.

```
ping saveetha.ac.in
```
## Output:
![Screenshot 2025-03-10 113255](https://github.com/user-attachments/assets/f2140cdd-ae48-4c9e-96c0-b582a6e3fa24)

## Finding Hosting Company
get further detail by using ip2location.com website.
## Output:
![Screenshot 2025-03-14 134751](https://github.com/user-attachments/assets/27e9829e-5458-4061-b9f1-833b93c0a81e)


## History of the website:
## Output:
![Screenshot 2025-03-14 134952](https://github.com/user-attachments/assets/fcf2e520-d8a5-4133-a019-7a2b17ac1f48)

## Webserver Fingerprinting:
## Netcat:
```
nc example.com 80
```
## Output:
![Screenshot 2025-03-14 135754](https://github.com/user-attachments/assets/495bfd98-a6a1-421f-84c4-20fc524c9fc6)



## nmap:
```
nmap -V -Pn 192.168.1.100

```
## Output:
![Screenshot 2025-03-14 135855](https://github.com/user-attachments/assets/707919c0-099b-4d46-a7a6-636fc8eecf04)

## Whatweb:
```
whatweb infosys.com
whatweb zoho.com
```
## Output:
![Screenshot 2025-03-14 140903](https://github.com/user-attachments/assets/306a574b-6d57-4491-b9b7-62ebbebe22c8)

## Tracing the Location
## TCP Traceroute:
```
sudo traceroute -T www.saveetha.ac.in
```
## Output:
![Screenshot 2025-03-14 141635](https://github.com/user-attachments/assets/31ee4eda-b3e6-4e32-b047-f4dfb4d7d780)

## UDP Traceroute:
```
sudo traceroute -U www.saveetha.ac.in
```
## Output:
![Screenshot 2025-03-14 141958](https://github.com/user-attachments/assets/c2a9800d-41c7-4f7a-81bf-c8a5e15dd5be)

## ICMP Traceroute:
```
sudo traceroute  www.saveetha.ac.in
```
## Output:
![Screenshot 2025-03-14 142225](https://github.com/user-attachments/assets/a2d1195e-b572-4f26-a122-7136e8d75403)

## RESULT:
The information gathering techniques tools/procedure were  identified successfully
