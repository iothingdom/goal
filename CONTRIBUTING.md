## Dev env requirements

This project uses *node v0.10.35* and *npm v2.14.13* in order to be compatible with the openshift cartridge where it runs. Be sure to use [nvm](https://github.com/creationix/nvm) to switch node version. Alsom be sure to use the project version of npm ```./node_modules/.bin/npm```





## Installation

* clone this repository <br>
```git clone "https://github.com/rc-webdevelopment/development.git" randychampagne.com```
* change to project dir <br>
```cd randychampagne.com```
* install dependencies <br>
```npm install```





### run build recipe

* install project dependencies <br>
```./node_modules/.bin/npm install```
* to run build tasks and watch for changes <br>
```./node_modules/.bin/npm run build```





### run tests

* install project dependencies <br>
```./node_modules/.bin/npm install```
* to run all tests cases once <br>
```./node_modules/.bin/npm run test```
* to run tests cases and watch for changes <br>
```./node_modules/.bin/npm run test:watch```





### develop new modules

* init project dir inside modules dir
* make sure to use .es6 extension and syntax








