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
![image](https://github.com/user-attachments/assets/04cccd57-0923-418f-85e5-f3e9fd8bb2d5)

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
![image](https://github.com/user-attachments/assets/42bffaf7-a854-41fe-8b0f-0a9e6d51384b)

## History of the website:
## Output:
![image](https://github.com/user-attachments/assets/1897022a-c8d2-4d7f-99c3-8fb4846d2d51)
## Webserver Fingerprinting:
## Netcat:
```
nc 172.17.52.118 80
```
## Output:
![238301333-7c38b307-51d1-45b5-85ec-751ed930ba9b](https://github.com/Rohithravi333/InformationGathering/assets/119394126/96afee79-3b7a-4f34-85eb-f68f51716e15)
## nmap:
```
nmap -p 21 -sV --script=banner ftp.vim.org
```
## Output:
![238301531-4631c0fd-1296-4c74-82fa-8950c48c5a61](https://github.com/Rohithravi333/InformationGathering/assets/119394126/a94781d7-73dd-4c7b-b161-2d3db08b461c)
## Whatweb:
```
whatweb infosys.com
```
whatweb zoho.com
```
whatweb -v -a 3 172.17.52.201
```
## Output:
![238301746-ab6e52ed-b1c2-4c7c-b4cb-edc75d6de5e6](https://github.com/Rohithravi333/InformationGathering/assets/119394126/88a7f64b-0329-413a-a6a3-3603b9a6d0a9)

![238302016-3daa0d6f-df5d-4571-bf8b-c2fe63bbc3cc](https://github.com/Rohithravi333/InformationGathering/assets/119394126/18eaa01f-70e3-4397-bfe9-183cdbd27186)
## httprint:
```
httprint -h 172.17.52.201 -s /usr/share/httprint/signatures.txt -P0 |more
```
## Output:
![238301937-a70e6db5-d324-4bee-80f9-9dfdf9b37338](https://github.com/Rohithravi333/InformationGathering/assets/119394126/ee29150f-c068-429a-9e8f-4aafb8d8272e)
## Tracing the Location
## TCP Traceroute:
```
sudo traceroute -T www.saveetha.ac.in
```
## Output:
![238302079-a4c85efc-4084-4513-895e-325f5f53f5f7](https://github.com/Rohithravi333/InformationGathering/assets/119394126/2768c966-a25f-4ef1-91b7-fff9dd9c3271)
## UDP Traceroute:
```
sudo traceroute -U www.saveetha.ac.in
```
## Output:
![238302091-8c7b84b9-8045-45c3-ba6a-f2af47f40e5e](https://github.com/Rohithravi333/InformationGathering/assets/119394126/5adb9206-3226-46cf-b630-c6fee4ded328)
## ICMP Traceroute:
```
sudo traceroute  www.saveetha.ac.in
```
## Output:
![238302109-00a45edd-a2df-4cc6-858c-87d5b4a6b659](https://github.com/Rohithravi333/InformationGathering/assets/119394126/fb2632fa-b607-4b5b-815b-d3d147b52331)
## RESULT:
The information gathering techniques tools/procedure were  identified successfully
