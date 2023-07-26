---
Aliases: EDDSA
---

EdDSA stands for Edwards-curve Digital Signature Algorithm. It is a digital signature scheme based on elliptic curve cryptography (ECC) and was developed by Daniel J. Bernstein, Niels Duif, Tanja Lange, Peter Schwabe, and Bo-Yin Yang. EDDSA is designed to be efficient and secure for use in various cryptographic applications.

The algorithm utilizes the Edwards form of elliptic curves and provides strong security with relatively short key sizes compared to other signature algorithms like RSA or DSA. It offers high performance and resistance against various cryptographic attacks, making it suitable for resource-constrained environments such as embedded systems or mobile devices.

EDDSA generates digital signatures using a private key and verifies signatures using the corresponding public key. It provides authenticity, integrity, and non-repudiation in digital communications by ensuring that a message has not been tampered with and that it was indeed signed by the claimed sender.

EDDSA has gained popularity and has been adopted in various cryptographic protocols, including secure messaging systems, cryptocurrencies like Bitcoin, Ethereum's blockchain network, and other applications requiring secure digital signatures.

## How does EdDSA compare to ECDSA?

[EDDSA](https://www.wikiwand.com/en/EdDSA) (Edwards-curve Digital Signature Algorithm) is a variant of [[ECDSA]] (Elliptic Curve Digital Signature Algorithm). Both algorithms are used for digital signatures in cryptographic protocols and are based on elliptic curve cryptography.

Here are some key differences between EDDSA and ECDSA:

1. Simplicity: EDDSA is designed to be simpler than ECDSA. It removes some complex components from ECDSA, such as point compression, point multiplication, and point addition.

2. Security: Both algorithms provide a similar level of security when implemented correctly. However, EDDSA has been designed with a more modern cryptographic design philosophy, which may make it more resilient against certain types of attacks.

3. Speed: EDDSA is generally faster than ECDSA due to its simplified design. The removal of certain complex operations makes it more efficient for signing and verification processes.

4. Standardization: While ECDSA is widely standardized and used in various protocols and applications (such as Bitcoin), EDDSA is relatively newer and has fewer standardized implementations.

5. Key sizes: In terms of key sizes, both algorithms can use similar elliptic curves with different bit lengths to achieve varying levels of security. However, EDDSA typically uses larger key sizes compared to ECDSA for equivalent security levels.

6. Patents: ECDSA was patented by Certicom until 2008, which created some licensing concerns for its use in open-source software projects. On the other hand, EDDSA was designed to be patent-free from the beginning, making it more accessible for broader adoption.

Overall, while both EDDSA and ECDSA serve similar purposes and offer comparable security levels, EDDSA simplifies the algorithm without sacrificing security and provides improved efficiency in terms of speed.

