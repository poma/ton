# TON Releases [![Build Status](https://travis-ci.org/poma/ton.svg?branch=master)](https://travis-ci.org/poma/ton) [![Docker Cloud Build Status](https://img.shields.io/docker/cloud/build/poma/ton.svg)](https://hub.docker.com/r/poma/ton/builds)

This repository contains pre-built binaries for TON from the official source code in [ton-blockchain/ton](https://github.com/ton-blockchain/ton) repo: 

- light client
- full node
- validator
- fift and func compilers and libraries
- adnl, dht, and other utilities

Binaries are built for  OS X, Linux, Windows (WIP), and Docker.

Download from the [releases page](https://github.com/poma/ton/releases)

Docker image is [poma/ton](https://hub.docker.com/r/poma/ton) on docker hub

# Usage

You'll need to install following dependencies before using:

```sh
apt-get install -y openssl libreadline7
brew install openssl readline
```

# Description

This repository contains only the build scripts, the main source code is in the [official repo](https://github.com/ton-blockchain/ton)

The binaries are built on a public CI server. Both Travis and Docker hub provide verifiable builds with public logs, git commit hash, and build config snapshot, so unless Travis CI itself is malicious it's easy to verify that build was done using original source from `ton-blockchain/ton` repo without any modifications.

You can access build logs at [Travis](https://travis-ci.org/poma/ton) and [Docker hub](https://hub.docker.com/r/poma/ton/builds) webistes

# More info

For more info on TON visit [Awesome TON](https://github.com/copperbits/awesome-ton) page
