Hometask #1

Leonova Anna 4CS-32

Topic: Deploying Nginx on CentOS 9 Stream using Vagrant

Objective
Configure a Vagrantfile using the CentOS 9 Stream box.
Automatically install and start Nginx.
Forward port 80 → 8888.
Upload your website content from ./www-content.

Step 1

Configure Vagrantfile

Step 2 

Inside the www-content folder, create an index.html file

Run the Project

       vagrant up

Open in Browser

http://localhost:8888

To remove

       vagrant destroy -f
