This repository represents my current tinkering with python/json to interact 
with the vTiger webservices API, putting it out there for other persons to 
benefit. So far I've created a file (called vtigerauthdemo.py) that demos 
how to interact with the webservices API using Python

Working with vtigerauthdemo.py
-------------------------------

This is more of a code snippet to demonstrate what's possible. In order to test it you'll need to change some of the lines including.
The values you'll need to change include the following:

accessKey
       In order to use log into your vtiger server 
       and go to 'preferences' > 'user advanced options'.
       This is used instead of a password.

vtigerserver
       The address of the vTiger server
       e.g. http://myserver.com/vtiger

username
       User name for authentication 
       (more than likely 'admin').
