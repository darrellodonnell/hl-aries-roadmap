
ACA-py - BC Gov led - Is this the MVP (or v1.0 Aries Interop)?

* https://github.com/hyperledger/aries-cloudagent-python/blob/master/SupportedRFCs.md

## Aries RFC Concepts

- [0003-protocols](https://github.com/hyperledger/aries-rfcs/tree/master/concepts/0003-protocols) 
- [0004-agents](https://github.com/hyperledger/aries-rfcs/tree/master/concepts/0004-agents)
- [0005-didcomm](https://github.com/hyperledger/aries-rfcs/tree/master/concepts/0005-didcomm)
- [0008-message-id-and-threading](https://github.com/hyperledger/aries-rfcs/tree/master/concepts/0008-message-id-and-threading) (post v1)
- [0011-decorators](https://github.com/hyperledger/aries-rfcs/tree/master/concepts/0011-decorators) (post v1)
- [0017-attachments](https://github.com/hyperledger/aries-rfcs/tree/master/concepts/0017-attachments)
- [0020-message-types](https://github.com/hyperledger/aries-rfcs/tree/master/concepts/0020-message-types)
- [0046-mediators-and-relays](https://github.com/hyperledger/aries-rfcs/tree/master/concepts/0046-mediators-and-relays)
- [0047-json-LD-compatibility](https://github.com/hyperledger/aries-rfcs/tree/master/concepts/0047-json-ld-compatibility) REQUIRED?
- [0050-wallets](https://github.com/hyperledger/aries-rfcs/tree/master/concepts/0050-wallets) Is this needed v1 (i.e. don't we have working wallets?)
- [0094-cross-domain messaging](https://github.com/hyperledger/aries-rfcs/tree/master/concepts/0094-cross-domain-messaging) v1.1?


What are the versions about is v1 about?
* v1.0 Basic ability for Agents from different codebases but same base network to communicate and exchange. Limitations & Expectations
    * Wallets are system implemented and not generic.
    * Protocols won't be discoverable - if an Agent from one system is expecting to work with an Agent from another system it will need to support the protocols and work (out of band) together to define these.
    * 
* v1.1 Multi-Network 
* ...
* v2.0 
