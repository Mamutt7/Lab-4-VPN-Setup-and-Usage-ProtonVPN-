# Lab-4-VPN-Setup-and-Usage-ProtonVPN-
In this home lab, I will practice creating an Azure Virtual Machine and download a VPN from within that VM. I will document the different IP addresses and experiment with websites if the VPN is in another country.


(Create Virtual Machine in Azure)
1.	Browse to https://whatismyipaddress.com/ FROM WITHIN YOUR OWN MACHINE and take note of this in a text file
2.	Create a Resource Group
3.	Create a Windows 10 Virtual Machine in another geographic location (try a different country)
a.	Log into the VM with Remote Desktop
b.	Browse to https://whatismyipaddress.com/ and take note of this in a text file

![image](https://github.com/user-attachments/assets/dd30f6a1-bc59-4562-8b3e-b016beaaa9d5)


(Sign up for ProtonVPN and test the VPN connection)
4.	On your actual computer, sign up for the free version of Proton VPN https://account.protonvpn.com/signup?plan=free&language=en  
5.	Back within your VM, download the Proton VPN client
a.	Login to the VPN (https://account.protonvpn.com/login) and choose a VPN server in yet another country (such as Japan)
b.	Browse to https://whatismyipaddress.com/  and take note of this in a text file 
6.	Try browsing to Google, Disney, and/or Amazon and see if there is anything different about the sites in relation to the location of your VPN server. For example, the language or URL may be different

 ![image](https://github.com/user-attachments/assets/77b0905f-116c-4126-a656-214df4903240)



VM (NON-VPN)
--------------
IPv4: 172.214.244.206,
ISP: Microsoft Limited,
City: Chicago,
Region: Illinois,
Country: United States


VM (WITH VPN)
---------------
IPv4: 212.8.250.219,
ISP: WorldStream B.V.,
Services: Network Sharing Device,
City: Bucharest,
Region: Bucharest,
Country: Romania
