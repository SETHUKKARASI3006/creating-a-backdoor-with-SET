# Creating-a-backdoor-with-SET
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
## OUTPUT

<img width="1065" height="857" alt="image" src="https://github.com/user-attachments/assets/96d7f852-ade2-455b-b288-95b3f8d7ff9f" />


The command sudo setoolkit in the prompt gives menu with set prompt. Select menu1 for Social Engineering Attacks:
## OUTPUT

<img width="1066" height="887" alt="image" src="https://github.com/user-attachments/assets/d47b1c27-b0ec-4a83-9ca5-ad8cd1c8fc9b" />

It displays the following menu and select 2 for Website Attack Vectors:
## OUTPUT

<img width="1066" height="888" alt="Screenshot 2025-11-27 102329" src="https://github.com/user-attachments/assets/cdb4fd21-d31c-4d4f-925f-9002a09d11ad" />


The Credential Harvester Attack Method displays the following menu. In this menu1 for Web Templates is selected:
## OUTPUT

<img width="1066" height="888" alt="Screenshot 2025-11-27 102404" src="https://github.com/user-attachments/assets/9bb2957e-8c7f-4d94-8add-cabec0f67bbd" />


It shows the following screen in which the ip address of the attacker need to be given which is the default value:
## OUTPUT

<img width="1066" height="888" alt="Screenshot 2025-11-27 102717" src="https://github.com/user-attachments/assets/908da482-0f81-4143-a285-e835f47a48d7" />

It shows the following screen in which the option Google can be selected:
## OUTPUT

<img width="1066" height="888" alt="Screenshot 2025-11-27 103106" src="https://github.com/user-attachments/assets/b1742c37-2b0a-4b7f-ba09-4f2b4d252319" />


SET starts my Kali Linux Webserver on port 80, with the fake Google account login page. The setup is done:
## OUTPUT

<img width="1066" height="888" alt="Screenshot 2025-11-27 103156" src="https://github.com/user-attachments/assets/3d811eb8-824f-4f69-8bee-740a97512b7c" />


SET logs the information regarding the Google credentials:
## OUTPUT

<img width="947" height="402" alt="Screenshot 2025-11-27 104530" src="https://github.com/user-attachments/assets/7488eaa1-bbea-4cda-a198-0f1c2fed14ae" />


SET logs the information in the xml file under /root/.set directory:
## OUTPUT

<img width="952" height="564" alt="Screenshot 2025-11-27 104427" src="https://github.com/user-attachments/assets/a63c825c-b000-488c-966f-256c42b6cbe8" />


## RESULT:
The Social Engineering Toolkit (SET) is used to create backdoor is  examined successfully
