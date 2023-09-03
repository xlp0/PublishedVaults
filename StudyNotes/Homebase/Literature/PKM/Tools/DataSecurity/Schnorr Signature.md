---
Aliases: Schnorr Signature, Schnorr signatures
---
#cryptography 

Schnorr signatures are a type of digital signature scheme, named after its inventor [Claus Schnorr](https://www.wikiwand.com/en/Claus_P._Schnorr). They are used to verify the authenticity and integrity of digital messages or documents. 

Unlike other digital signature schemes, such as the widely-used RSA or [[ECDSA]] (Elliptic Curve Digital Signature Algorithm), Schnorr signatures have some unique features that make them attractive for certain applications.

One key advantage of Schnorr signatures is their simplicity and efficiency. They require fewer computational steps compared to other signature schemes, making them faster and more resource-efficient.

Another important feature of Schnorr signatures is their provable security. The scheme has been extensively studied by cryptographic researchers, and its security properties have been proven under well-established assumptions in cryptography.

Schnorr signatures also support various advanced cryptographic operations, such as multi-signatures (where multiple parties collectively create a single signature) and threshold signatures (where a group of parties collaboratively create a valid signature).

Furthermore, Schnorr signatures have desirable properties like non-malleability, meaning that even if an attacker obtains a valid signature, they cannot modify it to create a different valid signature on the same message.

In summary, Schnorr signatures offer simplicity, efficiency, provable security, and support for advanced cryptographic operations. These qualities make them an appealing choice for various applications requiring secure digital signatures.