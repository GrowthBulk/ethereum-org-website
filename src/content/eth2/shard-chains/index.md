---
title: Shard chains
description: Everything you need to know about shard chains
lang: en
sidebar: true
---

# Scaling and shard chains

<Subtitle>Shard chains are Eth2's answer to the scaling problem. They'll turn Ethereum into a super highway of interconnected blockchains. </Subtitle>

## What is a shard chain?

A shard chain is like a parallel blockchain that takes on some of the processing work.

They are inspired by sharded databases, which scalability by spreading the load of a database across multiple instances. In other words, sharding increases the number of actors in the network to scale.

Right now, all nodes in the Ethereum network must download, compute, store and read every transaction in the history of Ethereum before processing a new one. It's no surprise that it can only process ~15 transactions per second.

If your computer is processing transactions on a shard chain, it only needs to download, compute, store and read every transaction on that shard. This is far less work.

With many shards processing transactions in parallel, it's the job of the beacon chain to make sure they're all in sync.

## What's the beacon chain?

The beacon chain has a huge role in Eth2. It will coordinate the shards and their validators to make sure Ethereum is fast, yet still secure and decentralized.

In more detail the beacon chain will:

- manage validators and their stakes
- nominate the chosen block proposer for each shard at each step
- organize validators into committees to vote on the proposed blocks
- apply the consensus rules
- apply rewards and penalties to validators
- be an anchor point on which the shards register their states to facilitate cross-shard transactions.

_Source: Ben Edgington via [ETHHub](https://docs.ethhub.io/ethereum-roadmap/ethereum-2.0/eth-2.0-phases/)_

The beacon chain will slowly become more important as each new phase of Eth2 is rolled out.

<Button to="/eth2/the-beacon-chain/">More on the beacon chain</Button>

You can help ensure a smooth rollout by helping [test beacon chain clients](/en/eth2/get-involved#go-bug-hunting/).

You'll just need to run software that processes and validates test transactions on the Eth2 testnets.

## See when shards are coming

For more information on the rollout of sharding, check out the roadmap.

<Button to="/eth2/roadmap/">View the roadmap</Button>