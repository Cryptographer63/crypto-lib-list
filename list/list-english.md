# I. Basic Password Library

C/C++

- Miracl: https://github.com/miracl/MIRACL

MIRACL Crypto SDK - is a multi-precision integer and rational number encryption library in C, widely considered by developers to be the gold standard open source SDK for elliptic curve cryptography (ECC).

- Openssl: https://github.com/openssl/openssl

OpenSSL is a robust, commercial-grade, full-featured open source toolkit for the Transport Layer Security (TLS) protocol (formerly known as the Secure Sockets Layer (SSL) protocol).

- Tongsuo: https://github.com/Tongsuo-Project/Tongsuo

Copperlock/Tongsuo (formerly BabaSSL) is an open source base cryptographic library providing modern cryptographic algorithms and secure communication protocols, providing underlying cryptographic base capabilities for storage, networking, key management, privacy computing and many other business scenarios, enabling privacy, integrity and authenticatability of data during transmission, use and storage, providing privacy and security during the data lifecycle It provides the ability to protect the privacy and security of data throughout its lifecycle.

- NTL: https://libntl.org/doc/tour-intro.html

NTL is a high-performance, portable C++ library that provides data structures and algorithms for integers of arbitrary length; vectors, matrices and polynomials over integers and finite fields; and floating-point operations of arbitrary precision. NTL provides high-quality, state-of-the-art implementations of algorithms, including integer arithmetic of arbitrary length and floating-point arithmetic of arbitrary precision. Polynomial arithmetic over integers and finite fields, including elementary arithmetic, polynomial decomposition, irreducibility tests, computation of minimal polynomials, trajectories, norms and more.

- cryptopp: https://github.com/weidai11/cryptopp

cryptoPP is an open source frontal C cryptography library that integrates a very large number of cryptographic algorithms, so you are sure to find the one you are looking for.

- PBC Library: https://crypto.stanford.edu/pbc/

  The PBC (Pairing-Based Cryptography) library is a free C library built on the GMP library (released under the GNU Lesser General Public License) for performing mathematical operations on pairing-based cryptosystems.

- NaCl: http://nacl.cr.yp.to/ 

  NaCl is an easy-to-use and efficient cryptographic library for network communication, encryption, decryption, signing, etc. The goal of NaCl is to provide all the core operations needed to build higher-level cryptographic tools. Designed by Daniel J. Bernstein himself.   

- libsodium: https://download.libsodium.org/doc/ 

  Sodium is a portable, cross-platform compilable, installable, packable branch of NaCl with compatible and extended APIs for further usability improvements. Its goal is to provide all the core operations needed to build more advanced cryptographic tools. sodium supports multiple compilers and operating systems, including Windows (using MingW or Visual Studio, x86 and x64), iOS, Android, and Javascript and Webassembly.

- relic: https://github.com/relic-toolkit/relic

  RELIC is a research-oriented toolkit for modern cryptographic primitives, with an emphasis on efficiency and flexibility. RELIC can be used to build efficient and usable cryptographic toolkits for specific security levels and algorithm choices. , ECIES, Sakai-Ohgishi-Kasahara ID-based Authentication Key Protocol, Boneh-Lynn-Schacham and Boneh-Boyen Short Signatures, Paillier and Benaloh Homomorphic Cryptosystems, etc.)

- openabe: https://github.com/zeutro/openabe

  OpenABE is a cryptographic library that integrates a variety of attribute-based encryption (ABE) algorithms, industry-standard cryptographic features and tools, and an intuitive application programming interface (API). openABE is designed to allow developers to seamlessly incorporate ABE technology into applications that benefit from ABE to protect and control access to sensitive data. openABE is designed to be easy to use and does not require developers to be cryptographic experts.

- cpabe toolkit: https://acsc.cs.utexas.edu/cpabe/

  The cpabe toolkit provides a set of programs that implement a ciphertext policy-based attribute encryption scheme. It uses the PBC library for algebraic operations. Please note that cpabe toolkit may not compile for PBC versions above 0.5.4.

- Paillier Library: Advanced Crypto Software Collection

  Paillier is a public key cryptosystem that provides an additive homomorphism, making it useful for privacy-preserving applications. It is a simple GMP-based C library that implements the generation, encryption, and decryption of Paillier keys, and also makes the use of homomorphism easy.

