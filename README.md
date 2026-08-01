# PQC Networking Concepts

**Repository:** `siddharthseth888/pqc-networking-concepts`

---

### Summary and Understandings from this repo
This github repository is made to make you familiar with the NIST PQC frameworks in a very easy and presentable way. We are working between the Application and Transport Layer where TLS comes in the way to secure the data between these layer. TLS works on the **ECDLP (Elliptic curve Discrete Logarithmic Problem)** which uses **ECDHE (Elliptic curve Diffie Hellman Ephemeral)** as key agreement protocol and **ECDSA (Elliptic curve Digital Signature Algorithm)** for authentication and integrity between the parties but but **Shor's Algorithm and QFT (Quantum Fourier Transform)** can break into the hardness of ECDLP and this will lead to data breach so to completely provide security between the parties we require what is known as the **PQC protocols** which is standardised by NIST PQC frameworks which comes up with a statement that even Quantum computers cannot break this protocol.

This concept is used by Researchers and Mathematicians across the world and came up with a solution that is based on **LBC (Lattice based cryptography)**.

Now using LBC researchers have created **MLKEM (Module Lattice Key Encapsulation Mechanism)** and **MLDSA (Module Lattice Digital Signature Algorithm)**. 

These are the replacement for the ECDH and ECDSA existing algorithms in TLS-1.3, now TLS-1.3 with these algorithms can be concluded as TLS-1.4 which is the mandate TLS that should be used across the globe for web communications.
For further details, you can visit the repository https://github.com/Mbed-TLS/mbedtls .

- Thanks for Reading.
- Kindly take a look so that it looks sweet and simple rather than referring to the official documentation released by NIST namely FIPS203 and FIPS204.
- Build by a Developer for the Developers!
