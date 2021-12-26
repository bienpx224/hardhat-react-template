# hardhat-waffle-ethers-ts-template

Hardhat+Waffle+Ethers+Typescript template to compile and test a Solidity Smart Contract

## Prerequisites

- Node >= 10.0 ([https://nodejs.org](https://nodejs.org))
- yarn: `npm install --global yarn`

## Installation

Update env variables:

```
vi .env.example
mv .env.example .env
```

Install:

```
yarn install
npm i
```

## Commands

Compile:  You can replace yarn by npm. the scripts has been defined in package.json

```
yarn compile
or
npx hardhat compile
```

Run Hardhat Network:

```
yarn hnode
```

Open a hardhat console:

```
yarn console
```

Test:

```
yarn test
```

Test on Rinkeby test network:

```
yarn test:rinkeby
or 
npm test:rinkeby
```

Test including gas-report:

```
yarn test:gas
```

Deploy:

```
yarn deploy
```

Deploy to Rinkeby test network:

```
yarn deploy:rinkeby
```

Run the ReactJS app in the development mode (open [http://localhost:3000](http://localhost:3000) to view it in the browser):

```
yarn start
```

Build the ReactJS app for production to the `build` folder:

```
yarn build
```
