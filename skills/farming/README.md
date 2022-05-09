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

## Optimal Farming route to 99



`/farming check_patches` (For checking patch timers)&#x20;

`/default_compost`  - set to ultracompost

`/farming always_pay`&#x20;

`/farming plant [plant_name:Potato]` - (until level 5)&#x20;

`/farming plant [plant_name:Onion]` - (until level 7)&#x20;

`/farming plant [plant_name:Cabbage]` - (until level 12)&#x20;

`/farming plant [plant_name:Tomato]` (until level 15)



**Now farm tree seeds, Hardwood seeds, fruit tree seeds and Special seeds until 99**

**`Tree seeds`**` ```&#x20;

`/farming plant [plant_name:Oak Tree]` (until level 30)&#x20;

`/farming plant [plant_name:Willow Tree]` (until level 45)&#x20;

`/farming plant [plant_name:Maple Tree]` (until level 60)&#x20;

`/farming plant [plant_name:Yew Tree]` (until level 75)&#x20;

`/farming plant [plant_name:Magic Tree]` (Repeat to 99)&#x20;



**`Hardwood seeds`**` ```&#x20;

`/farming plant [plant_name:Teak Tree]` (Level 35-55)&#x20;

`/farming plant [plant_name:Teak Tree]` (Repeat to 99)&#x20;



**`Fruit tree seeds`**

`/farming plant [plant_name:Pineapple Tree]`(Level 51-57)&#x20;

`/farming plant [plant_name:Papaya Tree]`(until level 68)&#x20;

`/farming plant [plant_name:Palm Tree]` (until level 81)&#x20;

`/farming plant [plant_name:Dragonfruit Tree]` (Repeat to 99)



**`Special seeds`**&#x20;

`/farming plant [plant_name:Calquat Tree]` (Level 72-99)&#x20;

`/farming plant [plant_name:Spirit Tree]` (Level 83-99)&#x20;

`/farming plant [plant_name:Celastrus Tree]` (Level 85-99)&#x20;

`/farming plant [plant_name:Redwood Tree]` (Level 90-99)&#x20;



**Materials Needed:**

Seeds vary depending on how active one farms, these numbers are just a guideline (The less active farming, the better xp/hour, but require more slower growing seeds)&#x20;

* 100 Potato seed
* 100 Onion seed
* 100 Cabbage seed
* 100 Tomato seed
* 100 Acorn
* 100 Willow seed
* 100 Maple seed
* 100 Yew seed
* 800-1000 Magic seed
* 25 Teak seed
* 50-100 Mahogany seed
* 100 Pineapple seed
* 100 Papaya tree seed
* 100 Palm tree seed&#x20;
* 200-300 Dragonfruit tree seed
* 100-150 Calquat tree seed
* 100-200 Spirit seed
* 120-200 Celastrus seed
* 20-30 Redwood tree seed
* 2000-3000 Ultracompost
* 1000-1500 Potato cactus
* 2000-3000 Yannillian hops
* 200-400 Limpwurt root
* 20000-30000 Coconut
