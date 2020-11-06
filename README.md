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

More advances in HE:
- [Takeshita et. al.](https://eprint.iacr.org/2020/091.pdf) -Enabling Faster Operations for Deeper Circuitsin Full RNS Variants of FV-like SomewhatHomomorphic Encryption
- [Chen et.al.](https://eprint.iacr.org/2020/015.pdf) -Efficient Homomorphic ConversionBetween (Ring) LWE Ciphertexts


HE for private deep neural netowrk inferences:

- [CryptoNets](http://proceedings.mlr.press/v48/gilad-bachrach16.pdf) - CryptoNets: Applying Neural Networks to Encrypted Datawith High Throughput and Accuracy
- [FHE-DiNN](https://eprint.iacr.org/2017/1114.pdf) - Fast Homomorphic Evaluation ofDeep Discretized Neural Networks
- [Faster CryptoNets](https://arxiv.org/pdf/1811.09953.pdf) - Faster CryptoNets: Leveraging Sparsity forReal-World Encrypted Inference
- [Chimera](https://eprint.iacr.org/eprint-bin/getfile.pl?entry=2018/758&version=20180820:181811&file=758.pdf) - Chimera: a unified framework for B/FV, TFHE and HEAAN fully homomorphic encryption andpredictions for deep learning
- [TAPAS](https://arxiv.org/pdf/1806.03461.pdf) - TAPAS: Tricks to Accelerate (encrypted) Prediction As a Service
- [nGraph-HE](https://arxiv.org/pdf/1810.10121.pdf) - nGraph-HE: A Graph Compiler for Deep Learning onHomomorphically Encrypted Data
- [CryptoDL](https://dl.acm.org/doi/10.1145/3292006.3300044) - Low Latency Privacy Preserving Inference
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

- [Sameer Narahari Wagh (Distributed Logistic Regression)](https://snwagh.github.io/CV/thesis.pdf) - New Directions in EfficientPrivacy­Preserving Machine Learning

## MPC for Deep Learning:

- [SecureML](https://eprint.iacr.org/2017/396.pdf) - SecureML: A System for Scalable Privacy-PreservingMachine Learning
- [EzPC](https://eprint.iacr.org/2017/1109.pdf) - EzPC: Programmable, Efficient, and ScalableSecure Two-Party Computation for Machine Learning
- [GAZELLE](https://eprint.iacr.org/2018/073.pdf) - GAZELLE: A Low Latency Framework for SecureNeural Network Inference
- [ABY3](https://eprint.iacr.org/2018/403.pdf) - ABY3:  A Mixed Protocol Framework for Machine Learning
- [SecureNN](https://eprint.iacr.org/2018/442.pdf) - SecureNN: 3-Party Secure Computation forNeural Network Training
- [Flash](https://eprint.iacr.org/2019/1365.pdf) - FLASH: Fast and Robust Framework forPrivacy-preserving Machine Learning
- [FALCON](https://arxiv.org/pdf/2004.02229.pdf) - FALCON: Honest-Majority Maliciously Secure Frameworkfor Private Deep Learning
- [AriaNN](https://arxiv.org/pdf/2006.04593.pdf) - ARIANN: Low-Interaction Privacy-PreservingDeep Learning via Function Secret Sharing


<!-- ## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](http://creativecommons.org/publicdomain/zero/1.0)

To the extent possible under law, Jonathan Schneider has waived all copyright and
related or neighboring rights to this work. -->
