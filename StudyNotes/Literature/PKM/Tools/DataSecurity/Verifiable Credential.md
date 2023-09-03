---
Aliases: VC, Cryptographic Badge
---


In [[W3C]] terms, a Verifiable [[Credential]] (a.k.a. [[Cryptographic Badge]]) refers to a digital representation of information that is issued by an entity, such as an organization or individual, and can be verified by others. It is designed to provide proof of claims made by the issuer about the subject of the credential.

Verifiable Credentials follow a specific data model defined by the W3C's Verifiable Credentials Data Model specification. This model involves three key components: 

1. Issuer: The entity that issues the Verifiable Credential. It could be an organization, government agency, or any trusted party that has the authority to make claims about individuals or entities.

2. Holder: The subject of the Verifiable Credential who possesses and controls it. The holder may be an individual person or an organization.

3. Verifier: The entity that verifies the authenticity and integrity of the Verifiable Credential using cryptographic techniques. The verifier can independently assess the claims made in the credential without necessarily relying on a centralized authority.

Verifiable Credentials are typically stored digitally and can be shared securely and selectively with other parties using decentralized technologies like [[blockchain]] or distributed ledger technology (DLT). They enable individuals to have more control over their personal data by providing them with portable digital credentials that they can present when needed, eliminating the need for paper-based documents or reliance on centralized databases.

The W3C's work on Verifiable Credentials aims to establish standards for interoperability, privacy, and security in digital identity systems. It promotes open and decentralized approaches to identity verification while ensuring privacy protection and giving individuals greater agency over their personal information. 

# Other relevant terms
Please also check out the term: [[Verifiable Presentation]].

# W3C's Data Model of Verifiable Credentials

The World Wide Web Consortium (W3C) has developed a [data model for Verifiable Credentials](https://www.w3.org/TR/vc-data-model/), which provides a standardized way to represent and exchange digital credentials in a secure and interoperable manner.

Verifiable Credentials are digital representations of claims made by an issuer about a subject. These claims can include personal attributes, qualifications, affiliations, or other types of information. The Verifiable Credential data model defines the structure and format of these credentials to ensure consistency and compatibility across different systems.

At the core of the data model is the concept of a Verifiable Credential, which consists of three main components:

1. [[Issuer]]: The entity that issues the credential. This can be an individual or an organization that has authority or trust to make claims about a subject.

2. [[Subject]]: The entity to whom the credential applies. This can be an individual or an organization that is being issued the credential.

3. [[Claim|Claims]]: The information or attributes being asserted by the issuer about the subject. These claims are typically represented as key-value pairs, where the key represents the type of claim and the value represents its value.

In addition to these core components, Verifiable Credentials also include cryptographic proofs and signatures to ensure their integrity and authenticity. These proofs use public-key cryptography to enable verification of the credential's authenticity without revealing any sensitive information.

The W3C's Verifiable Credential data model also supports various extensions and additional features to enhance its functionality. For example, it supports revocation mechanisms to enable issuers to revoke previously issued credentials if necessary. It also allows for [[Decentralized Identity|decentralized identifiers]] ([[Decentralized Identity|DIDs]]) to be used as unique identifiers for subjects, providing more control over identity management.

Overall, W3C's Data Model of Verifiable Credentials provides a standardized framework for representing and exchanging digital credentials in a secure and interoperable manner. It enables individuals and organizations to easily share and verify credentials while maintaining privacy and security.


# References
[[@preukschatSelfsovereignIdentityDecentralized2021a]]
