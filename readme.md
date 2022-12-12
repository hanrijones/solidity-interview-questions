# Solidity job Interview Questions

## Table of Contents
  1. [Common 30 blockchain questions](#common-30-blockchain-question)
  2. [Top 20 solidity questions](#top-20-solidity-question)
  3. [Other questions](#other-questions)

# common-30-blockchain-question
## 1. What is Ethereum?
Ethereum is one of the largest public blockchains, a distinctive feature of which is the ability to create smart contracts.

## 2. What are Smart Contracts?
Smart Contracts are applications or programs built on blockchain.

## 3. What makes ethereum smart contracts so special compared to other programs?
Once a smart contract was deployed to the blockchain,  it cannot
be stopped (as long as the whole blockchain is working)
be hacked (as long as the code of the contract is correct)
be modified (code is immutable, but data may change).

## 4. Please, explain Ether
Ether is Ethereum's native cryptocurrency, which is the second most popular token after bitcoin. You can also consider ether as fuel for operating the distributed application platform Ethereum.

## 5. How Ethereum differs from Bitcoin?
Bitcoin is larger, but ethereum is faster (I mean how much time transactions take). Also bitcoin is more famous, but ethereum's smart contracts are much more advanced and they are the killer feature of the platform.

## 6. How Ethereum differs from Ripple?
The key difference is in the consensus mechanism. While PoW or PoS are used in Eth., Ripple uses a mechanism called Federated Byzantine Agreement (FBA).

## 7. What is EVM?
It's a virtual machine that handles scripts using the public nodes network. EVM is operated in a sandboxed environment which is isolated from the main network. It's the part of Ethereum that executes smart contract.

## 8. What is the average block size and block time in Ethereum?
The avg block size is about 30-50 kb and the block time is around 10-15 seconds.

## 9. What is Blockchain technology?
Blockchain is a chain of blocks (data) stored on multiple different servers (nodes). It can be public or private, peer-to-peer of multi-level network. The most popular blockchains are public and peer-to-peer networks. It means that anybody may join to the blockchain and every peer (node) has equal rights. Also all data from public blockchains are open, transparent, and immutable, but at the same time data form outside of the blockchain is pseudo-anonymous (you can't know who owners of the accounts are).

## 10. What is a node in Ethereum? How can you connect with a node?
Node is a every single server (computer) connected to the network that processes transactions and stores all blockchain data (independently from other servers). You can connect to a node by using WS-RPC, JSON-RPC, and IPC-RPC.

## 11. Can you hide a transaction? Where are transactions stored?
No, it's impossible to hide a transaction, they are all visible to everyone. Transactions are stored in a public ledger.

## 12. What is the role of the consensus mechanism? Which consensus does Ethereum use?
A consensus algorithm ensures that there is an agreement between different parties on the current state of the blockchain and determines who create a new block of transactions next. Further, it ensures that blockchain won't be re-written.
Ethereum is switching from PoW (Proof-of-Work) to PoS (Proof-of-Stake) consensus mechanism.

## 13. How to obtain Ethers?
You can obtain Ethers by mining or by trading with other cryptocurrencies.

## 14. What are DApps?
Decentralized applications are those that exist and operate in whole or in part in a blockchain.

## 15. Which programming language is used to write smart contracts and DApps?
There are several languages, but Solidity is the primary one (at least, the most popular).

## 16. What is Truffle?
Truffle is an open-source framework for rapid DApp and smart contract development and life cycle management.

## 17. What are the roles and responsibilities of an Ethereum Developer?
The main responsibility is to develop and maintain smart contracts, dapps, or other blockchain solutions. It may include software development itself, writing documentation, design architecture, etc.

## 18. Please, explain DAO.
A decentralized autonomous organization is an organization whose activities are regulated by rules determined in smart contracts. Tokens minted by DAO allow participation in DAO management.

## 19. Explain how PoW consensus works.
The central principle behind PoW consensus is to solve complex mathematical problems and make the largest number of guesses as quickly as possible. When a miner finds the right solution, they tell it to the whole network, receiving a reward in cryptocurrency provided by the protocol.

## 20. Explain the concept of PoS consensus.
Unlike PoW, in PoS miners can join the mining process by using their coins to stake. It allows users to mine for rewards using minimal hardware resources. The mining capacity of a particular miner depends on how many coins they have. The more tokens one has, the more chances are.

## 21. State the importance of account nonce in Ethereum?
An account nonce is a counter of transactions in each account. It helps in preventing replay attacks.

## 22. What is MetaMask?
MetaMask is a cryptocurrency wallet including in the form of a web browser extension used to store, send and receive ethers or any other ERC20 tokens.

## 23. What are Ethereum wallets?
Ethereum wallets are software that allows users to interact with their Ethereum accounts.

## 24. What do you know about hardware Ethereum wallets?
This type of wallet provides more security because it stores a private key on a physical device. It helps prevent any cyber-attack and keep your funds safe.


## 25. What are the types of Ethereum networks that exist?
These are of three types:
1. Private or local network (which you deploy on your own server)
2. TestNet - a number of public Ethereum networks existing for different tests.
3. MainNet - the main Ethereum network

## 26. How to optimize your smart contract?
1. Don't create unnecessary entities that you don't use.
2. Don't assign a default value to a state variable when you declare it.
3. One memory cell occupies 32 bytes. So declare several variables that take up less than 32 bytes in a row to save free space.
4. Lower dimensional variable takes up as much space as the largest one, exactly one cell. But when you truncate a variable (declare uint8 instead of uint),  it requires doing an operation and therefore takes gas.
5. At a state variable initialization it's desirable to set a static value.
6. Don't create intermediate unnecessary variables.
7. A mapping is more efficient than an array.
8. Dynamic arrays are more expensive than fixed-size arrays.
9. Don't create many little functions that call each other. But one mega function is not good as well.
10. Try using shorter strings (less than 32 bytes).
11. Don't change a value of a state variable many times (use an intermediate local variable).
12. Store big amounts of data outside of the blockchain.
13. As possible use third-party libraries.

## 27. Mention some most popular smart contract platforms
Ethereum
NEM
EOS
Hyperledger
RSK

## 28. Are there any standards for smart contracts?
There aren't any legal or business standards. But developers have their own standards for smart contract design. For example, in Ethereum, they're called ERC with some numbers (i.e. ERC20).

## 29. What is the first thing that you need to define in a Solidity file?
License identifier and solidity version. The first one you need if you want to publish your code as open-source to avoid legal problems. The second one reduces incompatibility glitches.

## 30. What is Remix IDE?
A remix is an online and desktop software that allows you to carry out a full cycle of smart contract development.

## 31. Gas usage in a transaction depends on which factors? How can you calculate the transaction fee?
Gas usage depends on two things. The first is the amount of stored data and the second one is the number of operations used in a smart contract.
The transaction fee can be calculated by using the following formula:
Ethers = Tx fees = used Gas * Gas price


# top-20-solidity-question
## Top 20 Solidity interview Question

## 1. What is Solidity?
Solidity is a high-level language used in the blockchain ecosystem for implementing smart contracts. Designed specifically for targeting Ethereum Virtual Machine, Solidity was influenced by several programming languages, such as JavaScript, Python, and C++.

## 2. What are some important features of Solidity?
Solidity has some salient features, which include libraries, contracts, and inheritance support. With Solidity, users can also create custom data types which can be a crucial part of smart contract development.

## 3. What types of applications can be developed using Solidity?
Solidity finds its application in creating smart contracts on Ethereum, which is a decentralized platform that is responsible for running smart contracts. Smart contracts function just as programmed and they are not prone to third-party interference. While it is most commonly used for developing smart contracts, you can also develop complex decentralized applications. You can develop various aspects, such as voting systems, crowdfunding platforms, decentralized exchanges, lending platforms, and much more.

## 4. What are the main differences between Solidity and other programming languages like Python, Java, or C++?
One main difference between Solidity and other programming languages like Python, C++, and Java is their application. While you can create centralized applications using these popular programming languages, Solidity is created to work with the Ethereum Virtual Machine. Therefore, it has certain special features such as creating smart contracts.

## 5. What is machine code in relation to Solidity contracts?
Machine codes are a compilation of solidity contracts, which are written in a high-level language. And it is the machine code that is executed on the Ethereum blockchain by the computer’s processor. A basic understanding of machine code is needed to understand what Solidity contracts are and how they work.

## 6. What is an enum? What are the restrictions on their use?
Enums are one of the methods used for creating user-defined types in Solidity. While you can implement an implicit conversion when using enums, they allow explicit conversion both to and from all integer types. Enums require at least one member, and the explicit conversions check the runtime value ranges. When there’s a failure, it results in an exception.

Professional Certificate Program in Blockchain
in Collaboration with IIT KanpurENROLL NOWProfessional Certificate Program in Blockchain

## 7. What is EVM bytecode?
EVM is the abbreviation for Ethereum Virtual Machine, which is a low-level programming language that is compiled from Solidity— a high-level language. EVM helps reduce the operating system dependency by sitting between the application layer and the operating system. Because of EVM, Ethereum contracts can be on almost any computer.

## 8. What is a library and how many types are there?
A library is a reusable piece of code that is used by smart contracts. There are two types of libraries, which are deployed and embedded libraries. While deployed libraries have an address of their own and can be used by several other smart contracts, embedded libraries are used by smart contracts wherein they are used as a part of the code. Additionally, embedded libraries do not have their own address.

## 9. What is the function of the consensus algorithm?
The consensus algorithm is one of the aspects that make decentralization possible for blockchain-powered platforms and applications. Consensus algorithms enable a mechanism that ensures a majority of the token holders and stakeholders agree upon and decide the credibility of a transaction while also deciding how to add new blocks of transactions. Consensus helps prevent the chances of any user making unauthorized changes.

## 10. What do you understand about the Ethereum network?
The Ethereum network is an open-source blockchain platform that leverages blockchain technology. It is most commonly used for creating decentralized applications that do not depend on a single authority or a centralized entity and instead are monitored by all the peers.

## 11. What are the differences between Ethereum and blockchain and bitcoin?
The most basic difference between bitcoin and Ethereum is that bitcoin is a cryptocurrency and the latter is a ledger technology that is used to create new programs. Bitcoin was created as an alternative to the national currency while the Ethereum platform was created for programmatic contracts and applications which use its own currency— ETH. While bitcoin transactions might take minutes to be completed, it only takes seconds to complete Ethereum transactions.

## 12. What are the benefits of using smart contracts on Ethereum?
There are several advantages of using smart contracts on Ethereum over traditional contracts, such as a greater degree of security since smart contracts are stored on the blockchain. This makes these contracts immune to tampering. Since smart contracts are designed to automate various tasks including the transfer of funds and verification of identities, they’re more efficient.

## 13. What tools can be used for testing Solidity codes?
Some of the most popular and commonly used tools for testing Solidity codes are Solium and Truffle. You can find and fix issues in your Solidity codes with Solium, which is a linter. Truffle can be used as a development environment, asset pipeline, and testing framework for Ethereum.

## 14. Is it possible to use loops in Solidity?
Yes, you can use loops in Solidity. However, this may come with certain restrictions such as not being able to use a for loop for iterating over an array. One thing to remember is to avoid using infinite loops in Solidity. When you create infinite loops, it results in the loss of gas and failure to continue executing your contract.  

## 15. What is a constant function in Solidity?
A constant function is one that does not make any modifications to the state of the contract. Therefore, you can call the function from anywhere without worrying about security concerns.

Blockchain Certification Training Course
Gain expertise in core Blockchain conceptsVIEW COURSEBlockchain Certification Training Course

## 16. What is the concept of storage variables in Solidity?
The variables stored on the blockchain are referred to as storage variables in Solidity. These variables are used for storing important data concerning the contract. Storage variables cannot be changed and are permanent.

## 17. What is the first thing that needs to be defined when creating a Solidity file?
The first you should define when creating a Solidity file is the class. This helps avoid errors related to compilation that is caused due to incompatibility between various versions of Solidity. Therefore, the version number must be declared.

## 18. What is a smart contract’s ABI?
A smart contract’s ABI specifies its interface and the set of functions accessed from outside the smart contract. The ABI is used only for defining the events of the contract and function signatures, such as names of the function, return types, and argument types. However, it does not define their implementation.

## 19. What type of language is Solidity?
Solidity, which is designed for creating smart contracts, is a statically-typed programming language. It makes use of ECMAScript-like syntax. Therefore, existing web developers would be familiar with it.

## 20. What are the two APIs that a smart contract uses to interface with it?
The two APIs used by a smart contract to interface with it are eth_sendTransaction and eth_call. Calls, when compared to gas, as a better option because gas is expensive while calls don’t cost anything. Therefore, while gas can change the blockchain, calls don’t. However, while transactions don’t return a value, that is not the case with calls.


# other-questions
## 1. Why is Solidity used in blockchain?
Solidity is used in blockchains for creating smart contracts. These smart contracts are responsible for implementing business logic and generating transactional records in the blockchain system. Solidity is used for various blockchain platforms, such as Ethereum, Ethereum Classic, and Binance Smart Chain.

## 2. Is Solidity frontend or backend?
Solidity is a backend language. The reason why blockchain platforms need a different backend language with specific features is that the front end is similar for both centralized and decentralized applications. What makes them different is the backend, which requires a unique high-level programming language such as Solidity.

## 3. How much do Solidity developers make?
Solidity developers have the scope to earn well with time owing to the demand for professionals who can use the language to create smart contracts for blockchain systems. The current national average salary that Solidity developers can earn is INR 9,00,000 per annum in India.

## 4. Is Solidity the future?
Since decentralized applications and programs are gaining more popularity with time and have a greater scope of application for different sectors, it is safe to say that Solidity is the future. 

## 1. Is it accurate that private variables are truly private?
This is one of the most popular Solidity interview questions. The answer is No. Only the EVM has access to private information (Ethereum Virtual Machine, the part of Ethereum that executes smart contracts). On the other hand, smart contract data is stored on the Ethereum blockchain, which is open to the world. Anyone can read secret variables of smart contracts using a particular tool for analyzing blockchain data.

## 2. What is a smart contract's ABI?
The ABI specifies a smart contract's interface or the set of functions that may be accessed from outside of the smart contract. Only the function signatures (function names, argument types, and return types) are defined by the ABI, not their implementation. The contract's events are likewise defined by the ABI. The ABI is used by Ethereum client libraries like web3 to interface with the smart contract outside of the smart contract.

## 3. What is the equivalent of a Javascript console.log in Solidity for debugging?
This question is often a part of the Solidity developer interview questions. In Solidity, there is no comparison; however, you can use events, even if they aren't built for this.

## 4. How can you protect yourself from a re-entry attack?
You will frequently come across this Solidity developer interview question.

Solution 1: Lower balances and update other state variables before invoking the other contract. Solution 2: Implement a re-entrancy guard that uses a variable to determine when a call is second in the stack. Solution 3: Limit the amount of gas available to the called contract. This is automatically done if you use transfer().

## 5. What are the two APIs that a smart contract uses to interface with it?
This is one of the most popular Solidity interview questions. eth_sendTransaction (transaction) and eth_call (call) are the two APIs that are used by a smart contract to interface. Transactions are expensive (gas) and can change the blockchain. Calls don't cost anything; therefore, they can't change the blockchain. However, calls can return a value, which isn't the case with transactions.

## 6. What is the method of payment for gas?
Gas is paid in ether using the formula: ether cost = gasPrice * gas. In this formula, the gas represents the gas cost of executing a transaction. gasPrice is in wei / gas, usually expressed in Gwei. A transaction also shows a gasLimit parameter- it specifies the maximum number of gas that a transaction can pay. A transaction without this could potentially deplete an account's Ether.

## 7. What are the requirements for deploying a smart contract on the Ethereum network?

- A bytecode of smart contract
- An Ethereum address with sufficient Ether
- A wallet to sign the transaction
- A tool to create the transaction and coordinate the signing process with the wallet

## 8. What exactly is EVM bytecode?
This is one of the most popular Solidity interview questions. EVM bytecode is a low-level programming language that is compiled from a high-level programming language like Solidity. EVM is a virtual machine that sits between the operating system and the application layer to reduce OS dependency. Ethereum smart contracts, thanks to EVM, can be run on nearly any computer. The EVM bytecode comprises opcodes, which are EVM elementary instructions. These opcodes define basic operations such as adding two numbers (ADD), loading data from memory (mload), and so on. The Ethereum yellow paper defines over 100 of these opcodes. We need higher languages like Solidity to help us reason at a higher level of abstraction because coding directly using opcodes would be incredibly tiresome.

## 9. Is it feasible to send a transaction without having to charge customers for gas?
You’ll often find this question among the Solidity developer interview questions, and the answer is Yes. You'd have people sign a message on the front end first. The message and signature would then be routed to a centralized backend (off-chain) that would establish a transaction and include the payload (message + signature). This means that instead of the user's wallet, the app's wallet will cover gas costs. A smart contract will validate the signature's validity and perform an activity on behalf of the user on the blockchain.

## 10. What is a library and how many types are there?
A library is a piece of code that other smart contracts can re-use. There are 2 types of libraries:

- Deployed- They have their own address, and several other smart contracts can use them.
- Embedded- They don’t have their own address and are deployed as part of the code of the smart contract that uses them.


#####
# 1.How did you get into smart contract (SC) development?

With the extreme hype around blockchain technologies, the demand for smart-contract and blockchain developers is rising. With knowledge and experience in IT technologies and computer language coding, it is possible to learn the Solidity programming language for smart-contract development in a pretty short amount of time. In addition, from a technical point of view, blockchain developer requirements aren’t more complicated or challenging than other coding languages. Of course, this isn’t an easy task, but considering the major blockchain benefits and interest in innovation, I decided to commit myself to learning SС development.

# 2.Can you describe the main steps of SC development?

When all the requirements are clearly set, like ERC standards and patterns, coding can be started. First of all, one should choose the language (Solidity being the most popular).

The next step is to write or reuse the contract in some of the IDE. It is good practice to use a framework (Truffle) as a development environment.

Testing is one of the most important steps in SC development. There are several types of testing:

●    functional

●    integration

●    manual

Also, there are some packages that help check code style, small security issues, and test coverage (Solhint, Solium, Solidity coverage).

The contract can be deployed to the Ethereum main network when all of these steps have been finished.

## 3. What is blockchain?

Blockchain is a digital ledger that consists of a system of blocks with cryptographically encrypted records of various transactions. Because it is decentralized, blockchain provides security, permanence, transparency, and immutability.

As all information is recorded and stored in blocks, each of these blocks contains certain data on transactions. Additionally, the block contains references to the previous one in chain, records on the reward system as well as unique answers to mathematical problems. This is essential to the mining process. This type of scheme is referred to as a “block structure,” and because it stores all types of important information, this structure can vary. Here is one of the block structure examples:


<img src="./blockchain_structure.jfif?raw=true" width="1200">

## 4. What is the blockchain consensus algo?

Consensus algorithms are processes in computing that reach agreements on single-data value in blockchain processes. The algorithms are meant to provide network reliability involving numerous unreliable nodes for double-spending prevention.

There are different types of algorithms, like PoW, PoS, DPoS, PoA, PoWeight, BFT or DAGs. Here are some examples and their characteristics:
<img src="./consensus algo.png?raw=true" width="1200">

## 5. How is Ethereum blockchain different from Bitcoin blockchain?

Blockchain-based Ethereum is a public software platform that enables application deployment independently of central authorities. Ethereum allows you to work for Ether, not just mine a cryptocurrency (as is done in Bitcoin). The Bitcoin blockchain was initially designed to store and conduct transactions only in Bitcoin form. A distinctive feature of Ethereum is the ability to run any application code in decentralized manner, while Bitcoin, for instance, offers the use of just one application in particular.

Therefore, the Ethereum blockchain not only transacts payments, but also provides smart-contract execution and runs decentralized applications. Providing a wider range of opportunities, Ethereum is often used as a software platform for different startups.

## 6. What is Wei, and how does it differ from Ether?

Wei is considered to be an Ether unit or the lowest denomination of Ether, like pennies to pounds or cents to dollars, for instance. Here is the chart of unit values:

<img src="./1529919179683.png?raw=true" width="800">

## 7.   What is a smart contract?

A smart contract (crypto-contract) is a program with a set of codes used to directly control cryptocurrency transfers and assets between parties dependent upon certain conditions. A blockchain user creates the code and later executes it by blockchain node. The contract executes itself only if the conditions are met. SC can be created on platforms like Ethereum, NXT, and Chain, with automated transactions and script in Bitcoin.

## 8.   What languages can smart contracts be written in?

There are different smart-contract languages (SCL) a contract can be written in. Let’s divide the languages into three main categories: Bitcoin, Ethereum and DSLs.

## 9.   What is Web3.js?

Web3 for Javascript is a collection of libraries that allow interaction with local/remote nodes on the Ethereum blockchain where HTTP/IPC connection can be used.

These libraries provide Web3 objects that allow applications to run on Ethereum and conduct blockchain interactions. Web3 provides a large number of functions to keep track of block data, see transaction number/balance, and additional features. Read insights on Solidity #3 meetup to find out more about the peculiarities of Web3.js functions.

## 10.   Give some details on the Truffle development environment: framework, structure, and migrations.

Truffle is a framework used for SC development in Ethereum. It was built to provide maximum speed, and includes smart optimization for best results. Its structure has the following features:
Migrations, an essential part in SM deployment, are JS files responsible for task staging. During project evolvement, migration scripts are created and recorded through a special contract on-chain to ensure further blockchain evolution.

## 11. What is EVM?

EVM (Ethereum Virtual Machine) is a decentralized application platform that executes smart contracts,provides security, and prevents attacks like denial-of-service. It is is maintained and run by many network-connected nodes. All network nodes run EVM and execute some instructions. Additionally, EVM establishes communication without interference, and eliminates program access to each other’s status.

## 12. How do gas limit and gas price influence the mining of transactions?

As Ethereum transactions run on gas instead of Ethers, the execution of certain commands and transactions costs gas. This type of execution is presented by the amount of gas you send (gas price) and a total block gas limit. The gas limit is modified by the user who sends the transaction; it is the amount of gas sent along. The gas price is the actual transaction cost, which combines the cost of the transaction and the cost of execution. The transaction price equals gas used multiplied by gas price.

The gas limit of a transaction can put the time of mining into a block. Transactions with high gas limits can be less prioritized and take more time to get into the block.

## 13. What are the existing access modifiers, and how are they different?

There are a number of Solidity function modifiers that are used to change the behaviour of various functions. They can check function conditions automatically, before the execution. Access modifiers are contract inheritable properties. Functions can be divided into:
● external
● private
● public
● internal

These functions differ one from another according to call method, either externally, from other contracts, or publicly, via messages. They may provide only internal, private access.

## 14. What is a fallback method?

It is a process of triggering fallback functions when the function signature does not match any other function specified in the identifier, or if specific data isn’t supplied. Functions can also be executed when plain Ether is received (without any data provided).

## 15. What are the Ethereum network types? What are the differences between them?

As of today, most Ethereum projects are run on the Ethereum public blockchain, which provides access to a number of participants, nodes, currencies, and markets. Depending on permitted access, there are three main types of Ethereum network: public, private, and consortium blockchains. 

## 16. How are libraries different from contracts?

Though libraries and contracts are somewhat similar, libraries can be deployed once at a particular address. Thus, the library code can be reused via the DELEGATECALL EVM feature. When one calls library functions, the code executes itself in the contract. Visually, library call functions are the same as base-contract call functions, but libraries won’t be visible in the hierarchy of inheritance. Compared to contracts, library restrictions include: no state variables, the inability to inherit or be inherited, and the inability to receive the Ether.

## 17. Please describe specific contract interaction features: DELEGATECALL, STATICCALL, library differences, use cases, and gas costs.

DELEGATECALL allows the user (delegates the right) to perform various actions with storage. It is a security risk that provides trust in the sending and receiving of contracts, and ensures the storage safety.

STATICCALL is a new opcode used to increase security in smart contracts. It can also call another contract, but disables any modifications or state changes during the call.

Libraries act as key players. They don’t have a storage option, and don’t hold an Ether. That is why libraries have to undergo an audit before being put into production (with DELEGATECALL, for instance).

Library types include the following:
● static
● dynamic
● shared
● remote

A library is defined as static when its code can be accessed during the invoking program process. A dynamic library is distinctive, as it can be loaded at run time and linked by a dynamic linker when the program is prepared for execution. A shared library (object) is a file that is possible to share by further executable/shared files. Remote libraries are used to separate executables over the web to another computer.

Below is an example of library use:

<img src="./1529919664524.jfif?raw=true" width="800">

Gas cost depends upon the number of instructions, their type, and the amount of storage.

## 18. What is the Ecrecover function? Provide an example, please.

Ecrecover recovers public key addresses from an elliptic curved signature, and returns zero errors.

Here is an example of a function:

## 19. Talk about storage vs memory.

Storage and memory are keywords used in coding to store or save certain types of data, like arrays or structs. They are two of three areas where EVM stores items.

Storage resides in contract-state variables. Each of these contracts has an individual storage that is persistent, but a bit expensive to use. Storage can map up to 256-bit words within itself, but can’t read or write to any other storage.

Memory, on the other hand, holds temporary items and can be erased between function calls. It is linear, and has the ability to address at the byte level, also limited to 256 bit-width. In addition, memory is more expensive, depending upon expansion size and quadratic scalability.

## 20. What is the ERC20 interface?

ERC20 is a token standard that describes different functions and events that must be implemented in an Ethereum token contract. In order to meet ERC20 standards, an interface contract declares a set of necessary functions and events. Here is an interface example:

<img src="./1529919779043.jfif?raw=true" width="800">

## 21. What is the ERC721 interface?

ERC721 is an open, free standard describing how to build tokens on Ethereum. Its main distinctive feature is that all ERC721 tokens are unique. An interface has to allow these tokens to be managed/owned/traded. Here is an interface example:

## 22. What are the most common SC vulnerabilities?

Given that smart contracts are immutable, it is extremely important to deploy intelligent code without any pitfalls. It has to be secure and resistant to possible attacks. This is why the developer has to evaluate the principal risks and vulnerabilities that are likely to occur. Among the major ones:

<img src="./1529919914551.jfif?raw=true" width="800">
<img src="./1529919947290.jfif?raw=true" width="800">
<img src="./1529919998091.jfif?raw=true" width="800">
<img src="./1529920012275.jfif?raw=true" width="800">
