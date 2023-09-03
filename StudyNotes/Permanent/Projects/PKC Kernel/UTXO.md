---
Aliases: UTXO, Unspect Transaction Output
---

[[UTXO]] stands for [[UTXO|Unspent Transaction Output]], which is a fundamental concept in blockchain technology. In a UTXO-based blockchain system, such as Bitcoin, transactions are represented as inputs and outputs.

When a user wants to send cryptocurrency to another user, they create a transaction that references the unspent outputs (UTXOs) from previous transactions that they own. Each UTXO represents an amount of cryptocurrency associated with a specific address. The sum of all the UTXOs referenced in a transaction's inputs must be greater than or equal to the sum of the outputs.

Once a transaction is verified and added to the blockchain, the referenced UTXOs are considered spent and cannot be used again in future transactions. Instead, new UTXOs are created as outputs of the transaction, which can be spent in future transactions.

The UTXO model provides several benefits. Firstly, it allows for easy verification of transaction validity by simply checking if the referenced UTXOs have been spent or not. Secondly, it enables better privacy as each output is associated with a specific address rather than an account balance. Lastly, it facilitates scalability since each node only needs to keep track of unspent outputs rather than maintaining a complete history of all transactions.

However, managing UTXOs can also introduce some complexity and inefficiency. Wallets need to carefully select appropriate UTXOs for spending to avoid unnecessarily large fees or fragmented outputs. Additionally, large numbers of small-value UTXOs can lead to increased storage requirements and slower processing times.

## What is UTXO's relationship with Double Entry Bookkeeping

The connection between UTXO and [[Double Entry Bookkeeping]]([[Double Entry Bookkeeping|DEB]]) lies in the idea that they both aim to maintain an accurate record of transactions and ensure the consistency of balances. While Double Entry Bookkeeping is based on recording debits and credits in different accounts, UTXO keeps track of unspent outputs that can be used as inputs for future transactions.

Overall, UTXO's relationship with Double Entry Bookkeeping is that they both provide mechanisms for tracking financial transactions and maintaining accurate records of balances. However, their implementation differs due to the unique nature of blockchain technology.

# Conclusion
Overall, the UTXO model plays a crucial role in ensuring the integrity and security of blockchain transactions while providing certain advantages and considerations for users and developers alike.

# References
![[@nakamotoBitcoinPeertoPeerElectronic2008]]