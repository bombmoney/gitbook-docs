# Bonds (BBOND)

![The "Pit", where you can interact with the protocol's bonding mechanism](<../.gitbook/assets/image (9).png>)

### What are BBOND (Bonds)?

Bonds are unique tokens that can be utilized to help stabilize BOMB price around peg (10,000 BOMB = 1 BTC) by reducing the circulating supply of BOMB if the TWAP (time-weighted average price) goes below peg.

### When can I buy BBOND (Bonds)?

BBOND can be purchased only during periods of supply contraction and when the TWAP of BOMB is below 1.

At the beginning of every new epoch during contraction periods, BBONDs are issued in the amount of 3% of BOMB's circulating supply, with a max debt amount of 35%. This means that if bonds reach 35% of the circulating supply of BOMB, no more bonds will be issued.

{% hint style="info" %}
Note that during a zen epoch (when an epoch ends with a TWAP between 1.0 - 1.01), **no BBOND will be issued, even though the Boardroom does not print.**
{% endhint %}

{% hint style="danger" %}
BBOND TWAP (time-weighted average price) is based on the BOMB TWAP from the previous epoch as it ends. In other words, the BOMB TWAP is real-time but the BBOND TWAP is not.
{% endhint %}

### Where can I buy BBOND (Bonds)?

You can buy BBONDs if any are available through [bomb.money](https://app.bomb.money/bond) in the [Pit](https://app.bomb.money/bond). Anyone can buy as many BBONDs as they want as long as they have enough BOMB to pay for them.

There is a limit of available BBONDs per epoch during contraction periods (3% of BOMB's current  circulating supply), and are sold first-come-first-serve.

### Why should I buy BBOND (Bonds)?

The first and most important reason to buy BBOND is that they help to maintain the peg, but they are not the only measure in place to keep the protocol on track.&#x20;

BBONDs don't have an expiration date, so you can view them as an investment in the long-term health of the protocol to be redeemed for a premium at a later date.

#### Incentives for Holding BBOND

The idea is to reward BBOND buyers for helping the protocol, while also protecting the protocol from being manipulated by big players.

So after you buy BBOND using BOMB, you have two possible ways to get your BOMB back:

1. Sell back your BBOND for BOMB **while the peg is between 1 - 1.1** (10,000 BOMB = 1 BTCB) with no redemption bonus. This is in place to prevent an instant dump as soon as peg is recovered.
2. Sell back your BBOND for BOMB **while the peg is above 1.1** (10,000 BOMB = 1 BTCB) with a bonus redemption rate.

The longer you hold, the more both the protocol and you benefit from BBOND.

{% hint style="success" %}
Example:

1. When BOMB = 0.8, burn 1 BOMB to get 1 BBOND (BBOND price = 0.8)
2. When BOMB = 1.15, redeem 1 BBOND to get 1.105 BOMB (BBOND price = 1.27)&#x20;
{% endhint %}

So, which one is better?

If I buy BOMB at 0.8, and hold it until 1.15 and then sell, I'm getting +$0.35 per BOMB.

But, if I buy BOMB at 0.8, burn it for BBOND, and redeem it at 1.15, I'm getting 1.105 BOMB \* 1.15 (BOMB current price) = 1,271 (+$0.47) per BBOND redeemed.

But, what if getting back to peg is taking too long?

We will adjust our use cases to have different behaviors on contraction and expansion periods to benefit both BOMB and BBOND holders when needed.

### What is the formula to calculate the redemption bonus for BBOND?

To encourage the redemption of BBOND for BOMB when BOMB's TWAP > 1.1 and in order to incentivize users to redeem bonds at a higher price, BBOND redemption is designed to be more profitable with a higher BOMB TWAP value. The BBOND to BOMB ratio is 1:R, where R can be calculated using the formula as shown below:

$$
R=1+[(BOMBtwapprice)-1)*coeff)]
$$

$$
coeff = 0.7
$$

### When can I swap BBOND for a premium?

You can only redeem BBONDs for a premium when the previous epoch's TWAP is greater than 1.1.
