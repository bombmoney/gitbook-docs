# Tokens

### BOMB - bomb.money Token

![bomb.money (BOMB)](<../.gitbook/assets/bomb-256 (1).png>)

Contract: [0x522348779DCb2911539e76A1042aA922F9C47Ee3](https://bscscan.com/address/0x522348779dcb2911539e76a1042aa922f9c47ee3)

The BOMB token is designed to be used as a medium of exchange. The built-in stability mechanisms within the protocol aim to maintain BOMB's peg of 10,000 BOMB = 1 Bitcoin (BTC) in the long run.&#x20;

{% hint style="warning" %}
Note that BOMB **actively pegs via an algorithm**, but that **does not mean** it will be valued at 10,000 BOMB to 1 BTC at all times as **it is not collateralized**. **BOMB is not to be confused for a crypto or fiat-backed stablecoin.**
{% endhint %}

### [xBOMB - BOMB Protocol Governance Token](xbomb-bomb-staking.md)

![xBOMB](../.gitbook/assets/xbomb-logo.png)

Contract: [0xAf16cB45B8149DA403AF41C63AbFEBFbcd16264b](https://bscscan.com/address/0xaf16cb45b8149da403af41c63abfebfbcd16264b)

xBOMB is the governance token of BOMB Protocol.  It can be obtained by staking BOMB.

Learn more about xBOMB on the [xBOMB - BOMB Staking page](xbomb-bomb-staking.md).

### BSHARES - BOMB Shares

![BSHARE](<../.gitbook/assets/bshare-256 (1).png>)

Contract: [0x531780FAcE85306877D7e1F05d713D1B50a37F7A](https://bscscan.com/address/0x531780face85306877d7e1f05d713d1b50a37f7a)

BOMB Shares (BSHARE) are one of the ways to measure the value of the Bomb Money Protocol and shareholder trust in its ability to consistently maintain BOMB close to peg. During epoch expansions the protocol mints BOMB and distributes it proportionally to all BSHARE holders who have staked their tokens in the [**Boardroom**](boardroom.md).

BSHARE has a **maximum total supply of 70,001** tokens distributed as follows:

1. _Treasury/DAO Allocation: 5,500_ BSHARE vested linearly 12 months\*
2. _Team Allocation: 5,000_ BSHARE vested linearly over 12 months
3. _Rewards: 59,500_ BSHARE are allocated for incentivizing liquidity providers in two farming pools for 12 months
4. Initial mint: 1 BSHARE minted upon contract creation for the initial pool

{% hint style="success" %}
The Bomb Money team will use the treasury funds in any way that they feel is best for the long-term success of the protocol.&#x20;
{% endhint %}

### [BBOND - BOMB Bonds](bonds-mechanism.md)

![BBOND](<../.gitbook/assets/bbond-256 (1).png>)

Contract: [0xDA1d9C79240003195d0a67f202efcCCC3F78b994](https://bscscan.com/address/0xda1d9c79240003195d0a67f202efcccc3f78b994)

The main purpose of BOMB Bonds (BBOND) is to help incentivize fluctuations in the BOMB supply during epoch contraction periods. When the TWAP (time-weighted average price) of BOMB falls below 10,000 to 1 BTC, BBONDs are issued and can be bought with BOMB at the current price. Exchanging BOMB for BBOND burns BOMB tokens, taking them out of circulation (deflation) and helps to get the price back up to peg. These BBOND can be redeemed for BOMB when the price is above peg in the future, plus a premium based on how high above peg we currently are. This conversely creates inflation and subsequent sell pressure for BOMB when it is above peg, helping to push it back toward 10,000 BOMB to 1 BTC ratio.

{% hint style="info" %}
Unlike early algorithmic protocols, BBONDs do not have expiration dates.
{% endhint %}

All BBOND holders will be able to redeem their BBOND for BOMB tokens as long as the treasury has a positive BOMB balance, which typically happens when the protocol is in epoch expansion periods.
