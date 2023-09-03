
Filecoin is a decentralized storage network that allows users to rent out their unused hard drive space in exchange for Filecoin (FIL), its native cryptocurrency. It was created by Protocol Labs, the same organization behind the InterPlanetary File System ([[IPFS]]), to build a robust and efficient decentralized storage system.

The Filecoin network is designed to provide secure and reliable data storage by connecting users who need storage with miners who offer their storage capacity. Miners are incentivized to participate in the network by earning FIL tokens for providing storage and retrieving data when requested.

The key technology behind Filecoin is its proof-of-spacetime consensus mechanism, which ensures that miners are storing the data they claim to store over a specified period of time. This mechanism provides strong guarantees about data availability and integrity on the network.

Filecoin aims to solve some of the challenges associated with centralized cloud storage, such as high costs, lack of control over personal data, and reliance on a single provider. By utilizing a decentralized network of independent miners, Filecoin enables users to store their data securely, privately, and at potentially lower costs.

In addition to its storage functionality, Filecoin also supports decentralized applications ([[dApp|dApps]]) through its integration with IPFS. This allows developers to build applications that leverage the benefits of decentralized storage while utilizing IPFS's content-addressable distributed file system.

Filecoin conducted an initial coin offering (ICO) in 2017, raising over $200 million in one hour. The mainnet launched in October 2020, enabling users to start using the network for storing and retrieving data.

# IPFS and libp2p

Filecoin was built using the [[libp2p]] networking stack. Libp2p is a modular networking framework developed by Protocol Labs, the same team behind Filecoin. It provides a variety of network protocols and components that enable secure peer-to-peer communication.

Filecoin utilizes libp2p to establish connections between nodes in its decentralized storage network. Libp2p handles tasks such as peer discovery, transport encryption, and connection management, which are essential for building a robust and scalable decentralized system like Filecoin.

By leveraging libp2p, Filecoin benefits from a well-tested and battle-hardened networking infrastructure that ensures reliable communication between nodes. This allows Filecoin to efficiently distribute and store data across its decentralized network of miners, ensuring data integrity and availability.

Moreover, libp2p's modular design enables Filecoin to adopt new protocols or upgrade existing ones without disrupting the entire system. This flexibility is crucial for maintaining compatibility across different versions of the Filecoin protocol and supporting future enhancements.

Overall, the integration of libp2p into Filecoin's architecture plays a vital role in establishing a resilient and efficient peer-to-peer network for decentralized storage.

# Conclusion

Overall, Filecoin aims to revolutionize the way we store and access data by providing a decentralized and secure alternative to traditional cloud storage solutions.