# 💠 Platform

## Boardroom

**Epoch duration:** 6 hours\
\
****Deposits / Withdrawal of MSHARE into the Boardroom will lock MSHARE for 4 epochs (24hrs) and MvDOLLAR rewards for 2 epochs (12hrs).&#x20;

The above is the same for MvDOLLAR rewards claiming, this will lock staked MSHARE for 4 epochs (24hrs) and the next MvDOLLAR rewards can only be claimed after 2 epochs (12hrs).

### Distribution of MvDOLLAR  during Expansion

**80%** as Reward for Boardroom MSHARE stakers\
**20%** goes to NFT Staking Contracts\
\
**Epoch Expansion:** Current expansion cap base on MvDOLLAR supply, if there are bonds to be redeemed, 65% of minted MvDOLLAR goes to treasury until it’s sufficiently full to meet bond redemption. If there is no debt it will follow max capped expansion rate.

### Boardroom **UI Information**

**Next Epoch** indicates a countdown timer to the next calculation of seigniorage. (Each epoch duration lasts for 6 hours)                                                                                                              &#x20;

**APR** refers to the simple returns in USD value relative to the amount of MSHARE staked (USD value).

_Note: **** APR fluctuates from time to time and is dependent on certain factors such as:_\
****Price of MvDOLLAR\
Price of MSHARE \
Amount of MSHARE staked in Boardroom

### Boardroom **on Contraction Periods**

The Boardroom will **not** mint any MvDOLLAR while TWAP < 1.01

### Boardroom **on Debt Phase**

****\
****Debt Phase takes place on the expansion epochs that start after a contraction period where there are still MvBONDs to be redeemed.

65% of Expansion during Debt Phase is allocated to the Treasury Fund to prepare for the MvBOND Redemption. This amount is still reserved whether or not **MvBOND** holders are redeeming bonds or not. Once MvDOLLAR in treasury is sufficiently full to meet all circulating bond redemption, expansion rates will resume too normal.

MvBOND emitted per epoch during contraction periods can be found on Regulations.

## **Shares**&#x20;

{% hint style="info" %}
**Allocations may change.**
{% endhint %}

Stake your LP to earn MSHARE share tokens

Shares Pools (Shares Reward) available for 12 months:                                                                                                                                                                 &#x20;

* MvDOLLAR-USDC LP: 18000 Shares
* MSHARE-USDC LP: 17000 Shares
* MSHARE-MvDOLLAR LP: 6000 Shares

## **Bonds**

****\
**MvBONDs** are available for purchase when MvDOLLAR falls below the peg. If MvDOLLAR's TWAP is between 1.00 and 1.01, neither MvBOND nor MvDOLLAR will be issued.

e.g. if MvDOLLAR TWAP < 1, exchange MvDOLLAR for MvDOLLAR will be in a 1:1 ratio.

MvBOND are available for redemption when MvDOLLAR goes above the 1 USDC peg.

To encourage redemption of MvBOND for MvDOLLAR when MvDOLLAR TWAP > 1.1 and incentivize users to redeem at a higher price, MvBOND redemption will be more profitable with a higher MvDOLLAR TWAP value, of which MvBOND to MvDOLLAR ratio will be 1:R, where R can be calculated in the formula as shown below _****_ where coeff = 0.7.

$$
R=1+[(MvDOLLAR(​twapprice)−1)∗coeff)]
$$
