# Web3 Basics

## Mental Model

- `区块链`: a shared ledger replicated across many machines.
- `钱包`: a key manager that controls addresses and signatures. Assets are recorded on-chain, not "stored inside" the wallet app.
- `地址`: the public identifier others can send assets to.
- `私钥 / 助记词`: the secret that controls the address. Whoever has it can move assets.
- `签名`: proof that the holder of a private key approved an action.
- `Gas`: the fee paid to the network to process a transaction.
- `智能合约`: code deployed on-chain that users and other contracts can call.

## Explain These Early

- `公链`: a blockchain anyone can inspect and usually anyone can use.
- `L1`: the base chain, such as Ethereum.
- `L2`: a network built to scale an L1, often cheaper and faster.
- `稳定币`: tokens designed to stay near a fiat price such as 1 USD.
- `交易所`: a service for buying, selling, or swapping assets. Distinguish centralized exchanges from on-chain decentralized exchanges.
- `DeFi`: on-chain financial applications such as swaps, lending, and staking.
- `NFT`: non-fungible token, usually used for unique items, memberships, or collectibles.

## Beginner-Friendly Analogies

- Wallet app -> keychain
- Address -> bank account number
- Private key / seed phrase -> master password plus legal ownership
- Gas -> network postage or handling fee
- Smart contract -> vending machine rules written in code
- RPC -> the doorway your wallet or app uses to talk to a chain

## Common Misunderstandings

- "My coins are in MetaMask."  
  Better: the chain records balances; MetaMask helps sign messages and transactions.
- "Gas is paid to the wallet company."  
  Better: Gas is usually paid to validators or sequencers on the network.
- "Signing is harmless because it is not a transaction."  
  Better: signatures can still approve actions and should be treated carefully.
- "Web3 equals speculation."  
  Better: speculation is one part; Web3 also includes identity, coordination, payments, and software infrastructure.

## Safe First Path For Absolute Beginners

1. Learn the difference between address, private key, seed phrase, and signature.
2. Install a reputable wallet and write down the seed phrase offline.
3. Practice with a fresh wallet and tiny amounts or testnet assets.
4. Learn to read a transaction preview before confirming.
5. Avoid connecting the same wallet to every site.
