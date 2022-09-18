# fviveswap
A one point destination to swap your cryptos on five different blockchains

## FviveSwap Interface for Polygon(Matic) Network

An open source interface for FviveSwap -- a protocol for decentralized exchange on Celo.

Enabling users to:

- Add and remove their liquidity positions on FviveSwap protocol
- Swap tokens on FviveSwap protocol

Future Plans:

- Add the functinality of Farming, Staking and Limit Orders
- Making it live on the Celo Blockchain (coming very soon 😉)

## Deploying the FviveSwap on local machine

Clone the repository

move into the polygon Directory

```sh
cd polygon
```

move into the UserInterface Directory

```sh
cd UserInterface
```

install dependencies using **yarn** or **npm**

**having some dependency version problems in yarn, so advised to use npm commands instead**

```sh
yarn

or

npm install
```
If using Windows then run these two commmands after npm install

```sh
rm -r ./node_modules/@uniswap/sdk
```
And Then this command

```sh
cp -r ./forks/@uniswap/sdk ./node_modules/@uniswap/sdk
```

start the development server
```sh
yarn start

or

npm start
```

build with production mode
```sh
yarn build

or

npm run build
```