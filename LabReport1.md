Lab Report 1: Remote Access Tutorial
=====================================

VS code Installation
----------------------

Visit the link to the VS code main website:
[VS code website page](https://code.visualstudio.com/Download)
Follow instructions to download VS code for your respective platform and OS system.

![Image](https://github.com/RyanC1681/cse15l-lab-reports/blob/main/VSChomepage2.jpg)

Course specific account
---------------------------------

Visit this link to find the course specific account:
[ETS course account lookup](https://sdacs.ucsd.edu/~icc/index.php)

If you are a new student, use the bottom section to login and find the account. Otherwise, fill in the top section. The search will turn up two account usernames. Click on the one that starts with cs15lwi23—. 
![Image](https://github.com/RyanC1681/cse15l-lab-reports/blob/main/ETSAccountLookup.jpg)


Reset the password by clicking on a pop-up banner or the link underneath the username, as seen below:
![Image](https://github.com/RyanC1681/cse15l-lab-reports/blob/main/(ETS password change.jpg))

Use your current tritonlink account password as your current password, and reset the password for the course account:
![Image](https://github.com/RyanC1681/cse15l-lab-reports/blob/main/(ETS password change 2.jpg))


Remote Access
==============

Install SSH
---------------------------

On Windows platforms, open the Settings application. Navigate to Apps, and then to Optional Features. Find View Features, and search for the OpenSSH Client. Install the client
After installation, make sure to check that the OpenSSH Client is in the installed features.

![Image](https://github.com/RyanC1681/cse15l-lab-reports/blob/main/OpenSSHinstallation.jpg)


Establishing SSH Connection
------------------------------

Open a new terminal on the computer, or Windows Powershell. 
type the command `ssh cs15lwi23---@ieng6.ucsd.edu` filling the placeholder charcters unique to your account.

![Image](https://github.com/RyanC1681/cse15l-lab-reports/blob/main/AccessSSHserver.jpg)

Running Commands
------------------------------
Typical commands of `cd`, `ls` can be used to navigate through the server's files, and commands such as `mkdir` or `cp` can create, modify, or copy files. The directory of all the course account usernames for the CSE15L course can be found by navigating using the command `cd /home/linux/ieng6/cs15lwi23/`

![Image](https://github.com/RyanC1681//cse15l-lab-reports/blob/main/SSHcommands.jpg)

Visit CSE 15L Lab Report 1[Lab Report 1 website page](https://ryanc1681.github.io/cse15l-lab-reports/LabReport1.html)







