 # VIRTUAL MACHINE CREATION IN LINUX
  ## AIM
To Install Virtualbox / VMware Workstation with different flavours of linux.
## PROBLEM STATEMENT
This experiment involves setting up a virtual machine with CentOS, a popular Linux distribution. This setup allows users to practice Linux commands, test applications, and develop software in a virtualized environment without affecting the host system.

## ALGORITHM
 ### Step 1:
 Open VirtualBox or VMware Workstation. For tis experiment i used VMware Workstation Pro
 ### Step 2:
 Open VMware and then Go to File -> New to create a new virtual machine OR Click Open Virtual Machine 
 ### Step 3:
 Enter a name for your Kali Linux  VM.Choose Linux as the type and Kali as the version (or select the closest option available if Kali is not listed).
 you can Download Kali linux here https://www.kali.org/get-kali/#kali-virtual-machines
 ### Step 4:
Select the Kali Linux ISO image you downloaded.
Set the  memory to 4024 MB (4 GB)
Allocate 4 processor core
Set the disk size to at least 80 GB
Complete the configuration by clicking Finish to create the virtual machine. This is based on my Laptop specification
 ### Step 5:
 Select the created VM, go to Details (or Settings), and navigate to the Network tab.
Configure Adapter 1 as NAT (for internet access through the host).
Configure Adapter 2 as Bridged Adapter (for direct access to the local network, if needed).
Click OK to save network settings.
### Step 6:
Click Start to boot up the newly created virtual machine.
the Deafult password is UserName: kali And Password :kali.  After logging in to Kali Linux, open a terminal to start using the command line.
## COMMANDS

### Hostname Setting :
    hostname
### IP Address Setting :
    nmtui
    ip a
### Date , System & OS Information :
    date 
    cal
### Basic File Management :
    pwd
    cd
    mkdir
    touch
### Basic File management – File Editor :
    Cat <file name> - Help us to shown the content from the file.

    Cat> <file name> - Help us to write or overwrite from the file.

    Cat>> <file name> - Help us to add on new lines from existing file content.


## OUTPUT :
### REG NUMBER: 212223240072
### NAME: Kishor Kumar B.
![1](img/Screenshot_2025-02-26_03_16_59.png)


![2](img/Screenshot_2025-02-26_03_22_33.png)

 
 
## RESULT :
Successfully installed Kali Linux on a virtual machine using VMware, providing a fully functional Kali Linux environment for testing and development.
 

  


