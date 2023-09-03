---
Aliases: Centralized Identity, centralized identity, account-based identity
---

[[Centralized identity]] refers to a system or framework where a single entity or organization has control over managing and verifying the identities of individuals or entities within a network or platform. In this system, the central authority holds and controls the personal information and credentials of users, allowing them to authenticate and access various services and resources. 

In a centralized identity system, users typically have a single digital identity that is recognized across multiple platforms or services. This can be advantageous as it simplifies the management of user identities and authentication processes for organizations. It also enables seamless integration between different services and reduces the need for users to create multiple accounts with different usernames and passwords. According to the book:[[@preukschatSelfsovereignIdentityDecentralized2021|Self-Sovereign Identity]], centralized identity system is also known as [[Centralized Identity|account-based identity]].

However, centralized identity systems also pose certain risks. Since a single entity controls all user data, there is a higher risk of data breaches or misuse of personal information. Additionally, users may have concerns about privacy and control over their own data as they rely on a central [[Authority|authority]] for [[Authentication|authentication]].

To address some of these concerns, [[Decentralized Identity|decentralized identity]] systems are being developed using technologies like [[Blockchain|blockchain]]. These systems aim to give individuals more control over their identities by allowing them to manage their own data while still ensuring security and interoperability across different platforms.

# How does Centralized Identity compare to Federated Identity?

[[Centralized Identity]] and [[Federated Identity]] are two different approaches to managing user identities in computer systems. Here's how they compare:

1. Control: In Centralized Identity, a single authority or organization has full control over the user identities and authentication process. This central entity manages and governs all aspects of identity management. In contrast, Federated Identity allows multiple organizations or domains to participate in the authentication process, with each maintaining control over their own user identities.

2. Trust model: Centralized Identity relies on a trust model where users trust the central authority to authenticate them and manage their identities securely. Federated Identity, on the other hand, uses a federated trust model where participating organizations establish trust relationships with each other to authenticate users across domains.

3. Scalability: Centralized Identity may face scalability challenges as it requires the central authority to handle all authentication requests from users across different applications or services. Federated Identity offers better scalability as the responsibility for authentication can be distributed among multiple identity providers (organizations).

4. Single Sign-On (SSO): Centralized Identity typically enables SSO within a single organization's systems or applications, allowing users to authenticate once and access multiple resources seamlessly. Federated Identity extends SSO capabilities beyond a single organization by enabling users to access resources across different organizations using a single set of credentials.

5. Privacy and data sharing: Centralized Identity often involves sharing user data with the central authority, raising concerns about privacy and security. In contrast, Federated Identity allows organizations to retain control over their user data while still enabling seamless authentication across domains.

6. Complexity: Implementing Centralized Identity can be relatively simpler as it involves managing identities within a single organization's systems or applications only. On the other hand, Federated Identity implementation can be more complex due to the need for establishing trust relationships between multiple organizations and ensuring compatibility between different identity protocols.

Overall, [[Centralized Identity]] offers centralized control but may lack scalability and involve privacy concerns. [[Federated Identity]], on the other hand, allows for distributed control, scalability, and enhanced privacy but requires more complex implementation efforts.

# How does Centralized Identity compare to Decentralized Identity?

[[Centralized Identity]] and [[Decentralized Identity]] are two opposite approaches to managing and controlling digital identity information. Here is a comparison between the two:

1. Control: In a centralized identity system, a central authority or organization holds and controls all the identity information of individuals or entities. This authority has the power to grant or deny access to this information. On the other hand, in a decentralized identity system, individuals have full control over their own identity data. They can choose which information to share and with whom, without relying on any central authority.

2. Privacy: Centralized identity systems often require individuals to disclose more personal information than necessary, as they collect and store vast amounts of data in a single location. This poses privacy risks, as the central authority becomes a target for hackers or may misuse the data. Decentralized identity systems prioritize privacy by giving individuals control over their own data and minimizing unnecessary disclosure.

3. Security: Centralized identity systems face security vulnerabilities because compromising the central authority can result in widespread breaches of personal information. In contrast, decentralized identity systems use cryptographic techniques like blockchain to enhance security and prevent unauthorized access.

4. Interoperability: Centralized identity systems are typically specific to certain organizations or platforms, making it challenging for users to seamlessly interact across multiple systems. Decentralized identity solutions aim for interoperability by allowing users to create portable identities that can be used across various platforms and services.

5. Trust: Centralized identity systems rely on trust in the central authority that manages the identities of individuals. In decentralized identity systems, trust is distributed among various participants through consensus mechanisms like blockchain technology.

6. Ownership: In centralized identity systems, individuals do not have true ownership of their own identities as they rely on an external authority for validation and verification processes. Decentralized identity systems enable individuals to truly own and control their identities without dependence on any third party.

Overall, [[DID|Decentralized Identity|decentralized identity]] offers greater control, privacy, security, interoperability, and ownership to individuals compared to [[Centralized Identity|centralized identity]] systems. However, the adoption and implementation challenges of decentralized identity solutions are still being addressed.