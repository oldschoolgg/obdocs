
Minions are a feature in Old School Bot that let you simulate playing a virtual runescape account in discord. You control a minion, who you send out to do various tasks, like killing monsters for loot, completing clue scrolls, and training skills. With the loot they get, you can craft items, sell them and trade to other real players.

> Minions are entirely virtual, and not in any way tradeable for real GP or real money. It's simulating the real game for fun. We strictly do not allow any bot users to break any of the official OSRS rules. Read the rules here: [Old School Bot Rules](https://www.oldschool.gg/oldschoolbot/rules)


This page is editable by anyone at [obdocs/minions.md](https://github.com/gc/obdocs) - if you notice any mistakes or missing information, you can add it yourself, or report it to us in the [support server](https://discord.gg/ob)

<h1 id="top">Activities</h1>  

### Skills

Currently available skills are:  
  * <a href="#agility">Agility</a>  
  * <a href="#fishing">Fishing</a>  
  * <a href="#mining">Mining</a>  
  * <a href="#smithing">Smithing</a>  
  * <a href="#woodcutting">Woodcutting</a>  
  * <a href="#firemaking">Firemaking</a>  
  * <a href="#runecrafting">Runecrafting</a>  
  * <a href="#cooking">Cooking</a>  
  * Crafting (WIP)  
  * Slayer (WIP)  
  * More skills are being worked on
  
You can view your minions' stats using `+m stats`.  


### Bossing

 Currently available bosses to kill are:  
  * Barrows  
  * Dagannoth Prime  
  * Dagannoth Rex  
  * Dagannoth Supreme  
  * Cerberus  
  * Giant Mole  
  * Vorkath  
  * Zulrah  
  * General Graardor  
  * Commander Zilyana  
  * Kree'arra  
  * K'ril Tsutsaroth  
  * Callisto  
  * Vet'ion  
  * Venenatis  
  * Chaos Elemental  
  * Chaos Fanatic  
  * Crazy Archaeologist  
  * King Black Dragon  
  * Scorpia  
  * Corporeal Beast  
  * Kalphite Queen  
  * Lizardman Shaman  
 Some bosses have requirements, like Quest points or gear, refer to <a href="#requirements">Boss and monster requirements</a> for more information.
  
 You can view your minions' killcount using `+m kc`.
 
### Miscellaneous
 * <a href="#questing">Questing</a>  
 * <a href="#skillcapes">Skillcapes</a>  
 * Boosts(WIP)  
 * <a href="#buyables">Buyable items</a>  
 * <a href="#requirements">Boss and monster requirements</a>  
 * <a href="#bankbackgrounds">Bank backgrounds</a>  


<h2 id="agility">Agility</h2>
You can train agility using `+laps [quantity] <course>`, for example `+laps 10 canifis`.  

Agility rewards you with marks of grace which you can use to buy Graceful equipment.

### Courses
| **Course** | **Required level** |
| - | :-: |
| Gnome stronghold | 1 |
| Draynor village | 10 |
| Al Kharid | 20 |
| Varrock | 30 |
| Canifis | 40 |
| Falador | 50 |
| Seers Village | 60 |
| Pollnivneach | 70 |
| Rellekka | 80 |
| Ardougne | 90 |

Click [here](https://i.imgur.com/LZGlSgj.png) for **Agility** XP rates and **Marks of Grace** per hour.

<a href="#top">Back to top</a>


<h2 id="fishing">Fishing</h2>
You can train fishing using `+fish [quantity] <fish>`, for example `+fish 100 lobster`.  

Fishing bait is buyable with `+buy fishing bait`.  

Feathers, Dark fishing bait or Raw Karambwanji aren't sold by the bot, and can be obtained by buying from other players or obtaining them yourself.

### Fish
| **Fish** | **Required level** |
| - | :-: |
| Shrimp | 1 |
| Sardine | 5 |
| Karambwanji | 5 |
| Herring | 10 |
| Anchovies | 15 |
| Mackerel | 16 |
| Trout | 20 |
| Cod | 23 |
| Pike | 25 |
| Salmon | 30 |
| Tuna | 35 |
| Lobster | 40 |
| Bass | 46 |
| Barbarian fishing | 48 |
| Swordfish | 50 |
| Monkfish | 62 |
| Karambwan | 65 |
| Shark | 76 |
| Anglerfish | 82 |
| Dark crab | 85 |

> **Karambwanji**(Not to be mistaken for **Karambwan**) requires **15** Quest Points to fish.<br>
> **Monkfish** requires **100** Quest Points to fish.<br>
> **Anglerfish** requires **40** Quest Points to fish.<br>
> Refer to <a href="#questing">Questing</a> on how to earn Quest Points.

Click [here](https://i.imgur.com/0PUaA3J.png) for **Fishing** XP rates.

<a href="#top">Back to top</a>


<h2 id="mining">Mining</h2>

You can train mining using `+mine [quantity] <ore>`, for example `+mine 10 coal`.  

Some ores reward you with golden nuggets or unidentified minerals.<br>
You can use nuggets to buy the prospector equipment and minerals to buy the three types of mining gloves.  

You get boosts from certain pickaxes:
* Dragon pickaxe 6%
* Infernal pickaxe 10%
* Gilded pickaxe 11%
* 3rd age pickaxe 12%

> Level 61 Mining is required for any pickaxe boost.

### Ores

| **Ore Name** | **Nuggets** | **Minerals** | **Required level** |
| - | :-: | :-: | :-: |
| Rune essence |  |   | 1 |
| Copper ore |  |   | 1 |
| Tin ore |  |   | 1 |
| Iron ore |  |   | 15 |
| Silver ore |  |   | 20 |
| Pure essence |  |   | 30 |
| Coal |  |  ✔ | 30 |
| Gold ore | ✔ |   | 40 |
| Mithril ore | ✔ |   | 55 |
| Adamantite ore | ✔ |   | 70 |
| Runite ore | ✔ |   | 85 |
| Amethyst |  |  ✔ | 92 |

Click [here](https://i.imgur.com/b3HNdSi.png) for **Mining** XP rates.

<a href="#top">Back to top</a>


<h2 id="smithing">Smithing</h2>
You can train smithing using `+smith [quantity] <bar>`, for example `+smith 50 bronze bar`.  

Smithing is one of the more useful skills on the bot, because it is required to create Godswords and such!
> Currently you can only smelt bars! Smithing the bars into items might get added later.

### Bars
| **Bar** | **Required level** | **Materials needed** |
| - | :-: | - |
| Bronze | 1 | Tin + Copper |
| Iron | 15 | Iron ore |
| Silver | 20 | Silver ore |
| Steel | 30 | Iron ore + 2 coal |
| Gold | 40 | Gold ore |
| Mithril | 50 | Mithril ore + 4 coal |
| Adamantite | 70 | Adamantite ore + 6 coal |
| Runite | 85 | Runite ore + 8 coal |

Click [here](https://i.imgur.com/tOTEqHS.png) for **Smithing** XP rates.

<a href="#top">Back to top</a>


<h2 id="woodcutting">Woodcutting</h2>
You can train woodcutting using `+chop [quantity] <logs>`, for example `+chop 50 willow`.  

You get boosts from certain axes:
* Dragon axe 9%
* Infernal axe 11%
* Gilded axe 12%
* 3rd age axe 13%

> Level 61 Woodcutting is required for any axe boost.

### Logs
| **Log** | **Required level** |
| - | :-: |
| Logs | 1 |
| Oak | 15 |
| Willow | 30 |
| Teak | 35 |
| Maple | 45 |
| Bark | 45 |
| Mahogany | 50 |
| Arctic pine logs | 42 |
| Yew | 60 |
| Sulliusceps | 65 |
| Magic | 75 |
| Redwood | 90 |

> **Sulliusceps** requires **25** Quest Points to chop.<br>
> Refer to <a href="#questing">Questing</a> on how to earn Quest Points.

Click [here](https://i.imgur.com/fVG81BQ.png) for **Woodcutting** XP rates.

<a href="#top">Back to top</a>


<h2 id="firemaking">Firemaking</h2>
You can train firemaking using `+light [quantity] <logs>`, for example `+light 50 willow`.  

Wintertodt might get released later!

### Logs
| **Log** | **Required level** |
| - | :-: |
| Logs | 1 |
| Oak | 15 |
| Willow | 30 |
| Teak | 35 |
| Arctic pine logs | 42 |
| Maple | 45 |
| Mahogany | 50 |
| Yew | 60 |
| Magic | 75 |
| Redwood | 90 |

Click [here](https://i.imgur.com/80iIwN9.png) for **Firemaking** XP rates.

<a href="#top">Back to top</a>


<h2 id="runecrafting">Runecrafting</h2>
You can train runecrafting using `+rc [quantity] <rune>`, for example `+rc 50 law`.  

### Runes
| **Rune** | **Required level** |
| - | :-: |
| Air | 1 |
| Mind | 2 |
| Water | 5 |
| Earth | 9 |
| Fire | 14 |
| Cosmic | 27 |
| Chaos | 35 |
| Astral | 40 |
| Nature | 44 |
| Law | 54 |
| Death | 65 |
| Wrath | 95 |

Click [here](https://i.imgur.com/FMxtMSj.png) for **Runecrafting** XP rates.

<a href="#top">Back to top</a>


<h2 id="cooking">Cooking</h2>
You can train cooking using `+cook [quantity] <food>`, for example `+cook 50 bass`.  

### Food
| **Food** | **Required level** |
| - | :-: |
| Beef | 1 |
| Shrimps | 1 |
| Chicken | 1 |
| Anchovies | 1 |
| Sardine | 1 |
| Herring | 5 |
| Mackerel | 10 |
| Trout | 15 |
| Cod | 18 |
| Pike | 20 |
| Salmon | 25 |
| Tuna | 30 |
| Karambwan | 30 |
| Jug of wine | 35 |
| Lobster | 40 |
| Bass | 43 |
| Swordfish | 45 |
| Monkfish | 62 |
| Shark | 80 |
| Anglerfish | 84 |
| Dark Crab | 90 |
| Manta Ray | 91 |

Click [here](https://i.imgur.com/iJuoDbb.png) for **Cooking** XP rates.

<a href="#top">Back to top</a>

<h1 id="questing">Questing</h1>
You can send your minion out to do quests for 30 minutes using `+quest`.<br>
It isn't actually doing any specific quests, but gaining quest points.<br>
Quest points unlock buyable items such as the Recipe for disaster gloves, Helm of neitiznot and more.<br>
You also need quest points to kill some of the bosses.

<h3 id="skillcapes">Skillcapes</h3>

Upon reaching level 99 in a skill, you can purchase a skillcape for 99k by typing `+skillcape <skill_name>`. If it's your first 99, you'll get an untrimmed cape.

<h3 id="buyables">Buyable items</h3>

Upon reaching the required Quest points for an item, you can purchase these items by typing `+buy <item>`.

| **Item** | **Quest points required** | **Price** |
| - | :-: | :-: |
| Quest Point Cape | 275 | 99k |
| Helm of Neitiznot | 75 | 500k |
| Magic Secateurs | 40 | 2.5m |
| Goldsmith gauntlets | 25 | 1m |
| Cooking gauntlets | 25 | 1m |
| Anti-dragon shield | 35 | 10k |
| Barrows gloves | 175 | 1m |
| Dragon gloves | 107 | 850k |
| Rune gloves | 85 | 700k |
| Adamant gloves | 65 | 600k |
| Mithril gloves | 50 | 500k |
| Black gloves | 35 | 400k |
| Steel gloves | 25 | 300k |
| Iron gloves | 20 | 200k |
| Bronze gloves | 10 | 100k |
| Hardleather gloves | 5 | 50k |
| Huge Fishing Bait Pack | N/A | 50k |

<a href="#top">Back to top</a>

<h3 id="requirements">Boss and monster requirements</h3>
| **Boss** | **Quest points required** | **Gear required** |
| - | :-: | :-: |
| Lizardman shaman | 30 | Karils Crossbow |
| Zulrah | 75 | Armadyl chestplate, Armadyl chainskirt, Ahrim's robetop and Ahrim's robeskirt |
| Vorkath | 205 | Armadyl chestplate, Armadyl chainskirt |
| Giant Mole | N/A | Full Dharok's set |
| Callisto | N/A | Full Verac's set |
| Venenatis | N/A | Full Verac's set |
| King Black Dragon | N/A | Anti-Dragon shield |
| Corporeal Beast | N/A | Zamorakian Spear |
| Cerberus | N/A | Bandos chestplate and Bandos tassets |

| **Monster** | **Quest points required** | **Gear required** |
| - | :-: | :-: |
| Lizardman | 30 | N/A |

<a href="#top">Back to top</a>

<h1 id="bankbackgrounds">Bank Backgrounds</h1>

If you meet the requirements and costs of a background, you can get it using `+bankbg <name>`. The image will replace the background of your bank. Bank backgrounds may require some, or all of these: having items in your collection log, paying GP or sacrificing items. They are meant to be very hard to obtain.

| **Name** | **GP Cost** | **Item Cost** | **Collection Log Items Needed** |
| - | :-: | :-: | :-: |
| Default | 0  |   |  |
| Bandos | 100m | The 4 Godsword Hilts | Entire GWD log excluding pets, + Bandos pet |
| Corporeal Beast | 100m  |   | Entire Corporeal Beast log including pet |
| Lumbridge (\*) | 100m  |   |  |
| Casket (Legend Arts) | 100m  |   | The 4 clue milestone item rewards|

Note: the Lumbridge background is only available to T3 patrons, who are still required to pay 100m for it.

<a href="#top">Back to top</a>
