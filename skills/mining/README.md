# Mining

You can train Mining using `/mine`**`name:`**`[ore]`. If no quantity is specified, it will default to a full trip. Using the powermine option will result in no ores being obtained, but provides significantly faster mining xp rates.

* `/mine`` `**`name:`**` ``Runite ore`` `**`quantity:`**` ``50`
* `/mine`` `**`name:`**` ``Iron ore`` `**`powermine:`**` ``true`

## Pickaxes

All pickaxes in the bot will provide a specific increase to your chance of mining ores (i.e. mining speed). The best pickaxe to use is a Crystal pickaxe (Lvl 71) with the second-best being a Dragon, Infernal, or 3rd Age pickaxe (Lvl 61). Gilded pickaxes perform the same as a rune axe. The Crystal pickaxe does not degrade and the Infernal pickaxe does not smelt ores while mining. Pickaxes do not need to be equipped for the bonus to apply.

## Mining Guild

If you have at least 60 Mining, the ore you are mining provides nuggets or minerals, and the rock is located within the Mining guild, you will gain an invisible +7 mining levels. This will grant a small increase to the speed in which you will mine ores. This boost does not let you use higher level pickaxes or mine higher level ores.

* **Ores in Guild** - Iron, Coal, Gold, Mithril, Adamant, Runite, Amethyst

## Powermining

Using this filter when mining ores allows your minion to reach much higher xp rates, at the expense of not receiving any ores from your trip. For ironmen, it may be beneficial to mine normally so they can use the ores for early smithing or crafting levels. You will still receive nuggets, minerals and clues when powermining.

## Gold & Silver Ore

If you have 99 crafting, you will get a significant 70% boost to your trip time, due to using the bank at the crafting guild. This applies only when mining gold and silver ores. You will still receive gold nuggets from gold ores.

## Celestial Ring/Signet

The Celestial ring or signet will provide an invisible +4 mining levels. It does not have to be charged for the boost to apply. It can also be equipped anywhere or left in your bank for the boost to apply. This boost does not let you use higher level pickaxes or mine higher level ores.

## Mining cape

The Mining cape provides a 5% bonus to the amount of ores you will receive. The extra ores received will not give extra xp, however, the bonus effect stacks with Varrock armours. The cape has no effect when powermining. It applies to all ores except for runite and amethyst. It does not need to be equipped for the bonus to apply.

## Varrock Armour

The Varrock diary rewards provide a 10% bonus to the amount of ores you will receive. Higher tiers of diary completion means higher tier ores are affected. The extra ores received will not give extra xp, however, the bonus effect stacks with the Mining cape. These armours have no effect when powermining. This effect also applies to sandstone and granite. It does not need to be equipped for the bonus to apply.

* **Varrock Armour 1:** Clay - Coal
* **Varrock Armour 2:** Clay - Mithril
* **Varrock Armour 3:** Clay - Adamant
* **Varrock Armour 4:** Clay - Amethyst

## Mining Gloves

These gloves give the chance to not deplete rocks when mining, effectively speeding up your mining trip. They must be equipped in any setup for the boost to apply.

|                        |                             |                     |
| ---------------------- | --------------------------- | ------------------- |
| **Item**               | **Ores Affected**           | **Mineral Cost**    |
| Mining gloves          | Silver, Coal, Gold          | 60                  |
| Superior mining gloves | Mithril, Adamant, Runite    | 120                 |
| Expert mining gloves   | All of the above + Amethyst | 60 + other 2 gloves |

## Prospector's Outfit

Must be equipped in the skilling setup for the boost to apply.

| **Item**          | **XP Boost** | **Golden Nugget Cost** |
| ----------------- | ------------ | ---------------------- |
| Prospector helmet | 0.4%         | 40                     |
| Prospector jacket | 0.8%         | 60                     |
| Prospector legs   | 0.6%         | 50                     |
| Prospector boots  | 0.2%         | 30                     |
| **Complete set:** | **2.5%**     | **180**                |

## Golden Nuggets & Unidentified Minerals

The amount of golden nuggets or unidentified minerals rewarded is based in the total trip time. The amount received is a randomly selected number between 0 and the total trip time divided by 4, floored/rounded down.

$$
⌊\frac{tripTime}{4}⌋=maxAmount
$$

For example, a trip of 30 minutes will award between 0 and 7 golden nuggets or unidentified minerals.

Other items not already listed above that can be purchased with nuggets or minerals are:

|                             |                          |
| --------------------------- | ------------------------ |
| **Item**                    | **Cost**                 |
| Gem bag                     | 100 Golden nuggets       |
| Coal bag                    | 100 Golden nuggets       |
| Bag full of gems            | 40 Golden nuggets        |
| Bag full of gems (minerals) | 20 Unidentified minerals |

## Ores

| **Ore Name**   | **Nuggets** | **Minerals** | **Required Level** | **Experience** | **XP/Hr @ 99** |
| -------------- | :---------: | :----------: | :----------------: | :------------: | -------------- |
| Rune essence   |             |              |          1         |        5       | 10,288         |
| Copper ore     |             |              |          1         |      17.5      | 26,881         |
| Tin ore        |             |              |          1         |      17.5      | 26,881         |
| Saltpetre      |             |              |          1         |        0       | 0              |
| Iron ore       |             |       ✔      |         15         |       35       | 50,332         |
| Silver ore     |             |              |         20         |       40       | 22,454         |
| Volcanic ash   |             |              |         22         |       10       | 9,810          |
| Pure essence   |             |              |         30         |        5       | 10,288         |
| Coal           |             |       ✔      |         30         |       50       | 31,644         |
| Gold ore       |      ✔      |              |         40         |       65       | 36,556         |
| Gem rock       |             |              |         40         |       65       | 20,865         |
| Mithril ore    |      ✔      |              |         55         |       80       | 17,231         |
| Adamantite ore |      ✔      |              |         70         |       95       | 12,654         |
| Runite ore     |      ✔      |              |         85         |       125      | 6,731          |
| Amethyst       |             |       ✔      |         92         |       240      | 14,321         |
