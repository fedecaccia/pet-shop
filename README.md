# Pete's Pet Shop

## Build, Test & Deploy Smart Contracts

- Install Truffle and dependencies

- Compile smart contracts:

```
truffle compile
```

- Migrate smart contracts to the blockchain, specifying one of the networks defined in truffle-config.js:

```
truffle migrate --network rinkeby
```

- Run tests (needs ganache running) with:

```
truffle test
```

## Run frontend server

```
npm run dev
```

Frontend will ask access to metamask wallet.
Metamask needs to be running on same network in which smart contracts have been deployed.