---
superclass: Adept
health_die: d10
melee_dmg_per_stamina: d10
ranged_single-target_dmg_per_stamina: d8
aoe_dmg_per_stamina: d6
Stat: Vig
tags:
  - xrrpgclass
  - publicxrrpgclass
focus: Damage
aliases:
  - Warrior
complexity: Low
---
Health die (roll for more max health): d10
Melee dmg per stamina: d10 + Vig
Ranged single-target dmg per stamina: d8 + Vig
AOE dmg per stamina: d6 + Vig
Stat: Vigor

Complexity: Low

# General

At level 1 you pick an advanced power to have as an adept. You can use those powers whenever you want, but they cost stamina.

Each class has a dmg per stamina stat, which is how much damage you can do per how much stamina you spend.

**You always deal your stat worth of dmg per each stamina you spend on an attack.**

As you level up you go back and forth between levelling up your basic power and your advanced power, which is one you pick from the list below. If you decide to go beyond level 6 you may also pick extra advanced powers (though you will have to level them up from Tier 1 to Tier 3)!

| Class Level | Class Abilities                                 | Stamina Cost |
| ----------- | ----------------------------------------------- | ------------ |
| 0           | Basic Power Tier 0 (and stat bonus from chroma) | -            |
| 1           | Advanced Power Tier 1                           | 1            |
| 2           | Basic Power Tier 1                              | 1            |
| 3           | Advanced Power Tier 2                           | 2            |
| 4           | Basic Power Tier 2                              | 2            |
| 5           | Advanced Power Tier 3                           | 3            |
| 6           | Basic Power Tier 3                              | 3            |
|             |                                                 |              |
| 7           | Extra Advanced Power Tier 1                     | 1            |
| 8           | Extra Advanced Power Tier 2                     | 2            |
| 9           | Extra Advanced Power Tier 3                     | 3            |
| 10          | Another Advanced Power Tier 1                   | 1            |
| 11          | Another Advanced Power Tier 2                   | 2            |
| 12          | Another Advanced Power Tier 3                   | 3            |
| 13          | Another Advanced Power Tier 1                   | 1            |
| 14          | Another Advanced Power Tier 2                   | 2            |
| 15          | Another Advanced Power Tier 3                   | 3            |
| 16          | Another Advanced Power Tier 1                   | 1            |
| 17          | Another Advanced Power Tier 2                   | 2            |
| 18          | Another Advanced Power Tier 3                   | 3            |

# Powers

