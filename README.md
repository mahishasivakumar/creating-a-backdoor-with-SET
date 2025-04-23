# EX 7: CREATING A BACKDOOR WITH SOCIAL ENGINEERING TOOLKIT (SET)
creating a backdoor with SET - Ethical Hacking Techniques course

# AIM:
To Create a backdoor with Social Engineering Toolkit (SET)
```
Register Number: 212222040095
Name: Mahisha S
```
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

![Screenshot 2025-04-23 185012](https://github.com/user-attachments/assets/4914bc56-24ee-4d9a-a607-af2e0405cbcc)



sudo setoolkit in the prompt gives menu with set prompt. Select menu1 for Social Engineering Attacks:

It displays the following menu and select 2 for Website Attack Vectors:
![Screenshot 2025-04-23 185025](https://github.com/user-attachments/assets/75b01db4-0f88-44f3-9135-ecfef4dad125)



The website Attack Vectors displays the following menu. In this menu3 for Credential Harvester Attack Method is selected:

![Screenshot 2025-04-23 185037](https://github.com/user-attachments/assets/40a1ac25-c890-4194-a9bb-510310308783)




The Credential Harvester Attack Method displays the following menu. In this menu1 for Web Templates is selected:

![Screenshot 2025-04-23 185050](https://github.com/user-attachments/assets/015da719-4bc2-48c8-84ff-144f213a4073)




It shows the following screen in which the ip address of the attacker need to be given which is the default value:

![Uploading Screenshot 2025-04-23 185110.png…]()



It shows the following screen in which the option Google can be selected:

![Screenshot 2025-04-23 185124](https://github.com/user-attachments/assets/ac21fab3-4725-4aa8-a7c2-d9f4e3e8d6e4)




SET starts my Kali Linux Webserver on port 80, with the fake Google account login page. The setup is done:

![Screenshot 2025-04-23 185144](https://github.com/user-attachments/assets/1a5e64f4-20fb-471e-93b2-e1fbd883bd0c)




In windows IE, on giving the url http://192.168.11.152, the fake Google page is displayed. The victim can enter the username and password

![Uploading Screenshot 2025-04-23 185224.png…]()



SET logs the information regarding the Google credentials:

![Uploading Screenshot 2025-04-23 185301.png…]()



SET logs the information in the xml file under /root/.set directory:

![image](https://github.com/user-attachments/assets/eb860581-4b9f-4923-b762-13423fb56ee0)


## RESULT:
The Social Engineering Toolkit (SET) is used to create backdoor is  examined successfully
