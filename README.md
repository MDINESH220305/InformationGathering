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


# OUTPUT:
 ## WHOIS
![Screenshot 2024-04-16 092224](https://github.com/MDINESH220305/InformationGathering/assets/162429215/d04ff227-5b4c-47e6-9513-24afb50e9542)
## IP2LOCATION
![Screenshot 2024-04-16 090308](https://github.com/MDINESH220305/InformationGathering/assets/162429215/f4f4ab39-192c-42e9-a763-ba0b23429d8a)
## WEB ARCHIVE
![Screenshot (1)](https://github.com/MDINESH220305/InformationGathering/assets/162429215/ec686892-404b-45ed-ac60-33a179a3ac4d)
# WEB SERVER FINGERPRINTING
## Netcat:
nc 172.17.52.118 80
# OUTPUT
## nmap:
![322687202-24f84e6f-6782-4b3b-a985-2c418c7a0868111](https://github.com/MDINESH220305/InformationGathering/assets/162429215/8490d35f-6b8e-4257-b683-6fb6456b7925)
```
nmap -p 21 -sV --script=banner ftp.vim.org
```
# OUTPUT
![322687394-cc41e9fd-3960-4902-8c55-173c654bd424222](https://github.com/MDINESH220305/InformationGathering/assets/162429215/82f7c0e2-ef4c-4e3f-9db7-86853b36fbc4)
## Whatweb:
```
whatweb infosys.com
whatweb zoho.com
whatweb -v -a 3 172.17.52.201
```
# OUTPUT
![322687661-287ba05b-6206-4340-9a81-0dbe50f4b0df333](https://github.com/MDINESH220305/InformationGathering/assets/162429215/9b6d72af-0ebc-4d92-9b55-5736ea9decd7)
```
httprint -h 172.17.52.201 -s /usr/share/httprint/signatures.txt -P0 |more
```
![322687917-61acedb1-8109-49d9-b23e-d027b5a3edd144](https://github.com/MDINESH220305/InformationGathering/assets/162429215/835779c5-cc8d-4745-9caa-4d4611a026ce)
## Tracing the Location:
```
sudo traceroute -T www.saveetha.ac.in
```
# OUTPUT
![322688058-161b5f9d-0a95-4e0d-9ba8-62303fcba8a3555](https://github.com/MDINESH220305/InformationGathering/assets/162429215/2739cf97-6399-4c45-9621-927e411f5520)

## UDP Traceroute:
```
sudo traceroute -U www.saveetha.ac.in
```
# OUTPUT
![322688798-daa6dc36-c180-44ec-b3e8-ee0b08ca0e01666](https://github.com/MDINESH220305/InformationGathering/assets/162429215/f4d14e6c-f50d-413f-b75a-37ffdb089fae)
## ICMP Traceroute:
```
sudo traceroute  www.saveetha.ac.in
```
# OUTPUT
![322689093-0540700c-aec8-4e89-9b55-9b9dac8d8f2677777](https://github.com/MDINESH220305/InformationGathering/assets/162429215/00016d50-32ae-46f5-8a04-908704303226)


## RESULT:
The information gathering techniques tools/procedure were  identified successfully
