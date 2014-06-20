Get Started
===========

Using a 64-bit Ubuntu 14.04 AWS EC2 AMI:

Install git & node
==================

```
sudo apt-get install -y git && curl -O http://nodejs.org/dist/v0.10.21/node-v0.10.21-linux-x64.tar.gz && tar -xvf node-v0.10.21-linux-x64.tar.gz && sudo cp -R node-v0.10.21-linux-x64/* /usr/local/
```

Obtain repo & run server
========================

```
git clone https://github.com/jay3dec/AngularJSVisualizationApp_Part4 && cd AngularJSVisualizationApp_Part4/ && node scripts/web-server.js
```

View in browser
===============

View in browser relative to AWS AMI URL, for example

http://ec2-54-218-21-92.us-west-2.compute.amazonaws.com:5000/app/index.html
