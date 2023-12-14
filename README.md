# Introduction 
In Vodafone IPBH network there are ~550 routers with ~150k configuration blocks. This ansible playbook creat config file baesd on the ethtrunk.j2 template.

# Getting Started
Playbook works from file (vars/main.yaml)  and the result is written to a file (CONFIGS/{hostname}.cfg). NO ANY CHANGES in routers!
1.	Installation process
    Ansible should be installed and configured.
    Host file for ansible must be exist
2.	Usage
    1.   Write the neccessary variables to the vars/main.yaml file. 
    2.   Run site.yaml playbook to creat teh configuration file based on the ethtrunk.j2 template.
    3. See files in out directory that show the necessary changes in routers.
   
3.	Latest releases
    Basic Ethernet-Trunk template in templates/ethtrunk.j2 The template does'nt take care about that case when the PTP source isn't the general source.

# Build and Test
TODO: Describe and show how to build your code and run the tests. 

# Contribute
Author: Ferenc Kakuk, ferenc.kakuk@vodafone.com, +36 31 782 4169


If you want to learn more about creating good readme files then refer the following [guidelines](https://docs.microsoft.com/en-us/azure/devops/repos/git/create-a-readme?view=azure-devops). You can also seek inspiration from the below readme files:
- [ASP.NET Core](https://github.com/aspnet/Home)
- [Visual Studio Code](https://github.com/Microsoft/vscode)
- [Chakra Core](https://github.com/Microsoft/ChakraCore)