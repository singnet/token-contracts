# token-contracts

[![CircleCI](https://circleci.com/gh/singnet/token-contracts.svg?style=svg)](https://circleci.com/gh/singnet/token-contracts)

Includes token contracts, migrations, tests

## Contracts

### AgiCrowdsale
* SingularityNET's original crowdsale contract

### SingularityNetToken
* ERC-20 implementation for SingularityNET AGI Token

### TokenVesting
* A contract to manage the gradual vesting of AGI tokens to an individual or entity

### TokenVestingFactory
* A contract to manage the creation of TokenVesting instances on-chain

## Deployed Contracts
* SingularityNetToken (Mainnet): 0x8eb24319393716668d768dcec29356ae9cffe285
* SingularityNetToken (Kovan): 0x3b226ff6aad7851d3263e53cb7688d13a07f6e81
* SingularityNetToken (Ropsten) : 0xb97E9bBB6fd49865709d3F1576e8506ad640a13B

## Requirements
* [Node.js](https://github.com/nodejs/node) (8+)
* [Npm](https://www.npmjs.com/package/npm)

## Install

### Dependencies
```bash
npm install
```

### Test 
```bash
npm run test
```

## Package
```bash
npm run package-npm
```

## Release
SingularityNetToken artifacts are published to NPM: https://www.npmjs.com/package/singularitynet-token-contracts
