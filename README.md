# Attack Defense Series Lab
### Privilege Escalation I (AppArmor)  

The student user access is provided on a Docker host. The Docker daemon is using a TCP socket and only restricted functionality is exposed to non-root users. The AppArmor profiles are also deployed to confine the containers. The flag is kept in the home directory of the root user of the Docker host.  
  
**Objective** : Elevate access and retrieve the flag!  
  
**Write Up** :   
- [01-write-up-priv-escal-I.md](https://github.com/ilosaurus/attackdefenseserieslab/blob/master/01-write-up-priv-escal-I.md)
