---
description: STEP-BY-STEP Instructions
---

# Create OpenBook Market

How to create an OpenBook Market ID in Solana using our dApp, "Create OpenBook Market," without the need for programming:

&#x20;

1. Access the Create OpenBook Market dApp: \[Link to the dApp]
2. Connect your wallet: Upon accessing the dApp, you'll need to connect your Solana wallet to proceed.
3. Select the "Token Base": Choose the token you've created, which currently holds no value but will be traded in the market.
4. Choose the "Quote Token": This is a token with an established value in the market, typically SOL (Solana's native token).
5. Set the "Minimum Order Size": Define the minimum amount that users can purchase of your token in a single order.
6. Define the "Price Tick": This represents the minimum price change that can occur for your token.
7. Select the market maker: Choose the preferred market maker for your OpenBook Market.
8. For the parameters to configure in the Minimum Order Size and Tick Size, here are the recommended inputs:&#x20;
   *   Event Queue Length: 2978

       Request Queue Length: 63

       Orderbook Length: 909

{% hint style="info" %}
These values are the standards recommended by the protocols, with the last one, 2.8 SOL, being particularly common. While you have the flexibility to use other numbers, adhering to these recommended values ensures optimal performance and compatibility with the Solana ecosystem.
{% endhint %}

&#x20;

#### <mark style="color:purple;">**Feel free to refer to the reference box provided below for additional guidance on configuring the Minimum Order Size and Tick Size parameters:**</mark>

<table data-header-hidden><thead><tr><th></th><th width="233"></th><th></th></tr></thead><tbody><tr><td>Token Supply</td><td>Min Order Size</td><td>Tick SIze</td></tr><tr><td>100 k</td><td>.01</td><td>.0001</td></tr><tr><td>1 m</td><td>.1</td><td>.00001</td></tr><tr><td>10 m</td><td>1</td><td>.000001</td></tr><tr><td>100 m</td><td>10</td><td>.0000001</td></tr><tr><td>1 b</td><td>100</td><td>.00000001</td></tr><tr><td>10 b</td><td>1000</td><td>.000000001</td></tr><tr><td>100 b</td><td>10000</td><td>.0000000001</td></tr></tbody></table>

This guide provides insights into successful tokenomics strategies observed in the industry. However, it's essential to conduct your research and develop a tailored strategy for your project. Tokenomics should align with your project's goals, target audience, and market conditions. Seek advice from experts and professionals, ensuring your tokenomics support your project's vision and create sustainable value.

&#x20;To complete the process, click on "Create Market" and confirm the transactions. Once created, you'll receive the Market ID. Remember to copy and save it as you'll need it to add liquidity on DEX platforms. Raydium is a popular choice for adding liquidity, with a current cost of 0.6 SOL.
