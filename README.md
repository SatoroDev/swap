![satoroswap](https://satoroswap.finance/favicon.png)

## Intro

[SatoroSwap](https://pancakeswap.finance/) is an automated market maker (“**AMM**”) that allows two tokens to be exchanged on the [Binance Smart Chain](https://www.binance.org/en/smartChain) (BSC). It is fast, cheap, and allows anyone to participate.

##

This repo is responsible for the **exchange/pool** interface of the AMM: [satoroswap.finance](https://satoroswap.finance/)

## Run locally

Install packages

```js
yarn
```

Start application

```js
yarn start
```

## Change BSC network

To change the BSC network from test net, modify the `REACT_APP_CHAIN_ID` value in `.env`.

- MAIN NET `56`
- TEST NET `97`

## Run integration tets

Firstly, if you need to install cypress

```js
yarn cypress install
```

Then to run the Cypress suite in CLI

```js
yarn cypress run
```

Or, to run Cypress with its GUI

```js
yarn cypress open
```


---
