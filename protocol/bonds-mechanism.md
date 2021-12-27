# Bonds Mechanism

### What are BBOND (Bonds)?

Bonds are unique tokens that can be utilized to help stabilize BOMB price around peg (10,000 BOMB = 1 BTCB) by reducing circulating supply of BOMB if the TWAP (time-weighted-average-price) goes below peg (10,000 BOMB = 1 BTCB).

### When can I buy BBOND (Bonds)?

BBOND can be purchased only on contraction periods, when TWAP of BOMB is below 1.

Every new epoch on contraction periods, BBONDs are issued in the amount of 3% of current BOMB circulating supply, with a max debt amount of 45%. This means that if bonds reach 45% of circulating supply of BOMB, no more bonds will be issued.

Note: BBOND TWAP (time-weighted average price) is based on BOMB price TWAP from the previous epoch as it ends.  This mean that BOMB TWAP is real-time and BBOND TWAP is not.

### Where can I buy BBOND (Bonds)?

You can buy BBONDs if any are available, through [bomb.money](https://app.bomb.money/bond), anyone can buy as many BBONDs as they want as long as they have enough BOMB to pay for them.

There is a limit amount (3% of BOMB current  circulating supply) of available BBONDs per epoch while on contraction periods, and are sold as first come first serve.

### Why should I buy BBOND (Bonds)?

First and most important reason is Bonds help maintain the peg, but will not be the only measure use to keep the protocol on track. We also have a DAO fund which will step in and buy BOMB to get it back to peg.

BBONDs don't have a expiration date, so you can view them as a investment on the protocol, because longterm you get benefits from holding bonds.

#### Incentives for holding BBOND

The idea is to reward BBOND buyers for helping the protocol, while also protecting the protocol from being manipulated from big players.

So after you buy BBOND using BOMB, you get 2 possible ways to get your BOMB back:

1. Sell back your BBOND for BOMB while peg is between 1 - 1.1 (10,000 BOMB = 1 BTCB) with no redemption bonus. This to prevent instant dump after peg is recovered
2. Sell back your BBOND for BOMB while peg is above 1.1 (10,000BOMB = 1BTCB) with a bonus redemption rate

The longer you hold, the more both the protocol and you benefit from BBOND.

{% hint style="success" %}
Example:

1. When BOMB = 0.8, burn 1 BOMB to get 1 BBOND (BBOND price = 0.8)
2. When BOMB = 1.15, redeem 1 BBOND to get 1.105 BOMB (BBOND price = 1.27)&#x20;
{% endhint %}

So, which one is better?

If I buy BOMB at 0.8, and hold it until 1.15 and then sell, I'm getting +0.35$ per BOMB

But, if I buy BOMB at 0.8, burn it for BBOND, and redeem it at 1.15, I'm getting 1.105 BOMB \* 1.15 (BOMB current price) = 1,271 (+0.47$) per BBOND redeemed.

But what if getting back to peg is taking too long ?

We are going to adjust our use cases, to have different behaviors on contraction and expansion periods to benefit BOMB and BBOND holders when needed.

### When can I swap BBOND for a bonus?

BBOND TWAP (time-weighted average price) is based on BOMB price TWAP from the previous epoch as it ends.  This mean that BOMB TWAP is real-time and BBOND TWAP is not. In other words, you can redeem BBOND for a bonus when the previous epoch's TWAP > 1.1.
