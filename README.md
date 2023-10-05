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

## OUTPUT:
![image](https://github.com/MohammedFaizal05/creating-a-backdoor-with-SET/assets/120553195/d31eba52-159c-4b00-83cc-78e4649431b7)

The command sudo setoolkit in the prompt gives menu with set prompt. Select menu1 for Social Engineering Attacks:

## OUTPUT:
![image](https://github.com/MohammedFaizal05/creating-a-backdoor-with-SET/assets/120553195/903d6c19-6d6c-44ae-b0d0-f1ab17d44be5)

It displays the following menu and select 2 for Website Attack Vectors:

## OUTPUT:
![image](https://github.com/MohammedFaizal05/creating-a-backdoor-with-SET/assets/120553195/a1b6b135-81d9-408e-b13d-57a269fcb8f6)


The website Attack Vectors displays the following menu. In this menu3 for Credential Harvester Attack Method is selected:

## OUTPUT:
![image](https://github.com/MohammedFaizal05/creating-a-backdoor-with-SET/assets/120553195/90feac9c-03af-4140-ae1a-c6287d2e5103)

The Credential Harvester Attack Method displays the following menu. In this menu1 for Web Templates is selected:

## OUTPUT:
![image](https://github.com/MohammedFaizal05/creating-a-backdoor-with-SET/assets/120553195/bb888dae-10d6-4206-9862-3c7bc92aead5)

It shows the following screen in which the ip address of the attacker need to be given which is the default value:

## OUTPUT:
![image](https://github.com/MohammedFaizal05/creating-a-backdoor-with-SET/assets/120553195/b691c6a0-5b37-4016-b9fe-a9bc1332a8b1)

It shows the following screen in which the option Google can be selected:

## OUTPUT:
![image](https://github.com/MohammedFaizal05/creating-a-backdoor-with-SET/assets/120553195/91f4d18a-1189-4f13-8091-b4e14a7fde2c)

SET starts my Kali Linux Webserver on port 80, with the fake Google account login page. The setup is done:

## OUTPUT:
![image](https://github.com/MohammedFaizal05/creating-a-backdoor-with-SET/assets/120553195/c2daabfd-8d9d-4ea6-bde0-fc0c2c71a668)

In windows IE, on giving the url http://192.168.1.2, the fake Google page is displayed. The victim can enter the username and password

## OUTPUT:
![image](https://github.com/MohammedFaizal05/creating-a-backdoor-with-SET/assets/120553195/47e41d5f-78d5-4aff-a65a-70cd445d2ce9)

SET logs the information regarding the Google credentials:

## OUTPUT:
![image](https://github.com/MohammedFaizal05/creating-a-backdoor-with-SET/assets/120553195/fa137d18-d537-43f1-a5f2-bf7ed7800556)

SET logs the information in the xml file under /root/.set directory:

## OUTPUT:
![image](https://github.com/MohammedFaizal05/creating-a-backdoor-with-SET/assets/120553195/7b369522-58f2-480f-bd41-421d7aa8086b)

## RESULT:
The Social Engineering Toolkit (SET) is used to create backdoor is  examined successfully
