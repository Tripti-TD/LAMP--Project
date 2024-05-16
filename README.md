# LAMP--Project
A project of installing WordPress on LAMP (Linux, Apache, MySql, PHP) stack.

# LAMP Stack
A LAMP stack is a bundle of four different software technologies that developers use to build websites and web applications. 
LAMP is an acronym for the operating system, Linux; 
the web server, Apache; 
the database server, MySQL; 
and the programming language, PHP.

# Linux OS
First, we need a Linux OS I am using Ubuntu

# Apache Web-Server
Apache is a web server software that is responsible for accepting HTTP requests from visitors and sending them back the requested information in the form of web pages. Or in simpler terms, it allows visitors to view content on your website

# MySql Database-Server
MySQL is a relational database management system (RDBMS) developed by Oracle that is based on structured query language (SQL).

# PHP Programming Language
PHP is an open-source, server-side programming language that can be used to create websites, applications, and more. It is a widely used general-purpose language that can be embedded into HTML.

History of commands to build the project.

![image](https://github.com/Tripti-TD/LAMP--Project/assets/128075759/6e5ee702-daec-4687-9014-f42d0f6fc8b1)

First we have to update our OS
< sudo apt update>

Next, install Apache MySQL and PHP
< sudo apt install apache2 >
open port no 80 for apache2

![image](https://github.com/Tripti-TD/LAMP--Project/assets/128075759/182e60cd-4bc0-4c8f-8ce8-902e6c9dc58d)

< sudo apt install mysql-server>
< sudo mysql_secure_installation>
create a user in MySQL and log in.

![image](https://github.com/Tripti-TD/LAMP--Project/assets/128075759/44697392-3ae8-4049-8f79-e1662f7b54ce)

create a database and give use to all privileges and use flush privilege.
The Flush Privileges statement reloads the grant tables' privileges, ensuring that any changes made to user permissions are immediately applied without requiring a restart of the MySQL server.

![image](https://github.com/Tripti-TD/LAMP--Project/assets/128075759/06cc91bb-9025-4e5f-8126-4694f54f7611)


< sudo apt install PHP libapache2-mod-php php-mysql>

Then install WordPress from the official WordPress site.
log in to WordPress and add form in it.

![image](https://github.com/Tripti-TD/LAMP--Project/assets/128075759/74132ed3-4070-42bf-bb48-aeb16243360a)

![image](https://github.com/Tripti-TD/LAMP--Project/assets/128075759/d48e8b35-e071-44a6-af23-ee9128095e90)

![image](https://github.com/Tripti-TD/LAMP--Project/assets/128075759/e24b0691-cea3-46e5-b349-72ec81122d6b)

![image](https://github.com/Tripti-TD/LAMP--Project/assets/128075759/32ffb45f-29e8-4ad8-8af3-9251b77e356f)




