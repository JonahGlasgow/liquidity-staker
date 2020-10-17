# @Com-XethLiquidityStaker

# Description
Xplosive Ethereum liquidity mining

Deposit your Liquidity Provider tokens to receive [XETH](https://www.coingecko.com/en/coins/xplosive-ethereum), the most **Xplosive Ethereum** token on mainnet!

Deployed Factory Contract: [StakingRewardsFactory](https://etherscan.io/address/0x078fcf4c11f58968b364a40a52cbb28e5514b592)

Deployed StakingRewards Contract: TBA on 10/20/2020 @ 12:00pm (UTC).

# Liquidity Mining

An initial liquidity mining program will go live **10/20/2020 @ 12:00pm (UTC)**. 

The initial program will run until **12/20/2020 @ 12:00pm (UTC)**. and target the following pool on Uniswap v2:

Target LP Pair - [ETH/XETH](https://info.uniswap.org/pair/0xac0fe6c0b239eedcc12bc3e997e5492b04cc61c3)

100,000 XETH will be allocated per pool to LPs proportional to liquidity, which roughly translates to:

1600 XETH for each pool per day

0.2438281012 XETH for each pool per block (14s blocktime)

These XETH are not subject to vesting or lock up.

# Basic Configuration
Contracts:
1. StakingRewardsFactory.sol - *Staking Pool Deployer*
2. StakingRewards.sol - *Deploys Each Individual LP Staking Pool* 
3. RewardsDistributionRecipient.sol - *Recipient Validator* 

Deployment Instructions: 
1. Make any additional changes to StakingRewardsFactory.sol
2. Configure Migrations.sol for *Staking Pool Deployer*
3. Deploy Project

# Notable Mentions
Special thank to the [Sparkle Loyalty Community](https://t.me/Sparkleloyalty) for contributing on this project.  

Forked from Uniswap 
[Uniswap Liquidity Staker](https://github.com/Uniswap/liquidity-staker)

