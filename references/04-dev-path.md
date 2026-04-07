# Developer Path

## Who This Is For

Use this file when the user wants to build, debug, or understand the technical stack behind Web3 apps.

## Core Concepts To Teach

- `EVM`: the execution environment used by Ethereum and many compatible chains
- `RPC`: the endpoint an app uses to read chain state or submit transactions
- `ABI`: the interface description that lets apps call contracts
- `wallet connection`: how a frontend asks a wallet to provide an address or sign data
- `indexing`: turning raw chain events into queryable app data

## Practical Learning Order

1. Learn basic JavaScript or TypeScript if needed.
2. Understand addresses, signatures, transactions, and networks.
3. Learn Solidity basics:
   - state
   - functions
   - events
   - access control
   - token standards like ERC-20 and ERC-721
4. Learn local testing and deployment on testnet.
5. Build a tiny frontend that:
   - connects a wallet
   - reads a balance
   - calls a contract read method
   - submits one safe write transaction on testnet

## Suggested Tooling

- `Solidity`: contract language for EVM chains
- `Foundry` or `Hardhat`: contract development and testing
- `viem` and `wagmi`: modern TypeScript tools for frontend + wallet interaction
- `ethers`: common contract interaction library, still widely used
- `OpenZeppelin`: standard contracts and security patterns
- block explorers and official docs for contract verification

## Minimum Demo Project

Build a testnet app with:

1. Wallet connect
2. Display current chain and address
3. Read an ERC-20 balance
4. Send a testnet token transfer
5. Show transaction hash and explorer link

This project teaches the full loop without exposing real capital.

## Common Builder Pitfalls

- confusing wallet signatures with transactions
- hardcoding the wrong chain ID
- assuming all EVM chains have identical costs and support
- storing secrets in frontend code
- skipping input validation on contract writes
- ignoring approval risk in token flows

## Security Mindset For Builders

- use battle-tested libraries first
- test unhappy paths, not just happy paths
- add clear transaction previews in the UI
- explain what users are signing
- prefer least-privilege approvals where possible

## When The User Asks For A Roadmap

Recommend:

1. one week on wallet and chain basics
2. one week on Solidity and contract testing
3. one week on frontend wallet integration
4. one week on building and deploying a tiny testnet dApp

Keep the first milestone small enough to finish.
