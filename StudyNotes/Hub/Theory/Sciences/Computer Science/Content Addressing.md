#NSM #content_addressable 

[[Content Addressing]] is a fundamental concept in [[Git]] and the InterPlanetary File System ([[IPFS]]). These systems are distributed peer-to-peer file systems and they are both content-addressable storage systems. For example, in [[IPFS]], content addressing is used to uniquely identify and locate data by its content rather than its location or address on the network. The notion of [[Content Addressing]] is also a foundational strategy in managing data by practicing [[Namespace Management]].

In traditional client-server systems, data is typically accessed by specifying its location using a [[Universal Resource Locator|URL]] or file path. However, in IPFS, data is identified using a cryptographic hash of its content. This hash serves as a unique fingerprint for the data, ensuring that identical content always has the same hash.

Key aspects of content addressing in [[Git]] and [[IPFS]] include:

1. Cryptographic Hashing: When a user adds a piece of data (a file or any content) to IPFS, the content is hashed using a cryptographic hash function, usually SHA-256. This generates a unique fixed-size hash that represents the content.

2. Unique Identification: The resulting hash is used as a unique identifier for the content. Since the hash is determined solely by the content itself, any change to the data, no matter how small, will result in a completely different hash.

3. Content Retrieval: To retrieve data from IPFS, a user or application specifies the content's hash instead of its location or address. IPFS nodes on the network use the hash to find and fetch the data from other nodes on the network.

4. Decentralized Distribution: Content addressing enables IPFS to be a fully decentralized and distributed system. Users can retrieve content from any node that hosts the data, and the content will always be identical regardless of the source.

5. Content Integrity: Content addressing ensures the integrity of the data. As long as the content remains unchanged, its hash will remain the same, guaranteeing that the data retrieved is the exact copy of what was initially added to IPFS.

6. Content Deduplication: Since identical content results in the same hash, IPFS deduplicates redundant data across the network. If multiple users add the same content, it will be stored only once, saving storage space and reducing network traffic.

Content addressing is a foundational feature of [[Git]] and [[IPFS]]. It is central to their design as distributed, peer-to-peer file systems. It allows users to interact with the system based on the content itself, leading to efficient and reliable content distribution across the [[IPFS]] network. [[Content Addressing]] will also be the main design principle for [[PKC]] implementations.

# References

![[@techwithnikolaHowGitWorks2023]]