# as3p2-starter-f23

You will have to edit some of these files to get your web servers working.

The included backend server runs on port 8080, 127.0.0.1:8080

## Included material

- backend binary, hello-server
- frontend, index.html
- nginx configuration file, hello.conf
- service file for backend, hello-server.service
- config for setting up servers, cloud-config.yml
- example curl commands for testing your server, curl.md

# File Locations

## cloud-config.yaml

Used in digitalocean as a initialization script for web1 and web2 servers

## hello-server.service

* /etc/systemd/system

## hello-server

* /var/www/back-end

## hello.conf

* /etc/nginx/sites-available

A symbolic link was created from this and is inside 
* /etc/nginx/sites-enabled

## index.html
* /var/www/my-site
