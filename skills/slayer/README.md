# Slayer \(NEW\)

Slayer is a skill where you're assigned to kill a certain amount of a certain monster - called a 'task', you keep completing lots of tasks to unlock more knowledge on slaying monsters, and gain points which can be used to unlock rewards.

So, in very simple terms to train slayer, all you need to do is: **Get a task** \(`+slayertask`\) then **Kill that monster** \(`+k monster`\).

## Commands

* **Get a new slayer task, or check your current task:**

  * `+slayertask turael` / `+st duradel`
  * You can set a Slayer master as your default using `--save`, so that you don't have to specify the name every time. E.g. `+slayertask duradel --save`

* **Automatically send your minion to kill your currently assigned task:**

  * `+autoslay` / `+as`

* **Skip your current task:**

  * `+st skip`

* **Buy rewards/unlocks from the Slayer shop:**

  * `+slayershop unlock malevolant masquerade`
  * `+slayershop unlock red slayer helmet`

* **List Slayer shop unlocks:**

  * `+slayershop unlock help`

* **Blocking tasks:**

  * Block current task: `+st block`
  * See block list: `+st list`
  * Unblock a task: `+st unblock blue dragon`

* **Getting a Slayer Helmet:**

  * Firstly, unlock the Slayer helmet using `+sls unlock slayer helmet`
  * With a black mask and 55 Crafting, buy the required items from the bot, and then `+create slayer helmet` 

* **Use a Cannon in your task**

  * If you own a cannon and cannonballs, the cannon can be used at some slayer tasks to speed it up, at the cost of cannonballs. You can do this by adding `--cannon` to your message. E.g `+k dagannoth --cannon`
  * You can buy a cannon using `+buy dwarf multicannon`.

* **Barrage your task:**

  * If you have sufficient Runes and the Magic level, you can barrage your tasks, to speed it up at the cost of runes. You can do this by adding `--barrage` to your message. E.g `+k abyssal demon --barrage .` You can also burst tasks using `--burst` instead.

* **Default to always barraging/bursting/cannoning**

  * `+cbops add/remove always barrage/burst/cannon`

* **Automatically slay your task with guided settings:**

  * `+as default/lowest/efficient/boss`
  * Optionally add `--save` to set your default
  * **Default**: kills the monster you're assigned
  * **Lowest**: kills the lowest combat level monster
  * **Efficient**: Use with `always cannon` for the most efficient tasks for Slayer XP.
  * **Boss**: Kills the boss variant or similar, \(e.g. Demonic gorillas for Black demons\)

