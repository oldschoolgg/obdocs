# Update - 2021/02/09

### Magic 

The Magic skill has been added, however it's only the skilling aspect of it, and not the combat aspect of it. You may wish to hold off on 
training Magic until its trainable through combat, or train it now with skilling, the choice is yours.

This also brings in the possibility to create jewelry boxes in your POH, because you can now create teleportation jewelry. 

- To start off training Magic, you'll need at least level 7 Magic to start casting skilling spells. For now, you
get this XP through questing. If you have already done some questing, you'll already have some Magic XP. If not, you'll
need to do some questing to get Magic XP.
- You can save runes by using a Staff that gives infinite runes, equip it in your skilling outfit.
- Next, you can train Magic through enchanting items (such as bolts or jewelry), using +enchant.

For example: +enchant 100 opal bolts  +enchant onyx amulet

See all enchantable items using +enchant --items.

- You can also cast a few spells, like bones-to-bananas or camelot teleports. 

For example: +cast 100 bones to bananas +cast camelot teleport

- You can also train magic through alching. E.g. +alch 100 rune platebody

Amulet of Glory Charging

You can now send your minion to charge your uncharged glories, and have a chance of a amulet of eternal glory. 

- Your minion does inventories of 26 glories at a time, minimum of 1 full inventory. To do 5 inventories of glories, do +chargeglories 5.
- You have a small chance of dying in a trip, and losing an inventory of glories.
- You get a significant 3x boost for having Wildy elite diary stat requirements, which FYI includes 96 magic. It's not recommended to do it without wildy elite diary!

### Gnome Restaurant

Added the Gnome Restaurant minigame! It's a fairly bad cooking training method, but offers some unique/odd rewards, like a gnome scarf, gnome goggles, mint cake, gnomeballs, and snake charm.

It's highly recommended that you don't do Gnome Restaurant unless you have some of the boosts.

You get boosts in Gnome Restaurant for... your experience (up to 20% boost at 100 score), 25% for graceful (in skilling outfit), 25% for 66+ Magic (for teleports),
20% for teleportation jewellery.

- For teleporation jewellery, you get a boost for: Amulet of glory(6) OR Games necklace(8) OR Ring of dueling(8). The one needed is random per trip.
- You lose the jewellery, unless its a glory, it just gets uncharged. Alternatively, an Amulet of eternal glory will never lose charge and can be used here.
- Check your CL with +cl gnome restaurant


### Other changes
- Added all dragonfire protection shields to work in place of anti-dragon shield.
- Fixed checking Zalcano kc.
- A few tiny bugfxies.


### Github Sponsors

Github sponsors is an alternative to patreon that you can support me on with money. You receive the same perks/rewards as patreon, and nothing with patreon has or will change. Also, for a limited time they are doubling all payments to me!

There's a few differences with Github sponsors:
- Zero fees
- I made the prices slightly cheaper
- They pro-rate charges (you can pay only like 20cents if its near the end of the month)
- For a limited time, they will DOUBLE your payment to me. Literally doubling money. For example, if you subscribe for $14/month, you pay only $14, but I get $28. This is however, for a limited time only, which is why I want to promote github sponsors now!
- The only requirement is a Github account.
- For now, there is only Tier 3/4/5. Tier 1 and 2 aren't available at the moment.

You can switch to Github sponsors, as a patron at any time. For 24 hours only I'll be offering a refund to patrons who cancel patreon and switch to github sponsors. This effectively means: you get 10 days of patron for free (this month so far), you pay slightly less, and you support me even more. If you wish to do this, follow the steps below then PM me on discord for your patreon refund.  Alternatively, you
can wait until the end of the month and then switch.

To support me on Github Sponsors
1. If you're already a patron, cancel your patreon membership first.
2. Create a github account if you don't have one.
3. Subscribe at https://github.com/sponsors/gc

I planned to have new custom artist-made bank backgrounds available in this update, but the artist is busy :( I'll be commissioning atleast 3 new custom bank backgrounds as a thank you to patrons ASAP.

# Update - 2021/02/08

- `+m stats` now shows more detailed information, in an embed.
- Added ability to check hunter creature kc with `+kc`, e.g. `+kc herbiboar`.
- Added `+unequipall` cmd which unequips everything in one of your setups, e.g. `+unequipall melee`.
- I recently finished a rewrite of lots of minigame code and migrating minigame data in the database.
- Tier 5 patrons can now set a custom minion icon. E.g. `+m seticon <emoji>`.
- Ironman who get 99's will now show what nth *ironman* they are to 99 in #notifications

### Added Gear Presets

Gear presets let you instantly equip a set of gear to one of your outfits. The way you create a gear preset is by "cloning" one of your existing gear setups. 
You then use a command to equip that preset to one of your setups. The items needed for the preset must all be in your bank, and not equipped.

There are global presets available to everyone by default, however currently the only one is "Graceful", which is the full plain graceful outfit.

- `+gearpresets` - see your presets
- `+gearpresets new <name> <setup>` - copy your <setup> gear into a preset called <name>. Example: `+gearpresets new corp melee`
- `+gearpresets delete <name>` - delete your setup called <name>. Example: `+gearpresets delete corp`
- `+gearpresets equip <name> <setup>` - equip your <name> setup to your <setup> outfit. Example: `+gearpresets equip corp melee`
- To equip a global preset, its the exact same as above, except use the global preset name. Example: `+gearpresets equip graceful skilling`

# Update - 2021/01/26

### The **Hunter** skill has been added by Fishy!

The general method of training hunter is to simply: `+hunt <creature>`. You can see all the creatures using `+hunt --creatures`. (Herbi is included, herbs!)
There is also a leaderboard for creature catching/hunting, for example..`+lb creatures herbi` for the most herbis caught (there'll be none at the time of writing)

You can also do Aerial Fishing: `+aerialfish`, and buy aerial-fishing items with `+aerialfish buy <name>`.

You can also do Birdhouses, for example: `+birdhouse run <name>` (e.g. yew birdhouse), then `+birdhouse check` and `+birdhouse collect`.

**Other Hunter Info:**
- Graceful boosts stuff! 
- Having Stams boosts herbiboar hunting.
- Minions get better at hunting a creature over time.
- You can die hunting black chins! You'll want high mage defense gear in misc gear setup(black d'hide works) - **you will lose this gear (and some chins) if you die**, and brews/restores.
- Hunter potion(4) works to skip level requirements. e.g. `+hunt creaturename --potion`
- The first 2 to 99 will get a trophy badge!

### Other Updates

- Fixed a few bugs
- You can now buy buckets of water (For POH pools)
- Removed untrimmed agility cape from skilling CL
- You can now create Toads legs from a swamp toad (from pickpocketing gnomes)
- The Barbarian Assault minigame has been *restricted* to this server only. It's not an ideal thing, but it's become necessary with how difficult it can be to find a team.
- You can now kill Chaos druids and Unicorns.
- You can now **mount an item** in your POH if you have level 99 Construction. First, build an item mount using `+poh build Item mount`. Then mount an item in it using `+poh mountitem <item_name>`. You can switch in a new item, and you'll get the mounted item back.
- You can now **change your wallkit** for your POH. Currently, there's only the Default and **Hosidius wallkit**. If you have hosidius blueprints from mahogany homes, simply do `+poh wallkit hosidius` and it will automatically consume the blueprints to permanently unlock the wallkit for you.
