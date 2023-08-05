# Module 2

# ****Getting Started with Ethereum and the EVM****

What makes Ethereum so special? That's where the EVM comes in. The Ethereum Virtual Machine is the heart and soul of Ethereum, enabling the execution of complex smart contracts that can automate everything from financial transactions to digital identity management.

## ****Ethereum and Vitalik Buterin: Inspiring the Tech Revolution****

Ethereum is a platform that allows developers to create all kinds of cool things, like decentralized apps, games, and even social networks. It's become one of the most popular blockchain platforms in the world, with a market capitalization of over $200 billion!

## ****What Even is Ethereum?****

What makes Ethereum truly special is its superpower - smart contracts. These are digital agreements that run automatically when certain conditions are met, kind of like magic spells in the digital realm.

But Ethereum isn't just a static platform - it's constantly growing and changing. It's like a living, breathing organism, with new features and functionality being added all the time. That's what makes it such an exciting platform to work with. So whether you're a developer looking to create the next big thing, or just a curious adventurer exploring the digital frontier, Ethereum is the place to be.

## ****Ethereum and dApps****

Ethereum is a decentralized platform that provides a high degree of security. It's not controlled by any central authority, which means there's no single point of failure or vulnerability.

Smart contracts automate processes, reduce the need for intermediaries, and increase transparency and efficiency. Ethereum also has a common standard for developing decentralized applications, which allows for interoperability between different applications and protocols. This means that developers can easily integrate their applications with other platforms, increasing the value and functionality of their application.

In addition, Ethereum has a large and active community of developers and users who are constantly innovating and creating new applications. This provides a wealth of knowledge and resources for developers, as well as a user base for applications to reach. Finally, Ethereum has a strong security model, with built-in measures to protect against common attacks such as denial-of-service (DoS) attacks, spam attacks, and more. This ensures that your applications are safe and secure on the platform.

# ****The Ethereum Virtual Machine****

The Ethereum Virtual Machine (EVM) is like a boss computer that runs smart contracts on the Ethereum network. Think of it as the brain of the blockchain that executes code in the form of bytecode. This bytecode is the compiled version of smart contracts written in high-level programming languages like Solidity.

The EVM is an essential component of Ethereum that automates processes and transactions on the network. When you initiate a smart contract, the EVM executes the bytecode and updates the state of the blockchain. This is done without intermediaries or central authorities, which is pretty legit if you ask me. Another cool thing about the EVM is that it's designed to be platform-independent, meaning you can write smart contracts in any programming language as long as it follows the Ethereum Virtual Machine specification. This makes it easier for developers to write smart contracts using their preferred language and brings more people to the Ethereum network.

## EVM

Whenever a developer writes a code, they must compile it, turn the solidity language code into byte code

But between this solidity code and byte code, there is a intermediary called OpCode

OpCode shows operational code for EVM to smart contract operations

If someone adds up all the opcodes and multiply it by their price, they get the GAS PRICE

The more complex that the smart contract is, the more is the gas price, because the smart contract needs to work more

## How EVM processes transactions

EVM processes transactions one by one, sequentially. Each time the EVM runs a transaction, the state of the EVM is updated  

# ****Technicals of the EVM****

EVM is a part of the protocol `geth`

When we run geth, we become part of the etherium network. All of the different machines, run geth

geth has the EVM

# Real World use cases and dApps

### ****So Who is Using Ethereum?****

1. Coca-Cola is using Ethereum to improve supply chain management, ensuring transactions are tracked and verified in real-time. Imagine every bottle of Coca-Cola you purchase being tracked from the moment it's created until it reaches your hands!
2. Microsoft is using Ethereum to create decentralized identities for its users, giving them more privacy and security. Imagine having complete control over your digital identity and being able to securely manage it in a way that's never been possible before.
3. JP Morgan is using Ethereum to create their own blockchain platform called Quorum, which allows for more secure and efficient transaction processing. Imagine being able to conduct financial transactions faster and with greater transparency than ever before.
4. ConsenSys is using Ethereum to create decentralized applications across various industries, from finance to energy. Their solutions are aimed at reducing friction, increasing efficiency, and creating more transparent and equitable systems. Imagine being able to interact with companies and systems in a completely transparent and trustworthy way.
5. Ubisoft is using Ethereum to create blockchain-based gaming experiences, where players can truly own their in-game assets and have complete control over them. Imagine owning virtual items that have real-world value and being able to transfer them to other players or sell them for actual money!

## ****What is DeFi?****

DeFi uses blockchain technology to allow people to lend, borrow, and trade directly with each other.

Ethereum is leading the way in DeFi, with a growing number of DeFi applications being built on the Ethereum network. In fact, the total value of assets locked in DeFi on Ethereum surpassed $100 billion in 2021, showing just how much demand there is for decentralized financial services.

Some popular DeFi are

1. Convex Finance
2. Uniswap
3. AAVE
4. Curve
5. Lido
6. MakerDAO

## ****Non-Fungible Tokens****

NFTs have become popular in the art world, where artists can sell their digital creations directly to collectors without the need for intermediaries like galleries. NFTs also provide proof of ownership and authenticity, which is important in the digital world where it's easy to copy and reproduce art without permission.

## ****Interoperability****

Interoperability is important for Ethereum because it enables greater collaboration and innovation among different blockchain networks. For example, Ethereum's decentralized finance (DeFi) ecosystem has been able to expand thanks to bridges that connect Ethereum to other blockchains, such as the Binance Smart Chain and the Polygon Network.

Interoperability is an exciting development for Ethereum and the wider blockchain industry, as it opens up new possibilities for decentralized applications and asset transfer. As the blockchain space continues to evolve, it will be interesting to see how interoperability evolves and shapes the future of decentralized technology.

## ****Bridges****

Ethereum can't do everything on its own, but as you just learned about interoperability, you know it doesn't have to! Enter bridges, the handy connectors that allow Ethereum to talk to other blockchain networks. Bridges make it possible to exchange value and information between different blockchains, opening up new possibilities for innovation and collaboration. Without them, Ethereum would be a lot less useful and powerful.

Bridges are not limited to blockchain networks, they can also connect to other technologies. For instance, `Chainlink` is a decentralized oracle network that provides real-world data to smart contracts on the Ethereum blockchain, and has been integrated with several blockchain bridges. This allows Ethereum-based applications to access off-chain data and trigger smart contract actions accordingly.

//What is  Oracle Network?

//How can we enter into any blockchain network?

//How does a block store information and can we modify the information in a block?

// If chainlink is able to link real world data to etherium/blockchain world, why has it not scaled yet
