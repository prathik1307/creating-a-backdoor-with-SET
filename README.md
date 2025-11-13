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
Social Engineering attacks are the various cons used by the hackers to trick people into providing sensitive data to the attackers. 
The command sudo setoolkit in the prompt gives menu with set prompt:

![1setoo](https://github.com/user-attachments/assets/1fbb053a-1a6f-4a89-b316-376861efe59b)

The command sudo setoolkit in the prompt gives menu with set prompt. Select menu1 for Social Engineering Attacks:

![2](https://github.com/user-attachments/assets/2cf06711-c6fb-4bc8-94bc-6ee44d38323b)

It displays the following menu and select 2 for Website Attack Vectors:

![3](https://github.com/user-attachments/assets/212b46fe-354c-4825-b653-47c5feaf0d16)

The website Attack Vectors displays the following menu. In this menu3 for Credential Harvester Attack Method is selected:

![4](https://github.com/user-attachments/assets/ebc379d3-fcd8-4fdc-ba62-a96fc7e510bb)

The Credential Harvester Attack Method displays the following menu. In this menu1 for Web Templates is selected:

![5](https://github.com/user-attachments/assets/60009a56-316e-49c8-94ca-79e237afeb93)

It shows the following screen in which the ip address of the attacker need to be given which is the default value:

![6](https://github.com/user-attachments/assets/a7b48bb6-754f-4240-b12a-df54dd691d21)

It shows the following screen in which the option Google can be selected:

![7](https://github.com/user-attachments/assets/d644bca6-33ae-45c4-b319-029135887e7a)

SET starts my Kali Linux Webserver on port 80, with the fake Google account login page. The setup is done:

![8](https://github.com/user-attachments/assets/feb28464-8782-4f94-ba7c-63ec43d9a25b)

In windows IE, on giving the url http://192.168.1.2, the fake Google page is displayed. The victim can enter the username and password

![9](https://github.com/user-attachments/assets/47cfd00b-2329-4f00-a507-91297d6c99ee)

SET logs the information regarding the Google credentials:

SET logs the information in the xml file under /root/.set directory:

![10](https://github.com/user-attachments/assets/f7aa0ef0-e9a9-4084-8d8f-61154bf5a62a)

## RESULT:
The Social Engineering Toolkit (SET) is used to create backdoor is  examined successfully

