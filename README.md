# The Entrepreneurship Society Demo

In this workshop we will setup a Geth node and connect to the Goerli testnet.

This repo contains:
- `truffle` - an example project (ie. smart contracts) configured for deployment to Goerli

## Setup

These steps with guide you through the installation of the necessary dependencies. 

### 1) Git



##### Linux:
> Ubuntu (Debian): `sudo apt update && sudo apt install git`

> Arch: `sudo pacman -Syu git`

> Red Hat: `sudo yum upgrade && sudo yum install git`

##### MacOS:

// TODO: How to install on MacOS 

----
### 2) Go
// TODO: What version of Go do we need?

To test if you have Go installed run `go version`

#### Automated Script
```
git clone https://github.com/udhos/update-golang
cd update-golang
sudo ./update-golang.sh
```

#### Manual Install

##### MacOS

1. Download https://dl.google.com/go/go1.10.5.darwin-amd64.pkg
2. Run `go1.10.5.darwin-amd64.pkg`
3. Restart all terminal windows

##### Linux

1. https://dl.google.com/go/go1.10.5.linux-amd64.tar.gz
2. `tar -C /usr/local -xzf go1.10.5.linux-amd64.tar.gz` (may require `sudo`)
3. Open `/etc/profile/` and add `export PATH=$PATH:/usr/local/go/bin` at the bottom
4. Run `source $HOME/.profile`

---

### 3) NodeJS + NPM

To test if you have NodeJS and NPM installed run `node --version` and `npm version`

If you have both NodeJS and NPM proceed to `Truffle`.

##### NVM

Node Version Manager (NVM) is a small tool that make installation of NodeJS and NPM very easy.

1. Run `curl -o- https://raw.githubusercontent.com/creationix/nvm/v0.33.11/install.sh | bash`. Read the output to ensure it is successful.

2. Restart all terminals.
3. `nvm install 10`
4. Check everythig works with `node --version` and `npm version`

---

### 4) Truffle

Requires `NodeJS + NPM`.

`npm i -g truffle` (sudo may be required)

---

### 5) Clone Repo & Setup Geth

1. `git clone https://github.com/ethereum/go-ethereum`
2. `cd go-ethereum`
3. `make geth`

---

### 6) Setup Geth




## Instructions