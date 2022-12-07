# Smart contracts for Nalnda Marketplace on Hedera

Hardhat commands:

```shell
npx hardhat accounts
npx hardhat compile
npx hardhat clean
npx hardhat test
npx hardhat node
node scripts/sample-script.js
npx hardhat help
```

Nalnda ERC20 test token deployed to: ```0x1D0fAb83197B3Df2F97D6dbA6daE261E10042dA8```

### Deploy contracts:

Step 1: Update the NALNDA_ERC20 in the .env file.

Step 2: Run command:
```shell
npx hardhat run scripts/deployContracts.js --network <BLOCKCHAIN_NETWORK>
```
> BLOCKCHAIN_NETWORK should be mumbai, rinkeby or ropsten.

### Deploy a new Nalnda ERC20 test token:

```shell
npx hardhat run scripts/deployNalndaToken.js --network <BLOCKCHAIN_NETWORK>
```
> BLOCKCHAIN_NETWORK should be mumbai, rinkeby or ropsten.
