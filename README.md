# Awesome Secure-Machine Learning [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)


> A curated list of source of secure machine learning



## Homomorphic Encryption

Survey papers introducing HE:

- [A Survey on Homomorphic Encryption Schemes: Theory and Implementation](https://dl.acm.org/doi/10.1145/3214303) - Introduing the development of HE and also several popular HE schemas.
- [Survey on Homomorphic Encryptionand Address of New Trend](https://www.semanticscholar.org/paper/Survey-on-Homomorphic-Encryption-and-Address-of-New-Alharbi-Samkri/6468cffa6d7a1fba27d4e813a0a22531757d1d8a) - With some introduction of HE's application recently.


HE schemes:
- [Paillier](https://link.springer.com/chapter/10.1007/3-540-48910-X_16)(SomeWhat HE) - Public-Key Cryptosystems Based on Composite Degree Residuosity Classes
- [BGV](https://eprint.iacr.org/2011/277.pdf) - Fully Homomorphic Encryption without Bootstrapping
- [BV](http://www.wisdom.weizmann.ac.il/~zvikab/localpapers/IdealHom.pdf) - Fully Homomorphic Encryption from Ring-LWE and Security for Key Dependent Messages
- [FV](https://eprint.iacr.org/2012/144.pdf) - Somewhat Practical Fully HomomorphicEncryption
- [GSW](https://eprint.iacr.org/2013/340.pdf) - Homomorphic Encryption from Learning with Errors:Conceptually-Simpler, Asymptotically-Faster, Attribute-Based
- [TFHE](https://eprint.iacr.org/2018/421.pdf) - TFHE: Fast Fully Homomorphic Encryptionover the Torus
- [HEAAN](https://eprint.iacr.org/2013/340.pdf) - Homomorphic Encryptionfor Arithmetic of Approximate Numbers 
- [HEAAN with bootstrap](https://eprint.iacr.org/2018/153.pdf) -Bootstrapping for ApproximateHomomorphic Encryption

HE for private deep neural netowrk inferences:

- [CryptoNets](http://proceedings.mlr.press/v48/gilad-bachrach16.pdf) - CryptoNets: Applying Neural Networks to Encrypted Datawith High Throughput and Accuracy
- [Faster CryptoNets](https://arxiv.org/pdf/1811.09953.pdf) - Faster CryptoNets: Leveraging Sparsity forReal-World Encrypted Inference
- [Chimera](https://eprint.iacr.org/eprint-bin/getfile.pl?entry=2018/758&version=20180820:181811&file=758.pdf) - Chimera: a unified framework for B/FV, TFHE and HEAAN fully homomorphic encryption andpredictions for deep learning
- [TAPAS](https://arxiv.org/pdf/1806.03461.pdf) - TAPAS: Tricks to Accelerate (encrypted) Prediction As a Service
- [nGraph-HE](https://arxiv.org/pdf/1810.10121.pdf) - nGraph-HE: A Graph Compiler for Deep Learning onHomomorphically Encrypted Data
- [LoLa](https://arxiv.org/pdf/1812.10659.pdf) - Low Latency Privacy Preserving Inference
- [SHE](https://arxiv.org/pdf/1906.00148.pdf) -SHE: A Fast and Accurate Deep Neural Network forEncrypted Data

HE for other models:
- [Hardy et. al.(Logistic Regression)](https://arxiv.org/pdf/1711.10677.pdf) - Private federated learning on vertically partitioned datavia entity resolution and additively homomorphicencryption
- [Crawford et. al. (Logistic Regression)](https://arxiv.org/pdf/1901.08755.pdf) - Doing Real Work with FHE: The Case of Logistic Regression
- [SecureBoost (XGBoost)](https://arxiv.org/pdf/1901.08755.pdf) - SecureBoost: A Lossless Federated Learning Framework
- [Cheon et. al. (Cluster)](https://eprint.iacr.org/2019/465.pdf) - Towards a Practical Cluster Analysisover Encrypted Data
- [Jaschke et. al. (Cluster)](https://eprint.iacr.org/2018/411.pdf) - Unsupervised Machine Learning on Encrypted Data
- [Han et. al. (Cluster)](https://eprint.iacr.org/2018/662.pdf) - Efficient Logistic Regression on Large EncryptedData
- [Li et. al. (Distributed Logistic Regression)](https://dl.acm.org/doi/10.1145/3394486.3403321) - Faster Secure Data Mining via Distributed Homomorphic Encryption

## Multiparty Secure Computation

- [ALCHEMY](https://github.com/cpeikert/ALCHEMY) - Haskell-based DSLs and interpreters/compilers, build on top of the lattice crypto library Lol.
- [Cingulata](https://github.com/CEA-LIST/Cingulata) - Compiler toolchain and RTE for running C++ programs over encrypted data.
- [crypto-geofence](https://github.com/Georeactor/crypto-geofence) - Geo-fencing demo application based on Paillier scheme.
- [nGraph-HE](https://github.com/NervanaSystems/he-transformer) - Deep Learning (DL) with HE through Intel’s DL graph compiler nGraph based on [SEAL](#SEAL).
- [Marble](https://github.com/MarbleHE/Marble) - A C++ framework that translates between nearly plaintext-style user programs and FHE computations.
- [Morfix.io](https://morfix.io/sandbox) - Web-based UI to play around with the [Microsoft SEAL](#SEAL) library.
- [OpenMined](https://github.com/OpenMined) - Decentralized data ownership & intelligence based on HE, blockchain and deep / federated learning.
- [SHEEP](https://github.com/alan-turing-institute/SHEEP) - HE evaluation platform with a set of native benchmarks and a library agnostic language.

## Databases

- [CryptDB](https://github.com/CryptDB/cryptdb) - Protecting confidentiality with encrypted query processing.
- [encrypted-mongodb](https://github.com/pdroalves/encrypted-mongodb) - Wrapper on MongoDB's Python driver that enables to query encrypted data.
- [Prisma/DB](https://github.com/PrismaDB/PrismaDB) - Security layer for relational database systems.
- [TimeCrypt](https://github.com/TimeCrypt/timecrypt) - Encrypted time-series database using homomorphic encryption-based access control.
- [ZeroDB](https://github.com/zerodb/zerodb) - E2E encrypted database using proxy re-encryption.


## Resources

- [Barak, Boaz](https://intensecrypto.org/public/lec_15_FHE.html). Chapter about FHE in Barak's introductory book to Cryptography, used for Harvard CS 127.
- [Barthelemy, Lucas](https://blog.quarkslab.com/a-brief-survey-of-fully-homomorphic-encryption-computing-on-encrypted-data.html). Brief survey of Fully HE. 2016.
- [Chen, Zhigang](https://zhigang-chen.github.io/A%20List%20of%20FHE%20Papers.html). A continuously updated list of FHE papers.
- [Gentry, Craig](https://crypto.stanford.edu/craig/craig-thesis.pdf). A fully homomorphic encryption scheme. Stanford University, 2009.
- [HomomorphicEncryption.org](https://homomorphicencryption.org). An open industry, government & academic consortium working on standardization of FHE.
- [KU Leuven](https://www.esat.kuleuven.be/cosic/tag/cosic-guide-to-crypto/). An introduction to homomorphic encryption.
- [Micciancio, Daniele](http://cseweb.ucsd.edu/~daniele/LatticeLinks/FHE.html). Links to papers and implementations of Lattice Cryptography schemes.
- [Microsoft Research](https://www.youtube.com/playlist?list=PLD7HFcN7LXRef-eTSGt_XOUJLZNoDINUn). Videos from SEAL/CKKS talks at Microsoft's Private AI Bootcamp.
- [Vaikuntanathan, Vinoid](https://people.csail.mit.edu/vinodv/FHE/FHE-refs.html). A list of references about FHE, covering top papers in the field.


## Related awesome lists

- [awesome-cryptography](https://github.com/sobolevn/awesome-cryptography)
- [awesome-crypto-papers](https://github.com/pFarb/awesome-crypto-papers)
- [awesome-mpc](https://github.com/rdragos/awesome-mpc) - Multi-Party Computation.


## Contribute

Contributions welcome! Read the [contribution guidelines](contributing.md) first.


## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](http://creativecommons.org/publicdomain/zero/1.0)

To the extent possible under law, Jonathan Schneider has waived all copyright and
related or neighboring rights to this work.
