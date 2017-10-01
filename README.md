# Abstraction
This project is used for reverse proxy for researching about releation between nginx (wfe) and tomcat (app) through docker.


Client -> proxy -> wfe -> app

# Setup
After installing docker, you setup as follows.

## SSL
use openssl. you can create private key, using shell under certs folder.

## DNS
use dnsmasq. you can execute "dnsmasq" shell under dns folder.

