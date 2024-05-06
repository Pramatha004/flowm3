
# MyContract Smart Contract


This is a simple smart contract which gives the value from the give funtion written in the programming language called Cadence.


## Description

This smart contract defines a Person structure and a dictionary named people, which translates String keys to Person's name. The smart contract also has two functions, addname and getId.

The Person struct contains two fields: name (a String representing the person's name) and no (a UInt32 reflecting the person's unique identification).


The addPerson method accepts two arguments: name, a String indicating the name of the person to be added, and no, a UInt32 representing the individual's unique identification. The function generates a new Person instance with the given name and number and adds it to the people dictionary.

In order to retrieve a Person instance from the people dictionary with a specified name, the getId function requires a single argument, name, which is a String representing the name of the person to be retrieved. 

The smart contract also includes an init function that initialises the people dictionary to an empty dictionary.
 

## Requirements

To run this code, you will need the following:

1)A Flow account with sufficient FLOW tokens to pay for the transaction fees

2)The Flow CLI tool installed on your machine

3)A code editor or IDE for modifying the code
## Usage

To use this smart contract, you will need to have access to a blockchain environment that supports Cadence smart contracts. One example of such an environment is the Flow Playground, which allows you to write and test Cadence code in a web-based IDE.

To deploy the smart contract to the blockchain, you can use the flow project deploy command provided by the Flow CLI. Once the smart contract is deployed, you can interact with it using the addPerson and getPerson functions.
## License

This code is licensed under the [MIT](https://choosealicense.com/licenses/mit/) license.See the LICENSE file for more information.


## Acknowledgements

This code was inspired by the Flow NFT Tutorial on the Flow documentation website. Special thanks to the Flow team for creating such a powerful and developer-friendly blockchain platform!
