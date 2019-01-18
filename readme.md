# edX Course: Linux Foundation LF170x Course "Blockchain: Understanding Its Uses and Implications"
* [Course Link](https://www.edx.org/course/understanding-blockchain-and-its-implications)
* [Course Repo]()

# Chapter 1 - Introduction to Blockchain

## Section 1 - Introduction to Blockchain

### Lecture 1 - What is Blockchain

* Comparing Blockchain to the Early Internet
	* When the internet first came along, we had no idea how it would forever change our lives. 
	* From smart phones and text messages to streaming movies and FaceTime visits with loved ones, no one knew the ways the world would change with the invention of the Internet.
	* We are currently in the early phases of blockchain and there is much potential yet to be unlocked.
* Blockchain is NOT Bitcoin:
	* Bitcoin is transacted over an open, public, anonymous blockchain network.
	* Bitcoin and cryptocurrencies are great use cases for blockchain, but there are many more use cases that utilize blockchain technology.

## Section 2 - Basics of Blockchain

### Lecture 2 - Blockchain - Let's Cover the Basics

* A block on a blockchain can be thought of much like a page in a notebook. Data is stored on a block, just like data is written on a page of a notebook.
* Any data can be stored on the same block. Examples of stored data include:
	* Medical Records
	* Property Agreements
	* Voting.
* Each block is chained or tied to the previous block by embedding the block with information from the previous block (we will go through this in depth later in the course). 
* If the data is tampered with anywhere in the chain, the links will break in a very obvious way:

### Lecture 3 - Introduction to Blockchain Components

* The blockchain is built of several different types of components, each with a specific role to play within the blockchain’s operation:
	* Ledger: A distributed, immutable historical record
	* Peer Network: Stores, updates, and maintains the ledger
	* Membership Services: User authentication, authorization, and identity management
	* Smart Contract: Program that runs on the blockchain
	* Wallet: Stores users' credentials
	* Events: Notifications of updates and actions on the blockchain
	* Systems Management: Component creation, modification, and monitoring
	* Systems Integration: Integration of blockchain with external systems.

* **Ledger: A distributed, immutable historical record** : The goal of the blockchain is to create a distributed, immutable record of the history of the blockchain called the ledger.

* **Peer Network: Stores, updates, and maintains the ledger** The ledger is stored, updated, and maintained by a peer network. Each node in this network maintains its own copy of the ledger. It is the job of the network as a whole to come to a consensus on the contents of each update to the ledger. This ensures that each individual copy of the ledger is identical without requiring a centralized "official” copy of the ledger.

* **Membership Services: User authentication, authorization, and identity management** : On some blockchains, anyone can join the peer network and all network members have equal powers and authority. Permissioned blockchains require authorization to join and Membership Services authenticates, authorizes, and manages the identity of users on the blockchain.

* **Smart Contract: Program that runs on the blockchain** : The original blockchains were designed to simply allow financial transactions to be performed and stored in the historical ledger, and had limited configurability. Since then, blockchains have evolved so that some have become fully functional distributed computers. Smart contracts are programs that run on the blockchain. Users can interact with smart contracts in a similar way that they interact with programs on a standard computer.

* **Wallet: Stores users credentials** : In blockchain, the user's wallet stores their credentials and tracks digital assets associated with the user's address. The wallet tracks user credentials and any other information that may be associated with their account.

* **Events: Notifications of updates and actions on the blockchain** The blockchain’s ledger and the state of the peer network are updated by events. Examples of events include the creation and dispersion of a new transaction across the peer network and the addition of a new block to the blockchain. Events may also include notifications from smart contracts on blockchains that support such contracts.

* **Systems Management: Component creation, modification, and monitoring** : The blockchain is designed to be a long-lived system in a field that is constantly evolving. Systems management provides the capability of creating, modifying, and monitoring blockchain components to meet the needs of its users.

* **Systems Integration: Integration of blockchain with external systems** :  As blockchain has evolved and increased in functionality, it has become more common to integrate blockchains with other external systems, commonly through the use of smart contracts. While this is not a specific component of the blockchain, systems integration is included to acknowledge this capability.

### Lecture 4 - Blockchain Actors

* **Architect** : A Blockchain Architect is the designer of the blockchain solution. For a blockchain solution to be functional, it first needs to exist. The blockchain architect is the person or group who design the blockchain.
* **Operator** : The Blockchain Operator stores, maintains, and updates the blockchain ledger. Once the blockchain solution is designed and built, an operator can join to create the peer network mentioned previously. The role of the operator is to set up and maintain peers within the network.
* **Developer** : The Blockchain Developer creates smart contracts to run on the blockchain. The functionality of the blockchain has been greatly expanded by the introduction of blockchains that support smart contracts. Developers design and upload smart contracts to the blockchain to expand its capabilities. In addition to implementing the smart contracts, you may also have front-end developers who implement applications that access the blockchain (i.e., the applications initiate the transactions on the blockchain).
* **Regulator** : The Blockchain Regulator: Many businesses operate under regulations regarding how their data should be stored and processed. For blockchain solutions, a regulator may have greater visibility into the historical ledger due to their role within the organization.
* **End User** : The End User is the consumer of services built around the blockchain. Typically, this involves using software that uses the blockchain as a backend storage solution. Users rarely interact directly with the blockchain.
* **Data Storage** : Data Storage is represented by traditional databases for storing data off-chain. The blockchain provides distributed, immutable storage with built-in integrity checking; however, it has a maximum capacity based on the standard block size and block rate. To provide integrity verification for large amounts of data, it is common to store the data off-chain and store a hash of the data on-chain. This guarantees that the data is not been modified while protecting the blockchain from becoming bloated.
* **Data Processing** : Data Storage is represented by traditional databases for storing data off-chain. The blockchain provides distributed, immutable storage with built-in integrity checking; however, it has a maximum capacity based on the standard block size and block rate. To provide integrity verification for large amounts of data, it is common to store the data off-chain and store a hash of the data on-chain. This guarantees that the data is not been modified while protecting the blockchain from becoming bloated.

### Lecture 5 - Who is Using Blockchain?

* **Business to Consumer (B2C)** : A Business to Consumer (B2C) is business or transactions conducted directly between a company and consumers who are the end-users of its products or services. Services being provided to the consumer is an area of interest to companies.

* **The Jewelry Industry (B2C Transparency)** : The jewelry industry has been known for fraud, child labor issues, false metal mining, and a clear lack of transparency. A precious metals consortium with IBM has established a blockchain initiative around how transparency can be brought to the consumer: 

	* The TrustChain™ Initiative tracks and authenticates diamonds and precious metals through every stage of the supply chain as it becomes a piece of finished jewelry.
	* It provides digital verification, physical product and process verification, as well as third-party oversight. The collaboration’s goal is to instill trust in the origin and ethical sourcing of jewelry by bringing together a community of responsible and ethical organizations across the complex and multi-tiered jewelry supply chain.
	* Consumers will see that TrustChain™ establishes a trusted product with documented provenance and brings together quality assurance, social and environmental responsibility, and authenticity spanning the entire jewelry ecosystem – from miners, manufacturers, wholesale suppliers, and retailers – on a single digital platform.

* **Business to Business (B2B)** 

### Lecture 6 - Dubai Use Case

* Dubai aims to be a pioneer in the adoption of emerging technologies such as blockchain, which it recognizes has a major potential to transform city services. Dubai is one of the first to fully implement blockchain on a city-wide basis.
* Dubai is investing in the Smart Dubai Office (SDO) and 1776 Launch Blockchain Challenge. Sponsored by His Highness Sheikh Hamdan, Dubai is funding blockchain implementation at many levels.
* The Dubai Blockchain Strategy is based on three pillars:

	* Government Efficiency: Implementing blockchain technology in government servic* es
	* Industry Creation: Supporting the creation of a blockchain industry through empower* ing startups and businesses
	* Thought Leadership: Leading the global thinking on blockchain technology.
* Dubai's adoption of blockchain technology at a city-wide scale is a testament to its commitment to positively transform government from service provider to service enabler.

## Section 3 - Distributed Ledgers

### Lecture 7 - History of Ledgers

* **Single-Entry Ledgers**
	* Ledgers first appeared around 3,000 B.C.
	* Single-entry only.
	* Chanakya, an Indian leader, creates the first documented accounting standards.
* **Double-Entry Accounting**
	* Double-entry ledger appears in 1340 A.D.
	* Tracks debits and credits.
	* Tells the story of a transaction from both/all sides.
	* The Italian Luca Pacioli, recognized as the father of accounting and bookkeeping, was the first person to publish a work on double-entry bookkeeping and introduced the field in Italy.
* **Triple-Entry Accounting**
	* Triple-entry accounting is an enhancement to the traditional double-entry system, in which all accounting entries involving outside parties are cryptographically sealed by a third entry.
	* Debits, credits, and an immutable link to all past debits and credits.
	* Triple-entry ledger appears in 2008 in a white paper by Satoshi Nakamoto (a.k.a., Blockchain).
* Let's review an example: A seller books a debit to account for cash received, while a buyer books a credit for cash spent in the same transaction, but in separate sets of accounting records. This is where the blockchain comes in: rather than these entries occurring separately in independent sets of books, they occur in the form of a transfer between wallet addresses in the same distributed, public ledger, which creates an interlocking system of enduring accounting records. Since the entries are distributed and cryptographically sealed, falsifying them in a credible way or destroying them to conceal activity is practically impossible.
* Triple-Entry Accounting Features:
	* Tamper-Proof Records
	* Distributed Ledgers
	* Double-Entry+Cryptography
	* Validated, Secure, and Private
	* Digitally Signed Receipts.

### Lecture 8 - Island of Yap

* Let's review an example on Yap Island:

	* Alice agrees to trade Bob her stone by the pond in exchange for all of his cattle.
	* Alice and Bob announce their transaction to the tribe.
	* Everyone updates their mental ledger.
	* From this point on, they agree that the stone by the pond is owned by Bob.

* Alice tries to corrupt Carol, so that Carol’s ledger shows that Alice never gave up ownership of the stone.

* Centralized ledger: Only one place to cheat.
* Decentralized ledger: Carol will be outvoted by the rest of the tribe, and her version of the ledger will not be accepted.
* If Alice wants to cheat, she will need a way to convince 51% or more of the tribe to accept an alternative ledger.

### Section 4 - Cryptography

### Lecture 9 - Cryptography and Hashing in Blockchain

* Blockchain provides users with data integrity in a trustless environment.
* This is accomplished using cryptography in a way that moves the burden of trust from data processors to cryptographic algorithms.
* In this section, we will discuss some of the ways cryptography is used in the blockchain.
* Let's explain the key terms use in cryptography:
	* Secret: The data which we are trying to protect
	* Key: A piece of data used for encrypting and decrypting the secret
	* Function: The process or function used to encrypt the secret
	* Cipher: The encrypted secret data, the output of the function.
* The Secret and the Key are passed into the Function to create the Cipher. F(S+K) = C

### Lecture 10 - Cryptographic Basics

* What is a **cryptographic function**?
	* A function for encoding or encrypting data to protect the contents from adversaries.
* Simple example function:
	* Secret = "Blockchain Training Alliance"
	* Function = Swap each letter in the secret with a new letter according to the Key
	* Key = "+2"
	* Cipher = "Dnqemejckp Vtckpcpi Cnnkcpeg".

* Blockchain makes use of several different **types of cryptography**. Among these are:
* Public Key Cryptography : Pair of public and private keys used for encryption and digital signatures.
* Zero-Knowledge Proof : Prove knowledge of a secret without revealing it.
* Hash Functions : One-way pseudo-random mathematical functions and Merkle trees.

### Lecture 11 - Public Key Cryptography

* Public key cryptography uses a pair of a public key and a private key to perform different tasks. Public keys are widely distributed, while private keys are kept secret. 
* Using a person's public key, it is possible to encrypt a message so that only the person with the private key can decrypt and read it. Using a private key, a digital signature can be created so that anyone with the corresponding public key can verify that the message was created by the owner of the private key and was not modified since. 
* Blockchain makes extensive use of public key cryptography.

### Lecture 12 - Zero-Knowledge Proof

* Zero-knowledge proof is the ability to prove a secret without revealing what the secret is.
* Let's review an example: Let's say there are two toy cars, identical in shape and size, except, one is red and one is blue. Jerry, who is color-blind, holds the toy cars behind his back. Jerry then shows one of the cars to Sam. Jerry then hides that car behind his back and shows Sam the other car. Sam can consistently detect the switch because the cars are different colors, but he never has to reveal the color of the cars to Jerry in order to prove the secret.

### Lecture 13 - Hash Functions

* Finally, hash functions feature heavily in blockchain. A hash function is a mathematical equation with four important properties:

	* Hash functions can take anything as input and create an output with a fixed size. This makes it possible to condense anything into a piece of data of a fixed size and is how messages are condensed for digital signatures.
	* It’s easy to calculate a hash, but hard to determine a hash input from the output. The best option is to keep trying inputs until one produces the desired output.
	* Inputs that differ by a single bit produce hashes that differ by half of their bits on average. This prevents someone from finding a desired hash input using a “hill climbing”.
	* It is infeasible to find two inputs that produce the same output when hashed. Since a hash can take any input and produce a fixed output, it makes sense that multiple different inputs will create the same output. A good hash function will make it so that you have to try a large number of inputs before finding two that produce the same output.