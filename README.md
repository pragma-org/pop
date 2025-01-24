# PoP : Proof-of-Provenance

This project aims at building a solution to track critical software lifecycle on Cardano.

It is meant to provide two set of tools:

* [Off-chain](off-chain) untrusted services to track events happening on-chain, provide a nice user interface to summarize those, and tools to interoperate with code infrastructure ie. artifacts repository like [hackage](https://hackage.haskell.org/), [crates.io](https://crates.io), [Docker hub](https://hub.docker.com/) or [maven central](https://central.sonatype.com/),
* [On-chain](on-chain) smart contracts and associated tooling to enforce PoP rules on Cardano.

A somewhat detailed specification of PoP is [available](pop-specification.md).
