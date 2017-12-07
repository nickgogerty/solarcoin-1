SolarCoin Core 0.14.2
=====================

Setup
---------------------
SolarCoin Core is the original SolarCoin client and it builds the backbone of the network. However, it downloads and stores the entire history of SolarCoin transactions (which is currently several GBs); depending on the speed of your computer and network connection, the synchronization process can take anywhere from a few hours to a day or more.

To download SolarCoin Core, visit [solarcoin.org](https://solarcoin.org).

Running
---------------------
The following are some helpful notes on how to run SolarCoin on your native platform.

### Unix

Unpack the files into a directory and run:

- `bin/solarcoin-qt` (GUI) or
- `bin/solarcoind` (headless)

### Windows

Unpack the files into a directory, and then run solarcoin-qt.exe.

### OS X

Drag SolarCoin-Core to your applications folder, and then run SolarCoin-Core.

### Need Help?

*ask for help by signing up to Solarcoin-group slack https://solarcoin.org/en/solarcoin-forum

Building
---------------------
The following are developer notes on how to build SolarCoin on your native platform. They are not complete guides, but include notes on the necessary libraries, compile flags, etc.

- [OS X Build Notes](build-osx.md)
- [Unix Build Notes](build-unix.md)
- [Windows Build Notes](build-windows.md)
- [OpenBSD Build Notes](build-openbsd.md)
- [Gitian Building Guide](gitian-building.md)

Development
---------------------
The SolarCoin repo's [root README](/README.md) contains relevant information on the development process and automated testing.

- [Developer Notes](developer-notes.md)
- [Release Notes](release-notes.md)
- [Release Process](release-process.md)
- [Source Code Documentation (External Link)](https://dev.visucore.com/solarcoin/doxygen/)
- [Translation Process](translation_process.md)
- [Translation Strings Policy](translation_strings_policy.md)
- [Travis CI](travis-ci.md)
- [Unauthenticated REST Interface](REST-interface.md)
- [Shared Libraries](shared-libraries.md)
- [BIPS](bips.md)
- [Dnsseed Policy](dnsseed-policy.md)
- [Benchmarking](benchmarking.md)

### Resources
* Discuss general SolarCoin development on #solarcoin-dev on Freenode. If you don't have an IRC client use [webchat here](http://webchat.freenode.net/?channels=solarcoin-dev).

### Miscellaneous
- [Assets Attribution](assets-attribution.md)
- [Files](files.md)
- [Fuzz-testing](fuzzing.md)
- [Reduce Traffic](reduce-traffic.md)
- [Tor Support](tor.md)
- [Init Scripts (systemd/upstart/openrc)](init.md)
- [ZMQ](zmq.md)

License
---------------------
Distributed under the [MIT software license](/COPYING).
This product includes software developed by the OpenSSL Project for use in the [OpenSSL Toolkit](https://www.openssl.org/). This product includes
cryptographic software written by Eric Young ([eay@cryptsoft.com](mailto:eay@cryptsoft.com)), and UPnP software written by Thomas Bernard.
