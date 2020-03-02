# Host_Nodejs_Sites_On_Linux
A comprehensive guide to hosting nodejs sites on Linux
Google Cloud ssh/Node.js+nginx+certbot
===========================
1.ssh-keygen -t rsa -f ~/.ssh/gc_mysites -C user_name

2.ssh -i gc_mysites user_name@your_ip_address

Server
============
1. Install centos 7
2. $sudo yum install wget
3. choose your nodejs tar at https://nodejs.org/download/release/
4.$wget https://nodejs.org/download/release/v8.9.4/node-v8.9.4-linux-x64.tar.gz
5.$sudo tar --strip-components 1 -xzvf node-v8.9.4-linux-x64.tar.gz -C /usr/local

#check your nodejs version
$node --version

Git:
$sudo yum update
$sudo yum install git
$git clone your_site

FAQ
======
remove entries from know_hosts:
$ ssh-keygen -R ip_address

