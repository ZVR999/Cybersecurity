# Cybersecurity_Practice
Current Lab set up, notes, and reports

Current Homelab Setup
-Virtualbox
-Kali Linux VM
-Metasploitable 2 VM

Virtualbox was downloaded from https://www.virtualbox.org/ for a Windows 10 host

Kali Linux VM was downloaded from https://www.offensive-security.com/

Metasploitable 2 VM was downloaded from https://docs.rapid7.com/metasploit/metasploitable-2/

Virtualbox is the hypervisor being used to host the 2 VMs seen above. After adding and importing these VMs into Virtualbox I did the following:

-Tested the network being used by the VMs on NAT, Internal and Host-Only settings making sure to not expose Metasploitable 2 to the Internet (keeping Meta on Host-Only or Internal). \n
-Created new strong passwords for both VMs
-Made sure that both VMs could see each other with the ping command
-Trial and Error was used with the configurations of the VMs settings to make sure that they weren't putting too much strain on the Host computer
-The little lab is all set up and ready for practice attacking/defending along with practice reports
