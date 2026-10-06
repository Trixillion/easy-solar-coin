EasySolarCoin (ESC)
===================

EasySolarCoin is an experimental, open-source proof-of-work cryptocurrency, forked from Litecoin Core v0.21.4. It is a hobby and learning project. It has no market value, no premine, and nothing in this repository is investment advice or an offer to sell anything.

Current parameters
------------------

- Ticker: ESC
- Algorithm: yespower 1.0 (N=2048, r=8, no personalisation string), a CPU-oriented proof of work
- Block time: 50 seconds
- Block reward: 40 ESC, halving every 3,150,000 blocks (about 5 years)
- Maximum supply: about 252 million ESC
- Premine: none
- Address prefixes: esc1... (bech32) and E... (legacy)
- Default ports: P2P 19733, RPC 19732
- Data directory: ~/.easysolarcoin

Status
------

The network is private and under development. The consensus rules, the algorithm and the difficulty adjustment may still change before any public launch.

This software is provided "as is", without warranty of any kind. ESC has no market value, and nothing here is a promise or expectation of value, profit or future listings.

Building
--------

See doc/build-unix.md for dependencies. On Ubuntu 22.04, run ./autogen.sh, then ./configure --without-gui --disable-tests --disable-bench --with-incompatible-bdb, then make -j4. The programs are built as src/escd, src/esc-cli, src/esc-tx and src/esc-wallet.

Credits and licence
-------------------

EasySolarCoin is based on Litecoin Core, which is in turn based on Bitcoin Core. Thanks to the Litecoin Core and Bitcoin Core developers. The original Litecoin README is kept in README-litecoin-original.md.

The yespower proof-of-work code is by Solar Designer (Openwall) and keeps its original licence headers in src/crypto/yespower.

This software is released under the terms of the MIT license. See COPYING for more information or see https://opensource.org/licenses/MIT. The original copyright notices must be kept.
