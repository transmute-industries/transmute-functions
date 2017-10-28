# Transmute Functions

Cloud functions for ethereum services.

Portability to other cloud providers in progress.

## Getting Started

```
yarn global add transmute-cli@latest
```

## Basic

```
transmute init --basic .
```

This will create a new dapp, which is configured to use transmute industries hosted functions, ethereum and ipfs. This app provides a pure front end development experience for users who do not wish to configure functions, ethereum or ipfs, but who do wish to develop against hosted version of these services.


## Advanced

```
transmute init --advanced .
```

This will create a new dapp, which contains these functions, as well as docker configurations for ethereum, ipfs and a demo web app. This boilerplate is meant to be a starting point for developers, not all of these services may be desired.

