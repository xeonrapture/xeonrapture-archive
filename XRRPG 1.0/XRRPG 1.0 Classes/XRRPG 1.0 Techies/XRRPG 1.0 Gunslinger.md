---
superclass: Techie
health_die: d6
melee_dmg_per_stamina:
ranged_single-target_dmg_per_stamina: d8-d12
aoe_dmg_per_stamina:
Stat: Wit or Int
tags:
  - xrrpgclass
  - publicxrrpgclass
focus: Damage, Utility
complexity: Med
---

Health die (roll for more max health): d6
Ranged single-target dmg per stamina: d8-d12 + Stat
Stat: Wit or Int

Complexity: Medium

# General

You gain a +2 bonus to all skill checks with technology (called the "tech bonus").

You are able to create any of the gadgets you use in this class as long as you can find scrap to make them (you have a +2 bonus to finding scrap plus your tech bonus). Otherwise you might have to buy parts, which will cost 30 Valdan credits per gadget (deduct the original price if you're modifying an existing gun).

Using a gadget always costs at least the amount of stamina of its Tier (unless they're performing the ability of a lower-level gadget). For example, some gadgets are upgraded versions of lower-level gadgets, and with those devices they can perform the abilities of their lower-level counterparts.

Every time you do an attack that does both dmg and a status effect, the enemy defends with their DDC and then rolls a save against the same attack roll to defend against the status effect.

If you decide to take another Technologist class at any point then you'll have to level it up from 1 to 6.

## Levelling Up

| Class Level | Gadget Max Tier | Stamina Cost | Details                                                               |
| ----------- | --------------- | ------------ | --------------------------------------------------------------------- |
| 1           | I               | 1            | You can make all the Tier I guns. Each gun can have 1 effect.         |
| 2           | I               | 1            | Each gun can have up to 2 effects.<br>Take another tech-related skill |
| 3           | II              | 2            | You can make all the Tier II guns.                                    |
| 4           | II              | 2            | You can hold up to 3 large weapons.<br>Your tech bonus goes up to +4  |
| 5           | III             | 3            | You can make all the Tier III guns.                                   |
| 6           | III             | 3            | Each gun can have up to 3 effects.<br>Your tech bonus goes up to +5   |

# Specific Info

You can now use Wit for aim attacks and can use Int for tech checks.

You can now make guns! Keep in mind you can only have up to 2 large weapons and 5 weapons total on your person at once.

Gunslingers can switch guns out without it costing them stamina!

Guns do half damage if you're out of their range. Rifle, musket, and sniper projectiles speed up after they leave the barrel, giving them both a minimum and a maximum range.

As you level up each gun can contain multiple effects, which you can switch between at will.

Keep in mind that Tier II and Tier III guns and gun effects require that you spend at least as much stamina as their Tier (e.g. Tier II guns and gun effects require at least 2 stamina, Tier III guns and gun effects require at least 3 stamina).

## Gun Details

| Gun         | Gun Size | Tier | Dmg | Min Range | Max Range | Details                                                                                                  |
| ----------- | -------- | ---- | --- | --------- | --------- | -------------------------------------------------------------------------------------------------------- |
| Pistol      | Small    | I    | d8  | -         | 150 ft    | Takes 1 less stamina (min of 1) when used with non-damage effects. Heat gun does a die tier less of dmg. |
| Shotgun     | Large    | I    | d10 | -         | 100 ft    | Can hit up to two creatures if they're within 5 ft of one another.                                       |
| Rifle       | Large    | I    | d10 | 30 ft     | 2,500 ft  |                                                                                                          |
| Revolver    | Small    | II   | d10 | -         | 150 ft    |                                                                                                          |
| Musket      | Large    | II   | 2d8 | 15 ft     | 1,000 ft  | Can only do one attack per turn.                                                                         |
| Machine Gun | Large    | III  | d12 | -         | 2,500 ft  | Each attack can hit up to three targets.                                                                 |
| Sniper      | Large    | III  | 2d8 | 100 ft    | 5,000 ft  |                                                                                                          |

## Dice Damage Tier

![[Damage Dice Tier]]

## Gun Effects

| Gun Type              | Tier | Description                                                                                                                                                                                                                                                                                |
| --------------------- | ---- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| Cold Gun              | I    | Inflicts the Frozen debuff, which means the next attack does another die of dmg per stamina spent. Does a die tier less of damage.                                                                                                                                                         |
| Heat Gun              | I    | Deals a die tier more of dmg per stamina, but it has to cool down next turn (e.g. a rifle goes from d10 of dmg to d12 of dmg per stam)                                                                                                                                                     |
| Onyx Gun              | I    | Normal percussive gun, does physical damage                                                                                                                                                                                                                                                |
| Healing Gun           | I    | Heals a d10 per stamina spent up to 5 times a day (one target).                                                                                                                                                                                                                            |
| Hacking Gun           | I    | Shoots a small device that hooks into the target, enabling hacking with a +2 bonus                                                                                                                                                                                                         |
| Grapple Gun           | I    | Can use to either move yourself to any place within 30 ft of you or do a contested check vs an enemy to move them to you, 30 ft range.                                                                                                                                                     |
|                       |      |                                                                                                                                                                                                                                                                                            |
| Advanced Cold Gun     | II   | Inflicts Advanced Frozen debuff, next _two_ attacks do another dice of dmg per stamina spent. Does a die tier less of damage.                                                                                                                                                              |
| Advanced Heat Gun     | II   | Deals *two* die tiers more of dmg per stamina, but it has to cool down next turn (e.g. a rifle goes from d10 of dmg to 2d8 of dmg per stam)                                                                                                                                                |
| Obsidian Gun          | II   | Target gets a -2 to physical Defense DCs this turn. This effect can stack up to -6.                                                                                                                                                                                                        |
| Stamina Gun           | II   | The target generates 1 more stamina the next 3 turns.                                                                                                                                                                                                                                      |
| Recon Gun             | II   | Gun shoots tiny cameras, mics, or xeon sensors that stick to the target. These are easily destroyed, but blend into their environments. Can also shoot trackers. Can have 5 out max at one time, and when you shoot one beyond the 5 cap it permanently deactivates one of the original 5. |
| Tranq Dart Gun        | II   | Target gets a -2 to attack checks next turn.                                                                                                                                                                                                                                               |
|                       |      |                                                                                                                                                                                                                                                                                            |
| Advanced Healing Gun  | III  | Can heal 2d10 HP per stamina up to 5 times a day (one target)                                                                                                                                                                                                                              |
| Force Gun             | III  | On hit forces the target to move up to 15 ft in any direction.                                                                                                                                                                                                                             |
| Advanced Stamina Gun  | III  | The target generates 2 more stamina the next 3 turns.                                                                                                                                                                                                                                      |
| Gravity Nullifier Gun | III  | Target's gravity is nullified for the next three turns.                                                                                                                                                                                                                                    |
| Uranium Gun           | III  | Nasty unstable purple beam, can only have one at a time<br>Does 3d10 + stat / stam of dmg but can only be used 3 times a day<br>Can only be a sniper rifle<br>(if you use it a 4th time it blows up, dealing you and everyone around you in a 50 ft radius 10d10 dmg)                      |
