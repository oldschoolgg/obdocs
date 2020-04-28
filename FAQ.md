[Edit this page on Github](https://github.com/gc/obdocs/blob/master/FAQ.md)

##### How do I see all the things I can do with my minion?
Most of the information on minions is on the [minions page](https://www.oldschool.gg/oldschoolbot/minions).

##### Why do prices in minions differ?
The price depends on your account age. If your discord account is over 1 year old, you get it for free. Less than 1 year, and it costs 50m. You can get this initial 50m from asking friends, or by using `+daily` every day for a while.

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

##### I got a pet from `+daily` but it doesn't show in my bank or collection log?
The pets from `+daily` are separate to pets your minion pets, and are only shown in `+mypets`.  You have 2 separate groups of pets, `+mypets` and then you have the real item pets in your `+bank` that you have gotten from killing stuff and training skills.

##### How do I create a godsword?
Example: `+create Bandos godsword` - note it requires you have the required Smithing level. You can pay another player to make it for you, if you wish.

##### How do I search for specific items in my bank?
You can use `+bank --search=name` to search for items in your bank, for example, to see all dragon items in your bank, you could do: `+b --search=dragon`.

