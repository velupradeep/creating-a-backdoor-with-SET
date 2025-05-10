```
NAME: PRADEEP V
REG NO: 212223240119
DEPT: AIML

```

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

## OUTPUT :

![og1](https://github.com/user-attachments/assets/25408289-f67b-4d77-9ed3-d781f3697873)

The command sudo setoolkit in the prompt gives menu with set prompt. Select menu1 for Social Engineering Attacks:

## OUTPUT:

![02](https://github.com/user-attachments/assets/34f10c67-345a-4391-a88a-10a2e3965453)

It displays the following menu and select 2 for Website Attack Vectors:

## OUTPUT:

![03](https://github.com/user-attachments/assets/0d1614a3-67aa-4d06-9fbf-206858e27f10)

The website Attack Vectors displays the following menu. In this menu3 for Credential Harvester Attack Method is selected:

## OUTPUT:

![05](https://github.com/user-attachments/assets/8499322e-5807-4366-be89-40ec794940d7)

It shows the following screen in which the ip address of the attacker need to be given which is the default value:

## OUTPUT:

![06](https://github.com/user-attachments/assets/790c3309-1ce7-42a7-9d69-579af7faad87)

It shows the following screen in which the option Google can be selected:

## OUTPUT:

![07](https://github.com/user-attachments/assets/5e619149-68dd-428a-97ff-d31c332171f3)

SET starts my Kali Linux Webserver on port 80, with the fake Google account login page. The setup is done:

## OUTPUT:

![09](https://github.com/user-attachments/assets/d3d49e25-d1f5-4fd7-8993-386683d32dc3)

In windows IE, on giving the url http://192.168.1.2, the fake Google page is displayed. The victim can enter the username and password

## OUTPUT:
![424639082-9c6ef595-8656-479e-95c4-1bd90710e750](https://github.com/user-attachments/assets/7a0de0bb-d12c-49b2-97c5-a07579635a6f)


SET logs the information regarding the Google credentials:

## OUTPUT:

![10](https://github.com/user-attachments/assets/cd7325bf-02a0-436a-a179-86872a6cb96f)

SET logs the information in the xml file under /root/.set directory:

## OUTPUT:

![11](https://github.com/user-attachments/assets/157698a3-5b50-48c3-a517-aec5303fad1f)


## RESULT:
The Social Engineering Toolkit (SET) is used to create backdoor is  examined successfully.
