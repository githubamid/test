## E-Commerce project
### This project uses blue/green deployment for faster delivary updates
## Getting Started
### In this manual you will receive comprehensive information on how 
### to deploy this project automatically
## Prerequisites
* Two virtual hosts
* Jenkins, Ansible
```
You should:
 1. Create production environment
 2. Customize orchestration and automation tools
```
## Installing on AWS
### Training environment
 1. Create user with EC2ReadOnlyAccess permission
 2. Save AWS credentials (secret key and access key ID) 
 3. Deploy first host with name Bastion Host  
 4. Deploy second host with name Production Host
 5. Both of this host have to be in one subnet
### Training tools
 1. Install Jenkins and Ansible on Bastion Host
 2. Customize authentication to GitLab from Jenkins 
 2. Configure dynamic inventory for Ansible
 3. Check access on Production Host with ansible ad-hoc command
 4. Create two pipeline (blue and green) in Jenkins with Jenkinsfiles
## Test and Deployment
   - WordPress
   - PHP
   - MySql
   - https://github.com/githubamid/project
## Technologies which were used in project
### Orchestration: Jenkins, git
### Automation tools: Ansible, bash
### CI description: by poll, tests, delivery
### Blue/Green Deployment
<img src="image/scheme.png" weith="10" hight="10">
