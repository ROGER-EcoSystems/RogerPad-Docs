# Introduction: OpenBook Market

Permissionless pools allow anyone to create a liquidity pool on Raydium. Once a pool is created it can then immediately be traded on the Raydium swap interface. The pool AMM will also place orders on the [OpenBook](https://github.com/openbook-dex/resources) order book (Serum is no longer supported), allowing liquidity to be traded on the Raydium Trading page, or any other OpenBook DEX GUI.

&#x20;

It is _highly_ suggested to carefully read and understand this _entire_ guide before creating a pool.

1. Permissionless Pools: Raydium allows anyone to create liquidity pools without needing prior approval. This feature enables the rapid creation of new trading pairs and liquidity provision.
2. Immediate Trading: Once a liquidity pool is created, it becomes immediately tradable on the Raydium Swap interface. This ensures that users can start trading the newly created pairs without delay.
3. Interaction with OpenBook: The liquidity pools also interact with the OpenBook order book, which enhances liquidity provision and trading opportunities. This integration allows liquidity to be traded not only on Raydium but also on other OpenBook decentralized exchange (DEX) interfaces.
4. Unique Market IDs: Each new liquidity pool must be linked to a unique OpenBook market ID. This ensures that each pool operates independently and is easily distinguishable within the ecosystem.
5. Minimum Liquidity Threshold: Liquidity pools must maintain a minimum liquidity threshold (equivalent to $100,000 USD) to ensure efficient market making. If liquidity falls below this threshold, the automated market maker (AMM) will pause placing orders until additional liquidity is added or token prices rise.
6. Market Cranking: OpenBook markets need to be "cranked" for consume events (fill orders) to be completed. Raydium doesn't automatically crank OpenBook markets for permissionless pools. Pool creators may need to crank the OpenBook market themselves if no other market participants are contributing to the crank.
7. Freeze Authority: Pool creation requires the base token to have freeze authority disabled. This ensures that liquidity can be freely provided and withdrawn from the pool without restrictions.
8. AMM ID: Each new liquidity pool is assigned an associated AMM ID, which can be used to easily search for the pool on the Swap or Liquidity page. This ID can also be shared with others to facilitate access to the pool.
9. Pool Vaults: A small fraction of the initial liquidity is transferred to the pool vaults instead of being minted as LP (liquidity provider) tokens. This ensures that the liquidity pool is never empty, and new LP tokens can always be minted if needed.



{% hint style="info" %}
These points provide a comprehensive overview of the process and considerations involved in creating liquidity pools on Raydium's permissionless platform.
{% endhint %}
