Project Structure
  block.js: Contains the Block class which defines the structure of a block in the blockchain.
  blockchain.js: Contains the Blockchain class which manages the chain of blocks.
  transaction.js: Defines the structure of a transaction.
  main.js: Entry point to interact with the blockchain, including creating transactions and mining new blocks.

  
How It Works
  Block Creation: Each block contains an index, timestamp, transaction data, previous block's hash, and its own hash.
  Hashing: SHA-256 is used to create a hash for each block.
  Proof of Work: A simple proof-of-work algorithm ensures blocks are mined correctly.
  Adding Blocks: Blocks are added to the chain after validation.
