# Ansible-docker exam

## Tasks
1. Make three Virtual Machines with Oracle VirtualBox.
2. On all machines, add user *exam* and make it a sudoer in sudoers file with nopassword.
3. Install pip and ansible on the **Ansible-Controller** machine.
4. Create an inventory file and a playbok (.yaml) which enables public-private SSH-key autentication from the Contorller machine towards the other two VM-s.
5. Make another inventory file with the updated credentials.
6. Use ansible to install an apache webservice which uses port 80 on **machine A**. 
7. Use ansible to install a nodejs application and its dependecies on **machine B**. This nodejs app must use port 8080.
8. Implement a proxy solution to pass requests from /node to nodejs.
9. Use ansible to install docker and create an image named exam/nodeapp and create a docker container from it, named *exam_container*.
10. The code must be stored in github.


