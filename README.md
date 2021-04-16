# syntropy-darp

This github repo is designed to be able to setup a Syntropy DARP node in under 10 steps.

Syntropy Site: https://www.syntropynet.com/
Syntropy Docs: https://docs.syntropystack.com/docs
GitHub: https://github.com/SyntropyNet

## Warning:
Currently this will only work for a ubuntu operating system, however I intend to make this work for Ubuntu and Debian. 
Who knows maybe further in the future CentOS and RHEL.

## Pre Reqs:
- User account with sudo permissions
- Ubuntu based operating system

## Install steps:
1. `sudo apt-get update`
2. `sudo apt-get install git`
3. `git clone https://github.com/HNGamingUK/syntropy-darp`
4. `cd syntropy-darp`
5. `./syntropy-darp.sh`
6. `sudo docker-compose up -d`
