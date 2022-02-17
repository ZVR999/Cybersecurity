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

-Tested the network being used by the VMs on NAT, Internal and Host-Only settings making sure to not expose Metasploitable 2 to the Internet (keeping Meta on Host-Only or Internal). 

-Created new strong passwords for both VMs

-Made sure that both VMs could see each other with the ping command

-Trial and Error was used with the configurations of the VMs settings to make sure that they weren't putting too much strain on the Host computer

-The little lab is all set up and ready for practice attacking/defending along with practice reports

-Within this repo I'll be creating an exercise file with a random name and I will upload pictures to go with the exercise file. For example, under the "Cybersecurity_Practice/Metasploitable 2/website_enumeration/gobuster" file path; the quick_practice file is the exercise file and you can see the pictures relating to that exercise file by looking at the quick_practice files that are appended with _pic.png_ (quick_practice_pic.png).

-I'll try and build out this repo so it's easy to understand what I'm doing, why I'm doing it, and how I'm doing it for possible future employers and buddies.

-An important note is that with every exercise I'm doing, after placing VMs on the Internal Network setting for their adapters within Virtualbox, you'll have to set the IP addresses for each computer/VM via a command or pre-built script of your choice so the VMs can see each other on the internal network. For example, "sudo ifconfig eth0 10.11.1.2" << is the command used in my bash script to set the IPv4 address on my Kali VM to that address.
