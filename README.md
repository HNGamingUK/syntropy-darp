# syntropy-darp

This github repo is designed to be able to setup a Syntropy DARP node in under 10 steps.

Syntropy Site: https://www.syntropynet.com/ <br>
Syntropy Docs: https://docs.syntropystack.com/docs <br>
GitHub: https://github.com/SyntropyNet <br>

## Warning:
Currently this will only work for a ubuntu operating system, however I intend to make this work for Ubuntu and Debian. 
Who knows maybe further in the future CentOS and RHEL.

## Pre Reqs:
- User account with sudo permissions
- Ubuntu based operating system

## Prior Warning (If using a VPS host)
- Your host could provide a firewall option within their control panel, if this is the case you will need to ensure ports 8080/tcp and 9835/udp are allowed. If you are unsure on how to do this your provider should have a guide, if not contact your providers support.

## Install steps:
1. `sudo apt-get update`
2. `sudo apt-get install git`
3. `git clone https://github.com/HNGamingUK/syntropy-darp`
4. `cd syntropy-darp`
5. `./syntropy-darp.sh`
6. `sudo docker-compose up -d`

Once installed succesfully you should be able to access the DARP UI in your browser of choice via http://[IP ADDRESS]:8080

## Update steps:
1. `cd syntrop-darp`
2. `sudo docker-compose pull`
3. `sudo docker-compose up -d`
