# Wallet

This exercise was tasked to me by CodeClan, Glasgow where I studied towards a PDA Level 8 in Professional Software Development. The exercise brief can be found below.

## Brief

Take the start code and have a look through it. You will see that there is a Wallet class which has four ArrayLists, one each for DebitCards, CreditCards, LoyaltyCards and Tickets.

**MVP**

- Create an IScan interface and have all the classes implement it. This interface should have a Scan method which has no parameters and returns a String

- Replace the four ArrayLists with one ArrayList which contains all the items in the wallet

- Replace all the overloaded versions of the addItem method with one method which adds an item to the newly created ArrayList

**Extension**

Thinking of the DebitCard and CreditCard classes and that there are things common to both classes, can you think of a way to refactor the code so that the common code is in one place, but not breaking the refactoring you’ve already done?
