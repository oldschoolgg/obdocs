---
description: Overview of how to use bank filters
---

# Bank Filters

There are a multitude of bank filters you can use to easily identify or search items in your bank. You can start by typing the /`b` command to display your bank. It is also possible to view the different pages of your bank with /`b X` (X being any page number).

### Searching Your Bank

There are 2 ways to search your bank for items.

* `/b [full item name]`
  * This command only returns results when the full item name is entered.
* `/bs [partial/full item name]`
  * This command will return anything that contains the term searched.

### Universal Filters

The following bank filters can be used with either of the bank search commands to display further information about each item or display the search results in a different format.

**Note:** You can combine many of these universal filters in your bank search (in any order).

* `--names` - displays the name of each item
* `--text` - displays the names of items in plain text format
* `--sv` - displays the sell value of items
* `--av` - displays the alch value of items
* `--id` - displays the ID of items
* `--ph` - includes currently equipped items (and their value) in your search results
* `--full` - displays the entire bank search in one image (or full bank if no other filters used)
* `--wide` - displays a wider bank image (MUST be used with --full)
* `--sort=name/value/alch` - sorts your results by name, value, or alch price
* `--text --full` - allows you to export your bank items in plain text format

The following command is an example of a bank search for the term "rune" with many filters.&#x20;

* E.g. /`bs rune --full --wide --sort=name --names`

![](../.gitbook/assets/rune\_search.png)

### Category Filters

The following bank filters can be used with either of the bank search commands to display items of a specific category. Universal filters can also be applied to these searches.

* `--food` - displays your food that can be used during PvM
* `--potions` - displays your potions
* `--herbs` - displays your clean and grimy herbs
* `--compost` - displays your compost and compostable items
* `--secondaries` - displays your herblore secondaries
* `--diary` / `--ad` - displays your achievement diary rewards and lamps
* `--clues` / `--tt` -- displays your clue scrolls and reward caskets
* `--herblore` - displays herbs, secondaries and potions
* `--farming` / `--seeds` - displays seeds and compost
* `--smithing` / `--smith` - displays any items related to the smithing skill
* `--crafting` / `--craft` - displays any items related to the crafting skill
* `--fletching` / `--fletch` - displays any items related to the fletching skill
* `--agility` / `--agi` - displays any items related to the agility skill
* `--prayer` / `--pray` - displays all bones and ensouled heads
* `--equippables` - displays your equippable items
* `--untradeables` - displays your untradeable items
* `--tradeables` - displays your tradeable items
* `--diango` / `--daily` - displays items from the daily rewards

### Collection Log Filters

The collection log filters can be used with either of the bank search commands to display the items from specific collection logs. Not all collection logs are available for bank searching. Universal filters can also be applied to these searches.

* E.g. /`b --cerberus`

![](../.gitbook/assets/cerberus\_bank.png)

* Some other collection logs that can be search include:
  * `--gwd` - displays all unique items from the 4 godwars bosses
  * `--dks` - displays all unique items from the 3 dagannoth kings
  * `--skilling` / `--skill` - displays any items that can be used to gain non-combat xp
  * `--slayer` - displays all unique slayer items
  * `--pets` - displays any pets you own
  * `--raids` - displays any raid uniques
  * `--capes` - displays any capes (including skillhoods)
  * `--quest` - displays any quest based items
  * `--random` - displays any items you received from random events
  * `--implings` - displays any impling jars you've caught
  * `--tzhaar` - displays any tzhaar items
  * `--revenants` - displays any revenant based items
  * `--cyclopes` - displays all obtained defenders
  * `--miscellaneous` - displays any miscellaneous items

### Other Filters

Here you can find other filters and bank related commands. Universal filters can also be applied to these searches.

* `/b --filter="clues [tier]"` - displays all clue items from a specific tier
  * Tiers can be: _easy / medium / hard / elite / master / shared / all_
* `--smallbank` - removes the extra space when displaying your bank background&#x20;
  * ONLY applies to players with custom bank backgrounds
  * This cannot be turned off if you are using the default bank background.
