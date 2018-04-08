# ethmon (Preisschild Fork)
ETHMiner ETC/ETHGPU Miner nodejs-based web monitoring utility

[![Releases](https://img.shields.io/github/downloads/Preisschild/ethmon/total.svg)][Releases]



ETHMiner:   http://github.com/ethereum-mining/ethminer/
Forked from:https://github.com/osnwt/ethmon

## Installation
* Download the newest Release and extract it
* Install nodejs and npm (http://nodejs.org) for your system (tested on MacOSX, Ubuntu and Windows)
  - Debian: sudo apt install nodejs npm
  - ArchLinux: pacman -S nodejs npm
* Change to the top directory of the package
* Install dependencies (npm install)
* Copy config.json.sample to config.json and edit where necessary (see CONFIG.md for detailed comments and optional parameters)
* Start the application (npm start)
* Open web browser to localhost:3000 (or your IP:3000)
* Enjoy

## Known issues
* On some Ubuntu releases after 'apt-get install npm' the node interpreter is called nodejs due to conflict with some other package. In that case you may need to replace "node ./bin/www" by "nodejs ./bin/www" in package.json file or better create a link from /usr/local/node to the nodejs binary 



## TODO
* Add email notifications of failures such like no response from miner or low hashrate
* Add a feature of restarting the miner in case of failures such like high number of rejects
* Style the web page for small screens of mobile devices (anybody?)
* ... Please open issues for suggestions
## Donations
If you find this utility useful, here are donation addresses:

(those are my (Preisschild) addresses since osnwt deleted his)

* BTC: 3KJc8krSC5gWxfe1MQ8V5qYX4NNc1xs4az
* ETH: 0xd8ae8bc2f0dda38bc27a4d537e9bb165da8aece8
* ETC: 0x0930a4d0abbc3d9591dc9f151f05dd6c0fe29915

