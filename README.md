# AVAXETH-Module-1-Project

This project contains a simple smart contract written in Solidity. The contract includes the implementation of the `require()`, `assert()`, and `revert()` statements. It can be deployed on both the Ethereum (ETH) and Avalanche (AVAX) blockchains.

## Smart Contract Details

The smart contract `SimpleContract` allows you to perform the following actions:

- `setNumber(uint _number)`: Sets the value of `myNumber` to the provided `_number` parameter. The `_number` must be greater than zero.
- `doubleNumber()`: Doubles the value of `myNumber`. It checks for potential overflow before performing the operation.
- `numberRevert(uint _number)`: Allows you to Revert or change the current value into a new value. The `myNumber` value must be different from the current value of `myNumber`. Upon successful revert, the `myNumber` value is set to the new value, and the transaction execution is reverted.


## Deployment

1. Open the smart contract in a Solidity development environment.
2. Compile the contract to generate the bytecode and ABI.
3. Connect to your desired Ethereum or Avalanche network using a provider like MetaMask or a custom node.
4. Deploy the contract by sending a transaction with the compiled bytecode and constructor arguments (if any). Ensure you have enough funds to cover the deployment costs.

## Interacting with the Contract

Once the contract is deployed, you can interact with it through function calls. Use the provided functions `setNumber()`, `doubleNumber()`, and `numberRevert()` to perform the respective actions. Remember to comply with the requirements and conditions stated in the function descriptions.

## Troubleshooting

If you encounter any issues or errors during deployment or interaction with the contract, refer to the error messages provided by the contract. Common issues include insufficient funds, invalid parameter values, or network connectivity problems.

Number of Contributors

1. Izaac Manuelle Lachica - Mapua University

### License 

The Izaac Manuelle Lachica License governs use of this work. 
