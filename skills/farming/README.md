# Farming

Farming in the bot works like farming ingame, where you will send your minion off on planting and/or harvesting trips, and your crops will grow in the background as you do other activities. The number of patches you have available will increase with the number of quest points you have and your farming level.

To plant crops, you can use the `+plant <name>` or `+farm <name>` commands. When a crop is fully grown, you can either use the `+harvest <name>` command, which will leave your patches empty, or the `+plant` or `+farm` commands which will plant whatever new crop you specify.

Some crops can be protected when planted using the `--pay` flag on the end of your farming command. Protection costs can be found on the [Farming training](https://oldschool.runescape.wiki/w/Farming_training) page of the OSRS Wiki. Protecting your crops will prevent them from dying at all, and most crops can be both protected and composted, if you wish to stack their properties. These payment bundles can be created using the `+create` command and works for most common crops such as potatoes, tomatoes, strawberries, bananas, oranges, etc, and are often taken in groups of 5 or 10.

You can set crop payment and compost to apply automatically using the `+defaultfarming tier compost/supercompost/ultracompost` and `+defaultfarming pay enable/disable` commands.

You can make supercompost from watermelons using the `+compostbin watermelon` command. Otherwise supercompost can be obtained from drops by wilderness bosses.

**Farming Payment Creatables**

| **Item name** | **Input items** |
| :--- | :---: |
| Tomatoes\(5\) | 5 Tomato |
| Tomato | Tomatoes\(5\) |
| Apples\(5\) | 5 Cooking Apple |
| Cooking Apple | Apples\(5\) |
| Bananas\(5\) | 5 Banana |
| Banana | Bananas\(5\) |
| Strawberries\(5\) | 5 Strawberry |
| Strawberry | Strawberries\(5\) |
| Oranges\(5\) | 5 Orange |
| Orange | Oranges\(5\) |
| Potatoes\(10\) | 10 Potato |
| Potato | Potatoes\(10\) |
| Onions\(10\) | 10 Onion |
| Onion | Onions\(10\) |
| Cabbages\(10\) | 10 Cabbage |
| Cabbage | Cabbages\(10\) |

When harvesting trees, you will either need the woodcutting level necessary to chop down the tree \(which will award logs\), or if you lack the necessary woodcutting level, 200gp for a farmer to remove the tree for you \(which will not award logs\).

Compost is buyable from the game shop using the `+buy` command, and is automatically applied to your crops if you have any available. If you have supercompost or ultracompost, you can use their respective flags \(`--supercompost` and `--ultracompost`\) to add them to your crops when planting. Ultracompost can be created by combining supercompost with volcanic ash, which you can mine with 22 Mining. Compost decreases the death chances for your crops as they grow and increases some crop yields, so it can be very useful to get the most out of your seeds.

## **Farming Boosts**

The speed of your farming trips and the xp you gain from farming activities can both be boosted, as well as the quantity of items harvested. The following items provide boosts to the farming skill:

* Farmers Strawhat = +0.4% to XP
* Farmers Jacket/Shirt = +0.8% to XP
* Farmers Boro Trousers + +0.6% to XP
* Farmers Boots = +0.2% to XP
* Full Farmers Outfit = +0.4% to XP on top of item bonuses
* Magic Secateurs = +10% to harvest quantity
* Farming Cape = +5% to harvest quantity
* Full Graceful Outfit = +10% to trip speed
* Ring of Endurance = +10% to trip speed \(currently you cannot charge the ring, making this boost unobtainable\)

The full [Farming commands breakdown](https://github.com/oldschoolgg/obdocs/blob/master/farming.md) gives an overview of all the commands introduced with the Farming skill.

**Farming Patches**

| **Patch type** | **Base patches** | **Number of possible additional patches** | **Additional patch requirements** |
| :--- | :---: | :---: | :---: |
| Herb | 4 | 5 | 65 Farming and 1, 10, 15, & 31 QP |
| Tree | 5 | 1 | 65 Farming |
| Allotment | 8 | 7 | 45 Farming and 1, 15, & 33 QP |
| Fruit tree | 4 | 2 | 85 Farming and 22 QP |
| Seaweed | 0 | 2 | 22 QP |
| Flower | 4 | 3 | 45 Farming and 1 & 33 QP |
| Hardwood | 0 | 3 | 3 QP |
| Vine | 12 | 0 | N/A |
| Bush | 3 | 2 | 45 Farming and 3 QP |
| Hops | 4 | 0 | N/A |
| Mushroom | 1 | 0 | N/A |
| Belladonna | 1 | 0 | N/A |
| Cactus | 1 | 1 | 45 Farming |
| Hespori | 1 | 0 | N/A |
| Calquat | 1 | 0 | N/A |
| Crystal | 0 | 1 | 33 QP |
| Spirit | 1 | 4 | 91 and 99 Farming |
| Celastrus | 0 | 1 | 85 Farming |
| Redwood | 0 | 1 | 85 Farming |

