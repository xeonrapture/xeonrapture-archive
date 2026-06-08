---
superclass: Magician
health_die: d6
melee_dmg_per_stamina:
ranged_single-target_dmg_per_stamina: d10
aoe_dmg_per_stamina: d8
Stat: Wit or End
tags:
  - xrrpgclass
  - publicxrrpgclass
focus: Damage, Utility, Effects
complexity: High
---
Health die (roll for more max health): d6
Single-target ranged dmg per stamina: d10 + Wit or End
AOE dmg per stamina: d8 + Wit or End
Stat: Wit or End

Complexity: High

# General

Possessors are very similar to physics but without a lot of the spells that inflict a condition. They get their power from harnessing the spirits of the mortal dead, and as such their magic is taboo and often corrupts the user. It's also more powerful than standard physic magic, and possessors have access to some spookier spells.

Really the only way to be a possessor without becoming evil is to develop relationships with the spirits you've chosen to control, or even better, make relationships with the spirits first and then make pacts with them so that they get something out of the deal.

# Spellcasting

You can use as much stamina as you'd like on any spell, but you must use at least as much as the spell's level. All status effect spells are a contest with your Wit vs whatever stat the opponent is using.

Max Concentration means how many spells you can have up at the same time and still cast other spells.

Stam means stamina spent on the spell. When dividing stamina, there's always a minimum of 1.

| Class Level | Max <br>Spell Tier | Total <br>Spells Known | Basic Range<br>(r) | Servant Health | Servant Stamina <br>Per Turn | Max <br>Concen-tration |
| ----------- | ------------------ | ---------------------- | ------------------ | -------------- | ---------------------------- | ---------------------- |
| 1           | I                  | 5                      | 20                 | Stam x 5       | Stam / 3                     | 2                      |
| 2           | I                  | 7                      | 20                 | Stam x 6       | Stam / 3                     | 2                      |
| 3           | II                 | 9                      | 30                 | Stam x 7       | Stam / 3                     | 3                      |
| 4           | II                 | 11                     | 30                 | Stam x 8       | Stam / 3                     | 3                      |
| 5           | III                | 13                     | 40                 | Stam x 9       | Stam / 3                     | 4                      |
| 6           | III                | 15                     | 50                 | Stam x 10      | Stam / 3                     | 4                      |
|             |                    |                        |                    |                |                              |                        |
| 7           | III                | 17                     | 50                 | Stam x 10      | Stam / 3                     | 5                      |
| 8           | III                | 19                     | 50                 | Stam x 10      | Stam / 3                     | 5                      |
| 9           | III                | All                    | 50                 | Stam x 10      | Stam / 3                     | 6                      |

Possessors can't use the same spell more than once in a row! Otherwise they tire out their thrall spirits. Also their possessor-specific spells they can only use a certain amount of times per day.

Servants (undead and constructs) have as much health and stamina as stated in the table above (their DDC is stated in the spell). Undead do a d8 + stat of dmg per stamina. Constructs do a dice lower of damage (d6) but have a Stam / 2 (min of one) plus to their Defense DC.

Pick up to 5 spells from this list. Dark spells are possessor-specific spells, and most can only be cast a certain amount of times per day.

# Spell List

