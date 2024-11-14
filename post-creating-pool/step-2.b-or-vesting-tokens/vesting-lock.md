---
description: Token Sale / Team Tokens
---

# Vesting Lock

### To create a lock with vesting for tokens on RogerPad, follow these steps:

<figure><img src="../../.gitbook/assets/TOKEN LOCK (2).png" alt=""><figcaption></figcaption></figure>

{% hint style="danger" %}
Before you start, make sure you conenct your Solana wallet with SOL to pay for Transaction Fee and ofcourse the token (your project token) involved.
{% endhint %}

1.  Highlight your Choice for LP Lock or Token Locking system or Vesting

    Team Token or ICO
2. Enter, depending on you choice from line 1, Contract Address for Token Locking and Pair Address for LP Lock.
3. Enter a name for this lvesting for you to identify easier later. Ex: Vesting Token 1
4. Enter the amount of tokens to be included in this vesting lock.
5. nter the wallet address(es), (default is connected wallet). This option is specially for vesting token program.
6. First Lock Releases: This should be the listing time on DEX.
7. First Lock Release % (percent): The percentage of the first batch of team tokens to be released. This is expressed as a percentage, not a number of tokens.
8. Cycle (days): The duration, in days, between each batch of vested tokens being released.
9. Cycle Release (percent): The percentage of tokens to be released in each cycle following the First Token Release batch. Note that this is expressed as a percentage, not a number of tokens. The remaining percentage will be released in the last cycle.
10. Click on "Approve". Phantom will prompt you to confirm the transaction and display the associated fee. If you agree, click on the “Confirm” button to complete the "Approve" process.
11. Click on "Lock". Phantom will again prompt you to confirm the transaction and display the associated fee. If you agree, click on the “Confirm” button to complete the "Lock" process.

#### Example Scenario:

Suppose your project's Vesting for Contributors schedule is as follows:

* 100 tokens sold at presale.
* 20% presale tokens released at First Lock Release.
* 10% released each subsequent month.
* The presale opens on January 5th.

In this scenario, contributors can claim 20 tokens (20% of 100 tokens) at Launch, and then 10 tokens every month thereafter. They can claim their tokens manually from the Launchpad page on RogerPad.

### The cost of Creating a vesting lock is 0.5 SOL

{% hint style="info" %}
Note: Make sure to exclude ROGERPAD’S lockup address _**(ROGER GUARD WALLET)**_ from fees, rewards, and max transaction amounts when initiating the locking of tokens.
{% endhint %}

>
