# Running a node (Lighthouse/Geth) on EIP-4844 devnet-7

Docker Compose setup for running a Lighthouse/Geth node on devnet v7. Builds docker images from EIP-4844 devnet-7 branches of Lighthouse and Geth.

## Run with Docker

```
docker-compose up
```

To rebuild images from the latest geth & lighthouse devnet-7 repos (required if you've previously used this repo to run earlier devnets):

```
docker-compose build --no-cache
```

## How to test

https://hackmd.io/@jimmygchen/H1XUtBIfn

## References 

- [4844-devnet76](https://4844-devnet-7.ethpandaops.io/)
- [Devnet-7 Spec](https://notes.ethereum.org/@parithosh/devnet-7-specs)
