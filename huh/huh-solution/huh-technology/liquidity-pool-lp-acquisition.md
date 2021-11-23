# Liquidity Pool (LP) acquisition

LP acquisition in basic terms means increasing the available liquidity by adding more HUH tokens and BNB into the LP. This feature is important because it increases the value of HUH tokens over time.

## **How does it work?**

On every buy and sell transaction, a fee is taken that is known as the liquidity fee which is stored in the contract. Please note, the fees taken are in HUH tokens not BNB. The HUH tokens taken are then accumulated in the contract until it gets to a threshold that triggers the ‘Swap and Liquify’ function.

## **Swap and Liquify**

This function is executed when the accumulated HUH tokens on the contract reaches a defined threshold where a designated portion is split into two equal halves.  The first half is sold for BNB, the acquired BNB is paired with the second half in HUH and both are then added to the LP.
