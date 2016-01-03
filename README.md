**##Instuctions for Udactiy project 5**

##Server access

Server can be accessed via SSH by logging in as *grader* using IP address 52.35.184.59 via port 2200

URL for application is: http://ec2-52-35-184-59.us-west-2.compute.amazonaws.com/

##Summary of changes made

1.Created a new user *grader* and gave it *sudo* permission, removed "root" access
2.changed the SSH port from 20 to 2200
3.configured the Uncomplicated Firewall to accept connections only through ports listed in the requirements
4.configured local timezone to UTC
5.installed and configured Apache server
7.installed git
8.installed postgreSQL and added a limited user "catalog"
9.installed software "jail2ban" which bans an IP address for 1 minute after 3 unsuccessful connections
10.cron scripts are in place to do weekly package updates
10.launched the "Catalog" App


##Resources Used	

DigitalOcean.com: Tutorial on running Flask app wih Apache
Udacity.com: linux server course
StackOverFlow.com: Some minor errors, that I could not figure out on my own
 