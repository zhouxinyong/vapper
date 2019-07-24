# homo (WIP)

[![lerna](https://img.shields.io/badge/maintained%20with-lerna-cc00ff.svg)](https://lerna.js.org/)

## Setup

```sh
git clone https://github.com/shuidi-fed/homo.git
cd homo
yarn install
```

## Run demo

### 1、link

```sh
cd packages/cli
yarn link
```

### 2、run

```sh
cd examples/vue-cli3
yarn install

# dev
homo dev

# build
homo build

# start the production server
homo start
```