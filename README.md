## This nodeserver has been converted to run on PG3. The code has been moved to https://github.com/therealmysteryman/udi-UniFiProtect-pg3.git


# UniFi Protect Camera Polyglot V2 Node Server

![Build Status](https://travis-ci.org/therealmysteryman/udi-UniFiProtect-nodeserver.svg?branch=master)

This Poly provides an interface between Unifi Protect and Polyglot v2 server. 
This nodeserver currently only support changing the recording mode. 

** Not supported and currently not in the store **

## Installation

Installation instructions

You can install manually :

1. cd ~/.polyglot/nodeservers
2. git clone https://github.com/therealmysteryman/udi-UniFiProtect-nodeserver.git
3. run ./install.sh to install the required dependency.
4. Add following custom variable :
    - unifi_host
    - unifi_port
    - unifi_userid
    - unifi_password

## Source

1. Using this Python Library to control the Unifi Protect - https://github.com/briis/pyunifiprotect/tree/master/pyunifiprotect
2. Based on the Node Server Template - https://github.com/Einstein42/udi-poly-template-python

## Release Notes
