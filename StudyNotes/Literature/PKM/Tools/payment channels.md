---
Aliases: Payment channel, Payment channels, payment channels
---

Payment channels in the Bitcoin [[Lightning Network]] are a mechanism for conducting off-chain transactions between two parties. They allow users to create a temporary and private payment channel, where they can send multiple transactions without broadcasting them to the main Bitcoin blockchain.

When a payment channel is opened, both parties commit a certain amount of Bitcoin to a multisignature address. The current state of this address is stored on the blockchain. Within this channel, the two parties can then conduct an unlimited number of transactions by updating the channel's state without actually sending any Bitcoin to the blockchain.

## Only Intermittened Commits to the mainnet
Only when one party decides to close the payment channel will the final state be broadcasted to the main blockchain, and each party will receive their respective share of funds according to the latest agreed-upon balance within the channel. This reduces transaction fees and increases transaction speed since only the opening and closing transactions need to be broadcasted on-chain.

Payment channels enable fast and low-cost microtransactions while maintaining security through cryptographic mechanisms. The Lightning Network is built upon these payment channels, allowing for an extensive network of interconnected channels that enable instant and scalable Bitcoin transactions.