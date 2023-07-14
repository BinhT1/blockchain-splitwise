# blockchain-splitwise

## Start the app

0. Install the required dependency.

```bash
$ npm install --save-dev hardhat
$ npm install --save-dev @nomiclabs/hardhat-ethers
```

1. Start the ethereum virtual node.

```bash
$ npx hardhat node
```

2. Deploy the smartcontract

```bash
$ npx hardhat run --network localhost scripts/deploy.js
```
