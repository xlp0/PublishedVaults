---
Aliases: WebAuthn, Web Authentication
---

WebAuthn, short for Web Authentication, is a web standard developed by the World Wide Web Consortium (W3C) and the [[FIDO]] Alliance. It is designed to provide a secure and convenient way to authenticate users on the web using public-key cryptography instead of traditional passwords.

WebAuthn allows websites to offer passwordless authentication or use an additional authentication factor alongside passwords. It supports various authenticators, including built-in biometrics (such as fingerprint or facial recognition sensors) on devices, USB security keys, and smart cards.

Passkey, on the other hand, refers to a type of authenticator used with WebAuthn. It is a hardware device that generates and stores cryptographic keys securely. Passkeys can be in the form of USB security keys, Bluetooth devices like phones or tablets, or even specialized hardware tokens.

When using WebAuthn with Passkey, the user registers their Passkey with a website by generating a new public-private key pair on the device. The private key remains securely stored within the Passkey while the public key is registered with the website. During subsequent login attempts, the website challenges the user's Passkey to sign a random challenge using its private key. The signed response is then sent back to the website for verification.

This process ensures that even if an attacker gains access to a user's password or intercepts communication between the user and website, they cannot impersonate them without possessing their physical Passkey device. The use of public-key cryptography also eliminates the need for websites to store or transmit passwords securely.

Overall, WebAuthn simplifies authentication for users by reducing reliance on passwords while providing stronger security through cryptographic techniques. By leveraging hardware-based authenticators like Passkeys, it offers enhanced protection against phishing attacks and credential theft.