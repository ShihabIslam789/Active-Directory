# Active-Directory
This project is to establish a running virtual machine ourselves from scratch and make it useable with an established internet to use. the goal is to create a domain and elect which users on a need basis. Below is an image  of how the netowkr works between the domain controller and other clients using the computer.


![Diagram](https://github.com/ShihabIslam789/Active-Directory/blob/main/Pictures/Structure%20Diagram.PNG)


## Domain account
Creating this account enables me to take full advantage of the security features of windows and the operating system being used. One could change the settings of the Microsoft Active Directory Service to establish one as a domain user to control other users actions. Here I can give myself domain accounts and change other users accounts. For example I can enforce them to change passwords and put up a date when their account expires.
 
 ![Domain](https://github.com/ShihabIslam789/Active-Directory/blob/main/Pictures/domain%20files.PNG)

 ### External Computers
 Computers trying to connect to the domain must be included by the domain accounter holder first. the other users  once given permission can connect to the domain and  do their inteded work. we establish a DHCP server to correctly connect which ip address should be using the internet.


 #### Code

 we wrote powershell script to automate the process to add users easily. users will be created based on a txt file I take and aprse through to add as users for the domain. 