---
description: STEP BY STEP
---

# Create OpenBook Market

How to create an OpenBook Market ID in Solana using our dApp, "Create OpenBook Market," without the need for programming:

&#x20;

1\.      Access the Create OpenBook Market dApp: \[Link to the dApp]

2\.     Connect your wallet: Upon accessing the dApp, you'll need to connect your Solana wallet to proceed.

3\.     Select the "Token Base": Choose the token you've created, which currently holds no value but will be traded in the market.

4\.     Choose the "Quote Token": This is a token with an established value in the market, typically SOL (Solana's native token).

5\.     Set the "Minimum Order Size": Define the minimum amount that users can purchase of your token in a single order.

6\.     Define the "[Price Tick"](../../../amm-open-book-market/open-book-market/tick-size-vs.-min-order.md): This represents the minimum price change that can occur for your token.

7\.     Select the market maker: Choose the preferred market maker for your OpenBook Market.

8\.     For the parameters to configure in the Minimum Order Size and Tick Size, here are the recommended inputs:

Event Queue Length: 2978

Request Queue Length: 63

Orderbook Length: 909

&#x20;These values are the standards recommended by the protocols, with the last one, 2.8 SOL, being particularly common. While you have the flexibility to use other numbers, adhering to these recommended values ensures optimal performance and compatibility with the Solana ecosystem.

&#x20;Feel free to refer to the reference box provided below for additional guidance on configuring the Minimum Order Size and Tick Size parameters:

&#x20;

|  Token Supply	 | Min Order Size | Tick SIze   |
| -------------- | -------------- | ----------- |
| 100 k          | .01            | .0001       |
| 1 m            | .1             | .00001      |
| 10 m           | 1              | .000001     |
| 100 m          | 10             | .0000001    |
| 1 b            | 100            | .00000001   |
| 10 b           | 1000           | .000000001  |
| 100 b          | 10000          | .0000000001 |

This guide provides insights into successful tokenomics strategies observed in the industry. However, it's essential to conduct your own research and develop a tailored strategy for your project. Tokenomics should align with your project's goals, target audience, and market conditions. Seek advice from experts and professionals, ensuring your tokenomics support your project's vision and create sustainable value.

&#x20;\
To complete the process, click on "Create Market" and confirm the transactions. Once created, you'll receive the Market ID. Remember to copy and save it as you'll need it to add liquidity on DEX platforms. Raydium is a popular choice for adding liquidity, with a current cost of 0.6 SOL.

### &#x20;Summary

\
Creating an OpenBook Market is essential, despite the associated costs. Saving Solana for launching other projects, such as meme coins, is a wise strategy.

&#x20;More info can be found: [https://docs.raydium.io/raydium/pool-creation/creating-a-standard-amm-pool#how-to-create-a-permissionless-pool](https://docs.raydium.io/raydium/pool-creation/creating-a-standard-amm-pool#how-to-create-a-permissionless-pool)
