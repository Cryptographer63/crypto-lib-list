一、基础密码库

1. NaCl: http://nacl.cr.yp.to/

NaCl是一个易于使用的高效密码库，用于网络通信、加密、解密、签名等。NaCl的目标是提供建立更高级别的加密工具所需的所有核心操作。由Daniel J. Bernstein亲自设计。

2. libsodium: https://download.libsodium.org/doc/

Sodium是一个可移植的、可跨平台编译的、可安装的、可打包的NaCl分支，具有兼容和扩展API，可以进一步提高可用性。其目标是提供构建更高级加密工具所需的所有核心操作。Sodium 支持多种编译器和操作系统，包括Windows（使用MingW或Visual Studio、x86和x64）、iOS、Android以及Javascript和Webassembly。

3. openabe: https://github.com/zeutro/openabe

OpenABE是一个加密库，它集成了各种基于属性的加密（ABE）算法、行业标准的加密功能和工具，以及一个直观的应用编程接口（API）。OpenABE的目的是让开发者将ABE技术无缝地融入到那些受益于ABE的应用中，以保护和控制对敏感数据的访问。OpenABE被设计为易于使用，不要求开发者是加密专家。

4. pyUmbral: https://github.com/nucypher/pyUmbral

pyUmbral是Umbral阈值代理重新加密方案的参考实现。它是开源的，用Python构建，并使用OpenSSL和Cryptography.io。使用Umbral，Alice（数据所有者）可以通过一组半信任的代理或Ursulas执行的重新加密过程，将任何打算给她的密文的解密权委托给Bob。当这些代理的阈值通过执行重新加密而参与时，Bob能够结合这些独立的重新加密，并使用他的私钥解密原始信息。

二、隐私增强技术库
1. Private Join and Compute: https://github.com/google/private-join-and-compute

谷歌开源的隐私增强技术库，包含ecc, paillier, elgamal等基础公钥密码算法。

2. CryptoTools：https://github.com/ladnir/cryptoTools

CryptoTools是一个可移植的c++14库，包含一系列用于构建加密协议的工具。这包括异步网络（Boost Asio），几个快速基元，如AES（AES-NI），Blake2（assembly），和 eliptic curve crypto（Relic-Toolkit，Miracl，或libsodium）。还有其他几个为实现协议而定制的实用程序。

3. ENCRYPTO_utils: https://github.com/encryptogroup/ENCRYPTO_utils

构建ABY和网络层的加密工具。

4. TFHE: https://github.com/tfhe/tfhe

TFHE是根据Apache 2.0许可条款发布的开源同态加密库。该方案来自论文《Faster fully homomorphic encryption: Bootstrapping in less than 0.1 seconds》，实现了更快的gate-by-gate bootstrapping。

5. Seal：https://github.com/microsoft/SEAL

微软SEAL是一个易于使用的开源（MIT许可）同态加密库，由微软的密码学和隐私研究小组开发。微软SEAL是用现代标准C++编写的，很容易在许多不同的环境中编译和运行。关于微软SEAL项目的更多信息，见sealcrypto.org。

6. lattigo：https://github.com/tuneinsight/lattigo

Lattigo是一个Go模块，实现了基于Ring-Learning-With-Errors的同态加密原语和基于Multiparty-Homorphic-Encryption的安全协议。该库的特点是。纯粹的Go实现，可以实现跨平台构建，包括为浏览器客户端进行WASM编译。Lattigo旨在支持分布式系统和微服务架构中的HE，由于其自然的并发模型和可移植性，Go是一个常见的选择。

7. blockchain-crypto-mpc：https://github.com/unboundsecurity/blockchain-crypto-mpc

blockchain-crypto-mpc是一个由Unbound Security发布的开源库，它提供了加密基础，以解决与加密资产和区块链应用相关的最困难的挑战之一。保护加密签名密钥和种子秘密。
