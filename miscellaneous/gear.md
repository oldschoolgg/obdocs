---
description: This page goes over how your gear functions on the bot.
---

# Gear

Your minion has 6 gear setups \(Melee, Mage, Range, Skilling, Misc, and Wildy\) in which you can equip your gear into depending on what activity you want to do on the bot. Below is a list of the commands that deal with equip and unequipping gear on your minion. Lets say you just finished questing and bought yourself a pair of barrows gloves and you would like to equip those in your range setup, you would type `+equip range barrows gloves`. Now lets say you already had a pair of mithril gloves equipped in your range setup and you wanted to equip the barrows gloves instead now, you do not need to unequip the other gloves first, the equip command will take the other pair off for you and equip the new item. Further below we will talk about `+gearpresets` a way for you to save a setup you like for later for easy equipping.  
  


![](../.gitbook/assets/osbot.png)

<table>
  <thead>
    <tr>
      <th style="text-align:left">Command</th>
      <th style="text-align:left">What it does</th>
      <th style="text-align:left">Example</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align:left">+autoequip</td>
      <td style="text-align:left">Automatically equips the BIS gear you have in your bank, for a particular
        attack style, to one of your gear setups. (note will not pull from other
        equipped gear)</td>
      <td style="text-align:left">+autoequip melee attack crush +autoequip mage attack magic</td>
    </tr>
    <tr>
      <td style="text-align:left">+equip</td>
      <td style="text-align:left">Equips an item to one of your gear setups.</td>
      <td style="text-align:left">
        <p>+equip skilling graceful hood</p>
        <p>+equip melee bandos boots</p>
        <p>+equip mage staff of fire</p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">+gear</td>
      <td style="text-align:left">Shows your equipped gear.</td>
      <td style="text-align:left">
        <p>+gear melee</p>
        <p>+gear --all</p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">+unequip</td>
      <td style="text-align:left">Unequips items from one of your gear setups.</td>
      <td style="text-align:left">
        <p>+unequip range Twisted bow</p>
        <p>+unequip melee Abyssal whip</p>
      </td>
    </tr>
    <tr>
      <td style="text-align:left">+unequipall</td>
      <td style="text-align:left">Unequips everything from one of your gear setups. (melee/range/range/skilling/misc)</td>
      <td
      style="text-align:left">+unequipall melee</td>
    </tr>
    <tr>
      <td style="text-align:left">+equippet</td>
      <td style="text-align:left">Equips a pet, like dropping it on the floor ingame.</td>
      <td style="text-align:left">+equippet smolcano</td>
    </tr>
    <tr>
      <td style="text-align:left">+unequippet</td>
      <td style="text-align:left">Unequips your pet.</td>
      <td style="text-align:left">+unequippet</td>
    </tr>
  </tbody>
</table>

### Gear Presets

Now that you have equipped the gear you like you probably would like to save that setup for later before you equip something up in that setup. This can done through the `+gearpresets` commands listed before. Along with the ability to make your own presets there are some global presets available to you at the start such as the "Graceful" preset which will equip full graceful in the specified gear setup.  
  
By default, you are restricted to having 3 gear presets. However, this is increased to 7 if you are a patron or a github supporter.

| Command | What it does | Example |
| :--- | :--- | :--- |
| +gearpresets | Shows you your presets you have made. | +gearpresets |
| +gearpresets new  &lt;name&gt; &lt;setup&gt; | copy your &lt;setup&gt; gear into a preset called &lt;name&gt;. | +gearpresets new corp melee |
| +gearpresets delete  &lt;name&gt; | delete your setup called &lt;name&gt;. | +gearpresets delete corp |
| +gearpresets equip  &lt;name&gt; &lt;setup&gt; | equip your &lt;name&gt; setup to your &lt;setup&gt; outfit. | +gearpresets equip corp melee |

#### Global Gear Presets

* Graceful
* Pyro
* Carpenter
* Rogue
* Clue
* Angler
* Prospector

### Wildy Setup

The wilderness setup is currently only used at revenants. **All** of the items equipped in this setup can be **permanently lost** if you are killed while doing activities that use this setup.

