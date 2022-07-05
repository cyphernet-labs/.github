## Best practices, standards and libraries for:
- Privacy-first networking
  * End-to-end encryption with Noise_XK on SECP256K1 curve
  * Leveraging mix networks (Tor today; I2P, Nym are WIP)
- Simplify building P2P networks – standalone or on top of Lightning network
- Doing distributed architectures in scalable and robust way
  * Microservice-based
  * Non-blocking services; async clients
  * Shared-nothing multithreading
  * Both mobile-ready/embeddable and cloud-ready with enterprise scaliability level

## Building blocks:
- Encoding: strict encoding (StEn) with schema, compiler
- Encryption: Noise_XK secp256k1 (Brontozaur)
- APIs: RPC-based binary schema-based messages with TLV extensions
- Networking: pure TCP or with ZeroMQ
- Addresses supporting TCP/IP, ZeroMQ, identities and encryption
- Extensions: via service buses build with microservices library or using AluVM virtual machine
