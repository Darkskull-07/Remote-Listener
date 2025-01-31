# Remote-Listener
Remotely connect to the system using netcat
Tools used -> Nmap,Netcat.
Os used-> Windows,kali linux
#initial 
-> To run Netcat in windows we need to download Nmap with Npcap
#1.Make linux into Listener mode
command for linux --> netcat -lp 4545   // l -> used to set  listener mode p -> port number 
#Port 4545 is used for various purposes, including by the WorldScores service, which is registered for both TCP and UDP protocols.
#2.Connect windows to linux using Netcat in cmd
command for windows --> ncat 192.165.XXX.XXX 4545
//This provides active connection between windows and linux
