# Day 5 - Backend Environment
## Daily Target
- Learn about backend environment in Linux.
- Install mysql
- Install php
- Install apache
- Install phpmyadmin
- Create mini project

## What I learned today
1. SSH
2. MySQL
3. PHP
4. Apache
5. PHPMyAdmin
6. Composer
7. Node.js & npm

### SSH
SSH is a secure way to connect to a remote server. Use SSH for extra layer of security for your backend environment.  

How to use SSH (to connect to localhost):
1. If SSH not installed, run `sudo apt install openssh-server`. Else, run `sudo systemctl start ssh`.  
2. Check if ssh is running using `systemctl status ssh`.
3. Create new SSH key using `ssh-keygen -t <key> -C "user-name"`.
4. Input the public key to authorized key using `cat ~/.ssh/<key>.pub >> ~/.ssh/authorized_keys` then give permission 600 for login without password `chmod 600 ~/.ssh/authorized_keys`.
5. Finally, run `ssh` command to login.


### MySQL
MySQL is a relational database management system. To install MySQL in Linux, use `sudo apt install mysql-server` command.  

### PHP
PHP is a scripting language for web development. To install PHP in Linux, use `sudo apt install php php-cli php-fpm php-json php-common php-mysql php-zip php-gd php-mbstring php-curl php-xml php-pear php-bcmath -y` command.  

### Apache
Apache is a web server. To install Apache in Linux, use `sudo apt install apache2` command.  

### PHPMyAdmin
PHPMyAdmin is a web interface for MySQL. To install PHPMyAdmin in Linux, use `sudo apt install phpmyadmin` command.  

### Composer
Composer is a dependency manager for PHP. To install Composer in Linux, use `sudo apt install composer -y` command.  

### Node.js & npm
Node.js is a JavaScript runtime environment. To install Node.js in Linux, use `sudo apt install nodejs npm -y`

### Troubleshooting
-

### Screenshots
![Documentation1](../screenshots/day-5-01.png)
![Documentation2](../screenshots/day-5-02.png)
![Documentation3](../screenshots/day-5-03.png)
![Documentation4](../screenshots/day-5-04.png)
![Documentation5](../screenshots/day-5-05.png)
![Documentation6](../screenshots/day-5-06.png)
![Documentation7](../screenshots/day-5-07.png)