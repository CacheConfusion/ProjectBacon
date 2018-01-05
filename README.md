# Project Bacon

## Getting started
This project requires [node.js](https://nodejs.org/en/) v8.x.x or higher and [npm](https://www.npmjs.com) 5.x.x or higher to be able to work properly.

### Prerequisites
Do the following to install the `node.js` and `npm` via `nvm` (check for the latest [nvm here](https://github.com/creationix/nvm)):
```
# Install the nvm through curl.
$ curl -o- https://raw.githubusercontent.com/creationix/nvm/v0.33.8/install.sh | bash

# Reload the .bashrc.
$ source ~/.bashrc

# Install the node.js v8 (or higher).
$ nvm install 8

# To start using the installed node.
$ nvm use 8
```

### Start the developer site
```
# Assumes that you are in the project root directory.

# Install the project dependencies.
$ npm install

# To run the liverload developer site.
$ npm start
```

### Build the project
```
# Assumes that you are in the project root directory.

# Install the project dependencies.
$ npm install

# To build the production.
$ npm run build
```

### Run style checker
```
# Assumes that you are in the project root directory.

# Install the project dependencies.
$ npm install

# To run the eslint.
$ npm run lint
```

## Extra
- [ES6 cheet-sheet](http://es6-features.org)
- [Phaser 3 API](https://phaser.io/phaser3/api)
- [Phaser examples](http://labs.phaser.io/)
