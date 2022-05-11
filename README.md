# wireguard
A collection of scripts to setup a Wireguard server on Ubuntu and create Wireguard server and client configuration files.

## Requirements
* Ubuntu

## Server Setup
* Download Wireguard Bits
````
git clone https://github.com/rickjacobo/wireguard
````
* Setup Dependencies
````
cd wireguard
sudo bash setup.sh
````

## Create Wireguard Configurations and Launch Wireguard Server
* Run configuration and follow wizard promts to create configuration files and launch the wireguard server.
````
pwsh
./gateway.ps1
````

## Client Setup
* [Wireguard Applications](https://www.wireguard.com/install)

### Copy Wireguard configuration files to peer
* Files are located in the wireguard/<subnet>/client folder
  
## Resources
* [Wireguard Applications](https://www.wireguard.com/install/)
* [Wireguard Quick Start](https://www.wireguard.com/quickstart/)
