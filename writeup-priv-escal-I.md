# Attack Defense Lab
## Privilege Escalation I (AppArmor)

**Important Note** : This document illustrates all the important steps required to complete this lab. This  is  by no  means  a  comprehensive  step-by-step  solution for this exercise.  This  is only provided as a reference to various commands needed to complete this exercise and for your further  research on this topic. Also,  note that the IP addresses and domain names might be different in your lab.


The student user access is provided on a Docker host. The Docker daemon is using a TCP socket and only restricted functionality is exposed to non-root users. The AppArmor profiles are also deployed to confine the containers. The flag is kept in the home directory of the root user of the Docker host.

### Objective :  Elevate access and retrieve the flag!  
### Solution :

**Step 1**: Check the sudo privileges granted to the user.  
Command: `sudo -l`  
  
![01](files/img/01.jpg)


**Step 2**:  Check the listening sockets on the machine.  
Command: `netstat -tlpn`  

![02](files/img/02.jpg)