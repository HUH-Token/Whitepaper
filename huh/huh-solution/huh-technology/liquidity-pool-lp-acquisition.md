# Liquidity Pool (LP) acquisition

LP acquisition in basic terms means increasing the available liquidity by adding more HUH tokens and BNB into the LP. This feature is important because it enables the value of HUH tokens to increase over time.

## **How does it work?**

On every buy and sell transaction, a fee is taken, known as the liquidity fee, which is stored in the smart contract. Please note, the fees taken are in HUH tokens not BNB. The HUH tokens taken are then accumulated in the contract until it reaches a threshold that triggers the ‘Swap and Liquify’ function.

## **Swap and Liquify**

This function is automatically executed when the accumulated HUH tokens on the smart contract reach a defined threshold, at this time, the designated portion is split into two equal halves: the first half is sold for BNB and the acquired BNB is then paired with the second half in HUH and both are then added to the LP.
