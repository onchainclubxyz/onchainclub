# How it works

## How Clanker Deploys Tokens and Fees Work

Clanker simplifies token deployment on the **Base network** and introduces rewards for both users (Requestors) and the protocol. Here's a breakdown of how it works.

***

### 1. Token Deployment Process

When a user tags Clanker in a cast with a token name, ticker, and optional image, the following happens:

1. **Token Creation**:
   * Clanker deploys a new **ERC-20 token** on the Base network using its `Clanker.sol` smart contract.
2. **Uniswap V3 Pool Creation**:
   * A Uniswap V3 pool is initialized with a starting market cap of approximately **$30,000**.
3. **Liquidity Provision**:
   * Clanker adds **single-sided liquidity** to the Uniswap V3 pool by sending the ERC-20 tokens to Uniswap’s Nonfungible Position Manager.
4. **Liquidity Locking**:
   * The liquidity (LP) NFT is locked for a default period of **2100 years** (yes, you read that right!).

***

### 2. Fee Structure

Clanker deploys tokens with a **1% fee Uniswap V3 pool**. Here’s how the fees are split:

* **60%** of swap fees go to the **Clanker Protocol**.
* **40%** of swap fees go to the **Requestor** (the user who requested Clanker to deploy the token).

For example:\
If a token generates $1,000 in swap fees:

* $600 goes to Clanker.
* $400 goes to the Requestor.

***

### 3. How to Claim Rewards

Rewards are collected as fees from token trades on the Uniswap V3 pool.

#### Current Claiming Process

* Rewards for tokens deployed **before November 18, 2024** were claimed and distributed manually by the Clanker DevCo team.
* WETH rewards have already been distributed. Token rewards are currently being processed.

#### Upcoming Self-Service Rewards

* In future updates (v2 contracts, ETA November 29, 2024), **Requestors** will be able to claim their rewards directly:
  * Through the token’s page on [clanker.world](https://www.clanker.world).
  * By interacting with the smart contract directly on a blockchain explorer like **Basescan**.

***

### 4. Summary

* **Clanker** deploys tokens on Base and creates a Uniswap V3 pool.
* Requestors earn **40%** of all trading fees from their token’s pool.
* Rewards will soon be claimable directly through Clanker’s website or smart contracts.

***

### Quick Links

* **Clanker Bot on Farcaster**: [@clanker](https://warpcast.com/clanker)
* **Clanker World**: [https://www.clanker.world](https://www.clanker.world)
* **Uniswap V3 Documentation**: [Learn More](https://uniswap.org)
* **Basescan (Base Explorer)**: [https://basescan.org](https://basescan.org)

***

With Clanker, deploying tokens is fast, automated, and rewarding. By earning a share of the swap fees, you can benefit from the success of the tokens you launch. 🚀

**Ready to deploy your token?** Learn how to launch a token with Clanker.
