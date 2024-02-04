![](https://toolboo.com/wp-content/uploads/2021/08/blockchain-1024x682.jpg)



# Chapter 2: Example of Blockchain

In this chapter, let’s explore a simple example of how a blockchain works. Imagine a scenario where we want to track ownership of digital assets (let’s call them “CryptoGems”) using a blockchain.

## CryptoGems Blockchain

1. **Genesis Block**:
    
    - Every blockchain starts with a **genesis block**. Our CryptoGems blockchain begins with this initial block.
    - The genesis block contains no transaction data but serves as the foundation.
2. **Adding Transactions**:
    
    - Alice wants to transfer 10 CryptoGems to Bob.
    - We create a new block containing this transaction:
        - Previous Block Hash: Genesis Block Hash
        - Timestamp: Current time
        - Transaction Data: “Alice transfers 10 CryptoGems to Bob”
        - Block Hash: Calculated using cryptographic hashing
3. **Linking Blocks**:
    
    - The new block is linked to the genesis block.
    - The hash of the genesis block is stored in the new block.
    - This linkage ensures the integrity of the entire chain.
4. **Continuing Transactions**:
    
    - Carol now wants to transfer 5 CryptoGems to Dave.
    - We create another block:
        - Previous Block Hash: Hash of Alice-Bob transaction block
        - Timestamp: Current time
        - Transaction Data: “Carol transfers 5 CryptoGems to Dave”
        - Block Hash: Calculated using cryptographic hashing
5. **Validation and Consensus**:
    
    - Nodes on the network validate transactions and reach consensus.
    - Once approved, the new block is added to the chain.
6. **Immutable Ledger**:
    
    - Any attempt to alter a block would change its hash.
    - Since the next block references the previous block’s hash, altering one block affects the entire chain.
    - This immutability ensures trust and security.

## Conclusion

Our CryptoGems blockchain demonstrates the core principles of blockchain technology. Each block builds upon the previous one, creating a transparent, secure, and decentralized ledger. In subsequent chapters, we’ll dive deeper into advanced features and explore real-world use cases. Stay tuned! 🌐🔗



![[Pasted image 20240204124640.png]]

<iframe width="560" height="315" src="https://www.youtube.com/embed/xqBCXaOCECM?si=FdinL5uJgNb1WYD0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