- Proxy Re-cryptography Library: http://spar.isi.jhu.edu/~mgreen/prl/

  Proxy Re-cryptography is a form of public key encryption that allows user Alice to "delegate" her decryption rights to another user, Bob. In a proxy re-encryption scheme, Alice delegates a semi-trusted proxy to translate the ciphertext encrypted under her key into the ciphertext encrypted under Bob's key. Once delegated, the agent operates independently of Alice. The proxy is considered "semi-trusted" because it cannot see the content of the translated message, nor can it re-encrypt Alice's message to a user to whom Alice has not granted decryption rights. This project is a C++ implementation of the proxy re-encryption scheme proposed in NDSS 2005 using the MIRACL library. Future versions of this library will incorporate the "proxy re-signature" scheme from CCS 2005.

- Broadcast Encryption: http://crypto.stanford.edu/pbc/bce/

  The Broadcast Encryption scheme allows a broadcaster to send an encrypted message to a set of receivers S, each of which has a different private key. Given any subset S' of S, the broadcaster can construct an encrypted message so that only the receivers in S' can decrypt it. This can be achieved by providing a pair of keys for each member of S. A copy of the message can then be encrypted separately under the key of each receiver in S'. However, this of course leads to very inefficient communication. The challenge is to construct a scheme in which the amount of communication is sublinearly related to the number of receivers. This project is an implementation of a BGW broadcast encryption scheme based on the PBC library.

Continuous updates are in progress ...

Java

- JPBC: http://gas.dia.unisa.it/projects/jpbc/#.YpLs7u5BxhE

  The Java Pairing-Based Cryptography Library (JPBC)

Continuously updated ...


Python

- pyUmbral: https://github.com/nucypher/pyUmbral

  pyUmbral is a reference implementation of the Umbral threshold proxy re-encryption scheme. It is open source, built in Python, and uses OpenSSL and Cryptography.io. Using Umbral, Alice (the data owner) can delegate the decryption of any ciphertext intended for her to Bob via a set of semi-trusted agents or re-encryption processes performed by Ursulas. when the thresholds of these agents are engaged by performing re encryption, Bob is able to combine these independent re-encryptions and decrypt the original message using his private key.

Continuously updated...

- GoPBC: The PBC Go Wrapper: https://github.com/Nik-U/pbc

The Go Pairing-Based Cryptography Library

- GoFE: https://github.com/fentec-project/gofe

GoFE is a cryptography library that provides implementations of functional cryptography schemes for different SOTAs, in particular FE schemes for linear (e.g. inner product) and quadratic polynomials.

- CONIKS: https://github.com/coniks-sys/coniks-go

CONIKS is a key management system that provides transparency and privacy for end-user public keys. CONIKS protects end-to-end encrypted communications from malicious or compromised communication providers and surveillance by storing users' encryption keys in a tamper-proof and publicly auditable key directory on the server side. This enables the messaging client to automatically authenticate the user's identity and prevent malicious/compromised servers from hijacking secure communications undetected. The library also includes an implementation of Verifiable Random Functions (VRF).


# II. Library of Privacy Enhancing Technologies

C/C++

- Private Join and Compute: https://github.com/google/private-join-and-compute

  Google open source privacy enhancement technology library , including ecc, paillier, elgamal and other basic public key cryptographic algorithms .

- CryptoTools: https://github.com/ladnir/cryptoTools

  CryptoTools is a portable c++14 library containing a range of tools for building cryptographic protocols. This includes asynchronous networks (Boost Asio), several fast primitives such as AES (AES-NI), Blake2 (assembly), and eliptic curve crypto (Relic-Toolkit, Miracl, or libsodium). There are several other utilities customized to implement the protocol.

- ENCRYPTO_utils: https://github.com/encryptogroup/ENCRYPTO_utils

  Cryptographic tools for building ABY and network layers.

- TFHE: https://github.com/tfhe/tfhe

  TFHE is an open source homomorphic encryption library released under the terms of the Apache 2.0 license. The scheme is from the paper "Faster fully homomorphic encryption: bootstrapping in less than 0.1 seconds" and implements faster gate-by-gate bootstrapping.

- Seal: https://github.com/microsoft/SEAL

  Microsoft SEAL is an easy-to-use open source (MIT licensed) homomorphic encryption library developed by Microsoft's Cryptography and Privacy Research Group. Microsoft SEAL is written in modern standard C++ and is easy to compile and run in many different environments. For more information about the Microsoft SEAL project, see sealcrypto.org.

- palisade: https://palisade-crypto.org/

