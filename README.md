# Linux Server Configuration Project for Udacity Full Stack Developer Nanodegree Course

- - - -

## IP address

34.218.30.13


## SSH port
2200


## URL to the hosted web application

http://ec2-34-218-30-13.us-west-2.compute.amazonaws.com/


## Installed software and configuration changes

1. Changed the SSH port from 22 to 2200.
2. Configured the Uncomplicated Firewall (UFW) to only allow incoming connections for SSH (port 2200), HTTP (port 80), and NTP (port 123).
3. Installed Apache.
4. Installed mod_wsgi.
5. Configured Apache to handle requests using the WSGI module.
6. Installed PostgreSQL.
7. Configured PostgreSQL so that remote connections are not allowed.
8. Installed git.
9. Installed Flask


## Third-party resources used to complete this project

1. Udacity forum
2. stackoverflow.com
