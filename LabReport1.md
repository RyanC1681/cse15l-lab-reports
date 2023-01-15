

Lab Report 1: Remote Access Tutorial
=====================================

VS code Installation
----------------------

Visit the link to the VS code main website:
[VS code website page](https://code.visualstudio.com/Download)
Follow instructions to download VS code for your respective platform and OS system.

![VSC home page ](https://user-images.githubusercontent.com/40802485/212566981-6102ad76-b847-4084-8b91-53660b6de7cf.jpg)

Course specific account
---------------------------------

Visit this link to find the course specific account:
[ETS course account lookup](https://sdacs.ucsd.edu/~icc/index.php)

If you are a new student, use the bottom section to login and find the account. Otherwise, fill in the top section. The search will turn up two account usernames. Click on the one that starts with cs15lwi23—. 
![ETSAccountLookupN](https://user-images.githubusercontent.com/40802485/212567023-fce0103b-42c1-47c1-b285-e3f75892d452.jpg)


Reset the password by clicking on a pop-up banner or the link underneath the username, as seen below:
![ETS password change](https://user-images.githubusercontent.com/40802485/212567070-1f4b054c-3bc5-4664-a6b9-c4eefabdaf67.jpg)


Use your current tritonlink account password as your current password, and reset the password for the course account:
![ETS password change 2](https://user-images.githubusercontent.com/40802485/212567083-17933078-78c0-46f6-bd1f-17434077f766.jpg)



Remote Access
==============

Install SSH
---------------------------

On Windows platforms, open the Settings application. Navigate to Apps, and then to Optional Features. Find View Features, and search for the OpenSSH Client. Install the client
After installation, make sure to check that the OpenSSH Client is in the installed features.

![OpenSSHinstallation](https://user-images.githubusercontent.com/40802485/212567094-ad6cabd7-b6fd-4391-a5a2-00c55f6ea745.jpg)



Establishing SSH Connection
------------------------------

Open a new terminal on the computer, or Windows Powershell. 
type the command `ssh cs15lwi23---@ieng6.ucsd.edu` filling the placeholder charcters unique to your account.

![AccessSSHserver](https://user-images.githubusercontent.com/40802485/212567100-25df7d62-1b1e-4de3-a441-1bb3c9e44684.jpg)


Running Commands
------------------------------
Typical commands of `cd`, `ls` can be used to navigate through the server's files, and commands such as `mkdir` or `cp` can create, modify, or copy files. The directory of all the course account usernames for the CSE15L course can be found by navigating using the command `cd /home/linux/ieng6/cs15lwi23/`

![SSHcommands](https://user-images.githubusercontent.com/40802485/212567102-6adb5b65-bf68-4df7-be7d-e21e11df519f.jpg)



[Visit CSE 15L Lab Report 1 website page](https://ryanc1681.github.io/cse15l-lab-reports/LabReport1.html)







