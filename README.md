# Swarm ID converter

This project is a small web app where you can paste a Swarm hash or a Swarm CID and it will print the appropriate Gateway or bzz.link addresses.

![Screenshot](screenshot.png)

## Try it!

https://bah5acgza33susxvxfdcreafjdx6ifbz5xxksu2g2ywwbnqfg4glc7n4syugq.bzz.link/

## Installation

Installing npm packages:

```
npm install
```

Building the bundle:

```
npm run bundle
```

Deployment with [swarm-cli](https://github.com/ethersphere/swarm-cli)
```
swarm-cli upload dist
```