| Spell                  | Tier | Con? | AOE? | Range | Times per Day | Effect                                                                                                                                                                                                                                                |
| ---------------------- | ---- | ---- | ---- | ----- | ------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Red Spells**         | ---  | ---  | ---  | ---   | ---           |                                                                                                                                                                                                                                                       |
| Heat Ray               | I    |      |      | r x 2 |               | Deals a d12 + stat of dmg per stamina, but you can't use any red spell next turn                                                                                                                                                                      |
| Scorching Bomb         | I    |      | X    | r     |               | No special effect, just does AOE<br>Can cast at Tier II, in which case it does a d12 + stat of dmg per stamina, but you can't use any red spell next turn                                                                                             |
| Flash Heat Trigger     | III  | X    | X    | r     |               | You specify the triggering conditions; the trigger can also be manual, and the range for manually triggering is r x 2. The spell expires after a day.                                                                                                 |
| Heat Wall              | II   | X    | X    | r     |               | Wall can be 40 ft long, can bend, one side of it exudes heat and damage in 10 ft radius<br>Deals a d12 + stat of dmg per stamina, but you can't use any red spell next turn                                                                           |
| Percussive Bomb        | II   |      | X    | r x 2 |               | Do dmg in a 15 ft radius, str or dex check or be pushed back to the edge of the radius                                                                                                                                                                |
| **Blue Spells**        | ---  | ---  | ---  | ---   | ---           |                                                                                                                                                                                                                                                       |
| Cold Ray               | I    |      |      | r x 2 |               | Inflicts the Frozen debuff, which means the next attack does another die of dmg per stamina spent                                                                                                                                                     |
| Freezing Bomb          | I    |      | X    | r     |               | No special effect, just does AOE<br>Can cast at Tier II, in which case it inflicts the Frozen debuff, which means the next attack does another die of dmg per stamina spent                                                                           |
| Flash Cold Trigger     | III  | X    | X    | r     |               | You specify the triggering conditions; the trigger can also be manual, and the range for manually triggering is r x 2. The spell expires after a day.<br>Inflicts Advanced Frozen debuff, next _two_ attacks do another dice of dmg per stamina spent |
| Cold Wall              | II   | X    | X    | r     |               | Wall can be 40 ft long, can bend, one side of it exudes cold and damage in 10 ft radius<br>Inflicts the Frozen debuff, which means the next attack does another die of dmg per stamina spent                                                          |
| **Gray Spells**        | ---  | ---  | ---  | ---   | ---           |                                                                                                                                                                                                                                                       |
| Create Darkness        | II   | X    | X    | r     |               |                                                                                                                                                                                                                                                       |
| Shade                  | III  | X    |      | r     |               | Make someone a stealthy shade, giving them a +10 on stealth checks                                                                                                                                                                                    |
| Xeon Sensing           | I    | X    |      | r x 2 |               | For 10 min you can see xenic spirits and other sources of xeon, including technology and magic items.                                                                                                                                                 |
| **Dark Spells**        | ---  | ---  | ---  | ---   | ---           |                                                                                                                                                                                                                                                       |
| Wither Flesh           | I    |      |      | r     |               | The spirits under your command suck the life force out of a creature, damaging them                                                                                                                                                                   |
| Corporealize Spirit    | I    | X    |      | r / 2 |               | Give a spirit physical form; not enough to do damage, they can speak simple sentences and interact with the physical world.<br>You can give them simple commands and they'll execute them. They last for up to an hour.                               |
| Take Spirit Appearance | II   |      |      | 0     | 3             | You can take the appearance of one of the spirits in your service for as many hours as stamina you spend on this spell.                                                                                                                               |
| Raise Hoard            | II   | X    |      | r / 2 | 3             | You raise a hoard of servants. The hoard as a whole has the health of a single strong servant. The hoard can't do damage but does have +1 x Stam used Endurance. It can break down doors and walls, restrain enemies, block spaces and doorways, etc. |
| Raise Dead             | I    | X    |      | r / 2 | 3             | A spirit under the control of a possessor inhabits the body of a deceased creature or person, or animates some non-living matter. Stats are +2 to 1 physical stat and a DDC of 13.                                                                    |
| Raise Dead II          | II   | X    |      | r / 2 | 3             | The servant is Special and imbued with one Lvl 1 Adept Basic or Advanced power. Stats are +3 to 1 stat and +1 to another, and a DDC of 15.                                                                                                            |
| Physical Thrall        | III  | X    |      | r / 2 | 3             | A spirit attempts to inhabit the body of a mortal. Do a Wit vs enemy Endurance and take over their body for 3 rounds on a failure. Every time they're hurt they can do a check to break out of it.                                                    |
| Haunting Figures       | II   | X    |      | r     | 3             | Your spirits torment a target, distracting them and damaging them. Do a Wit vs enemy Wit or Int and they have disadvantage to defend and attack for the next round if they fail.                                                                      |
| Necrotic Beam          | III  |      | X    | r     | 3             | Hits everyone on the line in a 60 ft range, does double dmg                                                                                                                                                                                           |
| Raise Dead III (Elite) | III  | X    |      | r / 2 | 2             | The servant is Elite and imbued with one Lvl 2 Adept Basic or Advanced power. Stats are +4 to 1 stat and +2 to another, and a DDC of 17.                                                                                                              |
