# creating-a-backdoor-with-SET
creating a backdoor with SET - Ethical Hacking Techniques course

# AIM:
To Create a backdoor with Social Engineering Toolkit (SET)

## DESIGN STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode


### Step 2:

Investigate on the various categories of tools as follows:

### Step 3:

Open terminal and try execute some kali linux commands

## EXECUTION STEPS AND ITS OUTPUT:
Social Engineering attacks are the various cons used by the hackers to trick people into providing sensitive data to the attackers.The command sudo setoolkit in the prompt gives menu with set prompt:

![EH exp 771](https://github.com/gowriganeshns/creating-a-backdoor-with-SET/assets/120623583/f8334d73-cc39-464e-81be-5755b9a410f1)

The command sudo setoolkit in the prompt gives menu with set prompt. Select menu1 for Social Engineering Attacks:

It displays the following menu and select 2 for Website Attack Vectors:
![EH exp 772](https://github.com/gowriganeshns/creating-a-backdoor-with-SET/assets/120623583/a02e45b3-4e1e-4bd2-9a89-727c8d4b2e8b)


The website Attack Vectors displays the following menu. In this menu3 for Credential Harvester Attack Method is selected:
![EH exp 773](https://github.com/gowriganeshns/creating-a-backdoor-with-SET/assets/120623583/43b9dd6a-d1bd-4fbe-b8cd-14d22426773e)

The Credential Harvester Attack Method displays the following menu. In this menu1 for Web Templates is selected: 
![EH exp 774](https://github.com/gowriganeshns/creating-a-backdoor-with-SET/assets/120623583/410d6ee9-bb16-4f8a-bbbf-bc76075fca91)

It shows the following screen in which the ip address of the attacker need to be given which is the default value:
![EH exp 775](https://github.com/gowriganeshns/creating-a-backdoor-with-SET/assets/120623583/fecc3ea4-6f4a-4966-99be-a822207ef66c)


It shows the following screen in which the option Google can be selected: 
![EH exp 776](https://github.com/gowriganeshns/creating-a-backdoor-with-SET/assets/120623583/96b25e17-e3a0-422e-b726-e1ffb92bd467)


SET starts my Kali Linux Webserver on port 80, with the fake Google account login page. The setup is done: 
![EH exp 777](https://github.com/gowriganeshns/creating-a-backdoor-with-SET/assets/120623583/0ac351b0-642b-4654-80d8-8e9eae1a4450)

In windows IE, on giving the url http://192.168.1.2, the fake Google page is displayed. The victim can enter the username and password 
![EH exp 778](https://github.com/gowriganeshns/creating-a-backdoor-with-SET/assets/120623583/3b0a4072-2d05-466b-b6e9-8ee65fcb1df9)

SET logs the information regarding the Google credentials: 
![EH exp 779](https://github.com/gowriganeshns/creating-a-backdoor-with-SET/assets/120623583/b57e1fff-8220-491d-9231-07841bcfb187)

SET logs the information in the xml file under /root/.set directory:
![EH exp 710](https://github.com/gowriganeshns/creating-a-backdoor-with-SET/assets/120623583/ca82cfbc-34dc-4529-af59-6898352b9147)

## RESULT:
The Social Engineering Toolkit (SET) is used to create backdoor is  examined successfully
