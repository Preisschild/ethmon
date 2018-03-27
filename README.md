# ethmon (Preisschild Fork)
ETHMiner ETC/ETHGPU Miner nodejs-based web monitoring utility


ETHMiner:   http://github.com/ethereum-mining/ethminer/
Forked from:https://github.com/osnwt/ethmon

## Installation
* Install nodejs and npm (http://nodejs.org) for your system (tested on MacOSX, Ubuntu and Windows)
* Clone this repository or download and extract files
* Change to the top directory of the package
* Install dependencies (npm install)
* Copy config.json.sample to config.json and edit where necessary (see CONFIG.md for detailed comments and optional parameters)
* Start the application (npm start)
* Open web browser to localhost:3000 (or your IP:3000)
* Enjoy

## Known issues
* On some Ubuntu releases after 'apt-get install npm' the node interpreter is called nodejs due to conflict with some other package. In that case you may need to replace "node ./bin/www" by "nodejs ./bin/www" in package.json file or better create a link from /usr/local/node to the nodejs binary 


