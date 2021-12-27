# Tokens

### BOMB - bomb.money Token

![bomb.money (BOMB)](../.gitbook/assets/bomb-256.png)

Contract: [0x522348779DCb2911539e76A1042aA922F9C47Ee3](https://bscscan.com/address/0x522348779dcb2911539e76a1042aa922f9c47ee3)



BOMB token is designed to be used as a medium of exchange. The built-in stability mechanism in the protocol aims to maintain BOMB's peg of 10,000 BOMB = 1 Bitcoin (BTC) in the long run.&#x20;

{% hint style="warning" %}
Note that BOMB **actively pegs via the algorithm**, it **does not mean** it will be valued at 10,000 BOMB : 1 BTC at all times as it is not collaterized . BOMB is not to be confused for a crypto or fiat-backed stablecoin.
{% endhint %}

### BSHARES - BOMB Shares

![BSHARE](../.gitbook/assets/bshare-256.png)

Contract: [0x531780FAcE85306877D7e1F05d713D1B50a37F7A](https://bscscan.com/address/0x531780face85306877d7e1f05d713d1b50a37f7a)

BOMB Shares (BSHARE) are one of the ways to measure the value of the BOMB Protocol and shareholder trust in its ability to maintain BOMB close to peg. During epoch expansions the protocol mints BOMB and distributes it proportionally to all BSHARE holders who have staked their tokens in the **Boardroom**.

BSHARE holders have voting rights (governance) on proposals to improve the protocol and future use cases within the BOMB money ecosystem.

BSHARE has a **maximum total supply of 70001** tokens distributed  as follows:

1. _Treasury/DAO Allocation: 5500_ BSHARE vested linearly 12 months\*
2. _Team Allocation: 5000_ BSHARE vested linearly over 12 months
3. _Rewards: 59500_ BSHARE are allocated for incentivizing Liquidity Providers in two shares pools for 12 months
4. Initial mint: 1 BSHARE minted upon contract creation for initial pool

* _Devs will use treasury funds in any way they feel is best for the long term success of the protocol._&#x20;

### BBOND - BOMB Bonds

![BBOND](../.gitbook/assets/bbond-256.png)

Contract: [0xDA1d9C79240003195d0a67f202efcCCC3F78b994](https://bscscan.com/address/0xda1d9c79240003195d0a67f202efcccc3f78b994)

BOMB Bonds (BBOND) main job is to help incentivize changes in BOMB supply during an epoch contraction period. When the TWAP (Time Weighted Average Price) of BOMB falls below 10,000:1 BTC ,  BBONDs are issued and can be bought with BOMB at the current price. Exchanging BOMB for BBOND burns BOMB tokens, taking them out of circulation (deflation) and helping to get the price back up to peg. These BBOND can be redeemed for BOMB when the price is above peg in the future, plus an extra incentive for the longer they are held above peg. This amounts to inflation and sell pressure for BOMB when it is above peg, helping to push it back toward 10,000 BOMB to 1 BTC ratio.

{% hint style="info" %}
Contrary to early algorithmic protocols, BBONDs do not have expiration dates.&#x20;
{% endhint %}

All holders are able to redeem their BBOND for BOMB tokens as long as the Treasury has a positive BOMB balance, which typically happens when the protocol is in epoch expansion periods.
