# Classic Geth

Go Ethereum, commonly known as Geth or Classic Geth, is a command line interface for running an Ethereum Classic node.

<aside class="notice">
Ethereum ETH and Ethereum Classic ETC both have a Geth implementation. Classic Geth simply emphasizes that we're using Ethereum Classic's Geth implementation.
</aside>

## Install

<aside class="notice">
Classic Geth requires _Go Lang._ and a _C-Compiler_.
</aside>

## MacOS

### Dependencies

- Install [Homebrew](https://brew.sh/) package manager.

> install homebrew

```shell
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```

- Install [Go Lang](https://golang.org/).

- Install a C-Compiler.

> Install a C-Compiler.

```shell
xcode-select --install
```

### Installing Classic Geth

Install Classic Geth using Homebrew package manager.

> Install Classic Geth with Homebrew

```shell
brew install ethereumproject/classic/geth
```

> Check Geth version
```shell
geth version
```

Update Geth (if applicable) 

The Ethereum Classic protocol is always being improved and maintained by the love of the Ethereum Classic developer community. Sometimes bugs are discovered, improvements are made, features are added, etc... Upgrade geth to the latest release by running

```shell
brew upgrade geth
```
