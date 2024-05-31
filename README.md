### Ansible Role for Nginx Deployment

This repository provides an Ansible role to install Nginx and automate the deployment of a web application using Nginx. It includes a handler to restart Nginx after deployment.

![image](https://github.com/rana854/Ansible_role1/assets/132678372/d8894512-a4ef-4f17-a244-4e1f69da9805)


#### Usage

1. Clone this repository to your local machine:

git clone https://github.com/rana854/Ansible_role1

2. Modify the inventory file (`hosts`) to include the IP addresses or hostnames of your web servers.

3. Customize the playbook (`site.yml`) if needed. Adjust variables or tasks to fit your specific application requirements.

4. Run the playbook:

ansible-playbook site.yml

![image](https://github.com/rana854/Ansible_role1/assets/132678372/40ef11ad-f994-440f-92ab-610d05f5e351)


#### Sample Web Application

The sample web application included in this playbook is located at `roles/webserver/templates/index.html.j2`. Modify this file to replace it with your actual web application content.

![image](https://github.com/rana854/Ansible_role1/assets/132678372/f066d29a-61a3-4f67-8683-1a7b11fa4ae3)




