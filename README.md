
SampleCoin Core
==============

https://cryptogera.com

What is SampleCoin?
------------------

Born on March 29, 2024 at 22:44:50 GMT, SampleCoin is an experimental digital currency of the Bitcoin family, which enables instant payments to anyone, anywhere in the world. It uses peer-to-peer technology to operate with no central authority: managing transactions and issuing money are carried out collectively by the network. SampleCoin Core is the name of open source software which enables the use of this currency.

SampleCoin has a maximum circulating supply of 84,000,000 SCO, which is four times larger than Bitcoin's maximum circulating supply of 21,000,000 BTC. It uses the Scrypt algorithm, just like the already popular Bitcoin family members: Litecoin and Dogecoin, thus making it compatible with the already existing cyptocurrency platform (developer code, mining software, mining pools, wallets, trading platforms) and mining hardware (CPU, GPU, ASIC).

For more information, as well as an immediately useable, binary version of the SampleCoin Core software, see [https://git.cryptogera.com/cryptogera/samplecoin/releases](https://git.cryptogera.com/cryptogera/samplecoin/releases).

TCP Ports
----------------

SampleCoin Core by default uses port `11683` for peer-to-peer communication that is needed to synchronize the "mainnet" blockchain and stay informed of new transactions and blocks. Additionally, a JSONRPC port can be opened, which defaults to port `11684` for mainnet nodes. It is strongly recommended to not expose RPC ports to the public internet.

| Function | mainnet | testnet | regtest |
| :------- | ------: | ------: | ------: |
| P2P      |   11683 |   10256 |   11406 |
| RPC      |   11684 |   10257 |   11407 |

License
-------

SampleCoin Core is released under the terms of the MIT license. See [COPYING](COPYING) for more information or see https://opensource.org/licenses/MIT.

