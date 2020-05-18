
Minions are a feature in Old School Bot that let you simulate playing a virtual runescape account in discord. You control a minion, who you send out to do various tasks, like killing monsters for loot, completing clue scrolls, and training skills. With the loot they get, you can craft items, sell them and trade to other real players.

You can also read the [FAQ](https://www.oldschool.gg/oldschoolbot/faq) for answers to common questions.

> Minions are entirely virtual, and not in any way tradeable for real GP or real money. It's simulating the real game for fun. We strictly do not allow any bot users to break any of the official OSRS rules. Read the rules here: [Old School Bot Rules](https://www.oldschool.gg/oldschoolbot/rules)


If you notice any mistakes or missing information in this page, you can [add it yourself](https://github.com/gc/obdocs/blob/master/minions.md), or report it to us in the [support server](https://discord.gg/ob)

[Edit this page on Github](https://github.com/gc/obdocs/blob/master/minions.md)


# Getting started

To get started, firstly [read the rules](https://www.oldschool.gg/oldschoolbot/rules), then get yourself a minion by typing `+minion buy`, or `+m buy` for short.

Next, decide what you want to do. Skilling? PVM? Questing? Read the rest of the page to see what you can do, and how - and just do whatever you want to do!

It's highly recommended to join the [support server](http://oldschool.gg/ob) for several reasons: All updates and changes to the bot are announced in the #news channel in the server. We have a #grand-exchange channel you can use to trade/sell items with others. We have a #notifications channel that shows all the rare drops, pets and other things that people are getting in real time! 


# Activities  

### Skills

Currently available skills are:  
  * [Agility](https://www.oldschool.gg/oldschoolbot/minions?Agility)  
  * [Fishing](https://www.oldschool.gg/oldschoolbot/minions?Fishing)  
  * [Mining](https://www.oldschool.gg/oldschoolbot/minions?Mining)  
  * [Smithing](https://www.oldschool.gg/oldschoolbot/minions?Smithing)  
  * [Woodcutting](https://www.oldschool.gg/oldschoolbot/minions?Woodcutting)  
  * [Firemaking](https://www.oldschool.gg/oldschoolbot/minions?Firemaking)  
  * [Runecrafting](https://www.oldschool.gg/oldschoolbot/minions?Runecrafting)  
  * [Cooking](https://www.oldschool.gg/oldschoolbot/minions?Cooking)  
  * [Crafting](https://www.oldschool.gg/oldschoolbot/minions?Crafting)  
  * [Prayer](https://www.oldschool.gg/oldschoolbot/minions?Prayer)  
 
### Miscellaneous
  * [Questing](https://www.oldschool.gg/oldschoolbot/minions?Questing)  
  * [Skillcapes](https://www.oldschool.gg/oldschoolbot/minions?Skillcapes)  
  * [Boosts](https://www.oldschool.gg/oldschoolbot/minions?Boosts)  
  * [Buyable items](https://www.oldschool.gg/oldschoolbot/minions?Buyable%20items)  
  * [Boss/Monster requirements](https://www.oldschool.gg/oldschoolbot/minions?Boss%20and%20monster%20requirements)  
  * [Bank backgrounds](https://www.oldschool.gg/oldschoolbot/minions?Bank%20Backgrounds)  
  * [Minion Icons](https://www.oldschool.gg/oldschoolbot/minions?Minion%20Icons)
  * [Patreon](https://www.oldschool.gg/oldschoolbot/minions?Patreon) 

You can view your minions' stats using `+m stats`.  


### Bossing

 Some bosses have requirements, like Quest points or gear, refer to [Boss and monster requirements](https://www.oldschool.gg/oldschoolbot/minions?Boss%20and%20monster%20requirements) for more information.
  
 You can view your minions' killcounts using `+m kc`.
 
#### Group Bossing

Some bosses are able to be killed in groups, these bosses currently are: All four GWD bosses, and Corp - more bosses are planned to be added. To do group bossing, you create a party, there are two kinds of parties: invite-only and mass. Invite only parties are for you to invite select people on your trip and mass parties can be joined by anyone. Parties have a leader, who is the person who created the party (ran the command).

Note that, similar to ingame, even if you have a very big group of people in a party killing a boss, you're still limited by that bosses respawn time, although the kills can get very very fast if you have lots of people.

Loot is rolled out completely randomly, for example if your party is doing 5 kills, it will give each kill loot to a random party member, the same person can be given loot multiple times, or none at all if unlucky.

Currently, boosts do not apply to group boss trips, however this will be added in the future.

You **cannot** join parties if: you're an ironman or if your minion is busy.

##### Invite-only group bossing
Example of invite-only group bossing party: `+groupkill party corp @Magnaboy @Alexsuperfly @Crow653` - this would make an invite-only party, that only those 3 people can join. Note that, the leader (the person who is running the command) doesn't have to add themselves to the list, they're always included automatically.

After, each user will have to confirm they want to join by clicking on the "join" reaction. The trip will start when all users have confirmed, or if the party leader has clicked the "start" reaction to start early.


##### Mass bossing
Example of a mass bossing party: `+groupkill mass corp` - this would make a mass party, that ANYONE can join. The trip will start after 2 minutes automatically, or when the party leader clicks the "start" reaction.


## Agility
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

## Fishing
You can train fishing using `+fish [quantity] <fish>`, for example `+fish 100 lobster`.  

Fishing bait is buyable with `+buy fishing bait`.  

Feathers, Dark fishing bait or Raw Karambwanji aren't sold by the bot, and can be obtained by buying from other players or obtaining them yourself.

### Fish
| **Fish** | **Required level** |
| - | :-: |
| Raw Shrimp | 1 |
| Raw Sardine | 5 |
| Raw Karambwanji | 5 |
| Raw Herring | 10 |
| Raw Anchovies | 15 |
| Raw Mackerel | 16 |
| Raw Trout | 20 |
| Raw Cod | 23 |
| Raw Pike | 25 |
| Raw Salmon | 30 |
| Raw Tuna | 35 |
| Raw Lobster | 40 |
| Raw Bass | 46 |
| Barbarian fishing | 48 |
| Raw Swordfish | 50 |
| Raw Monkfish | 62 |
| Raw Karambwan | 65 |
| Raw Shark | 76 |
| Raw Anglerfish | 82 |
| Raw Dark crab | 85 |

* **Karambwanji**(Not to be mistaken for **Karambwan**) requires **15** Quest Points to fish.
* **Monkfish** requires **100** Quest Points to fish.
* **Anglerfish** requires **40** Quest Points to fish.

Click [here](https://i.imgur.com/0PUaA3J.png) for **Fishing** XP rates.

## Mining

You can train mining using `+mine [quantity] <ore>`, for example `+mine 10 coal`.  

Some ores reward you with golden nuggets or unidentified minerals.<br>
You can use nuggets to buy the prospector equipment and minerals to buy the three types of mining gloves.  

If you have atleast level 61, you can get one of these boosts from owning one of these pickaxes:
* Dragon pickaxe 6%  
* Infernal pickaxe 10%  
* Gilded pickaxe 11%  
* 3rd age pickaxe 12%  

### Ores

| **Ore Name** | **Nuggets** | **Minerals** | Required level** |
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

## Smithing
You can train smithing using `+smith` & `+smelt`
`+smelt [quantity] <bar>`, for example `+smelt 50 bronze bar`
`+smith [quantity] <item>`, for example `+smith adamant dart tips`

Smithing is one of the more useful skills on the bot, because it is required to create Godswords and such!

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

## Woodcutting
You can train woodcutting using `+chop [quantity] <logs>`, for example `+chop 50 willow`.  

If you have atleast level 61, you can get one of these boosts from owning one of these axes:
* Dragon axe 9%  
* Infernal axe 11%  
* Gilded axe 12%  
* 3rd age axe 13%  

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

* **Sulliusceps** requires **25** Quest Points to chop.<br>
* Refer to [Questing](https://www.oldschool.gg/oldschoolbot/minions?Questing) on how to earn Quest Points.

Click [here](https://i.imgur.com/fVG81BQ.png) for **Woodcutting** XP rates.

## Firemaking
You can train firemaking using `+light [quantity] <logs>`, for example `+light 50 willow`.  

### Logs
| **Log** | **Required level** |
| - | :-: |
| Tree | 1 |
| Achey | 1 |
| Oak | 15 |
| Willow | 30 |
| Teak | 35 |
| Arctic pine | 42 |
| Maple | 45 |
| Mahogany | 50 |
| Yew | 60 |
| Magic | 75 |
| Redwood | 90 |

Click [here](https://i.imgur.com/80iIwN9.png) for **Firemaking** XP rates.

## Runecrafting
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

## Cooking
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

## Crafting
You can train crafting with the `+craft` command. For example, `+craft 100 leather gloves`. To start training crafting, you will probably want to first kill cows for cowhide, then turn the cowhide into leather using `+craft leather`, then craft leather gloves from those. Alternatively, you can also buy these items from our grand-exchange channel.

To see all the items you can craft, check the [Crafting Wiki Page](https://oldschool.runescape.wiki/w/Crafting) - most of the items are in the bot, with the exact same level and item requirements.

## Prayer
You can train prayer by burying bones, or offering them to the Chaos altar. For example to bury 100 Dragon bones, you can do `+bury 100 Dragon bones`, or to bury the maximum amount you can: `+bury Dragon bones`. Offering the bones to the Chaos altar works exactly the same, except you use `+offer` instead, for example: `+offer 100 Dragon bones`.

The Chaos Altar works like ingame, your minion will do 1 inventory trips back and forth to sacrifice, with a 10% chance of being PKed in the trip and losing some amount of your inventory of bones (depending on if you got PKed at the start/middle/finish).

The Prayer skill is also required for creating Spirit shields.

# Questing
Questing in the bot is simple and easy, and roughly 20% faster than ingame. Instead of doing specific quests, you just "quest" and gain QP for "questing". You can keep questing until you reach the max QP.

Quest points are required to kill some bosses (e.g. Vorkath) and required to buy some items (e.g. Barrows gloves).


# Skillcapes

Upon reaching level 99 in a skill, you can purchase a skillcape for 99k by typing `+skillcape <skill_name>`. If it's your first 99, you'll get an untrimmed cape.



### Boosts

Boosts work a little differently on the bot then they do ingame.  Currently, there are 4 types of boosts.  
Those would be **Minion Learning**, **Weekend Boosts**, **Item Speed Boosts** and **XP Boosts**.

#### Minion Learning  

The more time your minion spends on killing the same monsters, over time, it will take slightly less time to kill them.  
It takes for example 25 hours to get a 5% **Speed Boost** from Minion Learning.  

Minion learning allows you to get more kills in a single trip.  


#### Weekend Boosts  

Weekend Boosts reduce your total trip length by 10% on weekends.  


#### XP Boosts
These items just give you a flat percentage boost at the end of the trip.  


#### Item Speed Boosts
Some items reduce the time it takes to finish a trip.  Some boosts can stack together, for example an item that gives 10% boost and an item that gives 5% boost, will lower your trip by 15%.  The only items that do **NOT** stack with each other, are pickaxes, axes and mining gloves.  Only the highest value is counted.  

Below is a list of items/skills that boost your minion's activity.  

^1^ Max boost excluding weekend boost, patron perks, minion learning and any other extra boost.

|**God Wards Dungeon bosses** | **Item needed to receive boost** | **Boost Type**| **Max Boost ^1^** |
| :-: | :-: | :-: | :-: |
|![https://i.imgur.com/Aoynyet.png](https://i.imgur.com/Aoynyet.png)<br>Commander Zilyana(Sara)|![https://i.imgur.com/BqfyfaF.png](https://i.imgur.com/BqfyfaF.png)Ranger boots<br>![https://i.imgur.com/m4ljYLH.png](https://i.imgur.com/m4ljYLH.png)Armadyl crossbow|![https://i.imgur.com/Vz7oeaw.png](https://i.imgur.com/Vz7oeaw.png)5% speed<br>![https://i.imgur.com/Vz7oeaw.png](https://i.imgur.com/Vz7oeaw.png)5% speed| ![https://i.imgur.com/Vz7oeaw.png](https://i.imgur.com/Vz7oeaw.png)10% |
|![https://i.imgur.com/MKTNBsR.png](https://i.imgur.com/MKTNBsR.png)<br>K'ril Tsutsaroth(Zammy)|![https://i.imgur.com/bqPPeGv.png](https://i.imgur.com/bqPPeGv.png)Dragon warhammer|![https://i.imgur.com/Vz7oeaw.png](https://i.imgur.com/Vz7oeaw.png)10% speed| ![https://i.imgur.com/Vz7oeaw.png](https://i.imgur.com/Vz7oeaw.png)10% |
|![https://i.imgur.com/YpEBUDM.png](https://i.imgur.com/YpEBUDM.png)<br>Kree'arra(Arma)|![https://i.imgur.com/BqfyfaF.png](https://i.imgur.com/BqfyfaF.png)Ranger boots|![https://i.imgur.com/Vz7oeaw.png](https://i.imgur.com/Vz7oeaw.png)5% speed| ![https://i.imgur.com/Vz7oeaw.png](https://i.imgur.com/Vz7oeaw.png)5% |
|![https://i.imgur.com/TBVEcxB.png](https://i.imgur.com/TBVEcxB.png)<br>General Graardor<br><br>|![https://i.imgur.com/bqPPeGv.png](https://i.imgur.com/bqPPeGv.png)Dragon warhammer|![https://i.imgur.com/Vz7oeaw.png](https://i.imgur.com/Vz7oeaw.png)10% speed| ![https://i.imgur.com/Vz7oeaw.png](https://i.imgur.com/Vz7oeaw.png)10% |
|**Wilderness Bosses**|**Item needed to receive boost**|**Boost Type**|
|![https://i.imgur.com/FUDRrtb.png](https://i.imgur.com/FUDRrtb.png)<br>Callisto|![https://i.imgur.com/Cib3CT9.png](https://i.imgur.com/Cib3CT9.png)Barrows gloves<br>![https://i.imgur.com/z38Shwd.png](https://i.imgur.com/z38Shwd.png)Berserker ring|![https://i.imgur.com/Vz7oeaw.png](https://i.imgur.com/Vz7oeaw.png)2% speed<br>![https://i.imgur.com/Vz7oeaw.png](https://i.imgur.com/Vz7oeaw.png)2% speed| ![https://i.imgur.com/Vz7oeaw.png](https://i.imgur.com/Vz7oeaw.png)4% |
|![https://i.imgur.com/brj0guF.png](https://i.imgur.com/brj0guF.png)<br>Chaos elemental|![https://i.imgur.com/sb1656f.png](https://i.imgur.com/sb1656f.png)Archers ring<br>![https://i.imgur.com/Cib3CT9.png](https://i.imgur.com/Cib3CT9.png)Barrows gloves|![https://i.imgur.com/Vz7oeaw.png](https://i.imgur.com/Vz7oeaw.png)3% speed<br>![https://i.imgur.com/Vz7oeaw.png](https://i.imgur.com/Vz7oeaw.png)3% speed| ![https://i.imgur.com/Vz7oeaw.png](https://i.imgur.com/Vz7oeaw.png)6% |
|![https://i.imgur.com/nxDobMj.png](https://i.imgur.com/nxDobMj.png)<br>Chaos fanatic|![https://i.imgur.com/1HeouvW.png](https://i.imgur.com/1HeouvW.png)Karil's leathertop<br>![https://i.imgur.com/r1csy4v.png](https://i.imgur.com/r1csy4v.png)Karil's leatherskirt|![https://i.imgur.com/Vz7oeaw.png](https://i.imgur.com/Vz7oeaw.png)3% speed<br>![https://i.imgur.com/Vz7oeaw.png](https://i.imgur.com/Vz7oeaw.png)3% speed| ![https://i.imgur.com/Vz7oeaw.png](https://i.imgur.com/Vz7oeaw.png)6% |
|![https://i.imgur.com/8GyJaKK.png](https://i.imgur.com/8GyJaKK.png)<br>Crazy archaeologist|![https://i.imgur.com/GI3Nx9o.png](https://i.imgur.com/GI3Nx9o.png)Occult necklace|![https://i.imgur.com/Vz7oeaw.png](https://i.imgur.com/Vz7oeaw.png)10% speed| ![https://i.imgur.com/Vz7oeaw.png](https://i.imgur.com/Vz7oeaw.png)10% |
|![https://i.imgur.com/tRbklxI.png](https://i.imgur.com/tRbklxI.png)<br>Scorpia|![https://i.imgur.com/GI3Nx9o.png](https://i.imgur.com/GI3Nx9o.png)Occult necklace|![https://i.imgur.com/Vz7oeaw.png](https://i.imgur.com/Vz7oeaw.png)10% speed| ![https://i.imgur.com/Vz7oeaw.png](https://i.imgur.com/Vz7oeaw.png)10% |
|![https://i.imgur.com/PucrJNy.png](https://i.imgur.com/PucrJNy.png)<br>Venenatis|![https://i.imgur.com/Cib3CT9.png](https://i.imgur.com/Cib3CT9.png)Barrows gloves|![https://i.imgur.com/Vz7oeaw.png](https://i.imgur.com/Vz7oeaw.png)3% speed| ![https://i.imgur.com/Vz7oeaw.png](https://i.imgur.com/Vz7oeaw.png)3% |
|![https://i.imgur.com/d5bRYpQ.gif](https://i.imgur.com/d5bRYpQ.gif)<br>Vet'ion<br><br>|![https://i.imgur.com/bqPPeGv.png](https://i.imgur.com/bqPPeGv.png)Dragon warhammer|![https://i.imgur.com/Vz7oeaw.png](https://i.imgur.com/Vz7oeaw.png)3% speed| ![https://i.imgur.com/Vz7oeaw.png](https://i.imgur.com/Vz7oeaw.png)3% |
|**General Bosses**|**Item needed to receive boost**|**Boost Type**|
|![https://i.imgur.com/C8Pj39a.png](https://i.imgur.com/C8Pj39a.png)<br>Cerberus|![https://i.imgur.com/3hCaAyJ.png](https://i.imgur.com/3hCaAyJ.png)Spectral spirit shield<br>![https://i.imgur.com/JSFjj3B.png](https://i.imgur.com/JSFjj3B.png)Bandos chestplate<br>![https://i.imgur.com/8z6TtFt.png](https://i.imgur.com/8z6TtFt.png)Bandos tassets|![https://i.imgur.com/Vz7oeaw.png](https://i.imgur.com/Vz7oeaw.png)10% speed<br>![https://i.imgur.com/Vz7oeaw.png](https://i.imgur.com/Vz7oeaw.png)5% speed<br>![https://i.imgur.com/Vz7oeaw.png](https://i.imgur.com/Vz7oeaw.png)5% speed| ![https://i.imgur.com/Vz7oeaw.png](https://i.imgur.com/Vz7oeaw.png)20% |
|![https://i.imgur.com/6d3aSw7.png](https://i.imgur.com/6d3aSw7.png)<br>Corporeal beast|![https://i.imgur.com/bqPPeGv.png](https://i.imgur.com/bqPPeGv.png)Dragon warhammer<br>![https://i.imgur.com/vqHkYFX.png](https://i.imgur.com/vqHkYFX.png)Bandos godsword|![https://i.imgur.com/Vz7oeaw.png](https://i.imgur.com/Vz7oeaw.png)10% speed<br>![https://i.imgur.com/Vz7oeaw.png](https://i.imgur.com/Vz7oeaw.png)5% speed| ![https://i.imgur.com/Vz7oeaw.png](https://i.imgur.com/Vz7oeaw.png)15% |
|![https://i.imgur.com/dlgD4uB.png](https://i.imgur.com/dlgD4uB.png)<br>Dagannoth Prime|![https://i.imgur.com/xs0XM0D.png](https://i.imgur.com/xs0XM0D.png)Armadyl chestplate<br>![https://i.imgur.com/bZRieVo.png](https://i.imgur.com/bZRieVo.png)Armadyl chainskirt<br>![https://i.imgur.com/JSFjj3B.png](https://i.imgur.com/JSFjj3B.png)Bandos chestplate<br>![https://i.imgur.com/8z6TtFt.png](https://i.imgur.com/8z6TtFt.png)Bandos tassets|![https://i.imgur.com/Vz7oeaw.png](https://i.imgur.com/Vz7oeaw.png)2% speed<br>![https://i.imgur.com/Vz7oeaw.png](https://i.imgur.com/Vz7oeaw.png)2% speed<br>![https://i.imgur.com/Vz7oeaw.png](https://i.imgur.com/Vz7oeaw.png)2% speed<br>![https://i.imgur.com/Vz7oeaw.png](https://i.imgur.com/Vz7oeaw.png)2% speed| ![https://i.imgur.com/Vz7oeaw.png](https://i.imgur.com/Vz7oeaw.png)8% |
|![https://i.imgur.com/DKLWf3O.png](https://i.imgur.com/DKLWf3O.png)<br>Dagannoth Rex|![https://i.imgur.com/kJ9wmr4.png](https://i.imgur.com/kJ9wmr4.png)Occult becklace<br>![https://i.imgur.com/bAdFMyD.png](https://i.imgur.com/bAdFMyD.png)Iban's staff|![https://i.imgur.com/Vz7oeaw.png](https://i.imgur.com/Vz7oeaw.png)5% speed<br>![https://i.imgur.com/Vz7oeaw.png](https://i.imgur.com/Vz7oeaw.png)5% speed| ![https://i.imgur.com/Vz7oeaw.png](https://i.imgur.com/Vz7oeaw.png)10% |
|![https://i.imgur.com/Lj0t0q4.png](https://i.imgur.com/Lj0t0q4.png)<br>Dagannoth Supreme|![https://i.imgur.com/xs0XM0D.png](https://i.imgur.com/xs0XM0D.png)Armadyl chestplate<br>![https://i.imgur.com/bZRieVo.png](https://i.imgur.com/bZRieVo.png)Armadyl chainskirt<br>![https://i.imgur.com/JSFjj3B.png](https://i.imgur.com/JSFjj3B.png)Bandos chestplate<br>![https://i.imgur.com/8z6TtFt.png](https://i.imgur.com/8z6TtFt.png)Bandos tassets<br>![https://i.imgur.com/GU63s9I.png](https://i.imgur.com/GU63s9I.png)Saradomin godsword|![https://i.imgur.com/Vz7oeaw.png](https://i.imgur.com/Vz7oeaw.png)2% speed<br>![https://i.imgur.com/Vz7oeaw.png](https://i.imgur.com/Vz7oeaw.png)2% speed<br>![https://i.imgur.com/Vz7oeaw.png](https://i.imgur.com/Vz7oeaw.png)2% speed<br>![https://i.imgur.com/Vz7oeaw.png](https://i.imgur.com/Vz7oeaw.png)2% speed<br>![https://i.imgur.com/Vz7oeaw.png](https://i.imgur.com/Vz7oeaw.png)2% speed| ![https://i.imgur.com/Vz7oeaw.png](https://i.imgur.com/Vz7oeaw.png)10% |
|![https://i.imgur.com/Lyb6HG4.png](https://i.imgur.com/Lyb6HG4.png)<br>Giant Mole|![https://i.imgur.com/Cib3CT9.png](https://i.imgur.com/Cib3CT9.png)Barrows gloves<br>![https://i.imgur.com/z38Shwd.png](https://i.imgur.com/z38Shwd.png)Berserker ring|![https://i.imgur.com/Vz7oeaw.png](https://i.imgur.com/Vz7oeaw.png)5% speed<br>![https://i.imgur.com/Vz7oeaw.png](https://i.imgur.com/Vz7oeaw.png)5% speed| ![https://i.imgur.com/Vz7oeaw.png](https://i.imgur.com/Vz7oeaw.png)10% |
|![https://i.imgur.com/RY8Q4nl.gif](https://i.imgur.com/RY8Q4nl.gif)<br>Kalphite queen|![https://i.imgur.com/bqPPeGv.png](https://i.imgur.com/bqPPeGv.png)Dragon warhammer|![https://i.imgur.com/Vz7oeaw.png](https://i.imgur.com/Vz7oeaw.png)10% speed| ![https://i.imgur.com/Vz7oeaw.png](https://i.imgur.com/Vz7oeaw.png)10% |
|![https://i.imgur.com/B8d3SFz.png](https://i.imgur.com/B8d3SFz.png)<br>King Black Dragon|![https://i.imgur.com/m4ljYLH.png](https://i.imgur.com/m4ljYLH.png)Armadyl crossbow|![https://i.imgur.com/Vz7oeaw.png](https://i.imgur.com/Vz7oeaw.png)10% speed| ![https://i.imgur.com/Vz7oeaw.png](https://i.imgur.com/Vz7oeaw.png)10% |
|![https://i.imgur.com/5hEsHtN.png](https://i.imgur.com/5hEsHtN.png)<br>Vorkath|![https://i.imgur.com/bqPPeGv.png](https://i.imgur.com/bqPPeGv.png)Dragon warhammer|![https://i.imgur.com/Vz7oeaw.png](https://i.imgur.com/Vz7oeaw.png)10% speed| ![https://i.imgur.com/Vz7oeaw.png](https://i.imgur.com/Vz7oeaw.png)10% |
|![https://i.imgur.com/ybsrnDr.gif](https://i.imgur.com/ybsrnDr.gif)<br>Zulrah<br><br>|![https://i.imgur.com/Cib3CT9.png](https://i.imgur.com/Cib3CT9.png)Barrows gloves<br>![https://i.imgur.com/BqfyfaF.png](https://i.imgur.com/BqfyfaF.png)Ranger boots<br>![https://i.imgur.com/bAdFMyD.png](https://i.imgur.com/bAdFMyD.png)Iban's staff|![https://i.imgur.com/Vz7oeaw.png](https://i.imgur.com/Vz7oeaw.png)5% speed<br>![https://i.imgur.com/Vz7oeaw.png](https://i.imgur.com/Vz7oeaw.png)5% speed<br>![https://i.imgur.com/Vz7oeaw.png](https://i.imgur.com/Vz7oeaw.png)2% speed| ![https://i.imgur.com/Vz7oeaw.png](https://i.imgur.com/Vz7oeaw.png)12% |
|**Other Monsters**|**Item needed to receive boost**|**Boost Type**|
|![https://i.imgur.com/0ezmC4X.png](https://i.imgur.com/0ezmC4X.png)<br>Barrows|![https://i.imgur.com/Cib3CT9.png](https://i.imgur.com/Cib3CT9.png)Barrows gloves<br>![https://i.imgur.com/bAdFMyD.png](https://i.imgur.com/bAdFMyD.png)Iban's staff|![https://i.imgur.com/Vz7oeaw.png](https://i.imgur.com/Vz7oeaw.png)2% speed<br>![https://i.imgur.com/Vz7oeaw.png](https://i.imgur.com/Vz7oeaw.png)5% speed| ![https://i.imgur.com/Vz7oeaw.png](https://i.imgur.com/Vz7oeaw.png)7% |
|![https://i.imgur.com/RCq6gBl.png](https://i.imgur.com/RCq6gBl.png)<br>Blue dragons|![https://i.imgur.com/aHFRwuE.png](https://i.imgur.com/aHFRwuE.png)Zamorakian spear|![https://i.imgur.com/Vz7oeaw.png](https://i.imgur.com/Vz7oeaw.png)10% speed| ![https://i.imgur.com/Vz7oeaw.png](https://i.imgur.com/Vz7oeaw.png)10% |
|![https://i.imgur.com/1TK5Qas.gif](https://i.imgur.com/1TK5Qas.gif)<br>Lizardman Shamans<br><br>|![https://i.imgur.com/6wqLRr5.png](https://i.imgur.com/6wqLRr5.png)Ring of the gods|![https://i.imgur.com/Vz7oeaw.png](https://i.imgur.com/Vz7oeaw.png)3% speed| ![https://i.imgur.com/Vz7oeaw.png](https://i.imgur.com/Vz7oeaw.png)3% |
|**Skills**|**Item or skills needed to receive boost**|**Boost Type**|
|![https://i.imgur.com/PeOmcP0.png](https://i.imgur.com/PeOmcP0.png)<br> Cooking|![https://i.imgur.com/HzQFYeR.png](https://i.imgur.com/HzQFYeR.png)Cooking gauntlets|![https://i.imgur.com/Vz7oeaw.png](https://i.imgur.com/Vz7oeaw.png)See chart in [FAQ](https://www.oldschool.gg/oldschoolbot/faq?How%20do%20boosts%20work?)|
|![https://i.imgur.com/7i8JM9L.png](https://i.imgur.com/7i8JM9L.png)<br>Fishing|![https://i.imgur.com/URDEHIO.png](https://i.imgur.com/URDEHIO.png)Angler's outfit|![https://i.imgur.com/Vz7oeaw.png](https://i.imgur.com/Vz7oeaw.png)2.5% XP| ![https://i.imgur.com/Vz7oeaw.png](https://i.imgur.com/Vz7oeaw.png)2.5% XP |
|![https://i.imgur.com/zG0bWp7.png](https://i.imgur.com/zG0bWp7.png)<br>Mining|![https://i.imgur.com/8JQOBlg.png](https://i.imgur.com/8JQOBlg.png)Dragon pickaxe<br>![https://i.imgur.com/UY6Rp6U.png](https://i.imgur.com/UY6Rp6U.png)Infernal pickaxe<br>![https://i.imgur.com/CHNKQr2.png](https://i.imgur.com/CHNKQr2.png)Gilded pickaxe<br>![https://i.imgur.com/66w7fwS.png](https://i.imgur.com/66w7fwS.png)3rd age pickaxe<br>![https://i.imgur.com/x3m2j1I.png](https://i.imgur.com/x3m2j1I.png)Mining gloves<br>![https://i.imgur.com/1its8nr.png](https://i.imgur.com/1its8nr.png)Superior mining gloves<br>![https://i.imgur.com/nxBBe6A.png](https://i.imgur.com/nxBBe6A.png)Expert mining gloves<br>![https://i.imgur.com/hA7FGr6.png](https://i.imgur.com/hA7FGr6.png)Prospector Outfit|![https://i.imgur.com/Vz7oeaw.png](https://i.imgur.com/Vz7oeaw.png)6% speed<br>![https://i.imgur.com/Vz7oeaw.png](https://i.imgur.com/Vz7oeaw.png)10% speed<br>![https://i.imgur.com/Vz7oeaw.png](https://i.imgur.com/Vz7oeaw.png)11% speed<br>![https://i.imgur.com/Vz7oeaw.png](https://i.imgur.com/Vz7oeaw.png)13% speed<br>![https://i.imgur.com/Vz7oeaw.png](https://i.imgur.com/Vz7oeaw.png)2% speed<br>![https://i.imgur.com/Vz7oeaw.png](https://i.imgur.com/Vz7oeaw.png)4% speed<br>![https://i.imgur.com/Vz7oeaw.png](https://i.imgur.com/Vz7oeaw.png)6% speed<br>![https://i.imgur.com/Vz7oeaw.png](https://i.imgur.com/Vz7oeaw.png)2.5% XP| ![https://i.imgur.com/Vz7oeaw.png](https://i.imgur.com/Vz7oeaw.png)19% speed & 2.5% XP |
|![https://i.imgur.com/AyvDOtc.png](https://i.imgur.com/AyvDOtc.png)<br>Runecrafting|![https://i.imgur.com/M5jOoRH.png](https://i.imgur.com/M5jOoRH.png)Graceful outfit<br>![https://i.imgur.com/VeCwOcX.png](https://i.imgur.com/VeCwOcX.png)Agility 60+<br>![https://i.imgur.com/VeCwOcX.png](https://i.imgur.com/VeCwOcX.png)Agility 90+|![https://i.imgur.com/Vz7oeaw.png](https://i.imgur.com/Vz7oeaw.png)10% speed<br>![https://i.imgur.com/Vz7oeaw.png](https://i.imgur.com/Vz7oeaw.png)5% speed<br>![https://i.imgur.com/Vz7oeaw.png](https://i.imgur.com/Vz7oeaw.png)10% speed| ![https://i.imgur.com/Vz7oeaw.png](https://i.imgur.com/Vz7oeaw.png)20% |
|![https://i.imgur.com/U9i2NB0.png](https://i.imgur.com/U9i2NB0.png)<br>Smithing|![https://i.imgur.com/D5N7XUY.png](https://i.imgur.com/D5N7XUY.png)Goldsmith gauntlets|![https://i.imgur.com/Vz7oeaw.png](https://i.imgur.com/Vz7oeaw.png)Gold ore: 56.2 XP|
|![https://i.imgur.com/80QzvvT.png](https://i.imgur.com/80QzvvT.png)<br>Woodcutting|![https://i.imgur.com/BDIyEkU.png](https://i.imgur.com/BDIyEkU.png)Dragon axe<br>![https://i.imgur.com/fdbwYGh.png](https://i.imgur.com/fdbwYGh.png)Infernal axe<br>![https://i.imgur.com/plqFQlN.png](https://i.imgur.com/plqFQlN.png)Gilded axe<br>![https://i.imgur.com/VOLE3PK.png](https://i.imgur.com/VOLE3PK.png)3rd age axe<br>![https://i.imgur.com/f5d0NMw.png](https://i.imgur.com/f5d0NMw.png)Lumberjack outfit|![https://i.imgur.com/Vz7oeaw.png](https://i.imgur.com/Vz7oeaw.png)9% speed<br>![https://i.imgur.com/Vz7oeaw.png](https://i.imgur.com/Vz7oeaw.png)11% speed<br>![https://i.imgur.com/Vz7oeaw.png](https://i.imgur.com/Vz7oeaw.png)12% speed<br>![https://i.imgur.com/Vz7oeaw.png](https://i.imgur.com/Vz7oeaw.png)13% speed<br>![https://i.imgur.com/Vz7oeaw.png](https://i.imgur.com/Vz7oeaw.png)2.5% XP| ![https://i.imgur.com/Vz7oeaw.png](https://i.imgur.com/Vz7oeaw.png)13% speed & 2.5% XP |
|**Miscellaneous**|**Boost**|**Boost Type**|
|![https://i.imgur.com/bVMxdnI.png](https://i.imgur.com/bVMxdnI.png)<br>Clues|![https://i.imgur.com/QhdyDUi.png](https://i.imgur.com/QhdyDUi.png)Graceful outfit|![https://i.imgur.com/Vz7oeaw.png](https://i.imgur.com/Vz7oeaw.png)10% speed| ![https://i.imgur.com/Vz7oeaw.png](https://i.imgur.com/Vz7oeaw.png)10% |
|![https://i.imgur.com/BDkYYWj.png](https://i.imgur.com/BDkYYWj.png)<br>Questing|![https://i.imgur.com/QhdyDUi.png](https://i.imgur.com/QhdyDUi.png)Graceful outfit|![https://i.imgur.com/Vz7oeaw.png](https://i.imgur.com/Vz7oeaw.png)10% speed| ![https://i.imgur.com/Vz7oeaw.png](https://i.imgur.com/Vz7oeaw.png)10% |


### Buyable items

Upon reaching the required Quest points for an item, you can purchase these items by typing `+buy <item>`.

| **Item** | **Quest points required** | **Price** |
| - | :-: | :-: |
| ![https://i.imgur.com/WCGycDU.png](https://i.imgur.com/WCGycDU.png)Quest Point Cape | 275 | 99k |
| ![https://i.imgur.com/Cib3CT9.png](https://i.imgur.com/Cib3CT9.png)Barrows gloves | 175 | 1m |
| ![https://i.imgur.com/QYbrLjw.png](https://i.imgur.com/QYbrLjw.png)Dragon gloves | 107 | 850k |
| ![https://i.imgur.com/mvjoLOA.png](https://i.imgur.com/mvjoLOA.png)Rune gloves | 85 | 700k |
| ![https://i.imgur.com/xhhRr6P.png](https://i.imgur.com/xhhRr6P.png)Helm of Neitiznot | 75 | 500k |
| ![https://i.imgur.com/Pp2hNGC.png](https://i.imgur.com/Pp2hNGC.png)Adamant gloves | 65 | 600k |
| ![https://i.imgur.com/0ap6dGZ.png](https://i.imgur.com/0ap6dGZ.png)Mithril gloves | 50 | 500k |
| ![https://i.imgur.com/Hedj8zL.png](https://i.imgur.com/Hedj8zL.png)Magic Secateurs | 40 | 2.5m | 
| ![https://i.imgur.com/uwjKSEb.png](https://i.imgur.com/uwjKSEb.png)Anti-dragon shield | 35 | 10k |
| ![https://i.imgur.com/qXzN8mK.png](https://i.imgur.com/qXzN8mK.png)Black gloves | 35 | 400k |
| ![https://i.imgur.com/bAdFMyD.png](https://i.imgur.com/bAdFMyD.png)Iban's staff | 30 | 250k |
| ![https://i.imgur.com/wivDiNF.png](https://i.imgur.com/wivDiNF.png)Barrelchest ancor | 30 | 2m |
| ![https://i.imgur.com/Hnj7lRr.png](https://i.imgur.com/Hnj7lRr.png)Steel gloves | 25 | 300k |
| ![https://i.imgur.com/Lvexhtm.png](https://i.imgur.com/Lvexhtm.png)Goldsmith gauntlets | 25 | 1m |
| ![https://i.imgur.com/HzQFYeR.png](https://i.imgur.com/HzQFYeR.png)Cooking gauntlets | 25 | 1m |
| ![https://i.imgur.com/9zEdBbq.png](https://i.imgur.com/9zEdBbq.png)Iron gloves | 20 | 200k |
| ![https://i.imgur.com/RVM6G3N.png](https://i.imgur.com/RVM6G3N.png)Bronze gloves | 10 | 100k |
| ![https://i.imgur.com/72rIEv4.png](https://i.imgur.com/72rIEv4.png)Hardleather gloves | 5 | 50k |
| ![https://i.imgur.com/1XOVNWd.png](https://i.imgur.com/1XOVNWd.png)Huge Fishing Bait Pack | N/A | 50k |
| ![https://i.imgur.com/YH1WAdo.png](https://i.imgur.com/YH1WAdo.png)Huge Jug Pack (300x Jugs of water)| N/A | 30k |
| ![https://i.imgur.com/3Zt7EfD.png](https://i.imgur.com/3Zt7EfD.png)Feather pack (300x Feathers) | N/A | 30k

### Boss and monster requirements
|**God Wards Dungeon bosses** | **Items required** | **QP required** |
| :-: | :-: | :-: |
|![https://i.imgur.com/Aoynyet.png](https://i.imgur.com/Aoynyet.png)<br>Commander Zilyana(Sara)|![https://i.imgur.com/xs0XM0D.png](https://i.imgur.com/xs0XM0D.png)Armadyl chestplate **or**<br>![https://i.imgur.com/1HeouvW.png](https://i.imgur.com/1HeouvW.png)Karil's leathertop<br>**and**<br>![https://i.imgur.com/bZRieVo.png](https://i.imgur.com/bZRieVo.png)Armadyl chainskirt **or**<br>![https://i.imgur.com/r1csy4v.png](https://i.imgur.com/r1csy4v.png)Karil's leatherskirt| 75 QP |
|![https://i.imgur.com/MKTNBsR.png](https://i.imgur.com/MKTNBsR.png)<br>K'ril Tsutsaroth(Zammy)|![https://i.imgur.com/xs0XM0D.png](https://i.imgur.com/xs0XM0D.png)Armadyl chestplate **or**<br>![https://i.imgur.com/1HeouvW.png](https://i.imgur.com/1HeouvW.png)Karil's leathertop<br>**and**<br>![https://i.imgur.com/bZRieVo.png](https://i.imgur.com/bZRieVo.png)Armadyl chainskirt **or**<br>![https://i.imgur.com/r1csy4v.png](https://i.imgur.com/r1csy4v.png)Karil's leatherskirt| 75 QP |
|![https://i.imgur.com/YpEBUDM.png](https://i.imgur.com/YpEBUDM.png)<br>Kree'arra(Arma)|![https://i.imgur.com/xs0XM0D.png](https://i.imgur.com/xs0XM0D.png)Armadyl chestplate **or**<br>![https://i.imgur.com/1HeouvW.png](https://i.imgur.com/1HeouvW.png)Karil's leathertop<br>**and**<br>![https://i.imgur.com/bZRieVo.png](https://i.imgur.com/bZRieVo.png)Armadyl chainskirt **or**<br>![https://i.imgur.com/r1csy4v.png](https://i.imgur.com/r1csy4v.png)Karil's leatherskirt| 75 QP |
|![https://i.imgur.com/TBVEcxB.png](https://i.imgur.com/TBVEcxB.png)<br>General Graardor<br><br>| N/A | 75 QP |
|**Wilderness Bosses**| **Items required** | **QP required** |
|![https://i.imgur.com/FUDRrtb.png](https://i.imgur.com/FUDRrtb.png)<br>Callisto | ![https://i.imgur.com/s2MVh1n.png](https://i.imgur.com/s2MVh1n.png)Full Verac's | N/A |
|![https://i.imgur.com/brj0guF.png](https://i.imgur.com/brj0guF.png)<br>Chaos elemental| ![https://i.imgur.com/FnVfeBA.png](https://i.imgur.com/FnVfeBA.png)Black d'hide body **or**<br>![https://i.imgur.com/1HeouvW.png](https://i.imgur.com/1HeouvW.png)Karil's leathertop<br>**and**<br> ![https://i.imgur.com/318G7Vl.png](https://i.imgur.com/318G7Vl.png)Black d'hide chaps **or**<br>![https://i.imgur.com/r1csy4v.png](https://i.imgur.com/r1csy4v.png)Karil's leatherskirt| N/A |
|![https://i.imgur.com/PucrJNy.png](https://i.imgur.com/PucrJNy.png)<br>Venenatis|![https://i.imgur.com/s2MVh1n.png](https://i.imgur.com/s2MVh1n.png)Full Verac's|N/A |
|![https://i.imgur.com/d5bRYpQ.gif](https://i.imgur.com/d5bRYpQ.gif)<br>Vet'ion<br><br>|![https://i.imgur.com/s2MVh1n.png](https://i.imgur.com/s2MVh1n.png)Full Verac's|N/A |
|**General Bosses**| **Items required** | **QP required** |
|![https://i.imgur.com/C8Pj39a.png](https://i.imgur.com/C8Pj39a.png)<br>Cerberus|![https://i.imgur.com/Ee5excb.png](https://i.imgur.com/Ee5excb.png)Torag's platebody **or**<br>![https://i.imgur.com/9tkiIIu.png](https://i.imgur.com/9tkiIIu.png)Dharok's platebody **or**<br>![https://i.imgur.com/JSFjj3B.png](https://i.imgur.com/JSFjj3B.png)Bandos chestplate <br>**and**<br>![https://i.imgur.com/4ggKDTF.png](https://i.imgur.com/4ggKDTF.png)Torag's platelegs **or**<br>![https://i.imgur.com/b5NG8Bz.png](https://i.imgur.com/b5NG8Bz.png)Dharok's platelegs **or**<br>![https://i.imgur.com/8z6TtFt.png](https://i.imgur.com/8z6TtFt.png)Bandos tassets<br>**and**<br>![https://i.imgur.com/aHFRwuE.png](https://i.imgur.com/aHFRwuE.png)Zamorakian spear|N/A |
|![https://i.imgur.com/6d3aSw7.png](https://i.imgur.com/6d3aSw7.png)<br>Corporeal beast|![https://i.imgur.com/aHFRwuE.png](https://i.imgur.com/aHFRwuE.png)Zamorakian spear|N/A |
|![https://i.imgur.com/dlgD4uB.png](https://i.imgur.com/dlgD4uB.png)<br>Dagannoth Prime|![https://i.imgur.com/bJb6hUs.png](https://i.imgur.com/bJb6hUs.png)Full Guthan's<br>**and**<br>![https://i.imgur.com/xs0XM0D.png](https://i.imgur.com/xs0XM0D.png)Armadyl chestplate **or**<br>![https://i.imgur.com/1HeouvW.png](https://i.imgur.com/1HeouvW.png)Karil's leathertop<br>**and**<br>![https://i.imgur.com/bZRieVo.png](https://i.imgur.com/bZRieVo.png)Armadyl chainskirt **or**<br>![https://i.imgur.com/r1csy4v.png](https://i.imgur.com/r1csy4v.png)Karil's leatherskirt|N/A |
|![https://i.imgur.com/DKLWf3O.png](https://i.imgur.com/DKLWf3O.png)<br>Dagannoth Rex|![https://i.imgur.com/bJb6hUs.png](https://i.imgur.com/bJb6hUs.png)Full Guthan's<br>**and**<br>![https://i.imgur.com/Ee5excb.png](https://i.imgur.com/Ee5excb.png)Torag's platebody **or**<br>![https://i.imgur.com/JSFjj3B.png](https://i.imgur.com/JSFjj3B.png)Bandos chestplate <br>**and**<br>![https://i.imgur.com/4ggKDTF.png](https://i.imgur.com/4ggKDTF.png)Torag's platelegs **or**<br>![https://i.imgur.com/8z6TtFt.png](https://i.imgur.com/8z6TtFt.png)Bandos tassets|N/A |
|![https://i.imgur.com/Lj0t0q4.png](https://i.imgur.com/Lj0t0q4.png)<br>Dagannoth Supreme|![https://i.imgur.com/bJb6hUs.png](https://i.imgur.com/bJb6hUs.png)Full Guthan's<br>**and**<br>![https://i.imgur.com/Ee5excb.png](https://i.imgur.com/Ee5excb.png)Torag's platebody **or**<br>![https://i.imgur.com/JSFjj3B.png](https://i.imgur.com/JSFjj3B.png)Bandos chestplate <br>**and**<br>![https://i.imgur.com/4ggKDTF.png](https://i.imgur.com/4ggKDTF.png)Torag's platelegs **or**<br>![https://i.imgur.com/8z6TtFt.png](https://i.imgur.com/8z6TtFt.png)Bandos tassets|N/A |
|![https://i.imgur.com/Lyb6HG4.png](https://i.imgur.com/Lyb6HG4.png)<br>Giant Mole|![https://i.imgur.com/qCVH9Qw.png](https://i.imgur.com/qCVH9Qw.png)Full Dharok's|N/A |
|![https://i.imgur.com/RY8Q4nl.gif](https://i.imgur.com/RY8Q4nl.gif)<br>Kalphite queen|![https://i.imgur.com/oIvH4L4.png](https://i.imgur.com/oIvH4L4.png)Verac's flail<br>**and**<br>![https://i.imgur.com/FnVfeBA.png](https://i.imgur.com/FnVfeBA.png)Black d'hide body **or**<br>![https://i.imgur.com/1HeouvW.png](https://i.imgur.com/1HeouvW.png)Karil's leathertop<br>**and**<br>![https://i.imgur.com/PO87WWj.png](https://i.imgur.com/PO87WWj.png)Verac's plateskirt|N/A |
|![https://i.imgur.com/B8d3SFz.png](https://i.imgur.com/B8d3SFz.png)<br>King Black Dragon]|![https://i.imgur.com/m4ljYLH.png](https://i.imgur.com/m4ljYLH.png)Armadyl crossbow **or**<br>![https://i.imgur.com/PEzCNQy.png](https://i.imgur.com/PEzCNQy.png)Rune crossbow<br>**and**<br>![https://i.imgur.com/uwjKSEb.png](https://i.imgur.com/uwjKSEb.png)Anti-dragon shield<br>**and**<br>![https://i.imgur.com/FnVfeBA.png](https://i.imgur.com/FnVfeBA.png)Black d'hide body **or**<br>![https://i.imgur.com/1HeouvW.png](https://i.imgur.com/1HeouvW.png)Karil's leathertop<br>**and**<br> ![https://i.imgur.com/318G7Vl.png](https://i.imgur.com/318G7Vl.png)Black d'hide chaps **or**<br>![https://i.imgur.com/r1csy4v.png](https://i.imgur.com/r1csy4v.png)Karil's leatherskirt|N/A |
|![https://i.imgur.com/5hEsHtN.png](https://i.imgur.com/5hEsHtN.png)<br>Vorkath|![https://i.imgur.com/xs0XM0D.png](https://i.imgur.com/xs0XM0D.png)Armadyl chestplate<br>**and**<br>![https://i.imgur.com/bZRieVo.png](https://i.imgur.com/bZRieVo.png)Armadyl chainskirt|205 QP |
|![https://i.imgur.com/ybsrnDr.gif](https://i.imgur.com/ybsrnDr.gif)<br>Zulrah<br><br>|![https://i.imgur.com/xs0XM0D.png](https://i.imgur.com/xs0XM0D.png)Armadyl chestplate<br>**and**<br>![https://i.imgur.com/bZRieVo.png](https://i.imgur.com/bZRieVo.png)Armadyl chainskirt<br>**and**<br>![https://i.imgur.com/vfecEnK.png](https://i.imgur.com/vfecEnK.png)Ahrim's robetop<br>**and**<br>![https://i.imgur.com/RnpehNG.png](https://i.imgur.com/RnpehNG.png)Ahrim's robeskirt|75 QP |
|  **Other Monsters**  | **Items required** | **QP required** |
|![https://i.imgur.com/1TK5Qas.gif](https://i.imgur.com/1TK5Qas.gif)<br>Lizardman Shamans|![https://i.imgur.com/m4ljYLH.png](https://i.imgur.com/m4ljYLH.png)Armadyl crossbow **or**<br>![https://i.imgur.com/PEzCNQy.png](https://i.imgur.com/PEzCNQy.png)Rune crossbow **or**<br>![https://i.imgur.com/6s6zlTV.png](https://i.imgur.com/6s6zlTV.png)Karil's crossbow | 30 QP |
|![https://i.imgur.com/5SZzHxr.png](https://i.imgur.com/5SZzHxr.png)<br>Lizardman | N/A | 30 QP

# Bank Backgrounds

If you meet the requirements and costs of a background, you can get it using `+bankbg <name>`. The image will replace the background of your bank. Bank backgrounds require that you pay GP, items and having certain items in your collection log, they are quite hard to obtain.

Click on the bank bg name to see what it looks like.

| **Name** | **GP Cost** | **Item Cost** | **Collection Log Items Needed** |
| - | :-: | :-: | :-: |
| [Default](https://github.com/gc/oldschoolbot/blob/master/resources/images/bank_backgrounds/1.jpg?raw=true) | 0  |   |  |
| [Bandos](https://github.com/gc/oldschoolbot/blob/master/resources/images/bank_backgrounds/7.jpg?raw=true) | 100m | The 4 Godsword Hilts | Entire GWD log excluding pets, + Bandos pet |
| [Corporeal Beast](https://github.com/gc/oldschoolbot/blob/master/resources/images/bank_backgrounds/8.jpg?raw=true) | 100m  |   | Entire Corporeal Beast log including pet |
| [Casket (Legend Arts)](https://github.com/gc/oldschoolbot/blob/master/resources/images/bank_backgrounds/9.jpg) | 100m  |   | The 4 clue milestone item rewards|


# Minion Icons

You can sacrifice items, and their GP value will go towards you unlocking new minion icons. You will automatically receive the icon immediately after sacrificing enough GP. You can see a leaderboard of who has sacrificed the most using `+lb sacrifice`.

You can sacrifice items using `+sacrifice [quantity] <item>`, like `+sacrifice Bandos chestplate` or `+sacrifice 1000 gold ore`. You cannot sacrifice GP, instead you should buy items off other players with your GP and sacrifice those.

| Icon | Amount Required |
|:----------------------------:|:---------------:|
| ![](https://cdn.discordapp.com/emojis/679007949108281357.png?v=1) | 0 |
| ![](https://cdn.discordapp.com/emojis/673561629115416616.png?v=1) | 100m |
| ![](https://cdn.discordapp.com/emojis/673561610366746635.png?v=1) | 500m |
| ![](https://cdn.discordapp.com/emojis/673561610228465664.png?v=1) | 1b |
| ![](https://cdn.discordapp.com/emojis/673561609834070047.png?v=1) | 5b |
| ![](https://cdn.discordapp.com/emojis/673561609913892899.png?v=1) | 10b |

# Patreon

The Patreon is a way for users to donate to me (Magnaboy), if you wish. It's entirely your choice, if you want to. I will never sell items/GP from the bot for money, nor P2W perks/advantages. 

You can donate to me on Patreon here: [https://www.patreon.com/oldschoolbot](https://www.patreon.com/oldschoolbot)
