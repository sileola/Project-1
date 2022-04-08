# Project 1 Documentation

*  Task 1: INSTALLING APACHE AND UPDATING THE FIREWALL
    
    I ran the following commands on my virtual machine to update a list of packages in the Ubuntu package manager, to install Apache and to verify that it is running as a service in my OS:


`sudo apt update`

`sudo apt install apache2`

`sudo systemctl status apache2`

The outcome is depicted in the image below:

![Apache Status](./images/apache_status.PNG 'Apache Status')


A new rule to was then added to the EC2 configuration to open inbound connection through port 80, shown below:

![Inbound Connection Permitted](./images/new_http_rule.PNG 'Inbound Connection Permitted')


Next, I checked that my Apache server can be accessed locally in my virtual machine. Upper part of the result is shown below:

![Apache Server in Ubuntu](./images/apache_in_ubuntu.PNG "Apache Server in Ubuntu")


The webserver is now accessible through the set firewall, as shown below:

![Accessible Web Server](./images/accessible_apache.PNG "Accessible Web Server")





-   [Project 1 Repository Link](https://github.com/sileola/Project-1)




### To be continued