# This project demonstrate use of a different file to store tasks.
we have created two different task file under a folder called "tasks"
1. database_deployment.yml
2. web_deployment.yml

# It is the recommended method to use a separate task file for all different tasks for efficent use and maintainance

# Inorder to use those task files, add below commands in playbook
include: tasks/database_deployment.yml
include: tasks/web_deployment.yml