# Cybersecurity

THE BELOW IS BEING REDESIGNED

DESIGN LAYOUT


Sooooo, this got overwhelming real quick xD. 

Let's see.. So I'm thinking I'll use this repo with Git Pages to host my portfolio.

Things to include:

- Background of this dude typing

- Up to date picture since sweet god man have you seen your own pic on here?

- Blue/Red/Forensic/General Foundations. Probably in their own folders with subfolders

- Daily Blog Updates

- Mini goals and their achievement dates

- Primary goals

- 











1. Leave the VMs as is. After setup within Virtualbox, take snapshots of all of them just incase/for best practice.

2. Perform a penetration test on Metasploitable with Kali. This can be super simple or complex.

3. Write up the penetration test report for practice. This will show competency with penetration testing.

4. Breakdown and throughly document the exploits I use and why they work when using exploits. This will help to show mindsets and understanding of new code I run into.

5. Have Wireshark and other tools such as the ELK stack open and logging the Metasploitable network traffic. I'm debating on what VM I'll set this up with. Maybe on Kali since all the tools are already there.

6. Take the logs gathered to practice forensics. This will help show competency with forensic tools.

7. Use tools like Volitilty, Encase, The Sleuth Kit (+Autopsy), etc. for even more forensic practice.

8. Remedy the vulnerabilities accordingly

END RESULT

1. Be able to perform regular penetration tests with reports.

2. Be able to understand and eventually build out my own exploits.

3. Skills with logging and monitoring tools will be gained in addition to forensic practice.

4. Resulting in being able to break in, find/build my own ways in, patch the vulnerabilites found, blue and red team skills gained, and use forensic skillset to understand what to look for during/after an attack to then find ways to hide better during an attack. 


Repeat until hired, then specialize and repeat until dead xD.

*********************************************************************************************


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

Windows Server 2022 VM was downloaded from https://www.microsoft.com/en-us/evalcenter/

Virtualbox is the hypervisor being used to host the VMs seen above. After adding and importing these VMs into Virtualbox I did the following:

-Tested the network being used by the VMs on NAT Network setting

-Created new strong passwords for all VMs

-Made sure that VMs could see each other with the ping command

-Trial and Error was used with the configurations of the VMs settings to make sure that they weren't putting too much strain on the Host computer

-The little lab is all set up and ready for practice attacking/defending along with practice reports

-Within this repo I'll be creating an exercise file with a random name and I will upload pictures to go with the exercise file. For example, under the "Cybersecurity_Practice/Metasploitable 2/website_enumeration/gobuster" file path; the quick_practice file is the exercise file and you can see the pictures relating to that exercise file by looking at the quick_practice files that are appended with _pic.png_ (quick_practice_pic.png).

-I'll try and build out this repo so it's easy to understand what I'm doing, why I'm doing it, and how I'm doing it for possible future employers and buddies.

-There are a few exercises where I placed the VMs on an internal network. After sourcing information from Offensive Security's website and LinkedIn Learning; I've changed the network adapters to Nat Network (lol was scared with this that I'd accidentally expose meta to the internet, so I was hesitant to do this)

--TESTING OUT A NEW LAYOUT AND WILL DOCUMENT THE TRIAL AND ERROR AS I GO
