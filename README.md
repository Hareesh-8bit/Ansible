# Ansible

Ansible is a Configuration Management Tool from Redhat. It’s free and Open Source. Ansible allows you to automate your IT infrastructure starting from creating VM, Installing Software, Docker/Kubernetes Deployment and Configuring in VM through simple Configuration file (YAML). Ansible provides Different modules like file, database, cloud, inventory to install and configure your VM/Cluster. Think of cluster, you can configure you cluster and make it up-and running without any human touch. You don’t need any programming language knowledge to work with ansible. It is one of the keytool in DevOps ecosystem.
You can clone my Ansible Part-1 Repo, before reading further.
Ansible is a universal language, unraveling the mystery of how work gets done. Turn tough tasks into repeatable playbooks. Roll out enterprise-wide protocols with the push of a button. Give your team the tools to automate, solve, and share.
You can automate anything — Infrastructure, Application-deployment, networks, Containers, Security-and-compliance and cloud
Alternate tools like puppet and chef are available. Which can replace Ansible. But each tool has got it’s own beauty. Ansible does its work like a pro. So it’s not worth to compare Ansible with Chef or Puppet.
Ansible works over SSH. You can Install Ansible in a Laptop, Desktop, Deployment server or CI-CD Pipe. It works every where. You need to make sure that the target Machine/Server is accessible over SSH. Ansible support all type of SSH authentication
Username/Password Based SSH Auth
2. Private/Public Key Based SSH Auth
3. Jump Box and Tunnel based SSH Auth
Note: Ansible do support other protocol other than SSH to communicate with Target Machine/Server.
In Ansible, you need to define your inventory (VM details), your playbook (Automation Script details) and that’s it. Ansible will do the automation for you over SSH.
Install Ansible:
How to Install Ansible in Windows
There is out-of-box support for Linux. But you will find it difficult to up-and-running in Windows.
Windows 7/10: I have installed “cygwin” and able to install ansible in Cygwin. But it didn’t work properly. I would suggest to follow below path for Windows OS Ansible installation.
Download and Install Virtualbox.
2. Download Ubuntu Image for Virtualbox
3. Run Ubuntu under Virtualbox
4. Start Ubuntu
Continue reading this article, how to install configure Ansible in Ubuntu. You can follow same path for your Virtualbox Ubuntu Configuration.
How to Install Ansible in Linux
Ansible Can be installed in Ubuntu/CentOS/RHEL using Python. Expected Python 2.7 or above. By-default pip should be installed. If not, then use below command to install pip
Note: Use “yum” for centos/RHEL and “apt” for Ubuntu OS.
$ sudo apt get install python-pip
$ sudo yum install python-pip
Use pip to install Ansible in linux
$ sudo pip install ansible
Note: You can install Ansible through “apt” and “yum” command for ubuntu, centOS and RHEL. But i would recommend to install via python.
This is optional step to install Ansible via Linux Package Manager (without using python)
sudo yum install ansible
sudo apt-get install ansible
