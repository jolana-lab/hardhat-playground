# Hardhat playground

We're going to create a simple **smart contract** that implements a token that can be transferred.

## Steps

1. Write a contract

   put the contract under `contracts` (e.g. `Token.sol`)

2. Compile the contract.

   `npx hardhat compile`

3. Test the contract

   1. put the test file under `test` (e.g. `Token.js`)
   2. run `npx hardhat test`

4. Deploy the contract on localhost

   1. put the deploy script under `scripts` (e.g. `deploy.js`)
   2. start the localhost: `npx hardhat node`
   3. deploy: `npx hardhat run scripts/deploy.js --network localhost`

## References

- [#Hardhat's tutorial for beginners](https://hardhat.org/tutorial)
