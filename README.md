# Welcome to the Old School Bot Wiki!

The official wiki for Old School Bot. This wiki contains information and guides for the bot.

## Welcome to the Old School Bot Wiki!

Old School Bot is a discord bot based around Old School RuneScape. It has fun and useful commands, such as showing your account stats or simulating the loot from monsters and clues.

## Minions

Minions are a feature in Old School Bot that let you simulate playing a virtual RuneScape account in Discord. You control a minion, who you send out to do various tasks, like killing monsters for loot, completing clue scrolls, and training skills. With the loot they get, you can craft items, sell them, and trade to other real players.

You can also read the [FAQ](getting-started/faq.md) for answers to common questions.

Minions are entirely virtual, and not in any way tradeable for real GP or real money. It's simulating the real game for fun. We strictly do not allow any bot users to break any of the official OSRS rules. Read the rules here: Old School Bot Rules

## Getting Started

**To get started, firstly read the** [**rules**](getting-started/rules.md), then get yourself a minion by typing `/minion buy`. If your Discord account is 6 months old or older, your minion will be free. If it is between 1 and 6 months old, your minion will cost 20m. If your account is less than one month old, you are currently unable to purchase a minion as a precaution against alt accounts and bots (unless you become a patron which bypasses this restriction). To get your starting gp, you can use the `/minion daily` command every 12 hours to get a trivia question you can answer for gp and special Diango items.

Next, decide what you want to do. Skilling? PVM? Questing? Have a look around the rest of the wiki to see what you can do, and how - and just do whatever you want to do!

## Minion Icons

You can sacrifice items, and their GP value will go towards you unlocking new minion icons. You will automatically receive the icon immediately after sacrificing enough GP.

You can sacrifice items by using: `/sacrifice` (to specify quantity, put the number before the name).

* E.g. `/sacrifice`` `**`items:`**` ``bandos chestplate`
* E.g. `/sacrifice`` `**`items:`**` ``1000 gold ore`
* E.g. `/sacrifice`` `**`items:`**` ``100m coins`

You receive a 15 second bonus to your maximum trip length for every 2.5b gp you sacrifice. This scales up to a 1 minute increase when you've sacrificed a total of 10b gp. This scaling is halved for ironmen, only requiring 5b gp to get the 1 minute increase.

You can see a leaderboard of who has sacrificed the most value using `/lb sacrifice`` `**`type:`**` ``Most Value Sacrificed`

Tier 3 patrons or above receive 3 times the bonus to their trip length from sacrifice value. For example, a tier 3 patron with 2.5b sacrificed will receive a 45 second bonus and with 10b sacrificed will receive a 3 minute bonus.

![](<.gitbook/assets/image (6) (1) (1).png>)

## Bank Backgrounds

You can change your bank background using `/minion bankbg`` `**`name:`** . The image will replace the background of your bank. Bank backgrounds require that you pay GP, items and have certain items in your collection log. They are supposed to be difficult to obtain.

To see all available backgrounds, please visit the [bank backgrounds page](getting-started/bank-background.md).

Click on the bank bg name to see what it looks like.

