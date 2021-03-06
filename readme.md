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
* [Hash Demo](https://blockchaintrainingalliance.com/pages/lab-hash)

### Lecture 14 - Merkle Tree

* A special type of data storage structure based on hash functions is called a Merkle tree:
	* It is structured as a binary tree; the leaves contain the values to be stored andeach internal node is the hash of its two children.
	* It provides efficient lookups and protection against forgery since verifying a transaction is included in the tree. Can be accomplished by sending only the transaction, the hash contained in each node between the transaction leaf node and theroot, and the hash values used to create each hash sent.
	* Looking up a transaction in a Merkle tree with three levels includes sending two transactions (the desired one and the other child of its parent) and three hashes (the transaction’s parent, the root, and the root’s other child).

### Lecture 15 - Ethereum vs. Hyperledger Fabric: Cryptography Usage

* Ethereum and Hyperledger Fabric are two blockchain systems that are taking different approaches to moving business to the blockchain. On the next few pages, we will compare how Ethereum and Hyperledger Fabric make use of:
	* Public key cryptography
	* Zero-knowledge proofs
	* Hash functions.
* The use of public keys for identity management is a logical choice since knowledge of a public key is necessary for verification of digital signatures. Both Ethereum and Hyperledger Fabric use digital signatures on transactions and blocks to verify the identity of the creator and that the signed data has not been modified since signing. Public key cryptography is used in the blockchain as a method for managing users’ identities without revealing real world identities.  
	* In Ethereum, users are identified by an address that is directly related to the user's public key. This provides identity verification while preserving anonymity.  
	* In Hyperledger Fabric, users are identified via X.509 certificates. These certificates provide several pieces of information about the user, but one of these is also the user's public key.
* Zero-knowledge proofs are a cryptographic principle used in some blockchains to increase the privacy of users. Currently, Ethereum does not have support for zero-knowledge proofs, but adding the necessary functionality for zkSNARKS, a type of zero-knowledge proof, is currently included in the Ethereum development roadmap. Hyperledger Fabric does not currently support zero-knowledge proofs as a privacy feature.

### Lecture 16 - Ethereum vs. Hyperledger Fabric: Hashing Usage

* Hash functions are at the core of all blockchain technology. One of the primary uses for hash functions is chaining blocks together. In both Ethereum and Hyperledger Fabric, blocks include the hash of the previous block to tie the blockchain into a cohesive whole.
* Merkle trees are a data structure that allows authenticated storage with efficient data retrieval. Both Ethereum and Hyperledger Fabric are smart contract platforms that use a particular type of Merkle tree called the Patricia tree to store the current state of their virtual machine.
* Hash functions are used as the cryptographic puzzle at the center of the Proof of Work consensus algorithm. Ethereum currently uses Proof of Work for consensus, though a switch to Proof of Stake has been built into the road map from the beginning. There are only two consensus alogrithms implemented in Hyperledger Fabric - Solo and Kafka. SOLO is for development and Kafka is for production. 

## Section 5 - Transparency

### Lecture 17 - Transparency of Traditional Databases

* Traditional databases using the CRUD update model have four main operations: (Create, Read, Update, Delete)
* Traditional databases do not retain historical information:
	* Only the most recent versions of each value is visible.
	* Deleted values are not visible in the database.
* This limits the transparency of data contained in the database:
	* Values can be modified or deleted after creation.
* The CRUD update model of databases allows data to be changed or removed from the database. This means that the visible data in a database is not an accurate historical record of the database. The existence of an Update operation means that each value in the database is only the most recent version of that value and could have had different values in the past. The Delete operation means that values can be removed from the database.
* This limits the transparency of data in the database since values can be modified or deleted after creation.

### Lecture 18 - Transparency of a Blockchain

* The blockchain is designed to be a data structure that only allows appending:
	* The past history of the blockchain is visible and immutable.
	* Updates to the blockchain can be performed by including them in new blocks added to the blockchain.
* The blockchain is designed as a data structure where each block in the chain locks in the value of the previous block and so on, back to the first or genesis block. This means that the blockchain is an append-only data structure without support for modification or deletion.
* The entire history of the blockchain is publicly visible and stored in a distributed and decentralized fashion. Values in the blockchain can be “updated” by appending a new version of that value in a later block, but the complete history of the value is preserved.
* The blockchain is designed so that its entire history is visible and unchangeable. Transactions in the blockchain cannot be modified after creation, and their complete history is publicly visible. This means that the blockchain is a completely transparent data structure with the useful property that the integrity of the blockchain is easily verifiable by any user.

### Lecture 19 - Transparency: Databases vs. Blockchain

* Traditional databases and the blockchain were created for different purposes and have different levels of transparency. Traditional databases have low transparency since values can be modified or deleted; however, this changeability allows them to store data in an efficient manner, with only the most relevant versions of each value retained in storage.
* The blockchain is publicly visible and immutable, meaning that it has very high transparency. Its append-only structure and decentralized storage sacrifice storage efficiency for trustworthiness of the stored data.

## Section 6 - Immutability

### Lecture 20 - Immutability in the Blockchain

* Blockchain is designed to be an authoritative ledger of the history of the network
* This history may include financial transactions and business agreements where modifications to the ledger may have wide-reaching business impacts. Blockchain is based on an untrusted network, so trust that the blockchain has not been modified needs to arise from the structure of the blockchain itself, rather than from trust in the organization storing a certain copy.
* The blockchain needs to be immutable. If someone can change the blockchain after the fact, then it is no longer a trusted historical ledger. The blockchain is designed so that immutability is cumulative; each piece is linked to every other piece, creating a cohesive whole that is more difficult for an attacker to modify.
	* At the bottom level, transactions are digitally signed by their creators. An attacker can’t forge a transaction unless they steal a private key.
	* A block structure is predefined. Attackers can’t modify it to suit their purposes.
	* The chain part of the blockchain is achieved using hash functions. Each block includes the hash of the previous block, creating a clear link between each block in the blockchain.
	* Each block is digitally signed by its creator. The creator is selected through the blockchain’s consensus protocol, making it difficult for an attacker to be a legitimate creator.
* All four of these features help to make the blockchain resistant against changes occurring after the fact.

### Lecture 21 - Why Is the Blockchain Immutable?

* Each transaction cannot be forged or modified because it is mathematically infeasible to forge a digital signature. The structure of blocks is publicly defined, and invalid blocks will be publicly rejected.
* Each block “locks in” the value of previous blocks by including their hash. Attackers cannot find another block that will produce the same hash.
* A block cannot be forged or modified, because it is digitally signed by the creator. The creator of a block is either publicly known (Proof of Stake) or difficult to become (Proof of Work), making masquerading as the real creator difficult or impossible.
* Now, let’s take a moment to discuss how each of the features mentioned contribute to the immutability of the blockchain.
* At the bottom level, each transaction is digitally signed. This means two things about transactions:
	* Existing transactions can’t be changed after the fact, because the signature will no longer match.
	* Fake transactions can’t be created since an attacker can’t create a valid digital signature for a transaction between other parties.
* Both of these contribute to the immutability of the blockchain since they limit the range of transactions that an attacker has to work with if he wants to create a fake but valid blockchain.
* Next, the block structure is publicly defined in the protocol. This limits the types of modifications that an attacker can make to a block when trying to modify the blockchain.
* Third, each block contains the hash of the previous block. This is what ties the blocks of the chain together. Remember from earlier that one of the properties of a hash function is that it is extremely difficult to find two inputs to a hash function that create the same output. Since a block contains the hash of the previous block, it’s difficult to find a different version of the ledger’s history that matches the most recent block, as that would require finding two different versions of the previous block that have the same hash.
* Finally, each block is digitally signed by its creator. Since the creator of a block is selected via a consensus algorithm, it’s difficult for an attacker to become the legitimate creator of a given block. If an attacker is not the legitimate creator of a block, it’s impossible for them to create a digital signature that others would accept.

### Lecture 22 - Specific Immutability Mechanisms

* In Ethereum and Hyperledger, the immutability mechanism is the one that we’ve described previously. Each transaction and block is digitally signed and are linked using cryptographic hashes.
* Corda, on the other hand, relies on its notary service for immutability. Each Corda network has one or more notary services that verify transactions. Each transaction is considered separately and, if approved, is signed by the notary service. Transactions signed by a notary are finalized and cannot be modified after the fact.

### Lecture 23 - Hashing and Chaining

* It is important to understand the value of locking in the previous block by including its hash in the next block.
	* Creating a ledger of transactions with blocks that refer to previous blocks is a much better idea than numbering the blocks sequentially.
	* In a book with pages, 1, 2, 3, etc., it would be easy to tear out page 25 and replace it with another page.
	* The integrity of the book has been manipulated and altered. However, there is nothing about the new page number that ties it (chains it) to the content of the previous page.
	* Instead, in a blockchain, blocks are referenced by their hash and each block explicitly specifies which block (hash) it is building on.

* [Lab on Blocks](https://blockchaintrainingalliance.com/pages/lab-blocks)

## Section 7 - Smart Contracts

### Lecture 24 - Smart Contracts

* Smart Contracts
	* Can also be known as chaincode – program rules and decision points into blockchain transactions and processes.
	* Automate transactions and ensure they are all following the same rules.
	* Stored on the blockchain.
	* Address limitation of the Bitcoin protocol.
* Smart Contracts Provide
	* Autonomy: Smart Contracts can be developed by anyone, no need for intermediaries such as lawyers, brokers or auditions
	* Efficiency: Removing process intermediaries often results in significant process effort gains
	* Backup: A Blockchain and Smart Contract deployed to it can provide a pernanent record, allowing for autditing, insight, and traceability even if the creator is no longer in business
	* Accuracy: Replacing human intermediaries with executable code ensures the rpocess will allways be performed the same
	* Cost Savings: Replacing intermediaries often provides significant cost reduction

## Section 8 - Blockchain Security

* Blockchain is commonly called the future of computing. It takes a very different approach to data storage and processing and requires a very different perspective for security. 

### Lecture 25 - Blockchain Security vs. Standard Cyber Security: TheNEvironemnt

* One of the primary differences between cybersecurity in a traditional computing environment and on the blockchain is the environment itself and what it is and isn't designed to do.

* The traditional computing environment is a company network fully or, at least mostly, under the control of the company's computer security staff. While many organizations are making the shift to cloud-based environments, they still have a high degree of control over the security and configuration of their rented systems. Traditional networks are highly centralized, and the focus of cybersecurity on these systems is primarily perimeter-focused. All systems and authorized users on the network are trusted or semi-trusted, so the focus is on preventing attackers from entering from outside the network.

* Blockchain is designed to be a decentralized, distributed system running on untrusted hardware. While security in traditional environments is designed to provide security by putting all data in one place and building walls around it, security in blockchain is based on ensuring that data is protected from modification by copying data to as many locations as possible to make modification of all copies infeasible. Traditional infrastructure focuses on confidentiality and integrity, while blockchain is designed to provide integrity and availability.

### Lecture 26 - Blockchain Security vs. Standard Cyber Security: Security

* Both traditional computing environments and blockchain have security considerations associated with them. In many cases, the same attack is possible against both paradigms, but the details of how to implement it vary. 
* Here, we discuss how a few different attacks can be launched against traditional computing environments and blockchain:
	* Denial-of-service
	* Endpoint security
	* Intentional misuse
	* Code vulnerabilities
	* Data protection.

**Denial-of-Service (DoS)**

* A denial-of-service (DoS) attack is when an attacker makes it impossible for a system to serve its users as designed. This can be accomplished by exploiting a flaw in the system, but, more commonly, is accomplished by performing legitimate actions at a rate higher than the target can handle.  
* To be effective, denial-of-service attacks typically focus on a system’s weakest link or bottleneck. In traditional environments, denial-of-service attacks target a company's web server to prevent customers from accessing the company's services. This can be accomplished by making more connection requests than the server is capable of supporting. In blockchain, a denial-of-service attack involves submitting more transactions to the blockchain than it can handle.
* Since many blockchains have fixed-size blocks created at a fixed rate and are stored in a distributed fashion, they have a maximum capacity that a determined attacker can exceed, rendering the blockchain unusable.

**Eddpoint Security**

* Traditional infrastructure and blockchain environments also differ with regard to endpoint security. In traditional cyber, endpoints are under the control of the enterprise and have some level of heterogeneity. In blockchain, endpoints are the nodes and may be completely homogeneous.
* Heterogeneity can be dangerous because an attacker has more options for finding a vulnerability to exploit, while homogeneity means that a flaw in one system is a flaw in all of the systems.

**Code Vulnerabilities**

* Another way that traditional cyber and blockchain differ is in the level of trust in the code used in a company's applications. In traditional cyber, the company writes most of the code, and vulnerabilities can arise only from code that the company controls.  
* In blockchain, anyone can write a smart contract, and a flaw in the smart contract or the underlying platform code can have wide-reaching consequences. The only hack to date against the Bitcoin network was enabled by an integer overflow vulnerability in the Bitcoin protocol.
* When exploited, an attacker was able to assign himself more Bitcoin than was ever intended to be created. If the Bitcoin network didn't “break the rules” by modifying the historical ledger through a hard fork, Bitcoin would have become worthless. Anyone who wants to use Bitcoin has to accept the risks of hacks like this, they can't modify the code before including it in their application.

** Intentional Misuse**

* Both traditional and blockchain environments are vulnerable to attacks based on intentional misuse of the system. In traditional cyber, insider attacks or intentional misuse of the system by clients are possible. In fact, a denial-of-service attack is a specific type of intentional misuse.
* In blockchain, systems using Proof of Work incentivize miners to do something a lot, but not too much. The main weakness of Proof of Work is that a blockchain becomes insecure if more than half of the mining network's processing power is controlled by a single group.  
* Proof of Work incentivizes miners to control as much processing power as possible to win rewards, but doesn't want them to become too successful.

**Data Protection**

* Finally, traditional infrastructure and blockchain differ in their goals regarding data protection. In traditional cyber, data is siloed, and access is strictly controlled by the owners, placing responsibility for confidentiality, integrity, and availability in their hands.
* In blockchain, data is distributed, and the blockchain is relied upon to provide integrity and availability.

### Lecture 27 - Security: Public vs. Private Blockchains

* Let's discuss the differences between a public and a private blockchain:
* As the blockchain continues to evolve, the terminology has become confusing. Both public and private blockchains share many similarities:
	* Both are decentralized peer-to-peer networks, each maintaining a shared append-only ledger of digitally-signed transactions.
	* Both maintain transaction replicas in-sync through a protocol referred to as consensus.
	* Both provide certain guarantees on the immutability of the ledger.
* More importantly, the main difference between a public and private blockchain is related to who is allowed to participate in the network, execute the consensus protocol, and maintain the shared ledger.  
* A public blockchain network is completely open and anyone can join and participate in the network.
* A private blockchain network requires an invitation, and must be validated by either the network starter or by a set of rules. Private blockchains are usually set up as permissioned networks, placing restrictions on who is allowed to participate in the network, and only in certain transactions.

* [Lab Exercise](https://blockchaintrainingalliance.com/pages/lab-distributed)

## Section 9 - Public and Permissioned Blockchains

### Lecture 28 - Understanding the Difference

* [Public Blockchain vs Private Blockchain for the Enterprise Webinar](https://blockchaintrainingalliance.com/blogs/news/ethereum-vs-hyperledger)
* A public blockchain is really a permissionless blockchain. Anyone can effectively join the blockchain, meaning that they can read, write, or participate with a public blockchain. Public chains are decentralized, no one entity has control over the network, and they are secure in that the data can't be changed once validated on the blockchain.  
* A private blockchain is really a permissioned blockchain. Permissioned networks place restrictions on who is allowed to participate in the network and in what transactions.

### Lecture 29 - Public Blockchain Benefits

* The benefits of public blockchain are:
	* Open Read and Write : Anyone can participate by submitting transactions to the blockchain, such as Ethereum or Bitcoin; transactions can be viewed on the blockchain explorer.
	* Ledger Is Distributed : The database is not centralized like in a client- server approach, and all nodes in the blockchain participate in the transaction validation.
	* Immutable : When something is written to the blockchain, it can not be changed.;
	* Secure Due to Mining (51% rule) : For example, with Bitcoin, obtaining a majority of network power could potentially enable massive double spending, and the ability to prevent transaction confirmations, among other potentially nefarious acts.

### Lecture 30 - Private (Permissioned) Blockchains

* Lets discuss what private blockchains are and why they are utilized by enterprises:
	* Private blockchains are also referred to as permissioned or enterprise blockchains. Enterprises need to ensure some level of security, privacy, compliance, performance, and many of the properties that a private blockchain can provide.
	* Can be open sourced, consortium, or privately developed. There are many options for a private blockchain, and the most common ones are R3 Corda, Hyperledger, and Quorum.
	* Transactions are processed by select nodes in the blockchain. From a performance perspective, this is where having only a few nodes process transactions vs. 14,000 nodes in Ethereum’s case can really create a performance gain around latency and transaction speed.
	* Transactions are not publicly viewable (transparent) in the blockchain, and only select nodes can access the ledger.
	* Locally distributed, examples include: R3 Corda can transact between nodes, and the rest of the blockchain does not participate.

* The benefits of private blockchain are:

	* **Enterprise Permissioned**  : The enterprise controls the resources and access to the blockchain, hence private and/or permissioned.
	* **Faster Transactions** : When you distribute the nodes locally, but also have much less nodes to participate in the ledger, the performance is faster. 
	* **Better Scalability** : Being able to add nodes and services on demand can provide a great advantage to the enterprise.
	* **Compliance Support** : As an enterprise, you likely would have compliance requirements to adhere to, and having control of your infrastructure would enable this requirement more seamlessly.
	* **Consensus More Efficient (less nodes)** : Enterprise or private blockchains have less nodes and usually have a different consensus algorithm, such as [BFT](https://en.wikipedia.org/wiki/Byzantine_fault_tolerance) vs. POW.

### Lecture 31 - Public and Private Blockchain Decisions

* When it comes to decision making around what blockchain model to use, it's important to understand the considerations:
	* Governance: How is the application oversight occuring?
	* Integration: How does the blockchain work with you existing applications and can smart contracts be used?
	* Smart Contract: Dows your enterprise plan on using smart contracts?
	* Cryptocurrency Requirement: Enterprise blockchains generaly don't use cryptocurrency so that can help you decide
	* Consensus Algorithm: The algorithm can be very different if you're going to have miners vs enterprise nodes
	* Costing Model: Costs burdened by the enterprise or chared among a consortium

## Section 10 - Blockchain Flow

### Lecture 32 - Blockchain Prehistory to Early History

* **Architecting** : Blockchain architect designs and builds blockchain network:
	* Optionally, traditional databases are set up to store data off-chain.
	* Optionally, external processors are set up to allow blockchain to offload computation if necessary.
	* Optionally, peer relationships are set up with external systems via system integration.

* **Operators** : Once blockchain software has been developed, operators create wallets to hold their credential and are on-boarder through the Management Services system to create the peer network. This network stores,maintains and updates the blockchain's distributed ledger

* **Users** : Users can also join the blockchain by setting up wallets and being on-boarded by Management Services to fill their intended roles. This includes Developers and Regulators, who take a more active role in the blockchain than the standard user.

* **Developers and Smart Contracts** : In order for the blockchain to have functionality that the user can use, smart contracts need to be created on the blockchain. developers desing, implement and upload these smart contracts to the blockchain for the users to interact with

### Lecture 33 - Blockchain Transaction Flow

* **Smart Contract Triggered** : To begin, a blockchain user performs an operation that should be stored on the blockchain. This can be accomplished by interacting with software that interfaces with a smart contract on the blockchain.
* **Operators Spread Transaction** :  Once the smart contract is triggered, the relevant code is encapsulated in a transaction, which spreads to all blockchain operators through peer-to-peer transactions on their network.
* **Collections of Previous and Creation of New** : Through the blockchain’s consensus mechanism, one of the blockchain operators is selected to be the creator of the next block on the blockchain. This operator collects all of the transactions created since the previous block into a new block, and finalizes the new block.
* **Spread New Block** : This block is spread throughout the peer network through the same peer-to-peer communications as transactions.
* **Execute Code** : When block operators receive a copy of the new block, they add it to their copy of the distributed ledger and execute the smart contract code included in each transaction in the block. This guarantees that all members of the peer network agree on the current state of the blockchain’s distributed computer.
* **Operation Complete** : The user’s wallet monitors for the creation of new blocks that include transactions associated with the user. When a block containing the completed code from the user’s operation is received, an event is created to notify the user that the operation is complete.

## Section 11 - Consensus and Fault Tolerance

* The blockchain is a distributed and decentralized system, which means that it needs to have a way of tracking the official current state of the system. Since the blockchain can include financial transactions and business agreements, it is important that all parties involved are in sync regarding the terms of the agreement.  

### Lecture 34 - Introduction to Consensus in the Blockchain

* The blockchain is designed to be a shared, synchronized historical ledger, meaning that there needs to be a final decision at some point on what should and shouldn’t be included in the official record. Since blockchain is decentralized, there is no "higher authority" that can rubber-stamp and finalize the contents of a blockchain block.
* The method that Satoshi Nakamoto, the creator of blockchain, invented to achieve consensus is based on **scarcity**. In one way or another, blockchain consensus algorithms boil down to some kind of vote where the number of votes that a user has is tied to the amount of a limited resource that is under the user’s control. Based on the economic Laws of Supply and Demand, collecting enough of an asset to have a controlling share will drive up the price of the asset enough to make achieving that level of control unfeasibly expensive.
* Satoshi Nakamoto invented a consensus algorithm called Proof of Work for the use of Bitcoin. Since then, several other consensus algorithms have been invented to fit different use cases. These include Proof of Stake, Delegated Proof of Stake, Practical Byzantine Fault Tolerance, and Directed Acyclic Graphs. The most commonly used consensus algorithms are Proof of Work and Proof of Stake.

### Lecture 35 - Proof of Work

* **Computational Resources** : Proof of Work is based on the scarcity of computational resources
* **Incentivizes** :  In Proof of Work, users in the blockchain network who want to create the next block (and win the associated reward) are called miners. To win the right to mine a block, miners race to find an acceptable solution to a “hard” cryptographic problem. As we discussed previously, “hard” mathematical problems can only be solved by random guessing. When a miner finds an acceptable solution, they create a block and broadcast it to the network, finalizing that block. Proof of Work exploits the scarcity of computational resources by choosing a problem that can only be solved by guessing. There is no limit on the number of guesses that a miner can make at once. Proof of Work, therefore, incentivizes miners to run as many mining machines as possible to maximize the probability that they are the first to find a solution to the problem. Since mining computers take money to purchase and money to run, the amount of control that a user can exert over the blockchain is limited by the amount of money they have available to invest in mining equipment.
* **51% Security** : The security of the Proof of Work consensus is based on the assumption that no one controls more than half of the computational resources of a blockchain’s mining network. If this was the case, the miner has a high probability of finding an acceptable solution to the mining puzzle before anyone else for every block in the blockchain. This gives the miner complete control of the blockchain and breaks the decentralization of blockchain.

### Lecture 36 - Proof of Stake:

* **Scarce Commodity** : Proof of State is based on the scarcity of the given cryptocurrency
* **Stake** : Users in a Proof of Stake blockchain can "stake" or promise not to use the tokens they own. This gives them the opportunity to be selected as the next user to create or "forge" a new block and earn the reward. A block forger is pseudo-randomly selected from all of the users who have staked some of their assets, and the selection process is biased based on the size of the stake. For example, imagine that a wheel is divided into sections where the size of a section is proportional to the size of a user’s stake. The next block creator would be chosen by spinning the wheel and seeing whose section comes out on top. In Proof of Stake, each user has a copy of the wheel and they are all synchronized so that each person can independently determine the selection and get the same result. This is why Proof of Stake uses a pseudo-random instead of a random selection process.
* **Economic Infeasibility** : In Proof of Stake, an attacker needs to control enough of the staked currency to guarantee they will be selected to create every block. Since cryptocurrency is a limited asset, buying up enough of it to do this is expensive, making attacks on Proof of Stake systems economically infeasible.

### Lecture 37 - Specific Consensus Implementations

* **Ethereum** : Ethereum currently uses Proof of Work for consensus. And Casper is the planned migration of Ethereum from Proof of Work to Proof of Stake. Of the three blockchains studied, Ethereum is the only one that uses a standardized consensus mechanism. Ethereum was designed from the beginning to use Proof of Work for consensus, until a forced hard fork to the Proof of Stake implementation (codenamed Casper). This forced hard fork is baked into the Ethereum protocol and will be accomplished by slowly increasing the difficulty of the Proof of Work problem until the time taken to solve it increases to the point where Proof of Work becomes unusable. Proof of Stake does not require the same energy consumption as Proof of Work and is a more sustainable and scalable consensus mechanism.
* **Hyperledger Fabric** : Hyperledger Fabric breaks out consensus into components, allowing users to pick a consensus algorithm for their particular use. Hyperledger Fabric deliberately avoided hard-coding a consensus mechanism into the protocol by defining an “orderer component” that performs all of the consensus-related operations. This allows users of Hyperledger Fabric to select a consensus algorithm that fits their use case without being forced to make large-scale code edits.
* **Corda** : Each Corda network has a notary service made up of independent parties that approve blocks using any applicable consensus algorithms. Corda does not follow the standard blockchain model of transactions being bundled into blocks and then being finalized by the network as a whole. Instead, a Corda network contains one or more notaries consisting of several independent parties. Transactions in Corda are finalized by a notary with a multiparty digital signature using an algorithm like [Raft](https://raft.github.io/).

### Lecture 38 - Fault Tolerance in the Blockchain

Blockchain is a distributed, decentralized system that maintains a shared state. While consensus algorithms are designed to make it possible for the network to agree on the state, there is the possibility that agreement does not occur. Fault tolerance is an important aspect of blockchain technology.

### Lecture 39 - The Byzantine Generals' Problem

* The Byzantine Generals' Problem (discussed in the previous video):
	* Several generals needing to agree on a coordinated plan of attack.
	* One or more generals may be traitors.
	*All generals will abide by the majority decision, but may try to influence it.
* Blockchains are designed to have Byzantine Fault Tolerance:
	* All nodes are untrusted.
	* Nodes must come to a consensus on the official state of the blockchain.
* The Byzantine Generals' Problem is a scenario designed to demonstrate the difficulty of multiple parties coming to an agreement when communication can only be accomplished on a one-to-one basis and is untrusted. In the story, several Byzantine Generals are besieging a city with their separate armies. If they all attack together or all retreat together, they will be ok, but if some attack while others retreat, they will be destroyed.
* The generals can only communicate by messengers, who could be intercepted and forced to carry fake messages, and one or more generals may be a traitor. The goal is to find a way to achieve a consensus on strategy despite the possibility of traitors and false messages. Presumably, all generals will abide by what they believe is the majority consensus. The Byzantine Generals' Problem is solvable as long as two-thirds of the generals are honest.
* Blockchain is designed to be Byzantine Fault Tolerant, meaning that the network will come to a consensus on the official state of the blockchain, despite the fact that some members may misbehave. The solution to the Byzantine Generals' Problem is inefficient, so the blockchain needs some way of being confident of consensus without going through a full solution.

### Lecture 40 - Proof of Work vs. Proof of Stake

**Proof of Work** provides a game-theoretical distributed consensus algorithm:

* Proof of Work incentivizes mining nodes on the network to reach for the thermodynamic limit of computational cycles. This incentivizes decentralization because heat from mining nodes dissipates better in two separate places rather than one centralized location. Note, this decentralization is solely physical and a network distribution.
* Proof of Work has empirically proven that game-theory can be weaved into a protocol because it successfully applies incentives at every possible action within the network.
* Proof of Work only works because it is optimization-free and approximation-free.
	* Optimization-free means there is no possible way to circumvent the hashing of the mining protocol necessary to secure a block.
	* Approximation-free means there is no possible way to almost have a block. The process is binary; there are blocks and not blocks.

**Proof of Stake** provides an experimental internally game-theoretical consensus algorithm:

* It relies on nodes already having cryptocurrency to stake. It rewards nodes with the most money staked, and not the most computational power.
* It requires that each validating node be identifiable. This is because the staked coins must be held accountable for any malicious acts. Proof of Work does not require identification.
* In Proof of Stake,you are competing with a much larger group of nodes. There is no transactional friction involved in staking coins, unlike in Proof of Work, which requires buying mining hardware, hooking up internet, providing cooling systems, etc.

## Section 12 - Governance and Blockchain

### Lecture 41 - What Is Blockchain Governance?

* All organizations and software development projects need a way to finalize each decision along the roadmap. Most organizations are centralized and have a set leadership team. Several strategies for governing the decentralized blockchain have been developed.
* Effective blockchain governance includes:
	* Incentives
	* Methods of coordination.
* Before getting into the details of how governance works on the blockchain, it’s important to have a clear definition of what blockchain governance is. Every blockchain is an evolving system that needs to change to meet the needs of its users. If a blockchain isn’t relevant and useful, then it won’t survive.
* To evolve, the blockchain needs to make changes and needs a way to make final decisions on what these changes should be. Most organizations have a leadership team or a CEO who is the final authority for their organization. However, blockchain is designed to be decentralized, and not be under the control of any person or group. This means that blockchain needs another way to make decisions regarding the blockchain’s roadmap.
* For blockchain governance to be effective, it needs to include both incentives and methods for members to coordinate. Without incentives, members won’t participate in governance and the blockchain will become less aligned with user needs over time. Without a method for members to coordinate, it will be impossible for a blockchain network to come to an agreement on future changes.

### Lecture 42 - Blockchain Governance Strategies

* Several different blockchain governance strategies have been proposed and implemented for different blockchains. Here, we will review some blockchain governance strategies sorted from the fewest to the most members directly involved in the decision:  
	* Benevolent Dictator for Life"
	* Core Development Team
	* Open Governance
	* On-Chain Governance.

**Benevolent Dictator for Life** : The original creator or lead developer of a cryptocurrency has the final say on all decisions. 
	* The simplest blockchain governance strategy is nicknamed "Benevolent Dictator for Life". In this strategy, the creator of the blockchain is the final authority on all decisions regarding the blockchain. A good example of this type of leadership is Facebook, where Mark Zuckerberg has the final say on the future roadmap of the Facebook platform.

**Core Development Team** : A team of the most active developers decides what functionality should or shouldn’t be included.
	* The next step up places control of the blockchain roadmap in the hands of a Core Development Team. This is a strategy commonly used in open source programming projects, where users are able to offer or request features, but developers have the final say on what is or is not included in the official release.

**Open Governance** : The team making governance decisions for the blockchain is chosen by the users of the blockchain.
	* Some blockchains use the Open Governance method of handling governance of the blockchain. In this system, the team that makes the final technical decisions for a system is selected by the system’s users.

**On-Chain Governance** : The rules for how the blockchain operates are stored on-chain in smart contracts with built-in capability and procedures for modifications.
	* A blockchain-specific governance strategy is On-Chain Governance. In this form of blockchain governance, the rules describing how the blockchain should operate are stored on the blockchain itself. These regulations typically are implemented as smart contracts on the blockchain with built-in methods for users to modify the rules based upon their needs and the needs of the blockchain.

### Lecture 43 - Who Really Governs the Blockchain?

* Blockchain governance comes down to the users.
* Major changes to a blockchain require a hard fork. A hard fork is a change to the blockchain protocol that makes it incompatible with old clients.
	* For a hard fork to be successful, users need to agree to follow it.
	* Users can refuse to follow a hard fork, creating a divergent blockchain. The DAO Hard Fork on Ethereum created Ethereum Classic.
* Despite the official story of who governs the blockchain, in the end, the users are the ones who really make the final decisions of what will or will not be included in the blockchain. With the huge number of potential options, users can abandon a blockchain that makes changes that they disagree with.
* Any major change to a blockchain requires a "hard fork". All this means is that the blockchain protocol has changes that are not backward compatible, so blockchain clients that do not make the switch will not be able to operate on the main blockchain. For a hard fork to be successful, users of the blockchain need to make the decision to update their clients to incorporate the new changes.
* If not all users decide to make the switch after a hard fork, a divergent blockchain can be created. Since the blockchain is a distributed network, the decision to implement a hard fork doesn’t cause the old version of the blockchain to become non-functional. Users who choose not the follow the fork can decide to maintain the old blockchain, fragmenting the blockchain network.

### Lecture 44 - DAO Hard Fork on Ethereum Created Ethereum Classic

* One famous example of this type of fragmentation is the DAO hack on the Ethereum network. The DAO was an Ethereum smart contract that completed a record-breaking crowdfunding campaign on the Ethereum network, with all of this value stored within the DAO smart contract. A flaw in the smart contract’s code allowed an attacker to create another version of the smart contract under their control and siphon off a portion of the DAO contract’s funds, worth roughly 72 million dollars at the time. After much debate, the Ethereum network decided to implement a hard fork that allowed investors of the DAO to reclaim their stolen Ether.
* This was a very contentious decision because the historical ledger in the blockchain is supposed to be immutable and all transactions are final. Smart contracts are supposed to be their own final authority, so any action that could be performed with a smart contract, including exploiting a programming flaw to drain value from it, is considered fair game. The Ethereum network’s decision to reverse the DAO hack went against the principles of blockchain’s immutability and the supposed self-regulation of smart contracts.
* Some of the Ethereum network refused to follow the DAO hard fork, resulting in a divergent blockchain where the DAO hack was successful. This created the Ethereum Classic cryptocurrency, which shares the same history as Ethereum up to the DAO hack, but is completely independent after that point. Despite the "official" decision to reverse the DAO hack, users made the final call of whether or not they would abide by that decision.

### Lecture 45 - Governance in Ethereum

* We’ve been discussing the decisions made regarding the Ethereum blockchain, but haven’t discussed who made those decisions yet. Ethereum uses the “Benevolent Dictator for Life” mode of blockchain governance. While user input and input from the development team is welcome for Ethereum, Vitalik Buterin is the final authority on decisions regarding the Ethereum roadmap.

### Lecture 46 - Governance in Hyperledger Frameworks

* Hyperledger frameworks, on the other hand, use an Open Governance model to make technical decisions regarding the Hyperledger environment. The Hyperledger Technical Steering Committee (TSC) is the final authority for technical decisions in Hyperledger.
* Each year, the Hyperledger Technical Steering Committee is selected from the Hyperledger environment’s active contributors and maintainers.
* Contributors and maintainers can submit themselves as potential candidates for the eleven slots, and the slots are filled based on voting by the same group of contributors and maintainers. This model is designed to allow those with an active role in the Hyperledger development community to have a say in how that community is governed.

### Lecture 47 - Governance in Corda

* Corda also uses an Open Governance model to make technical decisions regarding the future of the blockchain. The Corda Network Governing Body will be selected to represent the interests of all users in the Corda network

## Section 13 - Identity and Anonymity on Blockchain

### Lecture 48 - Identity

* Identity in the blockchain is based on public key cryptography. A person’s address on the blockchain is their public key.
* Transactions on the blockchain include their public key and are digitally signed with the sender’s private key:
	* A digital signature verifies that someone in possession of the private key authorized the transaction.
	* Digital signatures can be easily verified using the corresponding public key, which is included in the transaction.
* Public key cryptography gives each person a pair of keys that work together:
* **Private keys** : They can decrypt things that public keys encrypted. They can only be tied to an identity if the owner wishes.
* **Public keys** : They can verify signatures made with private keys. They can only be tied to a private key if the owner wishes.


### Lecture 49 -  Specific Identity Implementations

Ethereum : A user’s identity is an address based on their public key.
Hyperledger : Identity is managed by X.509 certificates.
Corda : Identity is managed by X.509 certificates:
	* Public: Certificates published on blockchain
	* Confidential: Certificates only shared with parties involved in transaction.

### Lecture 50 - Advanced Blockchain Anonymity Techniques

* The following are only some of the mechanisms developed and implemented in various blockchains:
	* Zero-Knowledge Proofs : A prover proves knowledge of a secret without revealing it.
	* Stealth Addresses : Using one-time addresses for sending/receiving transactions for an account.
	* Ring Signatures : Type of digital signatures that lets any member of the group sign, but no one can tell which one signed.
	* CoinJoin : Transactions from several senders to several recipients are mixed together to hide who is paying whom.
	* Confidential Transactions : Uses homomorphic encryption to allow transactions to be processed while encrypted. Proves transaction value is in a range of values to prove that overspending did not occur.

**Zero-Knowledge Proofs** : Zero-knowledge proofs use cryptographic algorithms to allow a user to prove knowledge of a secret without revealing the secret. 
**Stealth Addresses** : Stealth addresses involve using one-time addresses to perform transactions on a blockchain. A stealth address is just a one-time address that makes it impossible to link a transaction to a known account. This prevents the data mining attacks on privacy that we discussed earlier.
**Ring Signatures** : We mentioned previously that transactions are digitally signed. With ring signatures, all that can be determined from a transaction is that a member of a group signed it, but not the particular member.
**CoinJoin** : The ability to see who is performing transactions with whom is dangerous to user privacy and anonymity. Protocols like CoinJoin mix several transactions together so that it is difficult to pair senders with recipients.
**Confidential Transactions** : Confidential transactions take advantage of homomorphic encryption, which makes it possible to perform mathematical operations on encrypted data. This means that the data contained in a transaction can be hidden from the public, while still allowing the network to verify that the transaction is valid.

### Lecture 51 - Specific Anonymity Implementations

* Ethereum : Ethereum currently does not have any advanced privacy options, but this is planned to change.
* Hyperledger
	* Channels: Subsections of the blockchain that make transactions visible only to members.
	* Private Transactions: Hashes of private data are stored to publicly verify it on the blockchain.
	* Zero-Knowledge Technology: Provers can demonstrate knowledge of a secret without revealing the secret itself.
* Corda : Parties on the Corda Network can be represented in one of two ways:
	* Party: A public key and name
	* Anonymous Party: Only a public key.

## Section 14 - Trust and Trustless

### Lecture 52 - Trust in Blockchains

* Just as there are benefits with blockchain technology, there are also some challenges. Blockchain is a culmination of technologies that have been blended to provide a trustless platform. Expect some challenges and use case justifications taking the old line of business apps to the blockchain.
* Let's recap the features of a blockchain that establishes trust:
	* Blockchain technology is about storing some kind of data (which are transactions in regards to the Bitcoin blockchain).
	* Blockchain is essentially transferring trust from an intermediary to technology.
	* Storing data in the blockchain is through cryptographic functions.
	* Private key/public key.
	* Collaboration through consensus.
* All transaction data on a chained block is assumed to be trustworthy.
* The users base this trust on the fact that:
	* This data has not been tampered with
	* The blockchain is immutable.
* Blockchains minimize the amount of trust required from any single actor in the system. They do this by distributing trust among different actors in the blockchain as defined by the consensus protocols.
* Blockchains have a shared ledger that gives us the absolute truth of the state of the system. It uses mathematics, economics, and game theory to incentivize all parties in the system to reach a “consensus” (i.e. coming to an agreement on a single state of the ledger).

# Chapter 2 - Governance and Consensus

## Section 1 - Standard vs. Blockchain Governance

### Lecture 53 - Introduction to Governance

* Humans tend to attract each other and build tribes, villages, town, cities, or empires. With that comes social norms among those who are living with or near each other. These norms have different ways of manifesting into existence, but the ones relevant to this conversation will be “rules”. It doesn’t matter if the governance is the real world or the digital world, there are shared underlying principles within both. They are:
	* Rules
	* Rulers
	* Participants
* Governance can be undertaken by a government, market, network, or social system (family, tribe, etc.).
* For a governance process to work effectively, the above three principles will need to play nice with each other. For example, the rules should be aligned with the overall participants' goals, and the rulers should enforce positive and negative actions within this governance structure.
* Now that we have a simple understanding of governance, let’s analyze how this is taking place in both the standard world and the blockchain world.

### Lecture 54 - Standard Governance

* Governance is a process that can apply to states, corporations, non-profits, non-governmental organizations, partnerships, business relationships, project teams, and any other grouping of humans with a purposeful activity.
* To keep things simple, we are going to cover standard governance through a lens that most blockchain systems evolved from. They are:
	* Representative Democracy
	* Direct Democracy

**Representative Democracy**

* With representative democracy, you have a select few who are voted upon by the people; those people have the power to suggest new rules. These rules are then voted upon by the select few. There are many pros and cons to different governance systems. Let's examine the pros and cons:
* Pros:
	* It's efficient
	* The decisions made are mostly balanced
	* The people get to choose their representative
	* It's slightly easier to address problems
	* It encoursges participation
* Cons:
	* Misplaced trust
	* Self-interest (e.g, once elected, then they are working in their own benefit)
	* Encourage deceptive election practices
	* Beenfits the majority (i.e. discounts the minority)
	* Lack of accountability for elected officials

**Direct Democracy**

* With a strict direct democracy, it is exactly that, direct. Any and all decisions made within that group will be voted upon directly by the people, without an intermediary.
* Two examples of semi-direct democracies would be Ancient Athens back in 500 B.C. and specific parts (the Swiss cantons of Appenzell Innerrhoden and Glarus) of current day Switzerland.
* Pros:
	* Votes actually count
	* Total transparency
	* Governmet accountability is promoted
	* Promotes less segregation and more collaboration/discussion
	* Government officials can be replaced quickly if their actions are deemed not in the best interests of the population
	* People tend to have better control over their quality of life
	* Voting becomes less of a priviledge and more a responsibility
* Cons:
	* It can be very difficult to make decisions
	* Not everyone is willing or wanting to participate
	* Could be more costly (educating voters & operating voting process)
	* There is potential for extreme manipulation (one higher power influences or presumes other to vote in one direction)
	* Humans are not always reasonable, meaning certain votes could be based on emotions
	* Once a group is too big. this model tends to fall apart
	* People can be selfish and that means the will not always vote for the greater good of everybody else
	* The attention span of the average person today is insanely short and information overload can kick in quickly

### Lecture 55 - How Does Blockchain Fit into Governance?

* Each and every blockchain ecosystem that has or is being created will need some kind of governance mechanism in place. When participants (miners, developers, and users) in the network are interacting, ideally they are acting in a way that’s best for the overall group. Being able to build a governance structure in a decentralized (sometimes anonymous, as well) world has proven to be extremely difficult, but this is a problem that many DLT companies are in the midst of solving.

* Most governance structures in the blockchain ecosystem are looking to achieve similar goals, such as:
	* Protocol changes and tech upgrades
	* Critical bug and vulnerability fixes
	* Using pooled funds for R&D.
* These goals can be achieved through many different methods of governance. Some of the popular ones being discussed at the moment are:
	* Futarchy : Participants in a system decide its values and those with the most info stake their ideas by betting on the outcome
	* Decentralized Autonomous Organization (DAO) : Allows for group governance through a combination of smart contracts and issuing tokens.
	* Liquid Democracy : System where everyone can vote for themselves or delegate their votes
	* Quadratic Voting : System of buying votes where each additional vote costs twice as much
* After all of this is decided, it becomes time for implementation, which is choosing the right mix of “on-chain” and “off-chain” governance. Let's examine these topics.

### Lecture 56 - On-Chain Governance

* In this type of governance, rules for instituting changes are encoded into the blockchain protocol. This means that any decision being made is automatically being translated into code (e.g. decisions concerning block size). Developers propose changes through code updates and each node votes on whether to accept or reject the proposed change.
* Pros:
	* It is truly a form of decentralized governance
	* Faster turnaround time for changes
	* The possibility of a hard fork is reduced due to economic incentives
* Cons:
	* Depending on the voting mechanism, users with more stakes can manipulate votes
	* Low voter turnout

### Lecture 57 - Off-Chain Governance

* Off-chain governance can be seen as decision-making that first takes place on a social level and is later actively encoded into the protocol by the developers. For instance, Bitcoin developers share their improvement proposals (BIPs) through a mailing list, whereas Ethereum collects improvement protocols (EIPs) on GitHub. 
* Fred Ehrsam (Coinbase co-founder) argues that the Bitcoin governance system resembles the checks and balances system of the US government. Just like the Senate, developers submit pull requests BIPs to the community, the miners take the role of the Judiciary who decides whether or not proposals are adopted in practice. Lastly, the users are just like citizens in a nation or state and can revolt and switch protocols or sell their tokens.
Pros:
	* Off-chain model serve as an important check to balance the power when it comes to making changes to software
	* Decisions are more thought out  and are compared to additional variables (e.g roadmap, funding, human resources, market trrends etc.)
Cons:
	* Limited ways to incentivize core development (issue in both Bitcoin and Ethereum)
	* Node operators hace to update their client manually to allign with the new chain
	* Slower than on-chain because of the human bottleneck

## Section 2 - Consensus

### Lecture 58 - Consensus

* Many different consensus mechanisms are needed in a decentralized world where there are no middlemen and where trust has truly become decentralized with the trustless movement of value.
* Consensus is a way to ensure the nodes on the network verify the transactions and agree with their order and existence on the ledger. In the case of applications like a cryptocurrency, this process is critical to prevent double spending or other invalid data being written to the underlying ledger, which is a database of all the transactions.
* With consensus, there are different solutions that fit different situations. When deciding to use a specific consensus mechanism, you’re taking on an opportunity cost (e.g. security, speed, etc.). The main difference between consensus mechanisms is the way in which they delegate and reward the verification of transactions. It’s important to mention that most blockchain ecosystems have a hybrid of different consensus mechanisms. There is no need to choose one over the other.

### Lecture 59 - Proof of Work

* Miners in the Bitcoin network are solving hard math problems to verify transactions and secure the overall network.
* Within PoW we have “Miners”, which are GPUs or ASICs chips running computational cycles to solve a math problem with the goal of reaching a set number previously provided to them. This set number is called a “target”, which is an SHA-256 hash with a long list of leading zeros and the “difficulty” (another term in the Bitcoin world) of this “target” adjusts every 2016 blocks (roughly 2 weeks), to ensure it takes roughly ten minutes for the miners to crack.
* There are three major ingredients needed to find this “target”:
	* A nonce (number only used once)
	* The transactional data
	* The previous blocks hash.
* This is all then hashed (combined) over and over with the nonce changing each time until the hash created from these three ingredients is lower than the “target” provided.
* Once the Miner has reached this “target”, they’re gifted with a transaction fee and mining reward (at the time this course was released, 12.5 bitcoins). The reward gets cut in half every 210,000 blocks (roughly 4 years).
* The next step is for the miner to broadcast to all the other miners that they have achieved the set “target” and have confirmed the block. Once that has been completed, they’ll move onto the next block.
* A good analogy is a lock and its combination. It takes a lot of work to figure out the combination, but once you do, it’s easy to verify.
* Pros:
	* Reliable (battle hardened through the years)
	* Extremely secure (Avoided many attacks)
	* With that comes trust in the trustlessness this consensus brings
* Cons:
	* Energy consumption (all these supercomputers running through math problems)
	* Vulnerability (there could be a 51% attack through majority computing power)
	* Halving reward lowers the overall incentives of miners to mine, centralization of hashing power
	* The rich get richer (e.g those whose can afford massive amounts of mining equipment use that in their favor - economies of scale)

### Lecture 60 - Proof of Stake

* With Proof of Stake (PoS) we have “Validators” – “Forging”, instead of "Miners" – "Mining". There are no computational cycles running through massive amounts of math problems trying to solve a problem like PoW. With PoS, we have validators sending a special type of transaction across the network, which gets locked into a deposit (otherwise known as validator pool) and that’s called “staking”.
* Once this validator has thrown his hat into the proverbial arena, then an algorithm pseudo-randomly selects a validator during each time slot (for example, every period of 10 seconds might be a time slot), and assigns that validator the right to create a single block. This block must point to some previous block (normally the block at the end of the previously longest chain), and over time, most blocks converge into a single constantly growing chain.
* The next step is for the validator to validate a grouping of transactions. Once that’s completed, they receive their staked funds back, plus the transaction fees (sometimes rewards when coin supply is being inflated from time-to-time) for that block.
* If the validator decides to act in a bad way (i.e. bad actor) and validate fraudulent transactions, they lose their stake that’s being held at the moment and are booted from the validator pool going forward (losing rights to forge). This is a built-in incentive mechanism to ensure they are forging valid transactions and not fraudulent ones.
* Pros:
	* Speed
	* Efficiency (less energy consumption)
	* Less hardware(does not need a supercomputer)
	* Less centralization due to forger being chosen at pseudorandom
* Cons:
	* Vulnerabilty (investing in the destruction fo the network)
	* The rich get richer (stake based consensus)

## Section 3 - Governance with Autonomy

### Lecture 61 - Decentralized Autonomous Organization (DAO)

* Decentralized Autonomous Organization (DAO) is a complex stack of smart contracts.
* It’s important to understand that, at the moment, there is no such thing as a completely autonomous DAO. There are specific parts that are autonomous and others that are not so autonomous.
* In simple terms, a DAO is an organization that runs on a stack of computer programs (called smart contracts in the blockchain world) that are all interconnected to maintain a set of pre-programmed rules that have been previously voted upon by a community.
* When thinking about regular corporations stripped all the way down to their bare bones, they are basically different groups following rules, responsibilities, and duties given from those sitting at the top of the organization. The bigger they are, the more complex these pieces become. At the moment, a DAO's goal is to automate this complex system piece by piece.
* Within each DAO, there is a kind of pooling process for humans to contribute new rules into the system. These rules are then presented to the community and voted upon, based on the DAOs previously created rules. These new rule commitments will need majority agreement (may be different for each DAO) from the community to make this rule real. If this new computer-coded rule is accepted by the community, then it will be placed into the stack of other computer coded rules to improve the overall autonomous organization.

## Section 4 - Governance for Enterprise

### Lecture 61 - Governance for Enterprise

* We’re focusing on governance in the consortium space, not governance within an enterprise company. So what is a "consortium"? A consortium is just a grouping of institutions (possibly individuals) getting together to achieve a mutual goal.
* This goal can be setting some standard for their industry (Department of Justice), selling product (Airbus), sharing resources (Universities), etc. In a consortium, the only real obligation you have to others who are taking part would be providing resources for specific tasks and sticking to the rules laid out prior to you joining. Within blockchain, there are many different industries creating their own consortiums, such as financial services, life science and health care, energy, media and telcos, and the public sector.
* Governance becomes much easier when it’s in a controlled environment, with each member agreeing upon set rules prior to jumping in with everyone else. Governance structures vary by industry and profit vs. non-profit, so there will be no set governance model everyone uses, but there are two we’ve come across in the blockchain space. 
	* One is including the formation of smaller subgroups to work on specific issues.
	* The second is providing several levels of potential engagement, ranging from participation in monthly calls to active technology development.
* The point we would like to get across here is that a consortium governance model is currently more efficient than most decentralized blockchains.
* Almost all consortiums up to this point have been permissioned and not decentralized permissionless blockchains, which is an opportunity cost most companies make when joining. At a high level, a permissioned blockchain is just that, a chain in which others must have permission to operate on. So, all the nodes operating on a permissioned chain have been verified by the central institution that is the authority of the network and the transactions that are confirmed don’t necessarily have to go through all the nodes.
* These consortium blockchains have historically taken two approaches:
	* **Business-focused consortia** : They aim to build and operate blockchain-based business platforms to solve a specific business problem (e.g. Digital Trade Chain – focused on cross-border payments). 
	* **Technology-focused consortia** : They seek to develop reusable blockchain platforms based on technical standards (e.g. Hyperledger) .
* There are some consortiums that do a hybrid of both business and technology, such as R3. Examples: Hyperledger, R3, Ripple, Digital Asset Holdings, Corda, B3i, EWF, etc. 
* Below are some of the pros and cons to consortium blockchains:
* Pros:
	* Lower Energy Consumption
	* Better chance of adoption in the short-term from set use-cases
	* Speed
* Cons:
	* Centralized Trust
	* Authority
	* Cencorship to decisions made

# Chapter 3 - Blockchain Problem Solving

## Section 1 - Immutability

* Immutability is when something is unable to be changed.

### Lecture 62 - Traditional Database (Transaction) Immutability

* The very nature of centrally-operated databases can’t be completely immutable, but that’s the case for blockchain as well. A centrally-run database can embed things into it with features that mention immutability (unchangeable). But if there is a central authority, they have all the ability in the world to override that feature.
* Another point to keep in mind is that immutability has been around for many years, just like the majority of the tech used via blockchain; it is the combination of these that makes it unique.

### Lecture 63 - Blockchain Immutability Concept

* Let's review the aspects of the public blockchain that improve the chances of it being immutable.
* There are many different variables, but the main one is consensus. In a blockchain, it refers to the logs of transactions which are created by consensus among the chain’s participants. The basic notion is that once a blockchain transaction has received a sufficient level of validation and posted on the chain, it can almost never be replaced or reversed or edited.
* If all the nodes within the network (Bitcoin specifically) are working to solve a really hard math problem by running many computers simultaneously, the chances of anyone overriding that are slim to zero.
* But, if someone wanted to undermine the immutability of the Bitcoin blockchain, here’s how they would do it:
	* First, they would install more mining capacity than the rest of the network put together, creating a so-called “51% attack.”
	* Second, instead of openly participating in the mining process, they would mine their own “secret branch", containing whichever transactions they approve and censoring the rest.
	* Finally, when the desired amount of time has passed, they would anonymously broadcast their secret branch to the network.
* Since the attacker has more mining power than the rest of the network, their branch will contain more Proof of Work than the public one. Every Bitcoin node will therefore switch over since the rules of Bitcoin state that the more difficult branch wins. Any previously confirmed transactions not in the secret branch will be reversed and the Bitcoin they spent could be sent elsewhere. The computing power required to achieve this is enormous and probably only theoretical, but it’s important to consider.
* One other less technical and malicious example would be from the Ethereum hard fork that directly happened after the DAO hack. In this example, the majority of the Ethereum nodes in the network decided to update the software preventing those hackers from withdrawing the cryptocurrency “earned” (stolen). This update could not be enforced, since every Ethereum user controls their own computer. Nonetheless, it was publicly supported by Vitalik Buterin, Ethereum’s founder, as well as many other community leaders. As a result, most users complied, and the blockchain with the new rules kept the name "Ethereum". A minority disagreed with the change and continued the blockchain according to its original rules, earning the title "Ethereum Classic".

## Section 2 - Transparency

**Transparency** : Anything that is see through, where there is very little fog or obstruction in the way. Just like immutability, transparency comes on a spectrum. Certain things are more transparent than others. In the context of business/technology, this can be seen as a way of operating that is easy for others to see what actions are being performed. For example, open source projects where all the source code is available for the masses.

### Lecture 64 - Traditional CRUD Explanation

* Before we jump into how blockchain technology can be seen as transparent in certain aspects, let’s review the traditional CRUD method used by most databases.
* In a traditional database, a client can perform four functions on data: Create, Read, Update, Delete. In a traditional database, there is usually an administrator, the authority giver who allows certain known participants in the database to do more than read/create; it allows them to update (change) and/or delete.
* Due to the fact that the administrator is controlling who has access and who doesn’t, it’s easier to track these changes and prevent actors from tampering. In the public blockchain world, this isn’t necessarily the case.

### Lecture 65 - Blockchain Append-Only

* Within the public blockchain world, every full node on the network is its own administrator, where it can Create (e.g. add) and Read; this is also known as Read/Write access (e.g. append-only). These nodes only add more data over time in the form of blocks, but all previous data is permanently stored and cannot be altered.
	* Read: query (e.g. search) and retrieve data from the blockchain
	* Write: add more data onto the blockchain.
* For example, if the blockchain has recorded that my Bitcoin wallet has 1 million BTC, that figure is permanently stored in the blockchain. When I spend 200,000 BTC, that transaction is recorded onto the blockchain, bringing my balance to 800,000 BTC. However, since the blockchain can only be appended, my pre-transaction balance of 1 million BTC also remains on the blockchain permanently, for those who care to look. This is why the blockchain is often referred to as an immutable and distributed ledger. 

## Section 3 - Autonomy

**Autonomy** : Independence or freedom, the ability to make your own decisions without being controlled by anyone else. This sense of freedom can be at the macro level of a country or at the micro level of a person. As children and adults, we all want a little autonomy in our lives, careers, or relationships, but it’s just a matter of how much autonomy one truly wants and can handle.

### Lecture 66 - Autonomy: Human Process-Driven Complexity

* The blockchain world is looking to solve all of this complexity with autonomy from intermediaries via automated smart contracts.
* In the traditional world of doing any kind of transaction with another party, there tends to be a lot of administrative paperwork, with third parties intervening every step of the way. Some of this is needed, but most of it becomes wasted time and effort which could be spent elsewhere. Depending on how complex a transaction is between two parties, designated specialists (contract drafters, signatories, regulators of the contract execution, authorities to help with disputes, etc.) can make the process more efficient. 
* This complexity can be seen within many areas of life. Take a moment to dissect the backend of certain services or products you use and this concept will become exposed very quickly.

### Lecture 67 - Autonomy with Smart Contracts

* Autonomy in the blockchain world can be seen from many different angles. We are going to focus solely on smart contracts in this section, due to the amount of autonomy it gives everyone involved. The concept of smart contracts has been around for a long time and was first proposed by Nick Szabo, who coined the term in 1994. The most simplified explanation is:

*"IF THEN ELSE" statement, which means IF X happens, THEN do Y, ELSE do Z.*

* Take this concept and apply it to two or more parties, all interacting on a mutually agreed upon contract that executes based on their actions (or non-actions). An example of a smart contract could be, "if this happens before the end of the year, then you pay me, else I pay you".
* These "smart" contracts aren’t very smart, at least for now. That’s due to the simple explanation above because these contracts are "if, then, else" statements, which can vary in complexity based on how they’re stacked.
* At the present moment, they can't make decisions without human intervention, AI, which is a highly debated topic at the moment by many neuroscientists/philosophers.
* Anyone is able to create their own smart contracts without a central authority giving the right to do so. These contracts are executed without too much human intervention, and they’re stored on blockchain technology which provides a sense of permanence. These are three of the main attributes that can bring more autonomy to exchanging information between parties. Setting up a pre-agreed upon contract that’s coded into a blockchain and executes automatically when certain actions are taken is one step in the direction of not only improving our autonomy as individuals, companies, but shifting wasted resources (middle men/women) toward more impactful work.  

## Section 4 - Multi-Party Transactions

### Learning 68 - Ordering Between Parties: Traditional Multi-Party Sync vs. Blockchain Multi-Party Sync

* In our current world of transactions, there’s always a third party to assist with connecting the sender and receiver. This has always been the most efficient way to move something from Point A to Point B. But with a third party making the connection comes the need to trust that they’ll get whatever is being sent in an efficient, economical, and effective way. This trust is open to human and process error. But we’ve discovered through experimentation that certain use cases could be automated via smart contracts.
* One example is cross-border payments. Sending money from one country (border) to another country (different border). The major issue with how this is traditionally done today (e.g. correspondent banking) is that certain transactions end up stopping off at 7–10 different checkpoint banks. This constant stopping is making the money movement more expensive (each bank takes a fee), slower, and less reliable (sometimes it might never make it). This type of transaction is heavily reliant upon third parties to facilitate the movement of information (money, in this case).

* Blockchain technology has been shown to provide many benefits, but one of the most prominent and immediate benefits is removing middle men (third parties) from a variety of processes. There is a long list of examples for middle men currently being removed, such as:
	* Energy distributors
	* Payment networks (Visa and Mastercard)
	* Content distributors (YouTube, Facebook, Medium, etc.)
	* Central exchanges (NASDAQ, London Stock Exchange, New York Stock Exchange, etc.)
	* Cloud database providers (AWS, Azure, etc.).
* How is the blockchain world removing this middle man? The answer is all around trust. Within the public blockchain world, where everyone is theoretically anonymous, there needs to be trust so we’re able to exchange valuable things without the concern of bad actors. Trust is built into the consensus mechanism that we’ve mentioned multiple times throughout this course. This incentivizes all the participants to help secure and validate good actions throughout the network. With that built-in "trustless" trust, we’re able to remove those middle men that provide no additional value, plus it could potentially increase the efficiency based on which public blockchain is being used.

## Section 5 - Double Spend

### Lecture 69 - How Blockchain Solves The Double Spend Problem

* Back in the early 1990’s, developers, cryptographers, and different groups of people were trying to solve the double-spend problem as it related to digital cash, previously known also as electronic cash. Double spending within Bitcoin is the act of using the same bitcoins (digital money files) more than once.
* If I buy an apple for $1, I cannot spend that same $1 to buy an orange. If I could, money would be worthless since everyone would have unlimited amounts and the scarcity that gives the currency value would disappear. The network protects against double-spending by verifying each recorded transaction within the blockchain utilizing a Proof of Work (PoW) mechanism (explained in the previous section).
* Bitcoin was the first decentralized protocol to solve this problem and now more protocols are following, such as: Proof of Stake (PoS), Delegated Proof of Stake (DPoS), Directed Acyclic Graphs (DAG) structures, Proof of Authority (PoA), etc.

### Lecture 70 - Digital Currency: Difficulties Prior to Blockchain

* Today, when someone mentions digital currency, usually Bitcoin or crypto is the first thing that comes to mind, but digital currency had a long history before Bitcoin popularized it. This history goes all the way back to 1983, when David Chaum introduced the idea of digital cash in a research paper. Then, in 1992, he founded DigiCash, an electronic cash company, which eventually went bankrupt in 1998 due to adoption (buyout by another financial institution).
* There were many other attempts to create digital cash over the years, but many failed due to a variety of reasons, such as:
	* Adoption
	* Security
	* Fraud
* Other attempts include:
	* CyberCash in 1994 (failed after the Y2K bug of 2000)
	* E-gold in 1996 (sunk by continuous money laundering, hacking, and extortion)
	* Liberty Reserve in 2006 (shut down in 2013 due to this becoming a great hangout spot for cybercriminals).

# Chapter 4 - Blockchain Use Cases

## Section 1 - Blockchain Use Cases

### Lecture 71 - Introduction to Use Cases

* We are already seeing blockchain disrupt many industries, including: healthcare, automotive, identity, government, real estate and insurance.
* In this chapter, we will hear from those who are leading these projects. Companies including IBM, Luxoft, and counties such as Cook County, Illinois (USA), are using blockchain to solve problems, save money, and change the way data is stored and exchanged.

### Lecture 72 - Blockchain Decision Chart

* A private blockchain might be a solution IF:
	* A traditional database does not meet our requirements
	* Our database required share write access
	* If all our participants trust each other or share a common goal
	* If our database is likely to be compromised or attacked
	* If the data should be private
* A public blockchain might be a solution IF:
	* A traditional database does not meet our requirements
	* Our database required share write access
	* If all our participants DO NOT trust each other or share a common goal
	* If a third party is NOT wanted or required
	* If we DO NOT need to control who has access to the blockchain (If we DO private blockchain)
* In all other case we don't need a blockchain

## Section 2 - Healthcare

## Section 3 - Voting

### Lecture 73 - How Blockchain Can Benefit Voting?

* Blockchain can be utilized in many different fields as a solution to the problems that a standard database might have. One such problem can be seen in voting. Recently, it was revealed that a major U.S. voting machine manufacturer had installed remote access software on some systems. This software allowed for the alteration of votes when counting the total.
* Instances like this create a lack of trust in America's voting system, as seen in a recent poll: "Exclusive poll: Majority expects foreign meddling in midterms". This poll suggests that only about a quarter of Americans feel confident that their vote is being counted. Blockchain would solve this issue by providing a distributed ledger that would ensure your vote is counted since the ledger you own is the same as the one counting the total.

## Section 4 - Identity Management  

## Section 5 - Land Records and Government

## Section 6 - Blockchain with Supply Chain

### Lecture 74 - Farm to Table

* Farms are complicated ecosystems with many moving parts, careful timing, and seasonal financing structures. However, after the food leaves a farm, it becomes part of a wide-reaching supply chain with a lot of parties. Buyers, sellers, distributors, and grocery chains all want to know where the food is along its journey. You also probably want to know where your food has been before you serve it on your dinner table.
* The trend toward blockchain agriculture promises to make each step of growing and distributing food simpler. It will offer all parties involved a single source of truth for the agriculture supply chain. In this article, we will cover four key ways that blockchain is changing agriculture.
* Walmart and IBM dive deeper in their use case as we will review on the next page.

## Section 7 - Internet of Things (IoT)  

### Lecture 75 - Internet of Things Explained

* Imagine you are sitting on your couch watching your favorite reality show or sports team on your smart TV. During a commercial break, an ad for Papa John’s latest culinary creation catches your attention as your stomach reminds you at the same time that you haven’t had dinner yet. So with a click of the remote, you select the items that you’d like to try and an order is queued in your mobile app that will communicate the details of your order, apply a coupon deal, and share your delivery address. However, a quick internal scan by your smart refrigerator reveals there are still some leftovers from the last time you ate out. Alexa alerts you before your order goes through and gives you an opportunity to cancel it. You decide to follow through with the order anyways, because after all, that old pizza doesn’t have stuffed crust inside of the already-stuffed crust.
* Within a half hour, you receive a notification on your TV that the delivery driver is three minutes away and your front door lights automatically turn on in anticipation. In a matter of minutes, the doorbell rings and your show pauses. As you approach the door to greet the delivery driver, it unlocks. After you enjoy your dinner and finish your show, your biometric wristband coordinates with your phone’s health app to analyze your dietary and exercise trends over the past week. Within seconds, a step count goal for tomorrow is set and several healthy options for your next meal are suggested in accordance with the contents of your fridge. This scenario is not far from being a reality, and smart homes with this degree of connectivity are only the beginning of the new technology paradigm in our immediate future.
* The potential applications for IoT devices are practically endless, and they encompass industrial and enterprise-level applications in addition to consumer applications. From companies to cities to countries, the opportunity to leverage IoT technology and the data it generates is massive. Businesses can enable dynamic supply chains responsive to consumer demand, cities can minimize energy consumption and traffic congestion, and countries can operate on highly efficient transportation grids and national security networks. However, there are two significant concerns currently inhibiting Internet of Things adoption, security and scalability.
* In terms of security, IoT devices and the networks they are plugged into can be susceptible to cyberattacks, putting private or personal data at risk. Many IoT devices are designed to operate on low power networks, utilizing only the essential components for connecting while excluding the computing power necessary to run custom cybersecurity protocols. That being said, a breach in a single device could compromise an entire network, rendering vast amounts of confidential information vulnerable to attack. Additionally, the majority of IoT networks operate on centralized cloud solutions, both for storage and processing purposes. This type of centralized architecture leaves a network exposed to cyber threats and also limits a network’s ability to share and process information. As the global IoT network expands to billions of new devices over the next few years, the sheer amount of data generated will overwhelm our current IT infrastructure, restricting much of the value IoT networks create.
* In recent years, another revolutionary type of technology has emerged that could very well be the solution for alleviating the primary pain points facing IoT technology, that technology is blockchain. Blockchain is a challenging topic to assign an all-encompassing definition to due to the extensive nature of the concepts and implementations that fall underneath its umbrella. As a matter of fact, the term “blockchain” today is not unlike the term "internet" in the late 1990’s and early 2000’s, in that it comprises a plethora of ideas, components, and applications all headed in unique directions. However, blockchain can be generally defined as a decentralized network where participants are granted certain rights to exchange, examine, and manage information or value securely with other members of the network. In addition to these rights, each node is responsible for working with all of the other nodes to confirm and keep an undisputed archive of all information made available throughout the network, which is also distributed amongst all the members.
* Blockchain could help address many of the security concerns faced by IoT networks. Cryptographically encoded communication channels would permit devices to speak and exchange data with one another securely, and Byzantine Fault Tolerant algorithms would identify threatening devices and prevent them from incapacitating the rest of the network. Permissions could also be granted to each IoT device, determining which nodes would be able to submit data, communicate with other nodes, and view the ledger within the network. So things that might be more susceptible to attack can be assigned write-only permissions, and the rest of the network would monitor these devices and verify that the data they are contributing is valid. Additionally, processing power is allotted to each participant in the network rather than being owned entirely by a central authority, improving latency and facilitating scalability within the network. By allocating resources and responsibilities democratically among network participants, an IoT network powered by blockchain could operate on a highly-efficient and scalable model. Dynamic interactions between devices could optimize end value and enable real-time, data-based decision making. Together, these two technology megatrends are very well suited to complement one another and their union will usher us into a new era of connectivity and utility.

Let’s review the smart home scenario from earlier and see a few examples of how an IoT network built on a blockchain framework could interoperate and harmonize. To begin, every smart device from your TV to your wristband would be able to connect and communicate securely within the blockchain network, ensuring absolute privacy of your personal data. This way your fridge can talk to your phone which talks to your smart lights and so on in a safe and efficient fashion. A blockchain network could also support payments, allowing an app on your phone to automatically pay for your pizza or other goods and services with digital currencies designed for highly efficient and inexpensive value transfer over the internet. Additionally, tasks like re-ordering household essentials or scheduling routine home maintenance could be automated by leveraging the data made available by assorted devices. The technical term for self-executing transactions like these is a "smart contract", which is a piece of code built on top of the distributed ledger (or data) layer programmed to execute a specific task once certain data inputs are met. For example, you could create a smart contract that re-orders coffee beans when it’s been 30 days since you bought your last bag or your annual AC inspection could be automatically scheduled with a preferred technician in accordance with your calendar’s availability. This opportunity for automation also sets blockchain apart as a superior solution to alternative IoT network structures, like edge computing within cloud-based systems. The smart contract layer built on top of the data and communication layers unlocks an unbelievable amount of potential for an IoT network, especially those with industrial or commercial focus.

Luxoft plans to implement blockchain to keep the IoT secure.

## Section 8 - Energy