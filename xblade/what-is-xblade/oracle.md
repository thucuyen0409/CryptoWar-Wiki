# Oracle

## Purpose

The price oracle imperatively targets to bring the xBlade payout gained by combat as well as minting and reforging fees into line with the current dollar value of xBlade

This indicates that if the dollar value per xBlade rises, the following will happen:

<li>xBlade payouts falls down</li>

<li>xBlade required for Mint Characters decreases</li>

<li>xBlade required for Mint Weapons decreases</li>

<li>xBlade required for Reforge decreases</li>

In the event that the price of xBlade in dollar falls below a threshold, xBlade payouts and requirements will increase. 

The oracle ensures that if players win a majority of their daily fights, they will earn more xBlade which is enough to pay for gas fee costs.

Depending on the changes in the dollar value of xBlade, the Oracle will dynamically adjust fight payouts up or down. 

## Reason

The purpose of using Oracle is to withhold the value of in-game currency at a fixed cost. There appears to be a stipulation for the amount of xBlade token circulating in the economy. For that reason, a remarkable increase in the number of users results in an outflow of all xBlade in the contract.

Thanks to the oracle, CryptoWar creates an interrelationship between active users and the currency value of xBlade. Assuming that xBlade price increases, the demand for xBlade will increase, owing to specimen of new game features or an influx of new players. 

The oracle empowers the fight transaction fees as well as minting fees for NFTs to be kept at a constant-dollar value, which permits new players to engage in the game with an affordable entrance fees even if the dollar value of xBlade rises.

## Obtaining Oracle xBlade/Dollar Rate

The Oracle follows the current dollar value of SKILL and changes SKILL price accordingly at an undisclosed rate to keep everything fair and unbiased between all players.

The following are steps to get the current rate of the oracle:

<li>Go to the oracle contract here: Oracle</li>

<li>Click on the number indicated by Function 3. currentPrice</li>

![image](https://user-images.githubusercontent.com/90205972/134936000-6d9e3a48-5079-4453-81b5-1132e7650fa4.png)

<li>Copy the value indicated in the BNB (1) row</li>

![image](https://user-images.githubusercontent.com/90205972/134936095-7ab9f05f-8a89-431a-9fa6-c48cf2ce5654.png)

<li>Divide 1 by that copied value. The result is the current dollar value of xBlade according to the oracle.</li>

When the calculated amount is different from the actual dollar value of SKILL, buffs to payouts and mint costs are expected if the Oracle is above the current value of SKILL, and vice versa, nerfs if below.
