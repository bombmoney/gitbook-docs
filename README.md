---
description: About bomb.money
---

# Introduction

Welcome to Bomb Money! If this is your first time here, please take some time to read through this documentation before you begin using the protocol. This documentation is intended to take you through the entire process of how to get started using Bomb Money to earn stable, high yields that are only possible through the power of DeFi, but with the stability and security of exposure to Bitcoin, the world's largest and most stable crypto asset. Let's dive in!

## Origins

Bomb Money is based upon the work of the brilliant **tomb.finance** project on the Fantom network. At the time, it was hard to believe that nothing similar existed on any other larger networks, so it was a great opportunity to bring an amazingly stable and robust DeFi protocol like **tomb.finance** with a few unique twists to the masses. As far as networks go, Binance Smart Chain (BSC) seemed like the perfect choice with its fast transaction speeds, low gas fees, and much larger user base, so one thing led to another and now here we are!\
\
This project would certainly not be possible without the work of the [tomb.finance](https://tomb.finance) team. Their project being fully open source and developed exceptionally well made it a pleasure to work with, and we would not be here today without their efforts, so we want to give a special thank you to them for that.

{% hint style="info" %}
Bomb Money was launched on November 23, 2021. The rest is history!&#x20;
{% endhint %}

## What's the point?

Ultimately, the purpose of the Bomb Money protocol is to provide the means for its underlying BOMB asset to maintain a value that is algorithmically pegged to the value to Bitcoin (BTC) at a 10,000 to 1 ratio.

So, what good is that? We will explore this idea further throughout this documentation, but for now without getting _too_ technical, this opens up a world of possibilities for existing, long-time Bitcoin holders, people already familiar with DeFi, as well as new users just coming into the space.

Bitcoin transactions are slow and expensive. There are not nearly as many attractive yield earning opportunities in DeFi for people to put their precious Bitcoin to work for them. BOMB, through the Bomb Money protocol, can solve many of these problems and more, generating immense value for our users in the process.

As the Bomb Money ecosystem grows over time, the potential future applications are quite literally endless. And, as you proceed through this documentation and learn more about how the Bomb Money protocol works, we will explore some of that potential in more detail.

{% hint style="info" %}
BOMB is the native token of the Bomb Money protocol. The built-in stability mechanisms within the protocol aim to maintain BOMB's peg of 10,000 BOMB = 1 Bitcoin (BTC) in the long run.
{% endhint %}

## What are the Bomb Money protocol tokens?&#x20;

Bomb Money’s multi-token protocol currently consists of the following four tokens, and each plays a critical role in how the protocol works to maintain peg:

1. **BOMB Tokens ($BOMB)** - The BOMB token is designed for use as a medium of exchange, and is intended to have many other use cases as the Bomb Money ecosystem grows. BOMB is algorithmically pegged to Bitcoin (BTC) at a ratio of 10,000 BOMB to 1 BTC.
2. ****[**xBOMB Tokens ($XBOMB)**](protocol/xbomb-bomb-staking.md) - xBOMB is the governance token of BOMB Protocol. It can be obtained by staking BOMB. This helps to keep BOMB supply limited while providing another means of earning yield for BOMB holders, among other planned use cases.
3. **BOMB Shares ($BSHARE)** - BSHARE can be staked in the [Boardroom](protocol/boardroom.md) to earn a portion of minted BOMB as rewards to those BSHARE holders for investing in the health and stability of the protocol.
4. ****[**BOMB Bonds ($BBOND)**](protocol/bonds-mechanism.md) - BBOND’s main job is to help incentivize and reward users for helping to regain peg during times of supply contraction below peg.

## How does it work?

The Bomb Money protocol works through a synergistic design of unique tokens and mechanisms that create an automatic, self-reinforcing system to help maintain the peg (10,000 BOMB = 1 Bitcoin). Each of these tokens and mechanisms will be explained in further detail within this documentation, but for now let's have a look at a brief overview of how it all works:

* When **BOMB price is over the peg**, new BOMB are minted by the protocol to inflate the supply in an attempt to drive the price down towards the peg. These new BOMB are allocated to BSHARE holders in the Boardroom, as a reward for their investment and trust in the protocol. This in turn increases the demand for and the value of BSHARE.
* When **BOMB price is at the peg**, no new BOMB will be minted, keeping the supply fixed during this time. Since there will be no new supply coming in, the peg will be maintained indefinitely at this point unless there is a shift in demand. More buying pressure during this time will push the price back up above the BOMB minting threshold. Conversely, more selling pressure will push the price below the peg.
* When **BOMB price drops below the peg**, the protocol will begin to mint BBONDs (up to a maximum debt limit). Experienced investors will have the ability to exchange their BOMB for these BBOND, which they can then redeem for BOMB at a premium above peg in the future. This removes BOMB from the total supply, applying upward pressure on the price towards the peg. Besides this, investors who believe in the protocol's ability to maintain peg can just buy BOMB to essentially purchase Bitcoin at a discount to the market. Both of these incentives are intended to create upward pressure on BOMB's price when under the peg so that the peg can be regained over time. BOMB staking (xBOMB), and other features of the protocol that will be discussed later, also help limit BOMB supply and apply upward pressure on the price during this time.

{% hint style="info" %}
There are so many different ways you can utilize the mechanisms of the Bomb Money protocol to earn yield. Pick a strategy that is right for you, based upon your own knowledge and experience. Even the most simple and basic of strategies can earn great returns, but feel free to experiment with more complex strategies as you learn how the protocol works!
{% endhint %}

## What exactly is the peg?

BOMB is a token that is intended to track the price of Bitcoin (BTC) algorithmically. The ratio for this peg is set at 10,000 BOMB to 1 BTC. BOMB **actively tracks this peg via an algorithm**, but that **does not mean** it will be valued at 10,000 BOMB to 1 BTC at all times as **it is not collateralized**. **BOMB is not to be confused for a crypto or fiat-backed stablecoin.**&#x20;

The entire design of the Bomb Money protocol is intended to try and maintain this peg as closely as possible, but as it is an algorithmic peg, this will never be a completely stable process. In fact, some of the unique profit-generating opportunities offered by the protocol actually only exist because of these price fluctuations.

To put it simply, there will **almost certainly be times when the price of BOMB is below peg**. This is a natural part of the process, and opens up opportunities for active investors/traders to "buy the dip" and help support the protocol by regaining peg, while also profiting from the discounted price.

![A visualization of BOMB price in relation to peg](<.gitbook/assets/BOMB Price Visualization.png>)

When the protocol is healthy and stable, the price of BOMB will likely look similar to above, with price fluctuating above and below peg as the mechanisms of the protocol work to influence supply and demand and maintain an average price around the peg.

Keep this in mind when developing your strategies and when taking a more active role in the protocol.
