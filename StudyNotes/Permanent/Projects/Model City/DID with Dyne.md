
# General features (written with Ben)

- [[DID]] identity
- Sign documents(Text,PDF,Video, Directory?), related to DIDs
 - based/related on signed documents, we want to issue [[Verifiable Credential]](VC)
- All data is ideally saved onto some [[IPFS]] nodes (separately run and registered by local agencies) and other more efficient storage systems ([[AWS S3]]).
- [[IPFS]] node to be run inside [[Docker|Dockerized]] services (Personal Knowledge Container, [[PKC]]) some services running on public cloud providers, such as [[AWS]] - possibly using [[Zenswarm]] storage - initially it can be a centralized storage
- Catalog interface, such as [[Obsidian]], to navigate the uploaded multi-media documents(Text, PDF, Video)
- It needs a mobile-friendly app ([[Chromium]] compatible) to do document upload and signatures

# Application


## Basic user features 
- [x] At sign-up, a DID is created for the user. 
- The sign-up can be open for all or require an invitation  
- Documents (data) to be uploaded must be signed while uploaded. 
- Share individual files and folders, along with their signatures (sharing with users registered on the platform)

## Organization setup:  
- The organization admin can:
 - setup a "Credential issuer"
 - issue credentials (via GUI or APIs) and DIDs (via invitation)
 - assign ACL (Access Control Lists) to users based on their DIDs
 - Browse all the files of the users in the organization

## Cryptography  
 *	Sign and verify messages and documents (pdf, doc, excel files, pictures, videos etc) using quantum proof signatures, [[ECDSA]], [[EdDSA]], and [[Schnorr Signature|Schnorr signatures]]
 *	Produce and verify zero-knowledge proof credentials, for "privacy by design" disposable identities
 *	Produce and verify W3C-VC credentials, using the standard ECDSA signature, as well as quantum-proof signature using the IETF draft implementation
 *	Produce and verify multi-signature, using "privacy by design" principles, based on the "Reflow" crypto multi-signature paper
*	Storage of signatures using XADES (XML external storage) and PADES (PDF internal storage), for the signatures supported by the standards