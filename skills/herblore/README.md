# Herblore

Herblore works as it does in OSRS: you clean herbs, make unfinished potions, prepare your secondary ingredients, and then make your final potions. In order to start training herblore, you need 10 qp to get the starting xp from the Druidic Ritual quest which will take you to level 3 herblore. If you did not have 10 qp when Herblore was released, you will have a 50% chance of getting the starting xp when questing post 10 qp. Making unfinished potions and preparing secondary ingredients provide no xp, cleaning herbs provides a little xp, and the bulk of your xp will be gotten from creating your final potions. Herblore uses the `+mix`, `+clean`, and `+crush` commands. Making unfinished potions, cleaning herbs, and preparing secondary ingredients can all be done by hand, but takes time. If you have the gp, you can pay Zahur to `+clean` your herbs or `+mix` your unfinished potions for 200 gp per herb or potion using the `--zahur` flag. To crush secondary ingredients, you can pay Wesley to do it for you using the `--wesley` flag for 50 gp per item.

All potions in OSRS are available to be made in the bot, however ingredients may not be easy or currently possible to obtain. You can see the levels required to clean herbs and make potions on the OSRS Wiki [Level up table page](https://oldschool.runescape.wiki/w/Herblore/Level_up_table). Zuhar will not clean herbs for you if you do not have the required herblore level to clean them yourself. Welsey will crush any item you need as there is no level requirement to process secondary ingredients.

**Herb Table**

| **Herb name** | **Cleaning level** |
| :--- | :---: |
| Guam | 3 |
| Marrentill | 5 |
| Tarromin | 11 |
| Harralander | 20 |
| Ranarr | 25 |
| Toadflax | 30 |
| Irit | 40 |
| Avantoe | 48 |
| Kwuarm | 54 |
| Snapdragon | 59 |
| Cadantine | 65 |
| Lantadyme | 67 |
| Dwarf weed | 70 |
| Torstol | 75 |

**Potions tables**

| **Finished potion** | **Potion base** | **Potion secondary** | **Required level** |
| :--- | :---: | :---: | :---: |
| Attack potion | Guam potion \(unf\) | Eye of newt | 3 |
| Antipoison | Marrentill potion \(unf\) | Unicorn horn dust | 5 |
| Strength potion | Tarromin potion \(unf\) | Limpwurt Root | 12 |
| Serum 207 | Tarromin potion \(unf\) | Ashes | 15 |
| Restore potion | Harralander potion \(unf\) | Red spiders' eggs | 22 |
| Compost potion | Harralander potion \(unf\) | Volcanic ash | 22 |
| Energy potion | Harralander potion \(unf\) | Chocolate dust | 26 |
| Defence potion | Ranarr potion \(unf\) | White berries | 30 |
| Agility potion | Toadflax potion \(unf\) | Toad's legs | 34 |
| Combat potion | Harralander potion \(unf\) | Goat horn dust | 36 |
| Prayer potion | Ranarr potion \(unf\) | Snape grass | 38 |
| Super attack | Irit potion \(unf\) | Eye of newt | 45 |
| Superantipoison | Irit potion \(unf\) | Unicorn horn dust | 48 |
| Fishing potion | Avantoe potion \(unf\) | Snape grass | 50 |
| Super energy | Avantoe potion \(unf\) | Mort myre fungus | 52 |
| Super strength | Kwuarm potion \(unf\) | Limpwurt root | 55 |
| Weapon poison | Kwuarm potion \(unf\) | Dragon scale dust | 60 |
| Super restore | Snapdragon potion \(unf\) | Red spiders' eggs | 63 |
| Super defence | Cadantine potion \(unf\) | White berries | 66 |
| Antifire potion | Lantadyme potion \(unf\) | Dragon scale dust | 69 |
| Ranging potion | Dwarf weed potion \(unf\) | Wine of Zamorak | 72 |
| Magic potion | Lantadyme potion \(unf\) | Potato cactus | 76 |
| Zamorak Brew | Torstol potion \(unf\) | Jangerberries | 78 |
| Saradomin Brew | Toadflax potion \(unf\) | Crushed nest | 81 |

Some potions require other potions as inputs, or require things other than the standard vial of water + herb + secondary setup.

**Non-standard potions**

| **Finished potion** | **Potion base** | **Potion secondary** | **Required level** |
| :--- | :---: | :---: | :---: |
| Guthix balance | Restore potion | Garlic, Silver dust | 22 |
| Antidote+ | Coconut milk | Toadflax, Yew roots | 68 |
| Weapon poison+ | Coconut milk | Cactus spine, Red spiders' eggs | 73 |
| Stamina potion | Super energy | Amylase crystal | 77 |
| Antidote++ | Coconut milk | Irit leaf, magic roots | 79 |
| Weapon poison | Coconut milk | Cave nightshade, poison ivy berries | 82 |
| Extended antifire | Antifire potion | Lava scale shard | 84 |
| Anti-venom | Antidote++ | 20x Zulrah's scales | 87 |
| Super combat potion | Super attack, Super defence, Super strength | Torstol | 90 |
| Super antifire potion | Antifire potion | Crushed superior dragon bones | 92 |
| Anti-venom+ | Anti-venom | Torstol | 94 |
| Extended super antifire | Super antifire potion | Lava scale shard | 98 |

