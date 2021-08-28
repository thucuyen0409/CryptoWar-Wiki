# Oracle

## Purpose

The price oracle's purpose is to balance the xBlade payout gained through combat, along with minting and reforging costs to the current dollar value of xBlade.

This means that the following will happen if the dollar value per xBlade **increases**:

* xBlade payouts decrease
* Mint Character costs less xBlade
* Mint Weapon costs less xBlade
* Reforge costs less xBlade

Conversely, if xBlade price in dollar falls under a specific amount the opposite of the above becomes true.

The oracle will ensure that daily income will always be larger than gas fee costs, unless the player chooses to lose a majority of their daily fights.

{% hint style="info" %}
The Oracle will dynamically adjust fight payouts up or down depending on changes in the dollar value of xBlade.
{% endhint %}

## Reason

The reason for the oracle's usage is so that the economy of the game is balanced around a set dollar value. There is a limited amount of xBlade token that can circulate in the economy, and an increase in users would likely drain all the xBlade present in the game contract.

By utilizing the oracle, CryptoWar forms a correlation between active users and the dollar value of xBlade. The assumption is that when xBlade price rises, the demand for xBlade increases as well through the release of new game features or an influx of new players.

The oracle will ensure consistent dollar value payouts per fight transaction at the time it was made, along with ensuring mint costs for NFTs remain at a consistent dollar value. This means that entry costs can be balanced and kept low enough to allow new players a chance to play even if the dollar value of xBlade rises.

## Obtaining Oracle xBlade/Dollar Rate

The oracle keeps track of the current dollar value of xBlade, and updates at an undisclosed rate to prevent players from taking advantage of the fluctuations in xBlade/Dollar price.

To get the current rate of the oracle, follow the steps outlined below:

1. Go to the oracle contract here : [**Oracle**](https://bscscan.com/address/0x1cbfa0ec28da66896946474b2a93856eb725fbba#readProxyContract)\*\*\*\*

2. Click on the number indicated by Function 3. currentPrice.

![Taken July 23, 2021](../../.gitbook/assets/current-price.png)

3. Copy the value indicated in the BNB \(1\) row.

![Taken July 23, 2021](../../.gitbook/assets/bnb.png)

4. Divide 1 by that copied value. The result is what the oracle thinks xBlade is currently worth in dollars.

If the calculated amount is different from the actual dollar value of xBlade you can expect nerfs to payouts and cheaper mint costs if the oracle is under ****the current value of xBlade, and the opposite if the oracle is over the current value of xBlade.

