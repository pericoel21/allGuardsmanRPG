---
display-name: Defense Check
tags:
  - core
  - mechanics
  - combat
aliases:
  - Defense
  - Defense Check
  - Dodge
  - Parry
abstract: Defense roll 101, how to & special uses or cases
status:
  - untested
---
# The Defense Check
When a PC is attacked by an enemy, a **Defense Roll is required to determine if the attack lands or misses.** The defense roll is a **[[rolling-dice|Check]] against the Tier of the attack** (modified up or down due to the specific circumstances).

> [!important] Defending, step by step
> 1. **Describe what the PC does to defend**
> 	   This determines the [[pc-stats|Stat]] used to defend, and might also give penalties or bonuses.
> 2. **Roll defense**
> 	   Roll under the selected stat, applying tags and other modifiers (like [[cover]])
> 3. **Subtract $ from the damage**
>       If the outcome is a [[criticals|Crit]], the damage is avoided completely.
>       The damage comes from the weapon used. Subtract from it the $ generated in the [[defense-check]].
> 4. **Take the damage**
> 	   The damage that you didn't get to reduce now is subtracted from your [[hit-points]]. If you reach 0, it doesn't carry over.
> 5. **Take a Wound**
> 	   If your [[hit-points]] are 0 and you take more damage, take a [[pain-wounds|Wound]]. Tier = damage.

## Selecting a Stat
The player describes how the PC handles the defense. This allows for any Defense Roll to be done with any Physical or Mental [[pc-stats|Stat]], within limits.

> [!info] A good rule of thumb
> Typically, a Physical attack will be handled by a Physical stat, and viceversa for Mental attacks and stats. The only clear exception is using awareness to dodge.

> [!important] Freedom for the GM
> The next table is useful if a GM wants to really regulate how defending works in the system.
> 
> However, the idea is for players to be reasonable in their arguing. Therefore, a GM should feel free to impose penalties as they see fit when a player's idea is too out there.

| Stat             | Use                                             |
| ---------------- | ----------------------------------------------- |
| [[strength]]     | Used to parry or block.                         |
| [[dexterity]]    | Used to parry or dodge.                         |
| [[constitution]] | Resist poison, sleep and other similar effects. |
| [[awareness]]    | Dodging.                                        |
| [[intelligence]] | Defend from illusions or traps.                 |
| [[willpower]]    | Defend from corruption, chaos and temptation.   |
> [!note] Dodging bullets
> When the character "Dodges" a shot, they are actually getting out of the way of the shooter before the trigger is pulled.
### Effectiveness of a Defense for a given Weapon
The chosen approach for the defense roll might be very useful against some attacks, but wildly ineffective against others. This can be determined by the tags of the weapon, or by simple logic.

> [!example] Example of ineffective Defenses
> - A flamethrower can hardly be blocked or parried.
> - Any bullet is going to be almost impossible to parry, but some super-human monstrosities might actually be able to do so.
> - A PC might be a good fencer, but they will probably be crushed if they try to parry the axe of a great demon, which is more than two meters long.

> [!example] Example of very effective Defenses
> - If a tough PC is hit by a poison dart, they might just take the small pin prick and defend with their CON.
> - A paranoid PC's player could argue for using AWA instead of DEX to dodge the bullet of a hidden shooter. The PC saw the glint of metal just before the shooter squeezed the trigger.

> [!danger] Telegraphing ineffective approaches to Defense
> If a weapon is going to bypass a specific approach to Defense, a GM should always try to telegraph that fact. It could be useful to describe the weapon or the enemy in some detail, or even let the players know the specific Tag which makes the attacker special.

## Crits & Fumbles
If a PC rolls a **[[criticals|Crit]] on a Defense Check**, the **damage is avoided completely** and the incoming attack has **no consequences**.

**Fumbles** are calculated **as usual**.

## Penalties & bonuses
> See [[cover]], [[tags]], [[rolling-dice]]

A GM will impose **penalties** in situations where:
- **Defending is difficult** regardless of the selected stat.
- The selected **Stat doesn't make a lot of sense**.
- The selected **Stat is weak or ineffective against the Weapon**, as described early.

> [!example] Examples of situations imposing penalties
> - The PC is not aware of the enemy.
> - The PC is immobilized, grappled or paralyzed.
> - The action performed as a defense is ineffective.
> - The selected Stat is ineffective.

A defense roll can have **bonuses**:
- If the **PC is in cover** while defending from a **ranged attack**.
- If the PC has **Tags that give some sort of defense**.
- If the selected **Stat is strong or effective against the weapon**.

> [!example] Examples of situations granting Bonuses
> - The enemy attacks too far away.
> - The PC is behind cover.
> - The PC is hidden.
> - The enemy is trying to shoot while being assaulted by someone else.


### Inability to Defend actively
One special case for the Defense Check is a **situation where a PC cannot act**, therefore **not being able to defend themselves**.

> [!example] A PC might be unable to Defend because...
> They are paralyzed, asleep, ambushed, tied up in a melee, interposing themselves between an attacker and other character...

In this situation, the character still has **a chance to avoid most of the damage**:
- The **Defense Check is still done.**
- The selected Stat **must be [[constitution|CON]] against any physical attack.**
- The selected Stat **must be a mental Stat against a mental attack.**
-  **The PC will take at least 1 Tier of damage**, even if the incoming Tier of damage is reduced to 0.

## Taking damage
> See [[pain-wounds]]

The purpose of a Defense Check to calculate the amount of damage taken from the attack.

The damage taken is calculating by **subtracting the Tier of Success ($) from the Tier of Damage** of the attack. The Tier of Damage depends on the weapon used. 

If the incoming Damage is more than 0, the PC takes the damage, **subtracting it from the [[hit-points|Hit Points]]** total.

**If the Hit Points amount reaches 0, it doesn't carry over** for that attack. However, **when taking damage with Hit Points equal to 0**, the PC **takes a Wound**, instead. The **Tier of the wound equals the incoming Damage**. When taking a wound, the PC must roll on the appropriate Wound table.