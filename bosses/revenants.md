# Revenants

Revenants are some high risk, high reward content that allows you to collect some handy wildy weapons and many high tier resources. Revs uses the gear in your wildy setup, which means, you CAN lose pieces of gear from this setup. Please read this entire page before embarking.

To start a trip, use the `+revs (style) (name)` command.

* E.g. `+revs range imp`
* E.g. `+revs mage dragon --skull`

**Note:** You can add `--skull` at the end of your cmd to fight the revs skulled. This removes the lower value items from the unique table but you risk more of your equipped items.

## Things To Know Before Starting

Like aforementioned, you will use the wildy setup for killing revs. You CAN lose everything from this setup if unlucky so, _**don't equip items you are not willing to lose.**_

You can check which items are potentially at risk and which items you will keep if killed. Use:

* `+revs --skull` - show items you will keep if skulled
* `+revs --smited` - show items you will keep if smited

**Note:** If you do revs while _skulled_ and get _smited_, you will lose your entire wildy setup.

### **Smite Chance** ![](../.gitbook/assets/Smite.png)****

You have a 1/300 chance to be smited while on a trip. However, if you do not have 5x prayer potion(4), which _you will warned about before embarking_, you have a 1/20 chance to be smited.

### **Death Chance** ![](<../.gitbook/assets/Skull (status) icon.png>)****

Your total death chance is calculated on your **magic defence stat** and your **defence level**. _You always have a minimum base 5% chance to die._ The lowest you can get your total death chance to is 10%.&#x20;

**Defence Level:** If your defence level is 99, the death chance from your defence level is 0%. If your defence level is not 99, use the following formula to work out the extra death chance %.

* Death chance = _(100 - defence level) / 4_

**Magic Defence Stat:** The lowest death chance you can achieve through this is 5%. The maximum magic defence stat is 238, however, you only need to reach 190 magic defence for this to be lowered to 5%. Anything higher than 190 will not get you any lower death chance.

**Death % Example:** You have 99 Defence + 200 magic defence stat. This means:

* You will get 0% extra death chance because you are 99 defence.
* \+ You will get the minimum extra 5% death chance from your magic defence stat.
* \+ You will get the default 5% death chance.
* \= Total 10% death chance.

### Attack Style Bonus ![](<../.gitbook/assets/Combat icon.png>)

You will receive a boost to revenant kill times based on which attack style you use and it's respective stat. The 3 styles the bot will utilise are crush attack, range attack, or magic attack. You can work out your attack boost with the following formula:

* Attack boost = _(current style bonus / maximum style bonus \* 100) / 4_

The highest attack boost you can obtain is 25%. The maximum style bonuses are listed below:

* Range attack bonus - 246
* Magic attack bonus - 177
* Melee crush bonus - 214

**Attack Style % Example:** You are using the range style with 94 range attack bonus:

* Attack boost = (94/246 \* 100) / 4 = 9.55% bonus

## Boosts

* 35% boost for equipping a charged wildy weapon (**must be equipped in wildy setup**)

## Uniques

#### Bracelets ![](<../.gitbook/assets/Bracelet of ethereum.png>)

Bracelets of ethereum can be charged (requires 2000 ether) but offers no benefit in the bot at this stage. You can also turn bracelets into ether which yields 250 ether per bracelet.

* `/create`` `**`item:`**`bracelet of ethereum`
* `/create`` `**`item:`**`revenant ether`

#### **Wildy Weapons** ![](<../.gitbook/assets/Viggora's chainmace.png>) **** ![](<../.gitbook/assets/Craw's bow.png>) ![](<../.gitbook/assets/Thammaron's sceptre.png>)

These weapons can be charged which will provide boosts at revs themselves and many other wildy bosses. It costs 7000 ether to charge a wildy weapon. To check the boosts which these items give, please visit the [Boosts & Requirements page.](https://wiki.oldschool.gg/bosses/boosts-and-requirements)

* `/create`` `**`item:`**`viggora's chainmace`
* `/create`` `**`item:`**`craw's bow`
* `/create`` `**`item:`**`thammaron's sceptre`

#### **Ancient Items** ![](<../.gitbook/assets/Ancient emblem.png>) ![](<../.gitbook/assets/Ancient totem.png>) ![](<../.gitbook/assets/Ancient statuette.png>) ![](<../.gitbook/assets/Ancient medallion.png>) ![](<../.gitbook/assets/Ancient effigy.png>) ![](<../.gitbook/assets/Ancient relic.png>)

You can sell the ancient items for the same value as in OSRS. Use the `+revs sell` command. This can't be done if your minion is busy.

* E.g. `+revs sell ancient relic`

|                   |              |
| ----------------- | :----------: |
| **Name**          | **GP Value** |
| Ancient emblem    |    500,000   |
| Ancient totem     |   1,000,000  |
| Ancient statuette |   2,000,000  |
| Ancient medallion |   4,000,000  |
| Ancient effigy    |   8,000,000  |
| Ancient relic     |  16,000,000  |

#### Other Uniques ![](<../.gitbook/assets/Amulet of avarice.png>) ![](<../.gitbook/assets/Ancient crystal.png>)

The Amulet of avarice currently has no use within the bot.

Ancient crystals are currently only used to create the Obelisk in a minion's PoH (4 required).
