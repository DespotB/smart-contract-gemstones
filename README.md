# smart-contract-gemstones

A small Solidity experiment: an ERC-721 NFT contract ("Gemesis") with whitelist/OG mint phases and a randomized mint order driven by Chainlink VRF.

> Small learning project from 2022 — not audited, not maintained. Do not use in production.

## Contents

- `contracts/gemesis.sol` — main ERC-721 contract (OpenZeppelin ERC721Enumerable + Ownable): whitelist and OG phases, reveal mechanic, randomized mint order
- `contracts/RandomNumberGenerator.sol` / `RandomNumberV2.sol` — Chainlink VRF integration for random numbers on-chain
