# Borker

Borker Protocol is an application layer protocol designed to ride on top of the Bitcoin p2p network and similar UTXO-based, transparent blockchains. It relies on the openess, security, and immutability of the underlying networks to defines a method of publishing and consuming unstoppable content.

Borker is an implementation of the Borker Protocol. It uses:

- [Dogecoin](https://github.com/dogecoin/dogecoin): The p2p blockchain network. 
- [Superdoge](https://github.com/borkerprotocol/superdoge-rs): A thin wrapper for Dogecoin for indexing utxos by address.
- [Borker-Server](https://github.com/borkerprotocol/borker-server): Indexing service and REST API for transactions conforming to the Borker Protocol. Depends on Superdoge or similar.
- [Borker-Wallet](https://github.com/borkerprotocol/borker-wallet): a Twitter-like PWA (Progressive Web Application) and crypocurrency wallet for connecting to Borker-Server to view and publish content.
- [Borker-Lib](https://github.com/borkerprotocol/borker-lib): Library for cryptographic operations and serialization/deserialization of Borker data. Used in both Borker-Server and Borker-Wallet.
- [Borker-Registry](https://github.com/borkerprotocol/borker-registry): Registry service for delegating server choice bootstrapping and network load balancing. Used by Borker-Server to discover Superdoge nodes. Used by Borker-Wallet to dicover Borker-Servers.

## The Docs

- View the [Protocol Specification](https://github.com/borkerprotocol/docs/blob/master/protocol-specification.md).

- View and contribute to the [Wiki](https://github.com/borkerprotocol/docs/wiki)
