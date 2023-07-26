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