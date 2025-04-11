# network-automation-lab
Assignment 2: Automate Network Devices with GitHub Actions
Abdullah Khan
Thursday, April 10, 2025


Part 1: Lab Setup
1.	Topology
 

2.	Initial Configuration of router 
 

 
3.	Testing SSH
 

Part 2: GitHub Repository Setup
1.	Creating a repository
 



2.	Adding a .gitignore
 
3.	Directory
 
Part 3: Self-Hosted GitHub Runner
1.	Setting up runner
 

2.	Labelling Runner
 
Part 3: Ansible
1.	Creating Ansible Playbook
a.	Inventory file (initial file without GitHub Secrets)
 
b.	Variable file
 
c.	Configuration file
 
 
2.	Creating Backup Task
 
3.	Committing/Uploading the Backups
a.	Done in workflow
Part 4: GitHub Actions Workflow
1.	Creating Workflow File
 
2.	Generating workflow
 

 
3.	Secrets & Environment Variables
 
 
4.	Triggering Workflow
Part 5: Verification
1.	Deliverables
a.	Triggering workflow
 
b.	Actions log
 
 

c.	Backups/ folder
i.	SSH connectivity failed.
Challenges
1.	SSH connectivity
a.	Cisco router supported older algorithms, so I added ansible.cfg file


