# Platform

## Boardroom

* Epoch duration: 6 hours
* Deposits / Withdrawal of BSHARE into/from the Boardroom will lock BSHARE for 6 epochs and BOMB rewards for 3 epochs.&#x20;
* BOMB rewards claim will lock staked BSHARE for 6 epochs and the next BOMB rewards can only be claimed 3 epochs later
*   Distribution of BOMB during Expansion

    **80%** as Reward for Boardroom BSHARE Stakers

    **15%** goes to DAO fund

    **5%** goes to DEV fund
* Epoch Expansion: Current expansion cap base on BOMB supply, if there are bonds to be redeemed, 65% of minted BOMB goes to treasury until its sufficiently full to meet bond redemption. If there is no debt it will follow max capped expansion rate

### Boardroom UI Available information

Next **Seigniorage** indicates a countdown timer to the next epoch. (Each epoch duration lasts for 6 hours)                                                                                                              &#x20;

**APR** refers to the simple returns in USD value relative to the amount of BSHARE staked (USD value).\
_Note: **** APR fluctuates from time to time and is dependent on certain factors such as:_

* Price of BOMB
* Price of BSHARE
* Amount of BSHARE staked in Boardroom(Locked Value)

### Boardroom on Contraction Periods

Boardroom will **not** mint any BOMB (_NO REWARDS ON BOARDROOM_) while TWAP < 1.01

### Boardroom on Debt Phase

Debt Phase take place on the expansion epochs that start after a contraction period where there are still Bbonds to be redeemed.

65% of Expansion during Debt Phase is allocated to the Treasury Fund to prepare for the BBOND Redemption. This amount is still reserved  whether or not BBOND holders are redeeming bonds or not.

Once BOMB in treasury is sufficiently full to meet all circulating bond redemption, expansion rates will resume to normal.

BBOND emitted per epoch during contraction periods can be found on Regulations.

## Shares

Stake your LP to earn BSHARE tokens

Shares Pools (Shares Reward) available for 12 months:

* BOMB-BTCB LP: 35500 Shares
* BSHARE-BNB LP: 24000 Shares

## Bonds

BBOND (bond tokens) are available for purchase when BOMB falls below the peg. If BOMB's TWAP is between 1.00 and 1.01, neither BBOND nor BOMB will be issued.

e.g. if BOMB's TWAP < 1, exchange BOMB for BBOND will be in a 1:1 ratio.

BBOND (bond tokens) are available for redemption when BOMB goes above the 1 BTCB peg.

To encourage redemption of BBOND for BOMB when BOMB TWAP > 1.1 and incentivize users to redeem at a higher price, BBOND redemption will be more profitable with a higher BOMB TWAP value, of which TBOND to BOMB ratio will be 1:R, where R can be calculated in the formula as shown below:

&#x20;                       R=1+\[(BOMB(​twapprice)−1)∗coeff)]

Where coeff = 0.7
