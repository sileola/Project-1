# Project 1 Documentation

I ran the following commands on my virtual machine to update a list of packages in the Ubuntu package manager, to install Apache and to verify that it is running as a service in my OS:


`sudo apt update`

`sudo apt install apache2`

`sudo systemctl status apache2`

The outcome is depicted in the image below:

![Apache Status](./images/apache_status.PNG 'Apache Status')


A new rule to was then added to the EC2 configuration to open inbound connection through port 80, shown below:

![Inbound Connection Permitted](./images/new_http_rule.PNG 'Inbound Connection Permitted')


-   [Project 1 Repository Link](https://github.com/sileola/Project-1)




### To be continued