PALISADE is an open source project that provides an efficient implementation of the Lattice Cryptography building block and leading homomorphic encryption scheme. PALISADE is designed for usability, offering a simpler API, modularity, cross-platform support and integration with hardware accelerators. PALISADE complies with the homomorphic encryption security standard of http://HomomorphicEncryption.org.

- lowmc: https://bitbucket.org/malb/lowmc-helib

lowmc is a FHE-friendly group cryptography scheme for which not much research has been done, but which is certainly interesting. To make it easier to understand, here is an example of a user who has very large data and now needs to encrypt it and put it in the cloud for computational analysis. If FHE encryption is used directly, the ciphertext expansion rate will be too high, making the communication overhead too high. At this point, the data can be encrypted using lowmc, i.e. using a packet cipher, and then the cipher text is sent to the cloud, where it is decrypted using homomorphic decryption, which turns it into a homomorphic encrypted cipher text that can then be computed and analysed.

 
Golang

- lattigo: https://github.com/tuneinsight/lattigo

  Lattigo is a Go module that implements a Ring-Learning-With-Errors based homomorphic cryptographic primitive and a Multiparty-Homorphic-Encryption based security protocol. The library is characterized by. A pure Go implementation that enables cross-platform builds, including WASM compilation for browser clients. Lattigo is designed to support HE in distributed systems and microservice architectures, and Go is a common choice due to its natural concurrency model and portability.
Continuous updates are in progress...


# III. Blockchain and Zero-Knowledge Proofs

Rust

- bellman: https://github.com/zkcrypto/bellman

bellman is a toolbox for building zk-SNARK circuits. It provides circuit characteristics and primitive structures, as well as basic gadget implementations such as boolean and numeric abstractions.

- Bulletproofs: https://github.com/dalek-cryptography/bulletproofs

This library is currently the fastest implementation of the Bulletproofs scheme, with single and aggregated range proofs, strongly typed multiparty computations, and a programmable constraint system API for proving arbitrary statements

C++

- libsnark: https://github.com/scipr-lab/libsnark

  This library implements the zkSNARK scheme, which is a cryptographic method for proving/verifying computational integrity in zero-knowledge.

- blockchain-crypto-mpc: https://github.com/unboundsecurity/blockchain-crypto-mpc

  blockchain-crypto-mpc is an open source library published by Unbound Security that provides cryptographic foundations to solve one of the most difficult challenges associated with crypto assets and blockchain applications. Protects cryptographic signature keys and seed secrets.
  
- ibSTARK: https://github.com/elibensasson/libSTARK

The libSTARK library implements scalable and transparent knowledge argumentation (STARK) systems that can be executed with or without zero knowledge (ZK) and can be designed as interactive or non-interactive protocols. zk-STARK has properties such as generality, transparency, scalability and post-quantum cryptographic security.

Solidity

- SolCrypto: https://github.com/HarryR/solcrypto

This library contains Solidity and Python implementations of cryptographic primitives such as ring signatures, proofs of knowledge, Packed ECDSA signatures, etc. They are designed to work together and make it easier to build new cryptosystems using composable primitives. These implementations can be easily switched to secp256k1 or alt_bn128 curves.

- vrf-solidity: https://github.com/witnet/vrf-solidity

vrf-solidity is an open source fast and efficient implementation of verifiable random functions (VRFs) written on Solidity. More precisely, the library implements VRF-proof verification functions based on the elliptic curve (EC) Secp256k1.
  
# IV. Quantum Security

- liboqs: https://github.com/open-quantum-safe/liboqs

liboqs is an open source C library for quantum-secure cryptographic algorithms. A collection of open source implementations of quantum-secure key encapsulation mechanisms (KEMs) and digital signature algorithms; liboqs is part of the Open Quantum Security (OQS) project led by Douglas Stebila and Michele Mosca, which aims to develop and integrate quantum-secure cryptography into applications to facilitate deployment and testing in the real world. In particular, OQS provides a prototype for integrating liboqs into TLS and SSH via OpenSSL and OpenSSH.

- rlwekex: https://github.com/dstebila/rlwekex

The software implements a key exchange protocol based on the Ring LWE problem from the following paper: Joppe W. Bos, Craig Costello, Michael Naehrig, Douglas Stebila. Post-quantum key exchange for the TLS protocol from the ring learning with errors problem. in Proc. IEEE Symposium on Security and Privacy (S&P) 2015, pp. 553-570. IEEE, May 2015. doi:10.1109/sp.2015.40, Eprint http://eprint.iacr.org/2014/599.

Translated with www.DeepL.com/Translator (free version)


