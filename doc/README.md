Groestlcoin Core 2.11.0
=====================

Setup
---------------------
[Groestlcoin Core](http://groestlcoin.org/download) is the original Groestlcoin client and it builds the backbone of the network. However, it downloads and stores the entire history of Groestlcoin transactions (which is currently several MBs); depending on the speed of your computer and network connection, the synchronization process can take anywhere from a half hour to a hour or more.

Running
---------------------
The following are some helpful notes on how to run Groestlcoin on your native platform. 

### Unix

You need the Qt4 run-time libraries to run Groestlcoin-Qt. On Debian or Ubuntu:

	sudo apt-get install libqtgui4

Unpack the files into a directory and run:

- bin/32/bitcoin-qt (GUI, 32-bit) or bin/32/bitcoind (headless, 32-bit)
- bin/64/bitcoin-qt (GUI, 64-bit) or bin/64/bitcoind (headless, 64-bit)



### Windows

Unpack the files into a directory, and then run groestlcoin-qt.exe.

### OSX

Drag groestlcoin-Qt to your applications folder, and then run groestlcoin-Qt.

### Need Help?

* Ask for help on [#groestlcoin](http://webchat.freenode.net?channels=groestlcoin) on Freenode. If you don't have an IRC client use [webchat here](http://webchat.freenode.net?channels=groestlcoin).
* Ask for help on the [BitcoinTalk](https://bitcointalk.org/) forums, in the [Alternate cryptocurrencies  board](https://bitcointalk.org/index.php?topic=525926.0).

Building
---------------------
The following are developer notes on how to build Groestlcoin on your native platform. They are not complete guides, but include notes on the necessary libraries, compile flags, etc.

- [OSX Build Notes](build-osx.md)
- [Unix Build Notes](build-unix.md)
- [Gitian Building Guide](gitian-building.md)

Development
---------------------
The Groestlcoin repo's [root README](https://github.com/groestlcoin/groestlcoin/blob/master/README.md) contains relevant information on the development process and automated testing.

- [Developer Notes](developer-notes.md)
- [Multiwallet Qt Development](multiwallet-qt.md)
- [Release Notes](release-notes.md)
- [Release Process](release-process.md)
- [Source Code Documentation (External Link)](https://dev.visucore.com/bitcoin/doxygen/)
- [Translation Process](translation_process.md)
- [Translation Strings Policy](translation_strings_policy.md)
- [Unit Tests](unit-tests.md)
- [Unauthenticated REST Interface](REST-interface.md)
- [Shared Libraries](shared-libraries.md)
- [BIPS](bips.md)
- [Dnsseed Policy](dnsseed-policy.md)

### Miscellaneous
- [Assets Attribution](assets-attribution.md)
- [Files](files.md)
- [Tor Support](tor.md)
- [Init Scripts (systemd/upstart/openrc)](init.md)

License
---------------------
Distributed under the [MIT software license](http://www.opensource.org/licenses/mit-license.php).
This product includes software developed by the OpenSSL Project for use in the [OpenSSL Toolkit](https://www.openssl.org/). This product includes
cryptographic software written by Eric Young ([eay@cryptsoft.com](mailto:eay@cryptsoft.com)), and UPnP software written by Thomas Bernard.
