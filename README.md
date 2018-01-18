# JKEnhanced-GrandMaster

JKEnhanced-GrandMaster seeks to...
* Make the gameplay more balanced over the course of the game.
* Improve things that are useless, including enemies.
* Add a new even harder difficulty mode to the game.

## Features

* Some features do not require Grand Master difficulty and are always on.
* Italic text indicates how things work without the mod and/or why the change was made.

### Weapons
General | Changes | Requires GM difficulty
:---:|---|:---:
Weapon Pickup | Grants a third of the regular ammo amount. | Yes

Weapon | Changes | Original | Requires GM difficulty
:---:|---|---|:---:
Bowcaster | Primary projectiles have as much horizontal as they do vertical spread. | *Had no horizontal spread.*  | No
 \\_ | Projectile angle offset for extra projectiles is not ignored with sense. | *All projectiles stack on top of each other with perfect accuracy when sense is on.* | No
 \\_ | Multiple projectiles shooting arc reduced by 60%. | *Too wide spread with multiple projectiles to be useful when enemy is not in shooters face.* | No
 \\_ | Secondary is half as accurate as primary. | *Secondary is perfectly accurate.* | Yes
Demp2 | Deals 300% or 400% extra damage to combat droids. | *Normally deals 500% or 700% extra.* | Yes

### NPCs
General | Changes | Requires GM difficulty
:---:|---|:---:
Flag "altFire" | Actually works now. NPC will toggle between primary/secondary to avoid self injury with explosives without messing up their fire rate. | No
Flag "cloak" | Any NPC with "cloak 1" in their file will share Imperial Saboteurs cloak mechanics. | No
Vision | By default NPCs can see roughly 50% further. | Yes

Specific | Changes | Original | Requires GM difficulty
:---:|---|---|:---:
Assassin Droid | Can shoot while shield is up. | *Could not shoot.* | Yes
Imperial Saboteur | Can shoot while cloaked. | *Could not shoot.* | No
 \\_ | Permanently cloaked, unless electrified. | Yes
Kyle (Boss) | Grip 'toss aside' strength is reduced by a third. | *Tossed you ridiculously far.* | No
 \\_ | Grip toss deals 15 impact damage. | *Dealt no damage.* | Yes
 \\_ | Desann and any unarmed normal reborn/cultist gains this ability. | *Normally only Kyle has grip toss.* | Yes
Mark1 | Can shoot with both guns simultaneously at any range. | *Shot one at a time depending on distance.* | No
 \\_ | Bowcaster damage scales with difficulty. | *Used a very high static value.* | No
 \\_ | Prefers to keep a distance to enemy. | *Used to run all the way up to your face.* | No
 \\_ | Shoots bowcaster bolts twice as often. | *The delay was ridiculously long.* | Yes
 \\_ | The arms are four times as durable. | *They were too easy to destroy.* | Yes
 \\_ | Shoots rockets instead of bowcaster bolts from a distance. | *Judging by the code, the bowcaster was actually meant to be a rocket launcher!* | Yes
 \\_ | Blaster bursts are fired twice as often and they are longer. | *Why not?* | Yes
Mine Monster | Runs right onto your skin. | *Didn't run close enough to attack.* | No

### Force Powers
General | Changes | Original | Requires GM difficulty
---|---|---|:---:
Level Advancement | Dark/Light Power advancement is limited to core force power level. | *No restriction.* | No

Saber | Changes | Original | Requires GM difficulty
---|---|---|:---:
Chance to deflect directly at enemy | Now 5%, 10% or 20% depending on Saber Defense level. | *Was 0%, 25% and 100%.* | Yes

Force Power | Level 1 | Level 2 | Level 3 | Original | Requires GM difficulty
:---:|---|---|---|---|:---:
Force Speed | Field of view distortion halved. | Same as level 1. | Same as level 2. | *Unnecessarily high values.* | No
 \\_ | Activating speed turns off the saber. Attacking ends speed. | Same as level 1. | Same as level 2. | *Could attack freely.* | Yes
Force Push | Area of effect cone halved. | Same as level 1. | Same as level 2. | *Not halved.* | Yes
Force Pull | No change. | Pull strength increased by 33%. | Pull strength reduced by 50%. | *Level 1/2 barely pulled a single target toward you while level 3 could send multiple targets to the orbit.* | No
 \\_ | Area of effect cone halved. | Same as level 1. | Same as level 2. | *Not halved.* | Yes
Force Sense | Spread Reduction: 20% | Spread Reduction: 40% | Spread Reduction: 60% | *Spread reduction was 0%, 100% and 100%.* | Yes
Force Absorb | Duration reduced to 5 seconds. | Same as level 1. | Same as level 2. | *Was 20 seconds.* | Yes
 \\_ | Does not absorb force points. | Same as level 1. | Same as level 2. | *Gave a portion of force points enemies use.* | Yes
Force Heal | For every 5hp healed max force points are reduced by 1 until a minimum of 20, lasting until the end of the level. Up to 50hp can be healed without penalty. | Same as level 1, but 100hp without penalty. | Same as level 2, but 150hp without penalty. | *No penalty.* | Yes
 \\_ | Heals 10hp per second without limit. | Same as level 1. | Same as level 2. | *Healed 5hp, 5hp and 20hp per second in 25hp bursts.* | Yes
Force Drain | Initiating drain reduces max hp every time by 5 until a minimum of 20hp. | Same as level 1. Ranged drain is disabled for the player. | Same as level 2. | *No penalty or disabling.* | Yes
 \\_ | Drain overcharge always enabled up to 100hp, regardless of max health. There is a 50% chance to lose 1hp overcharge every second. | Same as level 1, but chance is 33%. | Same as level 2, but chance is 25%. | *Only level 3 had overcharge up to 125% max hp, reduced at a rate of 1hp per second.* | Yes
Force Grip | Duration is 1 second. | No change. | No change. | *Level 1 duration was 5 seconds.* | Yes
