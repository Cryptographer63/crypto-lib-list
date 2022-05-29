一、基础密码库

1. NaCl: http://nacl.cr.yp.to/ 
NaCl是一个易于使用的高效密码库，用于网络通信、加密、解密、签名等。NaCl的目标是提供建立更高级别的加密工具所需的所有核心操作。由Daniel J. Bernstein亲自设计。
 
2. libsodium: https://download.libsodium.org/doc/ 
Sodium是一个可移植的、可跨平台编译的、可安装的、可打包的NaCl分支，具有兼容和扩展API，可以进一步提高可用性。其目标是提供构建更高级加密工具所需的所有核心操作。Sodium 支持多种编译器和操作系统，包括Windows（使用MingW或Visual Studio、x86和x64）、iOS、Android以及Javascript和Webassembly。
...

二、隐私增强技术库
1. Private Join and Compute: https://github.com/google/private-join-and-compute
谷歌开源的隐私增强技术库，包含ecc, paillier, elgamal等基础公钥密码算法。

2. CryptoTools：https://github.com/ladnir/cryptoTools
CryptoTools是一个可移植的c++14库，包含一系列用于构建加密协议的工具。这包括异步网络（Boost Asio），几个快速基元，如AES（AES-NI），Blake2（assembly），和 eliptic curve crypto（Relic-Toolkit，Miracl，或libsodium）。还有其他几个为实现协议而定制的实用程序。

3. ENCRYPTO_utils: https://github.com/encryptogroup/ENCRYPTO_utils
构建ABY和网络层的加密工具。
