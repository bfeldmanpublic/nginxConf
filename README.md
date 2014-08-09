nginxConf
=========

Configure nginx server as reverse proxy and bot filter.

An ec2 ubuntu instance has been established at http://54.85.74.189.

An nginx server has been configured to act as a reverse-proxy for all incoming HTTP requests on default port :80. Requests are proxied to www.distilnetworks.com.

A demonstration of bot detection filter is also including in the nginx.conf file.

The server will prevent access from requests originating from:
-IP address 192.225.213.20.
-Mobile devices




