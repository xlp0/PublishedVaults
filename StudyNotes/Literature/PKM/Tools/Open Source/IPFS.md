#NSM

IPFS (InterPlanetary File System) is a peer-to-peer protocol and network designed to create a distributed file system that allows users to store, share, and access data in a decentralized manner. It was developed by [[Juan Benet|Juan Benet]] in 2014.

Traditional file systems rely on centralized servers to store and distribute files. In contrast, IPFS uses a distributed network of nodes to store and retrieve data. Each file or piece of data is given a unique identifier called a Content Identifier ([[CID]]), which is derived from its content. This CID serves as an address for the data rather than relying on its location.

When someone wants to retrieve a file using IPFS, they send a request for the corresponding CID to the IPFS network. The network then locates nodes that have the requested content and retrieves it from them. The requested content is verified using cryptographic hashes to ensure its integrity.

One of the key features of IPFS is its ability to deduplicate files. Since each file is identified by its content, identical files are only stored once in the network, reducing redundancy and saving storage space.

IPFS also supports versioning, allowing users to keep track of different versions of files and easily access historical revisions.

Another important aspect of IPFS is its support for offline access. Users can download files from other nodes in the network even when there is no direct internet connection available.

IPFS has gained popularity due to its potential for decentralized web applications, improved resilience against censorship, and efficient distribution of large datasets. It has also been integrated into various projects and platforms, including decentralized storage systems like Filecoin.

IPFS was also tightly influenced by the popularity of [[Blockchain]] infrastructure, and can be used in conjunction with it to enable [[Web3]].

Overall, IPFS aims to provide an alternative approach to traditional centralized file systems by creating a distributed and resilient network for storing and accessing data in a peer-to-peer manner.

How does IPFS deal with long latency

IPFS (InterPlanetary File System) deals with long latency in a few ways:

1. Content addressing: IPFS uses content addressing to uniquely identify data based on its content. Each piece of data is assigned a unique hash that acts as its address. This allows IPFS to cache and distribute data across the network, reducing the impact of long latency by retrieving data from the nearest available source.

2. Distributed network: IPFS is a peer-to-peer network where nodes share and distribute data amongst themselves. When a file is requested, IPFS automatically searches for the nearest node storing that file and retrieves it from there. This distributed nature helps mitigate long latency by reducing the distance data needs to travel.

3. Caching: IPFS nodes are designed to cache frequently accessed content locally, making it accessible even during periods of high latency or when the original source is offline. This caching mechanism further reduces the impact of long latency by allowing users to retrieve content from nearby nodes instead of relying on distant sources.

4. BitSwap protocol: IPFS uses a protocol called BitSwap, which facilitates efficient exchange of blocks between nodes in the network. BitSwap allows nodes to request only specific blocks they need for a file instead of transferring entire files, reducing bandwidth requirements and improving performance in scenarios with high latency.

By combining these techniques, IPFS aims to minimize the impact of long latency by caching popular content locally, distributing files across multiple nodes, and optimizing data transfer between peers in a decentralized manner.