---
superclass: Magician
health_die: d6
melee_dmg_per_stamina:
ranged_single-target_dmg_per_stamina: d8
aoe_dmg_per_stamina: d6
Stat: Wit
tags:
  - xrrpgclass
  - publicxrrpgclass
focus: Damage, Utility
complexity: High
---
Health die (roll for more max health): d6
Ranged dmg per stamina: d8 + Wit
AOE dmg per stamina: d6 + Wit
Stat: Wit

Complexity: High

# General

Physics have learned the xenic language and as a result can tell the xeon what to do!

You can use as much stamina as you'd like on any spell, but **you must use at least as much stamina as the spell's tier**. All status effect spells are a contest with your wit vs whatever stat the opponent is using.

Physics have focuses that they cast their magic through! It can be pretty much anything though, from a wand to a staff to an orb.

Max Concentration means how many spells you can have up at the same time and still cast other spells.

Any time you level up you can replace 1 of your known spells with a new one.

For any of these spellcasting styles, if the amount refunded is the same as the amount of stamina used on the spell then this effect can't be used again this turn.

For range, take the Basic Range below and plug it into "r" in the table.
For the AOE radius, take the half of Basic Range (unless stated otherwise).
0 range is a touch spell.

To start, take 6 Tier I spells from the list below.

# Spellcasting Styles

| Class Level | Max Spell Tier | Total Spells Known | Basic Range (r) | Max Concentration |
| ----------- | -------------- | ------------------ | --------------- | ----------------- |
| 1           | I              | 6                  | 20              | 1                 |
| 2           | I              | 9                  | 20              | 1                 |
| 3           | II             | 12                 | 30              | 2                 |
| 4           | II             | 15                 | 30              | 2                 |
| 5           | III            | 18                 | 40              | 3                 |
| 6           | III            | 21                 | 50              | 3                 |
|             |                |                    |                 |                   |
| 7           | III            | 24                 | 50              | 4                 |
| 8           | III            | 27                 | 50              | 4                 |
| 9           | III            | All                | 50              | 5                 |

Pick a spellcasting style:

- Chroma Generalist: refund a third of the stamina used on a spell (min of 1) if the previously-used spell was of the opposite color (red and blue are opposites, green and gray are opposites)
- Chroma Specialist: refund a third of the stamina used on a spell (min of 1) if the previously-used spell was of the same color
- AOE Caster: refund a third of the stamina used on a spell (min of 1) if the spell is an AOE
- Single-Target Caster: refund a third of the stamina used on a spell (min of 1) if the spell has one target

# Spell List

