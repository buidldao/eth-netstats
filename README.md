Ethereum Network Stats
============
[![Build Status][travis-image]][travis-url] [![dependency status][dep-image]][dep-url]

This is a visual interface for tracking ethereum network status. It uses WebSockets to receive stats from running nodes and output them through an angular interface. It is the front-end implementation for [eth-net-intelligence-api](https://github.com/cubedro/eth-net-intelligence-api).

![Screenshot](https://raw.githubusercontent.com/cubedro/eth-netstats/master/src/images/screenshot.jpg?v=0.0.6 "Screenshot")

## Prerequisite
* node
* npm

## Installation
Make sure you have node.js and npm installed.

Clone the repository and install the dependencies

```bash
git clone https://github.com/cubedro/eth-netstats
cd eth-netstats
npm install
sudo npm install -g grunt-cli
```

##Build the resources
NetStats features two versions: the full version and the lite version. In order to build the static files you have to run grunt tasks which will generate dist or dist-lite directories containing the js and css files, fonts and images.


To build the full version run
```bash
grunt
```

To build the lite version run
```bash
grunt lite
```

If you want to build both versions run
```bash
grunt all
```

##Run

```bash
npm start
```

see the interface at http://localhost:3000

[travis-image]: https://travis-ci.org/cubedro/eth-netstats.svg
[travis-url]: https://travis-ci.org/cubedro/eth-netstats
[dep-image]: https://david-dm.org/cubedro/eth-netstats.svg
[dep-url]: https://david-dm.org/cubedro/eth-netstats


## Run on mac w/ parity

History (June 2018):
``` 
502  grunt
  503  WS_SECRET="chosen_secret" npm start
  504  grunt
  505  WS_SECRET="chosen_secret" npm start
  506  grunt
  507  WS_SECRET="chosen_secret" npm start
  508  grunt
  509  WS_SECRET="chosen_secret" npm start
  510  grunt
  511  WS_SECRET="chosen_secret" npm start
  512  c
  513  WS_SECRET="chosen_secret" npm start
  514  grunt
  515  WS_SECRET="chosen_secret" npm start
  516  c
  517  WS_SECRET="chosen_secret" npm start
  518  grunt && WS_SECRET="chosen_secret" npm start
  519  grunt && WS_SECRET="chosen_secret" npm start
  520  grunt && WS_SECRET="chosen_secret" npm start
  521  c
  522  grunt && WS_SECRET="chosen_secret" npm start
  523  grunt && WS_SECRET="chosen_secret" npm start
  524  grunt && WS_SECRET="chosen_secret" npm start
  525  grunt && WS_SECRET="chosen_secret" npm start
  526  npm install -s grunt-cli
  527  npm install -s pm2
  528  npm audit fix
  529  npm audit fix --force
  530  npm audit fix
  531  npm audit fix
  532  npm i --package-lock-only
  533  npm audit fix
  534  c
  535  git status
  536  npm install --save
  537  c
  538  h
  539  grunt && WS_SECRET="chosen_secret" npm start
  540  open .
  541  c
  542  grunt && WS_SECRET="chosen_secret" npm start
  543  grunt && WS_SECRET="chosen_secret" npm start
  544  grunt
  545  grunt && WS_SECRET="chosen_secret" npm start
  546  c

```
