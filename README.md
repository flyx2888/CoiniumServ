[![CircleCI](https://circleci.com/gh/bonesoul/CoiniumServ.svg?style=svg)](https://circleci.com/gh/bonesoul/CoiniumServ) [![Documentation Status](https://readthedocs.org/projects/coiniumserv/badge/?version=latest)](https://readthedocs.org/projects/coiniumserv/?badge=latest)
 
**CoiniumServ** is a high performance, extremely efficient, platform-agnostic, easy to setup pool server implementation. It features stratum and vanilla services, reward, payment, share processors, vardiff & ban managers, user-friendly embedded web-server & front-end and a full-stack API.


### Buy package
You can buy a compiled version of [CoiniumServ here](https://satoshibox.com/uiewhcmyuwxfs35j5aiyfoec) if you are having difficulties doing so yourself. You can then just configure & run it.

[![Buy with Bitcoin](http://satoshibox.com/img/button-bitcoin.svg)](https://satoshibox.com/uiewhcmyuwxfs35j5aiyfoec)
[![Buy with Ethereum](http://satoshibox.com/img/button-ethereum.svg)](https://satoshibox.com/uiewhcmyuwxfs35j5aiyfoec)
[![Buy with Litecoin](http://satoshibox.com/img/button-litecoin.svg)](https://satoshibox.com/uiewhcmyuwxfs35j5aiyfoec)
[![Buy with Dash](http://satoshibox.com/img/button-dash.svg)](https://satoshibox.com/uiewhcmyuwxfs35j5aiyfoec)

**VirusTotal scan results**: [0/58 clean](https://www.virustotal.com/en/file/f03dd7753d6d209d99f6b5095d28f0f6d7b8a50067a3ce709009b87c727b980d/analysis/1510948542/)

##### Donations

CoiniumServ is an open-source project. Your donations will be a great help & motivation for the development of the project.

* BTC: `3H1Bg5pYJCX262spwyinkiQXzvh1bQuSLZ`
* BCH: `1FSfdMCH3z6hY8ELB3tDiZfpoKTZQ3Sq6y`
* ETH: `0xa31d781583c5dc2a4551f465092949174bac1871`
* LTC: `MPv7LseAAWLXNXujvrRiNF8Bbx7DtJKx5J`
* ZEC: `t1RH29LN5reAmiE3j6tNdRpfsCC7CJpUn8M`
* DASH: `Xr43BZo5yvGoHr98coskkYc4SioYwR1okw`

### Screenshots

##### Console

![CoiniumServ running over mono & ubuntu](http://i.imgur.com/HvaPVrZ.png)

##### Embedded web frontend

![Embedded web frontend](http://i.imgur.com/oOF8lQ0.png)

### Status

Latest release: [v0.2.6.2](https://github.com/flyx2888/CoiniumServ/releases/tag/0.2.6.2)
Development release: [v0.2.6.3](https://github.com/flyx2888/CoiniumServ/archive/develop.zip)

### Getting Started

Start by checking our [Getting Started](https://github.com/flyx2888/CoiniumServ/wiki/Getting-Started) guide for installation instructions for *nix and Windows.

### Documentation

* [Docs](http://coiniumserv.readthedocs.io/en/latest/)
* [Wiki](https://github.com/flyx2888/CoiniumServ/wiki/)
* [FAQ](https://github.com/flyx2888/CoiniumServ/wiki/FAQ)

### User Support

Start by reading our [FAQ](https://github.com/flyx2888/CoiniumServ/wiki/FAQ) and [wiki](https://github.com/bonesoul/CoiniumServ/wiki/). You can also use our [issues](https://github.com/flyx2888/CoiniumServ/issues) page to report bugs.

##### Discussions

* [Bitcointalk.org](https://bitcointalk.org/index.php?topic=604476.0)

### Support the project

You can support the development of this project with direct donations;

* BTC: `3H1Bg5pYJCX262spwyinkiQXzvh1bQuSLZ`
* BCH: `1FSfdMCH3z6hY8ELB3tDiZfpoKTZQ3Sq6y`
* ETH: `0xa31d781583c5dc2a4551f465092949174bac1871`
* LTC: `MPv7LseAAWLXNXujvrRiNF8Bbx7DtJKx5J`
* ZEC: `t1RH29LN5reAmiE3j6tNdRpfsCC7CJpUn8M`
* DASH: `Xr43BZo5yvGoHr98coskkYc4SioYwR1okw`

If you would like to automatically donate a percentage of your pool's earning to support the project, check the [donation setup](https://github.com/flyx2888/CoiniumServ/wiki/Donation) guide.

### Features
* __Platform Agnostic__; unlike other pool-servers, CoiniumServ doesn't dictate platforms and can run on anything including Windows, Linux or MacOS.
* __High Performance__; Designed to be fast & efficient, CoiniumServ can handle dozens of pools together.
* __Modular & Flexible__; Designed to be modular since day one so that you can implement your very own ideas.
* __Free & Open-Source__; Best of all CoiniumServ is open source and free-to-use. You can get it running for free in minutes.
* __Easy to Setup__; We got your back covered with our [guides & how-to's](https://github.com/flyx2888/CoiniumServ/wiki).

##### General

* Multiple pools & ports
* Multiple coin daemon connections
* Supports POW (proof-of-work) coins
* Supports POS (proof-of-stake) coins

##### Algorithms

* __Scrypt__, __SHA256d__, __X11__, __X13__, X14, X15, X17, Blake, Fresh, Fugue, Groestl, Keccak, NIST5, Scrypt-OG, Scrypt-N, SHA1, SHAvite3, Skein, Qubit, C11

##### Protocols

* Stratum
 * show_message support
 * block template support
 * generation transaction support
 * transaction message (txMessage) support
* Getwork [experimental]

##### Storage Layers

* Hybrid mode (redis + mysql)
* [MPOS](https://github.com/MPOS/php-mpos) compatibility (mysql)

##### Embedded Web Server

* Customizable front-end
* Full stack json-api

##### Addititional Features

* ✔ Vardiff support
* ✔ Ban manager (that can handle miners flooding with invalid shares)
* ✔ Share & Payment processor, Job Manager

### Development

##### Model

* We have implemented extensive [tests](https://github.com/flyx2888/CoiniumServ/tree/develop/src/Tests) for all important functionality and never merge in code that breaks tests and stuff. Yet again, when a new functionality is introduced we also expect proper tests to be implemented within the PR. In simple words, most probably you won't notice any functionality-breaking changes within the repository.
* A strict ruleset for the [Development Model](https://github.com/flyx2888/CoiniumServ/wiki/Development-Model). You can follow our bleeding-edge [Develop](https://github.com/bonesoul/CoiniumServ) branch or stay with-in the stable [Master](https://github.com/flyx2888/CoiniumServ/tree/master) branch.

##### Contributing

Start reading by these;

* [Developer's Guide](https://github.com/flyx2888/CoiniumServ/wiki/Developer's-Guide)
* [Technical Documentation](https://github.com/flyx2888/CoiniumServ/wiki/Technical-Documentation)