| Type         | Power             | Tier    | Effect                                                                                                                                                                                                                          | Mechanics                                                                                                                                                                                                                               |
| ------------ | ----------------- | ------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Basic        | Burst strength    | 0       | Strong and fast                                                                                                                                                                                                                 | See chromas in Basic Rules                                                                                                                                                                                                              |
|              |                   | 1       | As strong and fast as the strongest and fastest of the species<br>Can withstand their own strength but they're no harder to cut or hurt than anyone else<br>                                                                    | You may do a 2d8 + Vig dmg per stamina attack 3 times a day<br>You may double your Class Dice on a Vig check 3 times a day                                                                                                              |
|              |                   | 2       | Far stronger and faster than the strongest and fastest of the species                                                                                                                                                           | Your powerful attack upgrades to do 2d10 + Vig dmg per stamina<br>You may double your Class Dice on a Vig check 3 times a day                                                                                                           |
|              |                   | 3       | So strong they can move many, many times their weight, absolutely devastating blows<br>So fast you can't see them move                                                                                                          | Your powerful attack upgrades to do 2d12 + Vig dmg per stamina<br>You may double your Class Dice on a Vig check 3 times a day                                                                                                           |
| **Advanced** | **---**           | **---** | **---**                                                                                                                                                                                                                         | **---**                                                                                                                                                                                                                                 |
| Powerful     | Lightening        | 1       | 1/4 own weight -> 5 seconds                                                                                                                                                                                                     | Quadruple jump distance<br>You take half fall dmg                                                                                                                                                                                       |
|              |                   | 2       | 1/8 own weight -> 5 seconds<br>1/4 own weight -> 1 minute<br>Can touch someone and make them 1/4 their own weight for ~10 seconds                                                                                               | 1/8 weight gives x8 jump distance<br>Touch effect gives them disadvantage on resisting being thrown<br>You can't take fall dmg                                                                                                          |
|              |                   | 3       | Nullify their own weight -> 5 seconds<br>1/8 own weigh -> 1 minute<br>1/4 own weight -> unlimited<br>Can touch someone and 1/8 their weight for ~10 seconds<br>Can make everything in a 10 ft radius 1/4 weight for ~10 seconds | 1/8 touch lightening attack gives them double disadvantage on resisting being thrown                                                                                                                                                    |
|              | Heat control      | 1       | Temps up to 600 don't affect you<br>Can heat self up enough to 2nd degree burn with a 5-second touch<br>Heat aura of the hottest sauna (10 ft radius, decreases from there)                                                     | Take half dmg from heat<br>d10 / stam for single-target dmg<br>d8 / stam for ranged dmg (10 ft max)<br>d6 + Vig /stam for AOE (10 ft radius)                                                                                            |
|              |                   | 2       | Temps up to 3000 don't affect you (volcano)<br>Can heat self up enough to 3rd degree burn with a 5-second touch<br>Heat aura so hot people around get 1st degree burns (10 ft radius)                                           | Take quarter dmg from heat<br>d12 / stam for single-target dmg<br>d10 / stam for ranged dmg (20 ft max)<br>d8 + Vig /stam for AOE (20 ft radius)                                                                                        |
|              |                   | 3       | Temps up to 10,000 don't affect you (star)<br>Can heat self up enough to 4th degree burn with a 5-second touch<br>Heat aura so hot people around get 2nd degree burns (10 ft radius)                                            | Take no dmg from heat<br>2d8 / stam for single-target dmg<br>d12 / stam for ranged dmg (30 ft max)<br>d10 + Vig /stam for AOE (30 ft radius)<br>Your powerful attack goes up by a dice tier (so 2d10 becomes 2d12 and 2d12 becomes 3d8) |
|              | Decrease friction | 1       | Can up to halve the friction on any part of your body, enables you to slide around<br><br>                                                                                                                                      | Up Vig Defense DCs by the Stamina you use<br>When contested by a blue's increase friction power, contest and take the difference                                                                                                        |
|              |                   | 2       | Can get rid of the friction on any part of your body<br>Can touch an object or person and up to halve the friction on it for up to 1 min                                                                                        | Touch effect halves someone speed and gives them disadv. on their next attack                                                                                                                                                           |
|              |                   | 3       | Can get rid of the friction on anything around you in a 10 ft radius for up to 10 minutes. Can be an AOE or selective                                                                                                           | Speed to 0 and a minus to  attack checks equal to the stamina they spend for the next turn if they fail the contest                                                                                                                     |
|              | Propulsion        | 1       | Can launch yourself very fast<br>Can expel force from your body, stronger than lvl 1 basic red                                                                                                                                  | Can push someone up to 15 ft away<br>You can triple your speed                                                                                                                                                                          |
|              |                   | 2       | Can fly freely for up to 10 minutes<br>Can expel force from your body, stronger than lvl 2 basic red                                                                                                                            | Flying costs 2 stam. a minute and has to cool down for an hour before use again<br>Can push everyone around you up to 30 ft away (can make it a single target if desired)<br>Fly is triple your speed                                   |
|              |                   | 3       | Can fly forever<br>Can expel force from your body, stronger than lvl 3 basic red                                                                                                                                                | Fly now costs 1 stam. a minute<br>Push attack goes 50 ft, can make it a line, an AOE, or a force wall                                                                                                                                   |
|              | Explosions        | 1       | Can create explosions from their body up to 10 ft radius<br>Touch or centered on themselves                                                                                                                                     | d8 + Vig dmg/stamina                                                                                                                                                                                                                    |
|              |                   | 2       | Can now create explosions up to 25 ft radius                                                                                                                                                                                    | Inner 5 ft radius is d10 + Vig dmg/stamina, outer radius d8 + Vig/stamina                                                                                                                                                               |
|              |                   | 3       | 50 ft radius explosions, intense heat and force                                                                                                                                                                                 | Inner 5 ft radius is d12 dmg + vig./stam., medium radius (5 ft to 25 ft) d10 + Vig/stamina, outer radius is d8 + Vig/stamina                                                                                                            |
