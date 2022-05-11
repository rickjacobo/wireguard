# wireguard
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

## Run Wireguard Configuration
* Run configuration and follow wizard promts to create configuration files and launch the wireguard server.
````
pwsh
./gateway.ps1
````

## Client Setup
### Requirements
* [Wireguard Applications](https://www.wireguard.com/install)

### Copy Wireguard configuration files to peer
* Files are located in ./<subnet>/client
  
## Resources
[Wireguard Applications](https://www.wireguard.com/install/)
[Wireguard Quick Start][https://www.wireguard.com/quickstart/]
