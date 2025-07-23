# Silent Profits: How Did Experts Earn Over $200k from ETH Fork Arbitrage?

## Understanding ETHW Arbitrage Opportunities

The Ethereum Merge created unprecedented opportunities for risk-free arbitrage, with reports of scientists earning nearly **10,000 ETHW** (approximately $200,000) through liquidity pool exploitation. This strategy involved using valueless tokens like USDC to extract valuable assets from decentralized exchanges (DEXs). The OKLink Chain Guardian team revealed that arbitrageurs collectively amassed **217,129 ETHW**, with the top address earning nearly **26,541.8 ETHW**—three times more than the infamous "zero-cost $200k" case.

👉 [Discover blockchain security tools](https://bit.ly/okx-bonus)

### Why USDC Became a "Lemon" on ETHW

The EthereumPoW (ETHW) chain emerged as miners resisted Ethereum's transition to Proof-of-Stake (PoS). While ETHW inherited all Ethereum assets, centralized stablecoins like USDC lost legitimacy. Stablecoin issuers refused to recognize ETHW's shadow assets, as real-world dollar reserves couldn't "split" during the fork. This created a loophole: **valueless USDC on ETHW could be used to siphon ETH(W) from liquidity pools**.

## DEX Arbitrage Strategies Unveiled

We analyzed eight major liquidity pools across Uniswap and SushiSwap, focusing on USDT-WETH, USDC-WETH, and WBTC-WETH pairs. The top three arbitrageurs include:

1. **0x3dca**: 26,541.8 ETHW
2. **0xefe**: 9,779.3 ETHW
3. **0x3dc**: 26,541.8 ETHW (same contract as 0x3dca)

### Key Arbitrage Mechanics

Two primary methods dominated:

1. **DEX Router Exploitation**: Interacting directly with DEX frontend contracts to exchange shadow assets for ETH(W)
2. **Custom Arbitrage Contracts**: Deploying multi-step strategies across liquidity pools

#### Case Study: 0x3dca's $200k+ Strategy
This address utilized a **multi-chain arbitrage contract (0xb98)** that:
- Borrowed 9,290 stETH and 33,235 USDC
- Converted assets across Uniswap V3 pools (USDT/WETH, WBTC/WETH, USDC/WETH)
- Netted 16,855.8 WETH converted to ETHW

#### Case Study: 0xefe's Zero-Cost Windfall
The "zero-cost $200k" author executed 90 trades, including one transaction yielding **926 ETHW** by:
- Converting 2.09 million USDC to WBTC
- Exploiting WBTC/WETH pool liquidity
- Using Uniswap V3 Router for final ETHW conversion

👉 [Explore crypto analytics tools](https://bit.ly/okx-bonus)

### Arbitrage Window Timeline

The ETHW arbitrage window remained open for **9 days** (September 15-24, 2022). Key observations:
- Top earners began operations within 5 minutes of the first ETHW block
- 80% of liquidity was drained from major pools in 48 hours
- Activity tapered off by September 23

## Blockchain Security & Risk Monitoring

This exploit highlights systemic vulnerabilities in DEX liquidity pools. OKLink's **TokenScanner** offers three critical defenses:
1. **Risk Analysis**: Real-time tracking of suspicious liquidity withdrawals
2. **Token Classifier**: Identifying rugpulls and shadow asset manipulation
3. **Safety Scoring**: Evaluating DEX liquidity health across 9 chains

### Proactive Defense Mechanisms
- Monitoring top liquidity pool beneficiaries
- Detecting concentrated market maker activity
- Flagging suspicious token swaps in WBTC/WETH pools

👉 [Enhance blockchain security](https://bit.ly/okx-bonus)

## Frequently Asked Questions

**Q: What triggered ETHW arbitrage opportunities?**  
A: The Ethereum Merge created duplicate assets on ETHW and ETH chains. Centralized stablecoins like USDC lost value on ETHW, creating a price discrepancy exploitable through DEX liquidity pools.

**Q: How did attackers exploit liquidity pools?**  
A: Arbitrageurs used valueless USDC/USDT to exchange for ETH(W) in pools like Uniswap's USDC-WETH pair. This drained liquidity from pools containing real ETH(W) assets.

**Q: What tools can detect such blockchain risks?**  
A: OKLink's TokenScanner monitors liquidity pool health, detects abnormal token swaps, and flags suspicious addresses through risk scoring and token classification systems.

**Q: How long did the arbitrage window remain open?**  
A: The primary window lasted **9 days** (September 15-24, 2022), with most liquidity drained within the first 48 hours.

**Q: Can this happen again during future forks?**  
A: Yes. Any blockchain fork creates asset duplication risks. Proactive monitoring tools and prompt liquidity withdrawal remain critical defenses.

## Conclusion
