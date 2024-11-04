## REG.NO:212222040178
## NAME:Vijay Shankar M
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
![380646321-902bcc97-2918-465c-8a51-1097feb9c9b0](https://github.com/user-attachments/assets/6349f14d-1c30-4eb5-9801-bad6a73f9e91)

It displays the following menu and select 2 for Website Attack Vectors: 
![380646389-0c2db713-ec1c-4805-af15-bec724c12332](https://github.com/user-attachments/assets/42b2d930-90a4-4a09-9873-345a90a27e0c)


The website Attack Vectors displays the following menu. In this menu3 for Credential Harvester Attack Method is selected: image
![380646445-d6d1bd40-378d-4279-a3fb-d7e20ee9803d](https://github.com/user-attachments/assets/178fc9ba-7cba-4740-be23-f6a72f5ede0e)

The Credential Harvester Attack Method displays the following menu. In this menu1 for Web Templates is selected: 
![380646509-5d783d46-ae7a-4edd-87cc-20d3ed23b137](https://github.com/user-attachments/assets/ff416b9b-a65c-47b8-9acb-60731df9bb07)

It shows the following screen in which the ip address of the attacker need to be given which is the default value: 
![380646607-78fff169-108c-4534-b512-978b72317527](https://github.com/user-attachments/assets/986254f6-ad91-4100-944d-165b0aebc7e3)

It shows the following screen in which the option Google can be selected 
![380646696-e8cb0533-919f-4cb7-87aa-64a1f1b51503](https://github.com/user-attachments/assets/6afeec53-f6b4-4ad1-8639-c2c36d207622)

SET starts my Kali Linux Webserver on port 80, with the fake Google account login page. The setup is done: 
![380646811-e0f6c430-1527-4f9b-a40d-be2070205bb1](https://github.com/user-attachments/assets/2d4ad1d0-5f1e-4d36-9140-821a60bbedab)

In windows IE, on giving the url http://192.168.74.***, the fake Google page is displayed. The victim can enter the username and password 
![380647311-63842432-fe52-4534-817f-a0a533af3961](https://github.com/user-attachments/assets/cd5c534d-b070-4abe-aef3-9b8bf5ab5ec9)

SET logs the information regarding the Google credentials: 
![380647444-6b62b56b-9112-41e2-ac91-63c9e15d7d1b](https://github.com/user-attachments/assets/66a49d48-563e-4700-a56e-56399a85ae21)

SET logs the information in the xml file under /root/.set directory: 
![380647523-80a7a0cf-66e6-41e5-92a9-42786dc3d083](https://github.com/user-attachments/assets/c3534a9e-926c-47a8-b63b-48b7e20b7dd4)


## RESULT:
The Social Engineering Toolkit (SET) is used to create backdoor is  examined successfully
