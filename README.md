# awesome-bitcoin-sv [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
> A curated list of Bitcoin SV services and tools for developers.

Bitcoin SV is the original Bitcoin, so [awesome-bitcoin](https://github.com/igorbarinov/awesome-bitcoin) is referred.

What is Bitcoin SV?

Bitcoin Satoshi Vision (SV) is the Bitcoin that follows the original design and stable protocol of Satoshi Nakamoto’s white paper. By achieving the original on-chain scaling vision, BSV aims to become the peer to peer electronic cash and value transmission network for global use.

More info [here](https://bitcoinsv.io).

## Contents

- [MetaNet](#metanet)
- [Libraries](#libraries)
- [Projects](#projects)
- [Infrastructure](#infrastructure)
- [Powered by](#powered-by)
- [Talks & Blogs](#talks--blogs)
- [Community](#community)
- [Tutorials](#tutorials)

<!-- /MarkdownTOC -->

<a name="metanet" />

## MetaNet
### Introductions
- [Technical Summary from nChain](https://drive.google.com/viewerng/viewer?url=https://nchain.com/app/uploads/2019/06/The-Metanet-Technical-Summary-v1.0.pdf)
- [The Metanet Starts](https://medium.com/@_unwriter/the-metanet-starts-84f255a65782)
- Edge Cases: The Metanet Blog [Part1](https://medium.com/nchain/edge-cases-the-metanet-blog-41b608c8fe67) [Part2](https://medium.com/nchain/edge-cases-the-metanet-blog-92f43c48490d) [Part2.1](https://medium.com/nchain/edge-cases-the-metanet-blog-c0e794d1c9c5)
- some CSW's blog about [metanet](https://medium.com/@craig_10243/the-start-of-metanet-ef0560e81505). see also [1](https://medium.com/@craig_10243/p2p-and-returning-ip-and-domain-based-transfers-9943d32bd38e) [2](https://medium.com/@craig_10243/bitcoin-as-the-base-layer-cff28c5dab9c) [3](https://medium.com/@craig_10243/ipv6-with-cga-and-bitcoin-a761d0185d5d) [4](https://medium.com/@craig_10243/the-secure-bitcoin-internet-2f589d81890f) [5](https://medium.com/@craig_10243/nsequence-and-p2p-exchange-9e4cbf32124c)
### Applications
#### Social Media
- [Twetch](https://twetch.app/) - An on-chain twitter.
- [WeiBlock](https://weiblock.app) - An on-chain microblog.
- [Poster.cash](https://poster.cash) - Social network client using the Memo protocol. It's powered by Bitdb and only communicates with a Bitdb node.
- [MetaTalk](https://metatalk.io/) - An on-chain chatroom, with multiple channels.
- [BitStagram](https://bitstagram.bitdb.network/) -  Share pictures and get tips.
- [Yours](https://www.yours.org/) - A social network where you can earn Bitcoin SV if you create value.
#### Storage
- [Bitsent](http://bitsent.net/) -  Easily share encrypted immutable files.
- [BitPaste](https://www.bitpaste.app/) - Store and share plain text snippets on the Bitcoin (SV) blockchain.
- [CryptoGraffiti](https://cryptograffiti.info/) - Store text/files on-chain. [Introduction](https://cryptograffiti.info/#d1e9e0047fca4f49ef9e36e422677a52e45379928cfe1f8262223362b70cd0be).
- [BitDiary](https://bico.media/6c0fd6bc82865d65ca888b8f4532336c3c018745c4f53c591407d74f3e03c5fb) - An on-chain diary.
#### Service & Tool
- [Dir.sv](https://dir.sv/) - An open source way to make money from organizing links on the blockchain.
- [etched](https://etched.page/) - An internet archive tool that permanently timestamps and stores web pages and images directly onto bitcoin itself.
- [PageShot](https://pageshot.bitcoinsv.si/) - Generate image from URL and store it in blockchain.
- [Codeonchain](http://codeonchain.network/) - Upload a repository to metanet.
#### Commerical
- [CityOnChain](http://cityonchain.com/) - City album.
- [SporeStack](https://sporestack.com) - Launch VPS servers for Bitcoin SV. API-driven.
- [audioB](https://www.audiob.app/) -  Discover and share original audio created by independent music producers, podcasters, DJs and more.
#### Others & Demos
- Game on Chain - [Mechine Learning](https://bico.media/7a304727ff7fc11916d281118a270e7faea5f48a03713f250ea416109a082593)  [Piano](https://bico.media/0a68bb439a78ab5a721f0a139abedcbe0259f7f050fbba2ebed6006bb953bd5e)  [Tetris](https://bico.media/14734bc19a533ab6c510ebd419ad1e980603b1f62084b3f24b7c3d440ec6bfea)
- Application on Chain - [Wish](https://bico.media/047df3e724ca92004e4d1f324d02e3b6f86bb5de46a6f33c210d2aefd94182d5)  [BeeSV](https://bico.media/e701a8d3e70f0542ace1503b1a660aa0a685dfad9151f5fecc82d9a919bf5603)
- Content on Chain - [Video](https://bico.media/6589ea97bc1bd74ddd782c122594e711d12efed5eac85ccbae432689b9008c4c) [Shem's album](https://bico.media/0f11d8e04040d75d7551badc6e5d0d2e5a88e224d34a4952583ee7d0d83e75c7)
- [BitChat](https://bitchat.bitdb.network/) - An on-chain chatroom, free for now.
- [BSV Controlled Device](https://www.twitch.tv/bsvcontrol) - Control the LEDs with an payment tx.
- [TxGun](https://github.com/gitzhou/bsv-tx-gun) - A stress test prototype.
- Onchain Blog - [Monkeylord's Blog](https://bico.media/455128ddc7aa80efbbfef71c6db2b3a44c54a6856af9b708c3e897f000d074eb)

<a name="libraries" />

## Libraries
- [Bitcoin SV Lib](https://github.com/moneybutton/bsv) - A pure and powerful JavaScript Bitcoin SV library. A fork of BitPay's bitcore-lib-cash, but for Bitcoin SV only. Maintained by Yours Inc.
- [bitcoinj-sv](https://gitlab.com/bitcoinj-sv/bitcoinj-sv/) - The bitcoinj-sv library is a Java implementation of the Bitcoin SV protocol. This library is a fork of Mike Hearn's original bitcoinj library aimed at supporting Bitcoin SV.
- [BitSV](https://github.com/AustEcon/bitsv) - An easy-to-use Python 3, Bitcoin SV library.
- [Electrum Client](https://github.com/you21979/node-electrum-client) - Electrum Protocol Client for Node.js.
- [bitcoinfilesjs](https://github.com/simpleledger/bitcoinfilesjs) - A JavaScript Library for building transactions for Bitcoin Files Protocol (BFP). [SDK](https://github.com/BitcoinFiles/bitcoinfiles-sdk)
- ECIES - Encrypt message with Bitcoin PublicKey, decrypt it with PrivateKey. BIE1 format, Electrum/Electron Cash Compatible. [JavaScript](https://github.com/monkeylord/electrum-ecies)/[Go](https://github.com/gitzhou/bitcoin-ecies)

<a name="projects" />

## Projects
- [BitSocket](https://bitsocket.org) - Message Bus for Bitcoin.
- [B Protocol](https://github.com/unwriter/B) - Bitcoin Simple Storage Protocol. [Try it](https://b.bitdb.network)
- [Datapay](https://github.com/unwriter/datapay) - Build and broadcast data transactions to the Bitcoin SV blockchain.
- [Planaria](https://planaria.network/) - Infinite API over Bitcoin.
- [paymail](https://github.com/bitcoin-sv-specs/paymail) - BSV paymail protocol. [express implementation](https://github.com/moneybutton/express-paymail) [client](https://github.com/moneybutton/paymail-client)
- [bottle](https://github.com/interplanaria/bottle) - A bitcoin browser.
- [BSV Editor](http://www.bowmain.co.uk/BSV/index.html) - A Bitcoin script compiler/debugger with GUI.

<a name="infrastructure" />

## Infrastructure
- Gateways - Browse/Upload metanet content. [Bico.Media](https://bico.media/) [Bitcoinfiles](https://www.bitcoinfiles.org/) [Bitpaste](https://www.bitpaste.app/)
- [miniGate](https://github.com/monkeylord/MiniGate) - launch your personal light-weight gateway.
- [BitDB](https://bitdb.network/) - An autonomous database that continuously synchronizes itself with Bitcoin. See [planaria](https://docs.planaria.network/).
- [BitBus](https://bitbus.network/) - Build your app or a smart wallet backend without running a Bitcoin full node.
- Search Engines - [Oyo](https://oyo.cash/) [trends](https://trends.cash/)
- [BitIndex](http://www.bitindex.network/) - Easily query utxo's and wallet balances from a simple API.

<a name="powered-by" />

## Powered by
- [Money Button](https://www.moneybutton.com/) - A digital currency payments button for websites and apps.
- [Tokenized](https://tokenized.cash/) - A comprehensive platform that makes it easy for users to issue, manage and trade security and utility tokens controlled by low-cost and secure smart contracts.


<a name="talks--blogs" />

## Talks & Blogs
- [Set in stone](https://medium.com/@craig_10243/set-in-stone-7ebc9d31500e)
- [The resolution of the Bitcoin Cash experiment](https://medium.com/@_unwriter/the-resolution-of-the-bitcoin-cash-experiment-52b86d8cd187)
- [Craig S Wright](https://medium.com/@craig_10243)
- [unwriter](https://medium.com/@_unwriter)

<a name="community" />

## Community
- [Metanet-ICU](https://metanet.icu/)
- [unwriter's slack](https://www.bitdb.network/atlantis)
- [Craig S Wright on Twitter](https://twitter.com/proffaustus)
- [Reddit](https://www.reddit.com/r/bitcoinsv)
- [Another Reddit](https://www.reddit.com/r/bitcoincashsv)

<a name="tutorials" />

## Tutorials
- [bitcoins  the hard way: Using the raw Bitcoin protocol](http://www.righto.com/2014/02/bitcoins-hard-way-using-raw-bitcoin.html)
- [BSV Planaria框架技术总结一 节点搭建](https://zhuanlan.zhihu.com/p/64697171)
- [BSV Planaria框架技术总结二 Bitquery](https://zhuanlan.zhihu.com/p/64796784)

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Monkeylord](https://github.com/monkeylord/) has waived all copyright and related or neighboring rights to this work.

