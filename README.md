# Node.js w/ Bower and Webpack Dockerfile

This repository contains **Dockerfile** of [Node.js](http://nodejs.org/) w/  [Bower](http://bower.io/) & [Webpack](http://webpack.github.io/) for [Docker](https://www.docker.com/)'s [automated build](https://hub.docker.com/r/phpdude/node-bower-webpack/).


### Base Docker Image

* [Official Node.js Repository](https://hub.docker.com/_/node/)

### Installation

1. Install [Docker](https://www.docker.com/).

2. Download [automated build](https://hub.docker.com/r/phpdude/node-bower-webpack/) from public [Docker Hub Registry](https://hub.docker.com/): `docker pull phpdude/node-bower-webpack`

### Usage

    docker run -it --rm phpdude/node-bower-webpack

#### Run `node`

    docker run -it --rm phpdude/node-bower-webpack node

#### Run `npm`

    docker run -it --rm phpdude/node-bower-webpack npm

#### Run `bower`

    docker run -it --rm phpdude/node-bower-webpack bower

#### Run `webpack`

    docker run -it --rm phpdude/node-bower-webpack webpack
