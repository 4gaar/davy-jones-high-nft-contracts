# Basic Sample Hardhat Project

This project demonstrates a basic Hardhat use case. It comes with a sample contract, a test for that contract, a sample script that deploys that contract, and an example of a task implementation, which simply lists the available accounts.

Try running some of the following tasks:

```shell
npx hardhat accounts
npx hardhat compile
npx hardhat clean
npx hardhat test
npx hardhat node
node scripts/sample-script.js
npx hardhat help
```

[Getting started](https://hardhat.org/getting-started)


# Deploying to moonbase alpha
```shell
npx hardhat deploy-all --network moonbase
```

# Verifyinig contract on moonbase alpha
```shell
npx hardhat verify --network moonbase <contract address>
```
