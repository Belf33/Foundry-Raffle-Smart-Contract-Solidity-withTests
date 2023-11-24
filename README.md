# Proveably Random Raffle Contracts

## About

This code is to create a proveably random smart contract lottery.

## What we want it to do?

1. Users can enter by paying for a ticket
    1. The ticket fees are going to go to the winner during the draw
2. After X period of time, the lottery will automatically draw a winner 
    1. And this will be done programatically
3. Using Chainlink VRF & Chainlink Automation 
    1. Chainlink VRF -> Randomness
    2. Chainlink Automation -> Time based trigger


install Chainlink VRF contracts 
```forge install smartcontractkit/chainlink-brownie-contracts@0.6.1 --no-commit```

## Tests!

## To install contracs Library

```forge install transmissions11/solmate --no-commit```

## install foundry-devops
```forge install Cyfrin/foundry-devops --no-commit```