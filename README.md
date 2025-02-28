# CryptoDeepTools

Crypto Deep Tools a set of scripts for detailed cryptanalysis of the Blockchain network in cryptocurrency Bitcoin


## [01BlockchainGoogleDrive](https://github.com/demining/CryptoDeepTools/tree/main/01BlockchainGoogleDrive)

* Parsing Blockchain in Google Drive

* Tutorial: https://youtu.be/ECAPypsmMQs
* Tutorial: https://cryptodeep.ru/blockchain-google-drive

---

## [02BreakECDSAcryptography](https://github.com/demining/CryptoDeepTools/tree/main/02BreakECDSAcryptography)

* Analyze the data from the file "RawTX.json". Script breakECDSA.py reconstructs the unsigned message for each to find the Z value. The result is returned as R, S, Z, PUBKEY for each of the inputs present in the data in the "RawTX.json" file.

* Tutorial: https://youtu.be/BYd-cuFRZmM
* Tutorial: https://cryptodeep.ru/break-ecdsa-cryptography

---

## [03CheckBitcoinAddressBalance](https://github.com/demining/CryptoDeepTools/tree/main/03CheckBitcoinAddressBalance)

* Check Bitcoin Address Balance: Script pubtoaddr.py Converts PUBKEY (HEX) to Bitcoin Address (Base58) // Script bitcoin-checker.py Checks the balance by scanning the Blockchain

* Tutorial: https://youtu.be/Hsk6QIzb7oY
* Tutorial: https://cryptodeep.ru/check-bitcoin-address-balance

---

## [04AlgorithmsForSecp256k](https://github.com/demining/CryptoDeepTools/tree/main/04AlgorithmsForSecp256k)

* Useful and Efficient Elliptic Curve Algorithms secp256k1

- [ ] **Algorithm for generating a point on the curve _E_**
- [ ] **Algorithm for adding points**
- [ ] **Point doubling algorithm**
- [ ] **Algorithm for finding the integer multiple point**
- [ ] **Algorithm for finding an integer multiple point (Scalar multiplication)**
- [ ] **Algorithm for generating a divisor _D_ over a curve _E_ with a carrier _supp(D)_ of a given size _d_**
- [ ] **Miller's algorithm for calculating the value of the Weil function _f<sub> n, P</sub>_ from a divisor _D_ such that** _supp(D)_ ∩ {P, O} = ∅
- [ ] **Weil pairing**
 
* Tutorial: https://youtu.be/gFbiBCNPsFk
* Tutorial: https://cryptodeep.ru/algorithms-for-secp256k

---

## [05VulnerableOpenSSL](https://github.com/demining/CryptoDeepTools/tree/main/05VulnerableOpenSSL)

* Vulnerable to Debian OpenSSL bug (CVE-2008-0166)

* Tutorial: https://youtu.be/zHkXups2I8k
* Tutorial: https://cryptodeep.ru/vulnerable-openssl

---

## [06KangarooJeanLucPons](https://github.com/demining/CryptoDeepTools/tree/main/06KangarooJeanLucPons)

* Pollard's kangaroo method computes discrete logarithms in arbitrary cyclic groups. It is applied when the discrete logarithm is known to lie within a certain range, say [ a , b ], and then has the expected time to execute the bulk operation. One way to break ECDSA signature schemes is to solve the discrete logarithm problem.

* Tutorial: https://youtu.be/UGUJyxOhBBQ
* Tutorial: https://cryptodeep.ru/kangaroo

---

## [07EndomorphismSecp256k1](https://github.com/demining/CryptoDeepTools/tree/main/07EndomorphismSecp256k1)

* Secp256k1 acceleration function using endomorphism which helps in optimizing ECDSA validation for bitcoin cryptocurrency.

* Tutorial: https://youtu.be/DH6FyNY-Gh0
* Tutorial: https://cryptodeep.ru/endomorphism

---

## [08ReducePrivateKey](https://github.com/demining/CryptoDeepTools/tree/main/08ReducePrivateKey)

* In this repository, we will use scripts that will help reduce the private key knowing only the leak from the "BLOCKCHAIN FOLBIT LEAKS" list and the public key from "UTXO".

* Tutorial: https://youtu.be/zu2yiaZ_LOs
* Tutorial: https://cryptodeep.ru/reduce-private-key

---

## [09BitcoinWalletRecovery](https://github.com/demining/CryptoDeepTools/tree/main/09BitcoinWalletRecovery)

* We all know that the disclosure of the private key in the ECDSA signature can lead to the complete recovery of the Bitcoin Wallet. In our earlier articles, we looked at weaknesses and vulnerabilities in blockchain transactions, but there are also ECDSA short signatures that also lead to the full recovery of a Bitcoin Wallet.

* Tutorial: https://youtu.be/xBgjWE5tA7Y
* Tutorial: https://cryptodeep.ru/shortest-ecdsa-signature

---

## [10MrRobotQR](https://github.com/demining/CryptoDeepTools/tree/main/10MrRobotQR)

* MrRobotQR is an open source script that automates the process from entering a search keyword to deriving the private key of a Bitcoin wallet. 

* Tutorial: https://youtu.be/bNMg2iJhMpg
* Tutorial: https://cryptodeep.ru/mr-robot-qr

---

## [11QianshiBTC](https://github.com/demining/CryptoDeepTools/tree/main/11QianshiBTC)


* QBitcoin Address Collision Finder

* Tutorial: https://youtu.be/KqJcPSIZ5RM
* Tutorial: https://cryptodeep.ru/quantum-computer-qianshi

---

## [12CoingeckoAgentFtpupload](https://github.com/demining/CryptoDeepTools/tree/main/12CoingeckoAgentFtpupload)


* Coingecko-VanityGen is a command-line utility that can generate cryptocurrency addresses given initial parameters.
Coingecko-VanityGen works with GPU runtime support (Google Colab) and generates beautiful crypto wallet addresses for the full list of the Coingecko aggregator according to its own parameters. The selection of the utility is based on a probabilistic search, which takes some time. The time depends on the complexity of the given template, computer speed and luck. To increase the speed of generating cryptocurrency addresses, there is oclvanitygen - which uses OpenCL-compatible GPUs.

* Tutorial: https://youtu.be/sB91EE-1mJo
* Tutorial: https://cryptodeep.ru/coingecko-agent-ftpupload

---

## [13TeslaBrainWallet](https://github.com/demining/CryptoDeepTools/tree/main/13TeslaBrainWallet)


* There are many forms to create a Bitcoin wallet. One of the first methods to create a Bitcoin wallet was known as BrainWallet. BrainWallet is convenient in the sense that it allows you to store a "passphrase" in memory or in a notebook. The passphrase is hashed using the SHA-256 algorithm, and is used as the seed to generate the private key. Due to its popularity and ease of use, many BrainWallets over the past few years have been used with weak passphrases. This weak private key generation method allowed attackers to steal quite a lot of BTC coins by simply cracking the password against the hashes stored on the blockchain. Let's move on to the experimental part:

* Tutorial: https://youtu.be/r0fTtBDWTnw
* Tutorial: https://cryptodeep.ru/tesla-brainwallet

---



|  | Donation Address |
| --- | --- |
| ♥ __BTC__ | 1Lw2kh9WzCActXSGHxyypGLkqQZfxDpw8v |
| ♥ __ETH__ | 0xaBd66CF90898517573f19184b3297d651f7b90bf |
