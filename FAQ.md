[Edit this page on Github](https://github.com/gc/obdocs/blob/master/FAQ.md)

##### How do I see all the things I can do with my minion?
Most of the information on minions is on the [minions page](https://www.oldschool.gg/oldschoolbot/minions).

##### Why do prices in minions differ?
The price depends on your account age. If your discord account is over 6 months old, you get it for free. Less than 6 months, and it costs 20m. You can get this initial 20m from asking friends, or by using `+daily` every day for a while.

#### Is RWT or autotyping against the rules?
YES. You will be banned from the bot, it's not allowed. To date, there has been 100+ users caught doing this and all have been wiped/banned.

##### I found a bug in the bot, where do I report it?
You can either make a github issue in the bot repo: [gc/oldschoolbot](https://github.com/gc/oldschoolbot) OR join the [support server](http://support.oldschool.gg/) and post the bug in the help/support channel.

##### I can't tell which items are which in my bank, how do I see what they are?
You can use `+bank --text` or `+bank --text --full` to see the names of your items.

##### How do I create a Barrows set, or deconstruct a Barrows set into the items?
Here's an example: `+create Dharoks armour set` to turn items into a set, or `+create Dharoks` to turn the set back into the items.

##### How do I sell all my bank, or an entire page, at once?
This is not currently possible, but might be added in a future update.

##### How do I sell items to someone?
You can sell items to other players using the `+sellto` command, which is used like this: `+sellto @person [totalprice] [quantity] [item]`. For example, if you wanted to sell 3 bandos chestplates for a *combined total* of 50m: `+sellto @Magnaboy 50m 3 Bandos chestplate`.

After using the command, both users will have to confirm the sale.

##### Can I trade items with someone else?
It is currently not possible to trade someone items for items, however you can use the `+sellto` command (see above) to sell items to another player.

##### I got a pet from `+daily` but it doesn't show in my bank or collection log?
The pets from `+daily` are separate to pets your minion pets, and are only shown in `+mypets`.  You have 2 separate groups of pets, `+mypets` and then you have the real item pets in your `+bank` that you have gotten from killing stuff and training skills.

##### How do I create a godsword?
Example: `+create Bandos godsword` - note it requires you have the required Smithing level. You can pay another player to make it for you, if you wish.

##### Can I pay a fee to have the bot make my Dragonfire Ward/Shield or Spectral/Arcane/Elysian/Blessed Spirirt Shield for me?
No. However, you can pay another player with the required levels to make it for you. You can look for someone to do it for you in the [support server.](https://www.discord.gg/ob)

##### How do I search for specific items in my bank?
You can use `+bank --search=name` to search for items in your bank, for example, to see all dragon items in your bank, you could do: `+b --search=dragon`.

##### How do I get runecrafting pouches?
There are 4 pouches, and the bot does it a bit differently to ingame. To obtain them, you first need the crafting level required for each tier (1, 10, 20, 30), and then a little bit of leather, and simply `+create medium pouch`.

##### How do I get Barrows gloves?
The various gloves require quest points and gp to buy. Barrows gloves require 175 quest points and 1m gp. The full list of gloves can be found on the [minions page.](https://www.oldschool.gg/oldschoolbot/minions?Buyable%20items)

##### Do I need to equip items to receive the boosts they provide?
Skilling boosts *only* work when equipped in your skilling gear setup, while bossing/PVM boosts currently work either when equipped or when in your bank.

##### How do I get X item?
You get most items exactly the same as you get them in the real game, all monsters drop the same things as ingame.

If it is a quest reward or thing you usually buy from a shop, you can get it by using `+buy`. Graceful can be obtained with 260 marks of grace and using the `+create graceful` command. Note that not all items are currently obtainable via either of these two methods.

##### Will X be added to the bot?
I plan on adding all skills, minigames and bosses from OSRS to the bot. Anything that can reasonably be added will be added in time.

##### Where can I make suggestions for the bot?
Join http://support.oldschool.gg/ and post your suggestion in the suggestions channel and we'll consider adding it.

##### Can you stack clues on Old School Bot?
No, you can't. It works like ingame.

##### How do I equip gear on my minion?
There are 5 different setups; Melee, Range, Mage, Skilling, and Misc. As an example, here's how you can equip a BCP to your melee setup: `+equip melee Bandos Chestplate`. If your doing a boss that needs Melee gear, the bot will check your Melee setup. It's done like this so you don't have to spend a long time equipping and unequipping stuff, you can just have your best stuff in each setup at all times.

The Skilling setup is where you equip skilling-related stuff, for example: Graceful or the Prospector outfit.

You also have a cosmetic pet slot, shared across all gear setups. It allows you to equip a pet, like its following your minion around. You can equip a pet using the `+equippet` command. For example, to equip the Commander Zilyana pet, you would use `+equippet pet zilyana`. You need to use the exact item name as it is ingame. 

##### How do I get money for a minion?
There's two options: `+daily`, `+dice` or if you're lucky, someone will gift you money.

##### Why can't I use certain commands?
This could be one of 2 reasons: either your account looks like an **alt** or your account is too **new**. Your Discord account needs to be at least **30 days** old.

##### Diango says I got the daily wrong despite it being correct?
This usually means you answered the question late, the incorrect message can be a bit delayed.

##### Why is the bot not responding to any commands?
First, mention the bot (like this: `@Old School Bot`), and it will tell you what prefix it is set to use for your server. If it still doesn't respond, It could have to do with permissions the bot has. If you're not sure how to fix this, you can ask in the [support server](https://discord.gg/ob).

##### The bot says it needs permission to ‘Manage messages’ in order to use a command. How do I do this?
Server settings > Roles > Old School Bot (The auto assigned one) > Turn `Manage Messages` on.
