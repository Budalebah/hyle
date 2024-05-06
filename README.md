# Hylé - your minimal layer one, focused only on verifying zero-knowledge proofs.

Repository for the [Hylé](https://hyle.eu) proof of concept chain.

Forked from [mini](https://github.com/cosmosregistry/chain-minimal) - the minimal Cosmos SDK chain.

**Current status**: proof of concept.

We plan to support all major proving schemes. Proving systems currently supported:
 - [x] Risc Zero
 - [x] Groth16
 - [ ] Cairo
   - [ ] Starknet
 - [ ] SP1
 - [ ] PlonK

### Installation

Install and run:

```sh
git clone git@github.com:hyle-org/hyle.git
cd hyle
make build # builds the `hyled` binary
make init # initialize the chain
./hyled start # start the chain
```

## Useful links

* [Hylé website](https://www.hyle.eu/)
* [Hylé documentation](https://docs.hyle.eu)
* [Cosmos-SDK Documentation](https://docs.cosmos.network/)
