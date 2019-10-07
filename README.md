# Exploring Ansible

   It is an Automation tool which enables to configure systems, deploy software and orchestrate complex tasks such as application deployment, intra-service orchestration, infrastructure management etc. Ansible is also considered to be one of the most popular configuration management tools. 
   
   Ansible allows to control fleet of servers from a single control server via SSH and uses YAML syntax.
   
   Prerequisites to running Ansible is to have Control Machine either in Linux/Mac/Windows server. On Control Machines, Ansible commands will be executed to control the fleet of servers.
   
   This is also an efficient tool when compare to tools like Puppet, Chef and Salt Stack. 
   
#### Installation on Linux / Mac

   Step 1. Install Python 
   
   Step 2. Install Ansible

#### Installation on Windows

   Step 1. Enabling Windows subsystem for Linux installation
   
   Open PowerShell as Administrator and run:
   
   ```
   Enable-WindowsOptionalFeature -Online -FeatureName Microsoft-Windows-Subsystem-Linux
   ```
   
   Step 2. Restart Machine
   
   Step 3. Install Linux Distribution for Microsoft Store - For Example - Ubuntu - This is actually a wrapper for Windows machine as Ansible will work only on Linux/Mac platforms. For Windows users, this approach will be convenient ones for using Ansible Framework.