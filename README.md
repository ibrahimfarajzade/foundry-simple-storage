# Foundry Simple Storage

This project contains a simple Solidity smart contract called `SimpleStorage`. It's a basic example demonstrating how to store and retrieve data on the Ethereum blockchain.

## Features

### SimpleStorage.sol

The `SimpleStorage` contract contains the following:

- **State Variables:**
  - `myFavoriteNumber`: A uint256 variable to store a favorite number.
  - `listOfPeople`: An array of `Person` structs.
  - `nameToFavoriteNumber`: A mapping from names to favorite numbers.

- **Structs:**
  - `Person`: A struct representing a person with a favorite number and a name.

- **Functions:**
  - `store(uint256 _favoriteNumber)`: Stores the provided favorite number.
  - `retrieve()`: Retrieves the stored favorite number.
  - `addPerson(string memory _name, uint256 _favoriteNumber)`: Adds a person to the list with their favorite number and name.

### DeploySimpleStorage.sol

This contract is used to deploy an instance of the `SimpleStorage` contract.

## Smart Contract Details

- **Solidity Version**: 0.8.19
- **License**: MIT

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
