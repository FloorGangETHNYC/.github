# PEW

<p align="center">
<a href="https://github.com/FloorGangETHNYC/Pew-Core">
<img src="https://github.com/FloorGangETHNYC/.github/blob/main/profile/diagrams/PewLogo.png" width=200/>
</a>

## Description

PEW is an new and innovative DAO governance system that solves the voting power inequality from current token-based governance systems by introducing an on-chain, reputation based score for voting power. Individuals have to self-declare their contributions to the DAO which are either vouched or refuted via Upvoting or downvoting respectively. The overall voting power an individual would have will be:

$A * Time\ Spent\ In\ DAO * B * Total\ Number\ Of\ Upvotes * C * Total\ Number\ Of\ Downvotes * D * Total\ Number\ Of\ Reviews\ Given$

where A, B, C, and D are customizable weights.

The framework that has been deployed easily allows new DAOs to be formed with a click of a button using a factory contract that deploys soulbound NFT collections.

🌐 Website: <https://pew-frontend.vercel.app/>

🖥️ Frontend: <https://github.com/FloorGangETHNYC/Pew-Frontend>

💡 Backend: <https://github.com/FloorGangETHNYC/Pew-Core>

📑 Deck: [Deck](https://github.com/FloorGangETHNYC/.github/blob/main/profile/resources/Pew_DAO_Information_Deck.pdf)

🧭 Architecture:

![smart-contract-architecture.drawio.svg](https://github.com/FloorGangETHNYC/.github/blob/main/profile/diagrams/smart-contract-architecture.drawio.svg)

![smart-contract-interfaces.drawio.svg](https://github.com/FloorGangETHNYC/.github/blob/main/profile/diagrams/smart-contract-interfaces.drawio.svg)

User Flow:

![user-flow](https://github.com/FloorGangETHNYC/.github/blob/main/profile/diagrams/user-flow.drawio.svg)

## Integrations

### Polygon

Deployed on Mumbai

```txt
PewCore: 0x3EbC54416FB8044E6246869d07A8cCe0BB19562c
PewNFTFactory: 0x4d56418C64853346e0E1b730029a2e6dC9b22313
```

### Optimism

Deployed smart contract without proof of humanity by WorldId on Optimistic Kovan

```txt
PewCore: 0x8fc514Fbbe46945932817ceCC2E2abc1Bc59539e
PewNFTFactory: 0x0f5E5A00c2fE59147BB4B2dA7976e6D4e8ae5057
```

### WalletConnect

Frontend

### Tatum

Frontend

### WorldId

Frontend and PewCore Smart Contract on Polygon Testnet

### IPFS

Storing Images of NFTs on IPFS

### Storj

Storing Images of the NFTs using Storj

### Opensea / NFts in General

NFTs are used as proof of membership of the DAO and governance score is associated to the NFTs.

NFTs are on-chain and are upgradeable based on the governance score (GS).

![ranks.png](https://github.com/FloorGangETHNYC/.github/blob/main/profile/diagrams/Ranks.png)

Contributions statements by users are also tagged to the NFTs. The IPFS Hash of the contribution is stored on chain.
