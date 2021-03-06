# THE GITHUB REPOSITORY IS ONLY A MIRROR, PLEASE PUSH PRs AND ISSUES ON GITLAB
https://gitlab.com/Preisschild/ethmon

# ethmon (Preisschild Fork)
ETHMiner ETC/ETHGPU Miner nodejs-based web monitoring utility


ETHMiner:   http://github.com/ethereum-mining/ethminer/

Forked from:https://github.com/osnwt/ethmon

## Installation
* Start ethminer with --api-port 3333 parameter 
* Download it with ```git clone https://gitlab.com/Preisschild/ethmon.git```
* Install nodejs and npm (http://nodejs.org) for your system (tested on MacOSX, Ubuntu and Windows)
  - Debian/Ubuntu: ```sudo apt install nodejs npm```
  - ArchLinux: ```pacman -S nodejs npm```
* Change to the top directory of the package: ```cd ethmon```
* Install dependencies: ```npm install```
* Copy config.json.sample to config.json and edit where necessary (see CONFIG.md for detailed comments and optional parameters)
* Start the application: ```npm start```
* Navigate with your web browser to ```http://IP:3000```

## Autostart
* Install pm2: ```sudo install -g pm2```
* Make pm2 startup automatically: ```sudo pm2 startup```
* Start ethmon with pm2: ```pm2 start bin/www```
* Save pm2s list to autostart: ```pm2 save```



## TODO
* Add email notifications of failures such like no response from miner or low hashrate
* Style the web page for small screens of mobile devices (anybody?)
* ... Please open issues for suggestions
## Donations
If you find this utility useful, here are donation addresses:

(those are my (Preisschild) addresses since osnwt deleted his)

* BTC: 3KJc8krSC5gWxfe1MQ8V5qYX4NNc1xs4az
* ETH: 0xd8ae8bc2f0dda38bc27a4d537e9bb165da8aece8
* ETC: 0x0930a4d0abbc3d9591dc9f151f05dd6c0fe29915