| Spell              | Tier | Con? | AOE? | Range            | Effect                                                                                                                                                                                                                                                         |
| ------------------ | ---- | ---- | ---- | ---------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Red Spells**     | ---  | ---  | ---  | ---              | ---                                                                                                                                                                                                                                                            |
| Heat Ray           | I    |      |      | r x 2            | Deals a d12 + stat of dmg per stamina, but you can't use any red spell next turn                                                                                                                                                                               |
| Scorch Ray         | II   |      |      | r x 2            | Deals a 2d8 + stat of dmg per stamina, but you can't use any red spell next turn                                                                                                                                                                               |
| Scorching Bomb     | I    |      | X    | r                | No special effect, just does AOE<br>Can cast at Tier II, in which case it does a d12 + stat of dmg per stamina, but you can't use any red spell next turn                                                                                                      |
| Flash Heat Trigger | III  | X    | X    | r                | You specify the triggering conditions; the trigger can also be manual, and the range for manually triggering is r x 2. The spell expires after a day.<br>Deals a 2d8 + stat of dmg per stamina, but you can't use any red spell next turn                      |
| High Jump          | II   | X    |      | 0                | Can jump up to 30 ft                                                                                                                                                                                                                                           |
| Lighten Target     | I    | X    |      | r                | Nullify all fall damage, double all throw distance<br>Half weight of any object                                                                                                                                                                                |
| Lighten Group      | II   | X    | X    | r                | Make them light, pushes are extremely effective                                                                                                                                                                                                                |
| Heat Wall          | III  | X    | X    | r                | Wall can be 40 ft long, can bend, one side of it exudes heat and damage in 10 ft radius<br>Deals a d12 + stat of dmg per stamina, but you can't use any red spell next turn                                                                                    |
| Percussive Bomb    | II   |      | X    | r x 2            | Do dmg in a 15 ft radius, str or dex check or be pushed back to the edge of the radius                                                                                                                                                                         |
| Force Wave         | III  |      | X    | r                | Move everything in a 30 ft cube one direction                                                                                                                                                                                                                  |
| Slippery Target    | II   | X    |      | r                | Wit + Class Dice + Stamina Spent vs enemy stat. Slippery target, making them unable to move and giving them a minus (Stamina Spent) to attack and defend rolls. They can do a check each turn to break out (new wit contest)                                   |
| Slippery Group     | III  | X    | X    | r                | Wit + Class Dice vs enemy stat. Slippery group, making them unable to move and giving them a minus (Stamina Spent) to attack and defend rolls. They can do a check each turn to break out (new wit contest)                                                    |
| **Blue Spells**    | ---  | ---  | ---  | ---              | ---                                                                                                                                                                                                                                                            |
| Cold Ray           | I    |      |      | r x 2            | Inflicts the Frozen debuff, which means the next attack does another die of dmg per stamina spent                                                                                                                                                              |
| Freeze Ray         | II   |      |      | r x 2            | Inflicts Advanced Frozen debuff, next _two_ attacks do another dice of dmg per stamina spent                                                                                                                                                                   |
| Freezing Bomb      | I    |      | X    | r                | No special effect, just does AOE<br>Can cast at Tier II, in which case it inflicts the Frozen debuff, which means the next attack does another die of dmg per stamina spent                                                                                    |
| Flash Cold Trigger | III  | X    | X    | r                | You specify the triggering conditions; the trigger can also be manual, and the range for manually triggering is r x 2. The spell expires after a day.<br>Inflicts Advanced Frozen debuff, next _two_ attacks do another dice of dmg per stamina spent          |
| Force Field        | II   | X    | X    | r / 2            | Effective against xenic attacks, so everything but obsidian and onyx and physical (roll Wit + Class Dice + Stamina Spent for defend rolls, if they beat it the field breaks)                                                                                   |
| Leaden Foe         | II   | X    |      | r                | Triple all fall damage, they're locked in place if they fail the check. They take Dmg X (Stamina Spent) each turn, and can do a new check each turn to break out (new wit contest).                                                                            |
| Cold Wall          | III  | X    | X    | r                | Wall can be 40 ft long, can bend, one side of it exudes cold and damage in 10 ft radius<br>Inflicts the Frozen debuff, which means the next attack does another die of dmg per stamina spent                                                                   |
| Grippy Target      | I    | X    |      | r                | On person, climbing checks are done with advantage<br>On small object, can stick it to surfaces                                                                                                                                                                |
| Grippy Group       | III  | X    | X    | r                | Climbing checks are done with advantage<br>Can inflict on a group of foes, if they fail a contest they are stuck to the ground and can't move. They can do a new contest each turn to break out.                                                               |
| **Green Spells**   | ---  | ---  | ---  | ---              | ---                                                                                                                                                                                                                                                            |
| Sense Up           | I    | X    |      | r / 2            | Advantage on Intuition sense checks for 10 min. You can also nullify any of the senses of a willing person!<br>At Tier II you can spend 2 stamina to do a contest to nullify one sense of an enemy.                                                            |
| Electromag. Seeing | II   | X    |      | r / 2            | See the whole electromagnetic spectrum for 10 min (includes heat signatures, xrays, radio waves)                                                                                                                                                               |
| Atmosphere         | II   | X    | X    | r                | Create a breathable atmosphere for 10 min                                                                                                                                                                                                                      |
| Healing            | I    |      |      | r                | Can heal 1d8 x (Stamina Spent)                                                                                                                                                                                                                                 |
| Life Force         | III  | X    | X    | radius<br>=r / 2 | Allies around you gain a third of the Stamina you spend each round. Lasts three rounds.                                                                                                                                                                        |
| **Gray Spells**    | ---  | ---  | ---  | ---              | ---                                                                                                                                                                                                                                                            |
| Send Thoughts      | I    |      |      | r                | Can send thoughts to others and they can send a little thought back                                                                                                                                                                                            |
| Create Darkness    | II   | X    | X    | r                | No one can see in the range unless they have heat vision or xeon sensing                                                                                                                                                                                       |
| Shade              | III  | X    |      | 0                | Make someone a stealthy shade, gives them +6 to stealth checks                                                                                                                                                                                                 |
| Xeon Sensing       | I    | X    |      | r x 2            | For 10 min you can see xenic spirits and other sources of xeon, including technology and magic items.                                                                                                                                                          |
| Binding            | II   | X    |      | r                | A white, glowing tether of xeon connects two objects, or something to you. You can manipulate the length and direction of the connection. Power of connection increases with stamina spent. If on a person, Wit + (Stamina Spent) vs enemy stat. Get creative! |
| Onyx Shielding     | II   | X    | X    | r / 2            | Only good against onyx and obsidian and physical, can be a flat wall, no bubbles (roll Wit + Stamina Spent for defend rolls, if they beat it the field breaks)                                                                                                 |
| **Clear Spells**   | ---  | ---  | ---  | ---              | For clear spells, the stamina cost of the original spell is replaced with the cost of the clear spell. Doesn't break Chroma Specialist streaks.                                                                                                                |
| Triggered Spell    | III  | X    |      | r                | Takes any existing spell and attaches it to a trigger. You specify the triggering conditions; the trigger can also be manual, and the range for manually triggering is r x 2. The spell expires after a day.                                                   |
| Ranged Spell       | III  |      |      | r x 4            | Casts any existing spell with range r x 4.                                                                                                                                                                                                                     |
| Amplified Spell    | III  |      |      | -                | Casts any existing spell with 50% more damage (rounded down).                                                                                                                                                                                                  |
| Empowered Spell    | III  |      |      | -                | Casts any existing spell, but the enemy rolls with disadvantage against your spell check.                                                                                                                                                                      |
