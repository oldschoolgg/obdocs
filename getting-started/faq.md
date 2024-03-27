# FAQ

### **How do I see all the things I can do with my minion?**

Read around on this wiki!

### **Where can I report bugs?**

You can make a bug report on the bot's [github page](https://github.com/oldschoolgg/oldschoolbot/issues/new?assignees=\&labels=\&template=bug.md). Before making a bug report, you should consider asking about your issue in the #help-and-support channel of the bot's [support server](https://discord.com/invite/ob).

### **Where can I make suggestions for the bot?**

Suggestions can be made through the bot's [github page](https://github.com/oldschoolgg/oldschoolbot/issues/new?labels=feature+request\&template=feature.md). Before making a suggestion, you should search the [repo](https://github.com/oldschoolgg/oldschoolbot/issues) to see if similar suggestions have already been made.

### **How do I sell items to someone?**

You can sell items to other players using the `/trade` command, which is used like this: `/trade`` `**`user:`**`@USER`` `**`send:`**`QUANTITY ITEM`` `**`price:`**`PRICE`. For example, if you wanted to sell 3 bandos chestplates for a _combined total_ of 50m: `/trade`` `**`user:`**`@Magnaboy`` `**`send:`**`3 Bandos chestplate`` `**`price:`**`50m`.

After using the command, both users will have to confirm the sale.

### **How do I equip gear on my minion?**

There are 8 different setups; Melee, Range, Mage, Skilling, Misc, Wildy. Fashion and Other (Please not that the other setup is locked to T3 patron or Higher). As an example, here's how you can equip a BCP to your melee setup: `/equip`` `**`gear_setup:`**`melee`` `**`item:`**`Bandos chestplate`. If you're doing a boss that needs Melee gear, the bot will check your Melee setup. It's done like this so you don't have to spend a long time equipping and unequipping stuff, you can just have your best stuff in each setup at all times.

The Skilling setup is where you equip skilling-related stuff, for example: Lumberjack or the Prospector outfit.

You also have a cosmetic pet slot, shared across all gear setups. It allows you to equip a pet, like its following your minion around. You can equip a pet using the `/gear pet` command. For example, to equip the Commander Zilyana pet, you would use `/gear pet`` `**`equip:`**`Pet zilyana`. You need to use the exact item name as it is ingame.

### How can I change my attack styles?

You can change your minions [attack style](combat-skills.md) by using `/minion train`` `**`style:`**` ``xxx`. Some monsters or slayer tasks will automatically use a specific attack style, which you cannot override (e.g. EHP slayer tasks that use barrage or a cannon).

### **Can I stop my minion from going on a trip I started by accident?**

Yes. Using the `/minion cancel` command you can tell your minion to drop everything and return at once. However, it takes the command literally and you will not receive any loot or xp, nor will you get any items you would have expended during the trip returned. For example, if you accidentally sent your minion off to smith 10 bronze daggers, using the cancel command would return your minion to idle status, but you would not have returned any bronze daggers, any smithing xp, or any of the 10 bronze bars initially allocated to your minion's trip. Please note you can also not cancel any Massing trips such as Nightmare/Nex/Raids or Minigames, you can also not cancel Inferno/Jad.

### **Why do prices in minions differ?**

The price depends on your account age. If your discord account is over 6 months old, you get it for free. Less than 6 months, and it costs 20m. You can get this initial 20m from asking friends, or by using `/minion daily` every day for a while.

### **How do I get money for a minion?**

There are two options: `/minion daily` and `/gamble dice`.

### **Why can't I use minion commands?**

This could be one of 3 reasons: either your account looks like an **alt**, your account is too **new**, or you have been banned for breaking the rules. Your Discord account needs to be at least **30 days** old.

### **Is RWT or autotyping against the rules?**

YES. You will be banned from the bot, it's not allowed. To date, there have been hundreds of users caught doing this and all have been wiped/banned.

### **Can I create an alt account?**

NO. You will be permanently banned from the bot on all accounts. However, you may create a single alt account as a permanent ironman, but you are not allowed to de-iron - ever. De-ironing the account for any reason will be considered as an alt and you will be banned. All other alt accounts are not permissible and you will be caught and banned. Creating an alt account is subject to the same restrictions regarding Discord account age as all other accounts.

### **I can't tell which items are which in my bank, how do I see what they are?**

You can use `/bank`` `**`flag:`**`show_names` or `/bank`` `**`format:`**`text_paged` to see the names of your items.

### **How do I sell all my bank, or an entire page, at once?**

This is not currently possible, but might be added in a future update.

### **How do I search for specific items in my bank?**

You can use `/bank`` `**`search:`**`TEXT` to search for items in your bank, for example, to see all dragon items in your bank, you could do: `/bank`` `**`search:`**`dragon`. If searching for an item with spaces, surround the item with double quotes `"`. For example: `/bank`` `**`search:`**`"golden nugget"`.

### **I got a pet from /daily but it doesn't show in my bank or collection log?**

The pets from `/minion daily` are separate to pets your minion pets, and are only shown in `/tools user mypets`. You have 2 separate groups of pets, `mypets` and then you have the real item pets in your `/bank` that you have gotten from killing stuff and training skills.

### **Do I need to equip items to receive the boosts they provide?**

Skilling boosts _only_ work when equipped in your skilling gear setup, while most bossing/PVM boosts currently work either when equipped or when in your bank. It is recommended to equip a set of graceful in your misc setup and leave the skilling setup for skilling outfits.

### **Why does my boost to skilling not show up when I have my boost item equipped?**

Certain boosts will be displayed at the start of your minion's trip while others will be displayed at the end, so pay attention to the displays both at the start and end of your trips. Additionally, some skilling items like dragon equipment are subject to the same skill level barriers as OSRS, so you will not see boosts from those items until your skill reaches the requisite level.

### **How do I get X item?**

You get most items exactly the same as you get them in the real game, all monsters drop the same things as ingame.

If it is a quest reward or thing you usually buy from a shop, you can get it by using `/buy`. Graceful can be obtained with 260 marks of grace and using the `/create`` `**`item:`**`graceful` command. If the item, like the graceful outfit, requires other items to be obtained, it will most often be obtained using the `/create` command. For example, to create an odium ward you would use the command `/create`` `**`item:`**`odium ward` which would consume the three odium shards in your bank and return a fully formed odium ward.

Note that not all items are currently obtainable via either of these two methods.

### **How do I create a godsword?**

Example: `/create`` `**`item:`**`Bandos godsword` - note it requires you have the required Smithing level. You can pay another player to make it for you in the [support server.](https://www.discord.gg/ob), if you wish.

### **Can I charge my items from Zulrah?**

You can [charge](../miscellaneous/charging-items.md) your [zulrah uniques](../bosses/zulrah.md) once they have been crafted/fletched into their respective usable counterparts. Mutagens currently cannot be added to serp helms.

### **How do I get Barrows gloves?**

The various gloves require quest points and gp to buy. Barrows gloves require 175 quest points and 1m gp. The full list of gloves can be found on the [buyables page](../miscellaneous/buyables.md).

### **How do I get Runecrafting pouches?**

There are 5 pouches available to players. There are no requirements obtain them, you simply type`/create`` `**`item:`**`medium pouch`, but you will still need the required [runecrafting](../skills/runecrafting/) level to use them. The only pouch that requires a crafting level is the Colossal pouch.&#x20;

### **Can I pay a fee to have the bot make my Dragonfire Ward/Shield or Spectral/Arcane/Elysian/Blessed Spirit Shield for me?**

No. However, you can pay another player with the required levels to make it for you. You can look for someone to do it for you in the [support server.](https://www.discord.gg/ob)

### **Will X be added to the bot?**

I plan on adding all skills, minigames and bosses from OSRS to the bot. Anything that can reasonably be added will be added in time.

### **Can you stack clues on Old School Bot?**

No, you can't. It works like in-game. You can have multiple caskets, but not clue scrolls.

### **Diango says I got the daily wrong despite it being correct?**

This usually means you answered the question late, the incorrect message can be a bit delayed.

### **Why is the bot not responding to any commands?**

First, mention the bot (like this: `@Old School Bot`), and it will tell you what prefix it is set to use for your server. If it still doesn't respond, It could have to do with permissions the bot has. If you're not sure how to fix this, you can ask in the [support server](https://discord.gg/ob).

### **How do I create a Barrows set, or deconstruct a Barrows set into the items?**

Here's an example: `/create`` `**`item:`**`dharoks armour set` to turn items into a set, or `/create`` `**`item:`**`unpack dharoks armour set` to turn the set back into the items.

### **The bot says it needs permission to ‘Manage messages’ in order to use a command. How do I do this?**

Server settings > Roles > Old School Bot (The auto assigned one) > Turn `Manage Messages` on.

### **How do I change my Bank Background?**

In order to change your bank background you will need to do `/minion bankbg`` `**`name:`**` ``default` as an example to see a list of potential bank backgrounds and how to obtain them head to [Bank background](bank-background.md).

### **How do I revert items?**

In order to revert items you will start by doing `/create`` `**`item:`**` ``revert` and searching for or typing in the item you are looking to revert. For a list of all those items that you can revert make sure you go to our page for [Reverting Items](../miscellaneous/reverting-items.md)

### How can I claim my free T1 perks after maxing in both bots?

After you have level 99 in every skill in OSB and level 120 in every skill in [BSO](bso-bot-school-old.md), you can claim your free T1 perks with `/claim`` `**`name:`**`Free T1 Perks`. It may take a small amount of time for the perks to kick in so please be patient after running the command.

### I lost a significant boost while doing raids, what happened?

There is a chance one of the items you had equipped became uncharged. When an item loses it's charges, it is usually unequipped and put back in your bank, therefore seeming like you lost a boost to your raid score. Simply [charge your item](../miscellaneous/charging-items.md) again and re-equip it.
