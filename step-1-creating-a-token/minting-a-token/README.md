---
description: GENERAL GUIDELINES
---

# 1️ Minting a Token

Before creating an SPL token on Solana, there are several important factors to consider. Let's break down each component to help you understand the key steps and decisions involved in creating your token.

<figure><img src="../../.gitbook/assets/4.png" alt=""><figcaption></figcaption></figure>

&#x20;Creating an SPL token on Solana involves several important considerations, from choosing a name and symbol to setting the total supply and creating a logo. Ensure you have a clear understanding of your token's purpose and tokenomics before starting. Be aware that the wallet you use to create the token will have authority over it, so use a secure wallet and keep your private keys safe.

### &#x20;Custom Properties

To start creating your SPL token, you need to determine these essential custom properties:

* Name: Choose a name that reflects your project's identity. If possible, keep it related to your brand or project name for consistency. It should be unique and easy to remember.
* Symbol (Abbreviation): This should be a concise representation of your token's name, typically 2-4 letters, but up to 8. Ensure it is unique and not easily confused with other tokens.
* Decimals: This determines how many decimal places your token can have. Typically, utility tokens have 6 decimals, while some tokens like whitelisting tokens use 0 decimals.
* Total Supply: Decide on the total supply of tokens. This is a crucial part of your tokenomics and should align with your project's financial landscape.

Use the Presale Calculator as a guide: [PRE-SALE CALCULATOR (make copy)](https://docs.google.com/spreadsheets/d/1qw42dxJ44ajS6Pquhi-jOg84Y7kCF45W0KSNwYkd0ns/edit#gid=1285820654)

* Description: Write a brief, clear explanation of your token's purpose and use case. This helps others understand what your token represents.

#### Logo Design

The logo is an important visual element of your token. It should be unique, memorable, and represent your brand. Pay attention to colors and imagery to make your logo stand out. Use a PNG format with a recommended size of 1000x1000 pixels.

### Additional Features

Consider these additional features and settings for your SPL token:

* Immutability: Decide if your token should be immutable, meaning you cannot change it after creation. [More Info](../../roger-solana-genesis/roger-solana-genesis/immutable-option.md)
* Revoke Mint: Consider whether to retain or revoke these authorities to improve security. [More Info](../../roger-solana-genesis/roger-solana-genesis/revoke-mint.md)
* Freeze Authority: Consider whether to retain or revoke these authorities to improve security. [More Info](../../roger-solana-genesis/roger-solana-genesis/revoke-freeze.md)

&#x20;

#### Authority Wallet

The wallet used to create the SPL token becomes the "Authority Wallet." This wallet has full control over your token, including minting more tokens, freezing accounts, and other administrative actions.

&#x20;

#### What Happens After Creating SPL Token Solana?

After creating your SPL token, you can view your total supply and other information in your wallet. Use tools like Solscan to search for and view detailed information about your token.
