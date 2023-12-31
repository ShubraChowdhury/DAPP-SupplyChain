# Supply chain & data auditing

This repository containts an Ethereum DApp that demonstrates a Supply Chain flow between a Seller and Buyer. The user story is similar to any commonly used supply chain process. A Seller can add items to the inventory system stored in the blockchain. A Buyer can purchase such items from the inventory system. Additionally a Seller can mark an item as Shipped, and similarly a Buyer can mark an item as Received.

# Libraries used for this project
#### Truffle v5.10.2 (core: 5.10.2): Used Truffle v5.10.2 for development, testing, and migrating  smart contracts
#### Ganache v7.8.0 : Used Ganache to deploy on local network to validate development and testing 
#### Solidity v0.5.16 (solc-js):Used Solidity to write smart contracts which is the programming language for Ethereum smart contract.
#### Node v18.16.0 : Node served as runtime environment for executing scripts and interacting with  network.
#### Web3.js v1.10.0 : Web3 to innteract with blockchain and develop DApp using JavaScript.

# Smart Contract Address

#### URL
##### https://sepolia.etherscan.io/address/0x83F5aD0723fb7C0903C9f6D98fc01299dF87F838
#### ADDRESS
##### 0x83F5aD0723fb7C0903C9f6D98fc01299dF87F838
#### Transaction Hash:
##### https://sepolia.etherscan.io/tx/0x926799507a449632e7eccf1afd7de3f260a48f94f6aa699a472ca96d27775a37
##### 0x926799507a449632e7eccf1afd7de3f260a48f94f6aa699a472ca96d27775a37

##### Activity Diagram
![Activity Diagram](images/Activity.png)

##### Sequence Diagram
![Sequence Diagram](images/Sequence.png)

##### State Diagram
![State Diagram](images/State.png)

##### Class Diagram
![Class Diagram](images/Class.png)

##### Compile Screenshot
![Code Compile](images/Compile.png)

##### Test Screenshot
![Test Success](images/Test1.png)

##### Test Screenshot
![Test Success](images/Test2.png)

##### Migrate To Sepolia
![Migrate To Sepolia](images/migrate-sepolia.png)

##### Migrate To Sepolia
![Migrate To Sepolia](images/migrate-sepolia2.png)

##### Migrate To Sepolia
![Migrate To Sepolia](images/migrate-sepolia3.png)

##### Ether Scan Link of Migration
[Ether Scan Link of Migration ](https://sepolia.etherscan.io/address/0x83F5aD0723fb7C0903C9f6D98fc01299dF87F838)

##### Ether Scan Screenshot of Migration
![Ether Scan Screenshot](images/EtherScan.png)

##### npm run dev
![npm run dev](images/run.png)

##### tuffle develop
![tuffle develop](images/tuffle.png)

##### Ganache Blocks
![Ganache Blocks](images/ganache.png)


The DApp User Interface when running should look like...
##### DApp Screen
![APP Screen](images/Screen-1.png)
##### History Not Showing Transaction
![History Not Showing Transaction](images/history.GIF)


## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

Please make sure you've already installed ganache-cli, Truffle and enabled MetaMask extension in your browser.

```
Give examples (to be clarified)
```

### Installing

> The starter code is written for **Solidity v0.4.24**. At the time of writing, the current Truffle v5 comes with Solidity v0.5 that requires function *mutability* and *visibility* to be specified (please refer to Solidity [documentation](https://docs.soliditylang.org/en/v0.5.0/050-breaking-changes.html) for more details). To use this starter code, please run `npm i -g truffle@4.1.14` to install Truffle v4 with Solidity v0.4.24. 

A step by step series of examples that tell you have to get a development env running

Clone this repository:

```
git clone https://github.com/udacity/nd1309/tree/master/course-5/project-6
```

Change directory to ```project-6``` folder and install all requisite npm packages (as listed in ```package.json```):

```
cd project-6
npm install
```

Launch Ganache:

```
ganache-cli -m "spirit supply whale amount human item harsh scare congress discover talent hamster"
```

Your terminal should look something like this:

![truffle test](images/ganache-cli.png)

In a separate terminal window, Compile smart contracts:

```
truffle compile
```

Your terminal should look something like this:

![truffle test](images/truffle_compile.png)

This will create the smart contract artifacts in folder ```build\contracts```.

Migrate smart contracts to the locally running blockchain, ganache-cli:

```
truffle migrate
```

Your terminal should look something like this:

![truffle test](images/truffle_migrate.png)

Test smart contracts:

```
truffle test
```

All 10 tests should pass.

![truffle test](images/truffle_test.png)

In a separate terminal window, launch the DApp:

```
npm run dev
```

## Built With

* [Ethereum](https://www.ethereum.org/) - Ethereum is a decentralized platform that runs smart contracts
* [IPFS](https://ipfs.io/) - IPFS is the Distributed Web | A peer-to-peer hypermedia protocol
to make the web faster, safer, and more open.
* [Truffle Framework](http://truffleframework.com/) - Truffle is the most popular development framework for Ethereum with a mission to make your life a whole lot easier.


## Authors

See also the list of [contributors](https://github.com/your/project/contributors.md) who participated in this project.

## Acknowledgments

* Solidity
* Ganache-cli
* Truffle
* IPFS




#### References:
###### https://knowledge.udacity.com/questions/719531
###### https://knowledge.udacity.com/questions/887570
###### https://knowledge.udacity.com/questions/109259
###### https://knowledge.udacity.com/questions/811320
###### https://knowledge.udacity.com/questions/808446
###### https://knowledge.udacity.com/questions/678566
###### https://knowledge.udacity.com/questions/680976
###### https://knowledge.udacity.com/questions/778717#785724
###### https://knowledge.udacity.com/questions/995050
