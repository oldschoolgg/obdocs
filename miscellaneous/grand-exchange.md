# Grand Exchange

The bot has it's own GE system which functions almost identically to how it does in the real game. Only tradable items can be bought and sold. Ironmen cannot use this function. Others things to be aware of:

* The maximum price per item is 2b and the maximum quantity per item listing is 5m.
* When buying or selling, the price is per item, not total price.
* 1% of all sales are deducted automatically which acts as a gold sink.
* There are buy limits (which resets every 4 hours).
* There are currently no market prices on items.
* You currently cannot see other players offers.
* You will be DM'ed by the bot when your item has bought/sold.
  * These DMs can be toggle off through `/config user toggle`

## Commands

**/ge buy**

* `/ge buy`` `**`item:`**` ``Rune scimitar`` `**`quantity:`**` ``250`` `**`price:`**` ``30k`

**/ge sell**

* `/ge sell`**`item:`**` ``Blue partyhat`` `**`quantity:`**` ``10`` `**`price:`**` ``1k`

**/ge cancel**

* This will cancel your listing. There is no confirmation for this command.

**/ge my\_listings**

* This will show all active listings you have.

## Number of GE Slots

Currently, all users will have 1 GE slot for buying or selling items. More slots can be unlocks (up to a maximum of 6) by completing the following tasks:

* 100 total level
* 250 total level
* 1000 total level
* 30% total CL completion
* 10k [BSO leagues points](https://bso-wiki.oldschool.gg/leagues)

In addition to this, players with T3 patron automatically have 3 extra GE slots (for a total of 9).

