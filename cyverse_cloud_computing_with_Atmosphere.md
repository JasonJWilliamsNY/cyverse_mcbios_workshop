# Introduction to Atmosphere Cloud Computing

[Atmosphere](http://www.cyverse.org/atmosphere) is one of the most versatile components of the CyVerse CI. Anything that you would normally be able to do with your local laptop/desktop, you can do on a virtual machine in the Atmosphere cloud. The advantage of using Atmosphere is that you can get access to greater resources (currently up to 16 CPU, 128GB RAM machines). Additionally, those resources are co-localized with the CyVerse Data Store so that moving to and from your instance is very easy to do. 

>**Tip:** To use Atmosphere, you must have an email address from an academic/governmental institution and request access to Atmosphere through the user portal.  To request access, login to user.iplantcollaborative.org and check to see if Atmosphere is listed under ‘My Services.’ If it is not, scroll down and click the “Request Access” button next to Atmosphere to complete a request form. 

1.	Login to Atmosphere 

### Connecting to Atmosphere instance via SSH

> **Tip:** Your Instance status must be ‘active’ in order for you to connect. Windows users can download [PuTTY](http://www.chiark.greenend.org.uk/~sgtatham/putty/download.html) to connect via the terminal.
2.  Open a terminal (Mac/Linux) and connect
```
$ ssh your_cyverse_username@cyverse.org
``` 
3. You will be asked to save and RSA key to the list of known hosts, enter ‘yes’
4. When prompted, enter your CyVerse password.<br><img src="https://mcbios.readthedocs.org/en/latest/img/atmosphere_4.jpg", style="width:600px;height:375px;"> 


