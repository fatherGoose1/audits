## Django, Security Researcher and Bug Bounty Hunter
Hi, I'm 0xDjango (real name Parker). I've been auditing and developing smart contracts since 2021. I am a former Lead Security Reseracher at Guardian Audits and currently lead the team at [https://www.birdseye.gg](Birdseye Security).

In 2022, I started competing in Code4rena contests and quickly racked up some contest wins. I switched to bug bounty hunting and became a top hunter on Immunefi, reporting multiple High and Critical vulnerabilities and saving at-risk funds in the process.

In late 2022, I built The Saloon (sunsetted), a Web3 bug bounty program program that utilized “bounty pools” to ensure fair distribution of bounty rewards following valid submission.

2023-2024, I developed and maintained a cross-chain bridge protocol called Flexy (prev. Gasbot). A first of its kind protocol, Flexy enabled gasless cross-chain asset transfers initiated through offchain signatures. The project was sunsetted in late 2024.

Following Flexy, I became a Lead Security Researcher at Guardian Audits. In this role, I led reviews, maintained client communications, and managed the security team.

Notable highlights:
- 4 - 1st place public contest finishes
- Top 50 Immunefi researcher with 29 paid reports
  - Saved $14 million from direct theft across multiple critical severity vulnerabilities
    - Beanstalk direct theft mitigation ($3.1M at risk)
    - Direct theft due to reentrancy in lending protocol - under NDA ($11M at risk)
    - Freezing of withdrawals from PancakeSwap CAKE staking pool ($15M at risk)
- Tenured judge at Code4rena

# Private Audits

| Date    | Audit Firm    | Protocol    | Description                                          |
|---------|---------------|-------------|------------------------------------------------------|
|Nov 2025  |Sherlock      |Aerostrategy |Efficient AERO reward locking and distribution        |
|Oct 2025  |Sherlock      |Reppo        |VE(3,3) gauge voting and reward distribution          |
|Aug 2025  |Guardian      |Ullr         |Permissionless liquidity locking contracts            |
|June 2025 |Guardian      |PurrSwap     |VE(3,3) implemenation with PurrSwap LP pools          |
|May 2025  |Guardian      |Gamma        |UniswapV4 limit order manager and hook contracts      |
|Apr 2025  |Guardian      |PurrSwap     |Custom UniswapV2 liquidity pools and manager contracts|
|Feb 2025  |Guardian      |Ethereal     |Off-chain orderbook                                   |
|Feb 2025  |Spearbit      |Centrifuge   |Governance mechanisms                                 |
|Dec 2024  |Spearbit      |Collar       |Liquidation-free, high-LTV borrowing                  |
|Sept 2024 |Spearbit      |Berachain    |Proof-of-liquidity core contracts                     |
|Aug 2024  |Spearbit      |Coinbase     |Coinbase verified Uinswap V4 pools                    |
|Apr 2024  |Spearbit      |Chroma       |Permissionless modular lending market creation        |
|Feb 2024  |Spearbit      |Astaria      |Startport lending protocol integration                |

## Bug bounties

| Platform      | Vulnerability                                                                                 | Severity | Payout |
|---------------|-----------------------------------------------------------------------------------------------|----------|--------|
|Immunefi       |DIRECT THEFT OF FUNDS due to allowance set for Beanstalk                                       |Critical  |$182k   |
|Immunefi       |Direct theft of user funds due to reentrancy                                                   |Critical  |$125k   |
|Immunefi       |mintAndStake() function allows attacker to steal value from victim via sandwich attack.        |Critical  |$20k    |
|Immunefi       |CollateralManager allows attacker to steal funds directly from users' wallets                  |Critical  |$10k    |
|Immunefi       |Error in REDACTED logic allows attacker to prevent users' token transfers and redelegation     |Critical  |$10k    |
|Immunefi       |Attacker can lock ANY user's funds in veXBE for maximum 2 years                                |High      |$50k    |
|Immunefi       |Logic Error in `CakePool.depositOperation()` can Freeze Withdrawals for all Boosted Farm Pools |High      |$40k    |
|Immunefi       |Lack of DelegateCash Clearing can lead to Theft of airdrops, imposter ownership of NFTs        |High      |$10k    |
|Immunefi       |Theft of all Pending Proposal's fees from InflationRootHashProposal.sol                        |High      |$10k    |
|Immunefi       |Staking/voting inflation and can lead to malicious governance proposal execution               |High      |$50k    |
|Immunefi       |Double Spend when extending loan duration while owing back interest                            |High      |$22k    |
|Immunefi       |Value can be stolen from Spot Limit Orders, minAmountOut is never checked                      |High      |$22k    |
|Immunefi       |Griefer can set all new users lock periods to maximum 4 years                                  |Medium    |$5k     |
|Immunefi       |Signature replay attack can cause freezing of funds                                            |Medium    |$5k     |
|Immunefi       |Anyone can steal owner/player's earned profit or borrow any WNFT                               |Medium    |$5k     |
|Immunefi       |Governance Manipulation: Anyone can reset others' delegated votes                              |Medium    |$2.5k   |
|Immunefi       |All Users' Margin can be permanently frozen                                                    |Medium    |$2k     |


## Audit Contests

| Date    | Platform      | Protocol | Description                               | Result |
|---------|---------------|----------|-------------------------------------------|--------|
|Mar 2022 |Code4rena      |LI.FI     |Cross-chain asset transfer protocol        |   🥇   |
|Apr 2022 |Code4rena      |Backed    |Peer-to-peer loans with NFT collateral     |   🥈   |
|Apr 2022 |Code4rena      |Mimo DeFi |Decentralized stablecoin issuance protocol |   🥇   |
|Jun 2022 |Code4rena      |Nested Fi |Decentralized crypto portfolio contracts   |   🥇   |
|May 2023 |Sherlock       |Eco       |Cross-chain bridge contracts               |   🥇   |

