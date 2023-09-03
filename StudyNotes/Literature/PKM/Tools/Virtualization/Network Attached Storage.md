---
Aliases: NAS
---
#NAS #PKC


[[Network Attached Storage]] ([[Network Attached Storage|NAS]]) is a specialized file storage device that is connected to a computer network, allowing multiple clients or users to access and share data from a central location. It provides file-level data access and operates as a dedicated server for file sharing and storage. It is a physical infrastructure for implementing [[Personal Cloud]] and [[PKC]].

Here are some key features and aspects of NAS:

1. Storage Capacity: NAS devices come in various sizes, ranging from compact units to enterprise-level solutions with high storage capacity. They can accommodate multiple hard drives or solid-state drives (SSDs) to provide scalable storage space.

2. Data Redundancy: Many NAS devices support RAID (Redundant Array of Independent Disks) configurations, which offer data redundancy by mirroring or striping data across multiple drives. This ensures that if one drive fails, the data remains accessible and intact.

3. File Sharing: NAS enables easy file sharing among connected devices on the network. Users can access shared folders and files from their computers, smartphones, tablets, or other networked devices using standard protocols like SMB (Server Message Block), NFS (Network File System), FTP (File Transfer Protocol), etc.

4. Remote Access: NAS devices often include remote access capabilities, allowing users to access their files from outside the local network using secure protocols such as VPN (Virtual Private Network) or cloud-based services provided by the manufacturer.

5. Backup and Sync: NAS devices typically offer built-in backup functionalities that allow automated backups of important files from connected devices on the network. Some models even support synchronization with popular cloud storage services for additional data redundancy.

6. Media Streaming: Many NAS devices have media server capabilities, allowing streaming of multimedia content such as videos, music, and photos to compatible media players or smart TVs within the network. Two well-known software products: [[Plex]] and [[Jellyfin]] are common solutions in [[Network Attached Storage|NAS]].

7. Security: NAS systems offer various security measures like user authentication, folder/file-level permissions, encryption protocols (e.g., SSL/TLS), firewall protection, etc., to ensure secure access and data protection.

8. Scalability: NAS devices can be easily expanded by adding more hard drives or upgrading existing drives to larger capacities. This scalability makes them suitable for businesses or individuals with growing storage needs.
## NAS and The Onion Router and IPFS

Network Attached Storage (NAS) device would act as a storage medium for the [[Tor]] and [[IPFS]] services utilized by [[UmbrelOS]]. The NAS would store the necessary files, databases, and configurations required for running these services. Users connected to the NAS can access and utilize these services seamlessly.

Tor is an anonymity network that allows users to browse the internet privately by routing their traffic through a series of volunteer-operated servers. By storing Tor-related files on the NAS, UmbrelOS can leverage its processing power for running Tor nodes, enhancing privacy for users accessing the internet through the network.

IPFS (InterPlanetary File System) is a distributed file system that enables data storage and retrieval in a decentralized manner. By utilizing NAS as its storage layer, UmbrelOS can store IPFS data on the NAS device, allowing users to access and share content stored within the IPFS network conveniently.

Now let's consider how this setup works with Layer 2 networks of [[Bitcoin]] like [[Lightning Network]] nodes or Core Lightning Network Node. The Lightning Network is a scaling solution for Bitcoin that enables fast and cheap transactions by creating payment channels between users.

In this context, UmbrelOS running on a device connected to a NAS can act as a Lightning Network node or Core Lightning Network Node. The NAS stores necessary data related to running these nodes like blockchain data, channel information, transaction logs, etc.

By utilizing NAS as its storage layer, UmbrelOS ensures high availability of data required for maintaining connectivity to the Lightning Network. This allows users connected to UmbrelOS via Layer 2 networks (such as Lightning Network nodes) to easily access and interact with the Bitcoin network without relying on centralized infrastructure.

In summary, employing NAS as the storage layer for Tor and IPFS services in UmbrelOS enables enhanced privacy and decentralized file sharing. Combining this with Layer 2 networks like Lightning Network nodes or Core Lightning Network Node ensures efficient and reliable connectivity to the Bitcoin network, fostering a more decentralized and secure ecosystem.

# Conclusion

Overall, Network Attached Storage provides a centralized and efficient way to store, manage, and share data across a network. It offers data redundancy, easy accessibility, and various additional features that make it a popular choice for both personal and business use cases.

## References
[[@nascomparesQNAPNASJellyfin2023]]