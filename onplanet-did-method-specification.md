# onPlanet DID Method Specification
v0.1, Patrick Hays, onPlanet
## Introduction

## Ethereum Smart Chain and Smart Contracts

## Overview

onPlanet uses a network of ERC721 and ERC1155 token contracts, NFTs, and DIDs to enable users to store, share, and control content with others.

## Method Format

- method-name: `onplanet`
- method-specific-id: `chainID`:`contractAddress`:`tokenID`
- `chainID`: The numerical blockchain ID registered with [Whereever].
- `contractAddress`: The contract address of the desired entity.
- `tokenID` (optional): The specific ERC721 or ERC1155 token ID stored on the `contractAddress`.

Binance Smart Chain: `did:onplanet:56:...`

BSC TestNet: `did:onplanet:97:...`
