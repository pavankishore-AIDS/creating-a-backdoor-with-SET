# creating-a-backdoor-with-SET
creating a backdoor with SET - Ethical Hacking Techniques course

# AIM:
To Create a backdoor with Social Engineering Toolkit (SET)

## DESIGN STEPS:
### Step 1:
Install kali linux either in partition or virtual box or in live mode.

### Step 2:
Investigate on the various categories of tools as follows.

### Step 3:
Open terminal and try execute some kali linux commands.

## EXECUTION STEPS AND ITS OUTPUT:
Social Engineering attacks are the various cons used by the hackers to trick people into providing sensitive data to the attackers. The command sudo setoolkit in the prompt gives menu with set prompt:

![o1 (3)](https://github.com/pavankishore-AIDS/creating-a-backdoor-with-SET/assets/94154941/cb5152fa-127a-425e-878a-acef4cafa055)


The command sudo setoolkit in the prompt gives menu with set prompt. Select menu1 for Social Engineering Attacks:

It displays the following menu and select 2 for Website Attack Vectors:

![o2 (3)](https://github.com/pavankishore-AIDS/creating-a-backdoor-with-SET/assets/94154941/c1569fed-0d5e-44f3-bf61-dca372b5b99f)

The website Attack Vectors displays the following menu. In this menu3 for Credential Harvester Attack Method is selected:

![o3 (3)](https://github.com/pavankishore-AIDS/creating-a-backdoor-with-SET/assets/94154941/695956ef-22a3-44cd-9b90-4bcbf0a00b5c)

The Credential Harvester Attack Method displays the following menu. In this menu1 for Web Templates is selected: 

![o4 (2)](https://github.com/pavankishore-AIDS/creating-a-backdoor-with-SET/assets/94154941/3fcf2012-5eed-4926-83c7-608c732a6693)

It shows the following screen in which the ip address of the attacker need to be given which is the default value:

![o5 (2)](https://github.com/pavankishore-AIDS/creating-a-backdoor-with-SET/assets/94154941/22e703a8-c2a9-4f24-9f0a-33660fbc3a0d)

It shows the following screen in which the option Google can be selected: 

![o6 (2)](https://github.com/pavankishore-AIDS/creating-a-backdoor-with-SET/assets/94154941/051c3e21-23a2-4ae5-8eef-f01d38bdb81a)

SET starts my Kali Linux Webserver on port 80, with the fake Google account login page. The setup is done: 

![WhatsApp Image 2024-05-10 at 20 29 41_72b00372](https://github.com/pavankishore-AIDS/creating-a-backdoor-with-SET/assets/94154941/927e1714-21c4-4535-a295-4854a6826802)


In windows IE, on giving the url http://192.168.1.2, the fake Google page is displayed. The victim can enter the username and password 

![WhatsApp Image 2024-05-10 at 20 30 26_e494272f](https://github.com/pavankishore-AIDS/creating-a-backdoor-with-SET/assets/94154941/073402da-d6d1-4b24-b172-6cc61a7e1588)


SET logs the information regarding the Google credentials: 

![o9](https://github.com/pavankishore-AIDS/creating-a-backdoor-with-SET/assets/94154941/b0f68586-3e00-4b71-81d7-90aef47c1c45)

SET logs the information in the xml file under /root/.set directory:

![o10](https://github.com/pavankishore-AIDS/creating-a-backdoor-with-SET/assets/94154941/5f0443ba-16b5-4343-bf75-adc7d3e742d4)

## RESULT:
The Social Engineering Toolkit (SET) is used to create backdoor is  examined successfully
