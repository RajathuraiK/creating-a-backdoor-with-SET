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
The command sudo setoolkit in the prompt gives menu with set prompt and select menu1 for Social Engineering Attacks::
## OUTPUT
![SET_output-1](./output-01.png)



It displays the following menu and select 2 for Website Attack Vectors:
## OUTPUT
![SET_output-2](./output-02.png)


The Credential Harvester Attack Method displays the following menu. In this menu1 for Web Templates is selected:
## OUTPUT
![SET_output-3](./output-03.png)


It shows the following screen in which the ip address of the attacker need to be given which is the default value:
## OUTPUT
![SET_output-4](./output-04.png)



It shows the following screen in which the option Google can be selected:
## OUTPUT
![SET_output-5](./output-05.png)




SET starts my Kali Linux Webserver on port 80, with the fake Google account login page. The setup is done:
## OUTPUT
![SET_output-6](./output-06.png)



In windows IE, on giving the url http://192.168.1.2 (use appropriate IP address), the fake Google page is displayed. The victim can enter the username and password
## OUTPUT
![SET_output-7](./output-07.png)

SET logs the information regarding the Google credentials:
## OUTPUT
![SET_output-8](./output-08.png)


SET logs the information in the xml file under /root/.set directory:
## OUTPUT

![SET_output-9](./output-09.png)




## RESULT:
The Social Engineering Toolkit (SET) is used to create backdoor is  examined successfully
