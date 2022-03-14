# Cybersecurity_Practice

THE BELOW IS BEING REDESIGNED SO I DON'T GET BORED OR TRAIL TOO FAR OF THE GENERAL PATH.

DESIGN LAYOUT

1. Leave the VMs as is

2. Perform a penetration test on Meta with Kali

3. Write up the penetration test report for practice

4. Breakdown and throughly document the exploits I use and why they work when using exploits

5. Have Wireshark and other tools open and logging the Meta network traffic

6. Take the logs gathered to practice forensics

7. Use tools like Volitilty, Encase, The Sleuth Kit (+Autopsy), etc. for even more forensic practice

END RESULT

1. Be able to perform regular penetration tests with reports

2. Be able to understand and eventually build out my own exploits

3. Skills with logging and monitoring tools will be gained in addition to forensic practice.

4. Resulting in being able to break in, find/build my own ways in, use forensic skillset to understand what to look for during/after an attack to then find ways to hide better during an attack. 

Repeat until hired, then specialize and repeat til dead xD.


Current Lab set up, notes, and reports

Current Homelab Setup
-Virtualbox
-Kali Linux VM
-Metasploitable 2 VM
-Windows 11 VM

Virtualbox was downloaded from https://www.virtualbox.org/ 

Kali Linux VM was downloaded from https://www.offensive-security.com/

Metasploitable 2 VM was downloaded from https://docs.rapid7.com/metasploit/metasploitable-2/

Windows 11 VM was downloaded from https://developer.microsoft.com/en-us/windows/downloads/virtual-machines/

Virtualbox is the hypervisor being used to host the 2 VMs seen above. After adding and importing these VMs into Virtualbox I did the following:

-Tested the network being used by the VMs on NAT Network setting

-Created new strong passwords for all VMs

-Made sure that both VMs could see each other with the ping command

-Trial and Error was used with the configurations of the VMs settings to make sure that they weren't putting too much strain on the Host computer

-The little lab is all set up and ready for practice attacking/defending along with practice reports

-Within this repo I'll be creating an exercise file with a random name and I will upload pictures to go with the exercise file. For example, under the "Cybersecurity_Practice/Metasploitable 2/website_enumeration/gobuster" file path; the quick_practice file is the exercise file and you can see the pictures relating to that exercise file by looking at the quick_practice files that are appended with _pic.png_ (quick_practice_pic.png).

-I'll try and build out this repo so it's easy to understand what I'm doing, why I'm doing it, and how I'm doing it for possible future employers and buddies.

-There are a few exercises where I placed the VMs on an internal network. After sourcing information from Offensive Security's website and LinkedIn Learning; I've changed the network adapters to Nat Network (lol was scared with this that I'd accidentally expose meta to the internet, so I was hesitant to do this)
