# Happy Ticket 🎟️  
A Web 2.5 NFT-ticketing MVP

## Overview
Happy Ticket is a digital ticketing platform that combines traditional web usability with blockchain ownership on Ethereum Sepolia. 
Users can purchase and own digital tickets without managing crypto wallets or gas fees directly.

## Core Functionality
The platform operates through a three-step process:
1. Social login automatically creates a custodial wallet from social media credentials
2. Standard payment methods purchase vouchers with subsidized gas costs
3. Vouchers convert to ERC-721 NFT tickets for permanent ownership

This approach provides artists and promoters with on-chain analytics while eliminating paper waste.

## Why Web 2.5?
Traditional NFT ticketing offers anti-fraud protection and permanent ownership records, but Web 3.0 user experience barriers like wallet management and gas fees create adoption challenges. 
Happy Ticket addresses this by providing familiar Web 2.0 interfaces while maintaining Web 3.0 ownership benefits.

## Architecture
```text
React
│
│  REST / JWT
▼
Nginx ── Node.js API ── MariaDB
│                       ▲
│ mintTicket()          │
▼                       │
Ethereum Sepolia ◀──────┘  (Truffle + Solidity)
```

## Live Demo (GIF)

<p align="center">
<img src="https://github.com/bstream0138/likelion_0x02_ticket/assets/95029317/c9401718-0026-405c-bd41-2b8599e1268c" width="240" height="628">
</p>

