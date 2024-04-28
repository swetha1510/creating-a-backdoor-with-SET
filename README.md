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
Social Engineering attacks are the various cons used by the hackers to trick people into providing sensitive data to the attackers.The command sudo setoolkit in the prompt gives menu with set prompt

![EH exp 771](https://github.com/swetha1510/creating-a-backdoor-with-SET/assets/120623583/2a313b84-5c83-41c1-982e-b06d8abd1d72)

The command sudo setoolkit in the prompt gives menu with set prompt. Select menu1 for Social Engineering Attacks:

It displays the following menu and select 2 for Website Attack Vectors:

![EH exp 772](https://github.com/swetha1510/creating-a-backdoor-with-SET/assets/120623583/c66b91a5-6613-4929-877c-efccaf10cae0)

The website Attack Vectors displays the following menu. In this menu3 for Credential Harvester Attack Method is selected:
![EH exp 773](https://github.com/swetha1510/creating-a-backdoor-with-SET/assets/120623583/369fd6d0-edfe-461f-9005-03d9e72bcd12)

The Credential Harvester Attack Method displays the following menu. In this menu1 for Web Templates is selected: 
![EH exp 774](https://github.com/swetha1510/creating-a-backdoor-with-SET/assets/120623583/d10a55ea-dbd5-41d4-ac19-a9e8a0dd927d)

It shows the following screen in which the ip address of the attacker need to be given which is the default value:
![EH exp 775](https://github.com/swetha1510/creating-a-backdoor-with-SET/assets/120623583/47458553-62e5-489c-b1d4-8777c144d9a3)

It shows the following screen in which the option Google can be selected: 
![EH exp 776](https://github.com/swetha1510/creating-a-backdoor-with-SET/assets/120623583/010a49c1-426c-4945-bfea-46f9db8ee730)

SET starts my Kali Linux Webserver on port 80, with the fake Google account login page. The setup is done: 
![EH exp 777](https://github.com/swetha1510/creating-a-backdoor-with-SET/assets/120623583/2c0c27ac-5e4c-4596-8a94-f28523bfe673)

In windows IE, on giving the url http://192.168.1.2, the fake Google page is displayed. The victim can enter the username and password 
![EH exp 778](https://github.com/swetha1510/creating-a-backdoor-with-SET/assets/120623583/127973db-1a8e-47c7-82cb-099af91ae6c4)

SET logs the information regarding the Google credentials: 
![EH exp 779](https://github.com/swetha1510/creating-a-backdoor-with-SET/assets/120623583/1bf7d9f0-e210-4b3c-ade2-e08461690fb4)

SET logs the information in the xml file under /root/.set directory:
![EH exp 710](https://github.com/swetha1510/creating-a-backdoor-with-SET/assets/120623583/31509331-d607-47e4-a6af-35ab7978afc8)

## RESULT:
The Social Engineering Toolkit (SET) is used to create backdoor is  examined successfully