| Name                                                                                                                                           | GP Cost | Item Cost                                       | Collection Log Requirement                                 |
| ---------------------------------------------------------------------------------------------------------------------------------------------- | ------- | ----------------------------------------------- | ---------------------------------------------------------- |
| [Bandos](https://raw.githubusercontent.com/oldschoolgg/oldschoolbot/master/src/lib/resources/images/bank\_backgrounds/7.jpg?raw=true)          | 100m    | All 5 Godswords                                 | All GWD Items (Including pets & Nex)                       |
| [Corporeal Beast](https://raw.githubusercontent.com/oldschoolgg/oldschoolbot/master/src/lib/resources/images/bank\_backgrounds/8.jpg?raw=true) | 100m    | 1 of each Elysian/Spectral/Arcane Spirit Shield | All Corp Items (Including pet and 4x spirit shield/elixir) |
| [Nightmare](https://raw.githubusercontent.com/oldschoolgg/oldschoolbot/master/src/lib/resources/images/bank\_backgrounds/10.jpg)               | 100m    | All 3 Orbs                                      | All Nightmare Items                                        |
| [Casket](https://github.com/oldschoolgg/oldschoolbot/blob/master/src/lib/resources/images/bank\_backgrounds/13.jpg?raw=true)                   | 100m    |                                                 | Large spade, Clueless scroll, Heavy casket, Scroll sack    |

### Patron-only bank backgrounds

These backgrounds are only available for purchase and usage by patrons.

Some of these also have an item cost/collection log requirement. You can view these by trying to purchase the background with `/minion bankbg`.

| Name                                                                                                                                 | GP Cost          | Patron Tier |
| ------------------------------------------------------------------------------------------------------------------------------------ | ---------------- | ----------- |
| [Lumbridge](https://raw.githubusercontent.com/oldschoolgg/oldschoolbot/master/src/lib/resources/images/bank\_backgrounds/3.jpg)      | 10m              | 3           |
| [Edgeville](https://raw.githubusercontent.com/oldschoolgg/oldschoolbot/master/src/lib/resources/images/bank\_backgrounds/5.jpg)      | 10m              | 3           |
| [Dark](https://raw.githubusercontent.com/oldschoolgg/oldschoolbot/master/src/lib/resources/images/bank\_backgrounds/11.jpg)          | 10m              | 3           |
| [Grass](https://raw.githubusercontent.com/oldschoolgg/oldschoolbot/master/src/lib/resources/images/bank\_backgrounds/13.jpg)         | 10m              | 3           |
| [Wilderness](https://github.com/oldschoolgg/oldschoolbot/blob/master/src/lib/resources/images/bank\_backgrounds/16.jpg?raw=true)     | 100m             | 3           |
| [Grand Exchange](https://github.com/oldschoolgg/oldschoolbot/blob/master/src/lib/resources/images/bank\_backgrounds/17.jpg?raw=true) | 2,147,483,647 GP | 3           |
| [Falador Park](https://github.com/oldschoolgg/oldschoolbot/blob/master/src/lib/resources/images/bank\_backgrounds/18.jpg?raw=true)   | 100m             | 3           |
| [Pets](https://github.com/oldschoolgg/oldschoolbot/blob/master/src/lib/resources/images/bank\_backgrounds/19.png?raw=true)           | 20m              | 3           |
| [Smokey](https://github.com/oldschoolgg/oldschoolbot/blob/master/src/lib/resources/images/bank\_backgrounds/21.png?raw=true)         | 20m              | 3           |
| [Nieve](https://github.com/oldschoolgg/oldschoolbot/blob/master/src/lib/resources/images/bank\_backgrounds/22.jpg?raw=true)          | 20m              | 3           |
| [ToB](https://github.com/oldschoolgg/oldschoolbot/blob/master/src/lib/resources/images/bank\_backgrounds/23.png?raw=true)            | 20m              | 3           |
| [Zilyana](https://github.com/oldschoolgg/oldschoolbot/blob/master/src/lib/resources/images/bank\_backgrounds/24.jpg?raw=true)        | 20m              | 3           |
| Konar                                                                                                                                | 20m              | 3           |
| [Morytania](https://raw.githubusercontent.com/oldschoolgg/oldschoolbot/master/src/lib/resources/images/bank\_backgrounds/12.jpg)     | 10m              | 4           |
| [Barrows](https://raw.githubusercontent.com/oldschoolgg/oldschoolbot/master/src/lib/resources/images/bank\_backgrounds/6.jpg)        | 10m              | 5           |

## Patreon/Sponsor

The Github Sponsor and Patreon are ways for you to donate to Magnaboy, if you wish. It's entirely your choice, if you want to. The best way to support him is Github as it takes less of a cut than Patreon. Magnaboy will never sell items/GP from the bot for money, nor P2W perks/advantages.

You can donate to him on Github here: [https://github.com/sponsors/gc](https://github.com/sponsors/gc)

You can donate to him on Patreon here: [https://www.patreon.com/oldschoolbot](https://www.patreon.com/oldschoolbot)
