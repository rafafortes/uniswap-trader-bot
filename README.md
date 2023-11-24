# Blockchain Project

This project includes a bot written in Node.js that monitors the prices of a specific pair on Uniswap and then trigger the swap under certain criteria defined by the configuration.

## Prerequisites

- Node.js v18.17.0 or greater

## Installation

- npm install

## Enviroment variables

- Make sure to setup a Moralis API Key on: https://moralis.io/
- Make sure to setup an Infura API Key on: https://www.infura.io/
- Then finally make sure to fill in the environment variables on the .env file

Example:
MORALIS_API_KEY: .... // YOUR MORALIS API KEY
INTERVAL: 300000 // 5 Minutes
TOKEN0_ADDRESS: 0x1f9840a85d5aF5bf1D1762F925BDADdC4201F984 // UNI
TOKEN1_ADDRESS: 0xB4FBF271143F4FBf7B91A5ded31805e42b2208d6 // WETH
WALLET: .... // YOUR PUBLIC WALLET ADDRESS
PRIVATE_KEY: .... // YOUR PRIVATE KEY
NETWORK: goerli // NETWORK NAME
INFURA_API_KEY: .... // YOUR INFURA API KEY
ROUTER_ADDRESS: 0x68b3465833fb72A70ecDF485E0e4C7bD8665Fc45 // UNISWAP ROUTER
PRICE_TO_BUY: 5 // TRIGGER A SWAP
AMOUNT_TO_BUY: 0.1 // HOW MUCH OF TOKEN1 WILL BE BOUGHT
PROFITABILITY: 1.1 // DEFINE THE PROFIT

## Initialization

- npm start

## Disclaimer

The bot has been inspired by the following articles:

https://www.luiztools.com.br/post/como-criar-bot-trader-para-uniswap-v3-em-node-js/
https://www.luiztools.com.br/post/como-criar-bot-trader-para-uniswap-v3-em-node-js-2/ 

Thanks to Luiz Tools! :)