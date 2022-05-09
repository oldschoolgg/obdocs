# Farming

Farming in the bot works like farming ingame, where you will send your minion off on planting and/or harvesting trips, and your crops will grow in the background as you do other activities. The number of patches you have available will increase with the number of quest points you have and your farming level.

To plant crops, you can use the `/farming plant` command.&#x20;

When a crop is fully grown, you can either use the `/farming harvest` command, which will leave your patches empty, or the `/farming plant` command which will plant the new crop you specify.

Alternatively, you can use `/farming auto_farm` to automatically plant the highest level seed in each patch you currently have access to.

Some crops can be protected by using the pay option on farming commands. Protection costs can be found on the [Farming training](https://oldschool.runescape.wiki/w/Farming\_training) page of the OSRS Wiki. Protecting your crops will prevent them from dying at all, and most crops can be both protected and composted, if you wish to stack their properties. These payment bundles can be created using the `/create` command and works for most common crops such as potatoes, tomatoes, strawberries, bananas, oranges, etc, and are often taken in groups of 5 or 10.

You can view the patches you currently have things planted in, as well as the time remaining before they are done growing, by using `/farming check_patches`

You can set crop payment and compost to apply automatically using the `/farming default_compost` and `/farming always_pay` commands.

When harvesting trees, you will either need the woodcutting level necessary to chop down the tree (which will award logs), or if you lack the necessary woodcutting level, 200gp for a farmer to remove the tree for you (which will not award logs).

Compost is buyable from the game shop using the `+buy` command.

You can make supercompost from watermelons using the `/farming compost_bin` command. Otherwise supercompost can be obtained from drops by wilderness bosses.

You can create ultracompost with the `/create` command, using 2 Volcanic Ash and 1 Supercompost.



**Farming Payment Creatables**

| **Item name**   | **Input items** |
| --------------- | :-------------: |
| Tomatoes(5)     |     5 Tomato    |
| Tomato          |   Tomatoes(5)   |
| Apples(5)       | 5 Cooking Apple |
| Cooking Apple   |    Apples(5)    |
| Bananas(5)      |     5 Banana    |
| Banana          |    Bananas(5)   |
| Strawberries(5) |   5 Strawberry  |
| Strawberry      | Strawberries(5) |
| Oranges(5)      |     5 Orange    |
| Orange          |    Oranges(5)   |
| Potatoes(10)    |    10 Potato    |
| Potato          |   Potatoes(10)  |
| Onions(10)      |     10 Onion    |
| Onion           |    Onions(10)   |
| Cabbages(10)    |    10 Cabbage   |
| Cabbage         |   Cabbages(10)  |

## **Farming Boosts**

The speed of your farming trips and the xp you gain from farming activities can both be boosted, as well as the quantity of items harvested. The following items provide boosts to the farming skill:

* Farmers Strawhat - 0.4% to XP
* Farmers Jacket/Shirt - 0.8% to XP
* Farmers Boro Trousers - 0.6% to XP
* Farmers Boots - 0.2% to XP
* Full Farmers Outfit - 0.4% to XP on top of item bonuses
* Magic Secateurs - 10% to harvest quantity
* Farming Cape - 5% to harvest quantity
* Full Graceful Outfit - 10% to trip speed
* Ring of Endurance - 10% to trip speed (must be [charged](https://wiki.oldschool.gg/skills/agility/hallowed-sepulchre#ring-of-endurance) & equipped)

The full [Farming commands breakdown](../../farming.md) gives an overview of all the commands introduced with the Farming skill.

**Note**: Some of the commands listed in the list above may be out of date, as the bot is slowly transitioning to having more commands under `/m`.

**Farming Patches**

| **Patch type** | **Base patches** | **Number of possible additional patches** | **Additional patch requirements** |
| -------------- | :--------------: | :---------------------------------------: | :-------------------------------: |
| Herb           |         4        |                     5                     | 65 Farming and 1, 10, 15, & 31 QP |
| Tree           |         5        |                     1                     |             65 Farming            |
| Allotment      |         8        |                     7                     |   45 Farming and 1, 15, & 33 QP   |
| Fruit tree     |         4        |                     2                     |        85 Farming and 22 QP       |
| Seaweed        |         0        |                     2                     |               22 QP               |
| Flower         |         4        |                     3                     |      45 Farming and 1 & 33 QP     |
| Hardwood       |         0        |                     3                     |                3 QP               |
| Vine           |        12        |                     0                     |                N/A                |
| Bush           |         3        |                     2                     |        45 Farming and 3 QP        |
| Hops           |         4        |                     0                     |                N/A                |
| Mushroom       |         1        |                     0                     |                N/A                |
| Belladonna     |         1        |                     0                     |                N/A                |
| Cactus         |         1        |                     1                     |             45 Farming            |
| Hespori        |         1        |                     0                     |                N/A                |
| Calquat        |         1        |                     0                     |                N/A                |
| Crystal        |         0        |                     1                     |               33 QP               |
| Spirit         |         1        |                     4                     |         91 and 99 Farming         |
| Celastrus      |         0        |                     1                     |             85 Farming            |
| Redwood        |         0        |                     1                     |             85 Farming            |
