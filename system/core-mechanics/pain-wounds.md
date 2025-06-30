---
display-name: Pain & Wounds
tags:
  - character
  - mechanics
  - core
  - combat
aliases:
  - Wounds
  - Wound
  - Health
  - HP
  - Pain
  - Pain & Wounds
abstract: Pain, Wounds and Recovery. All things HP
status:
  - todo
---
# Pain & Wounds
> See [[pc-stats]], [[npcs]], [[recovery-scars]], [[pc-progression]]

## Pain & Pain Threshold
The Pain stat tracks **how much damage** can a character handle **before they take a Wound**.
- The pain stat **starts at 0 and goes up**.
- The Wound is taken when the Pain exceeds the Pain Threshold.
- When **taking a Wound**:
	- The pain **resets to 0**.
	- The **excess damage** (if any) **does not carry over**.

### Pain Threshold for PCs
For PCs, the Pain Stat maximum is calculated by adding up:
- The [[luck|Luck]] Stat Tier.
- The [[willpower|Willpower]] Stat Tier.
- Any [[armor]] Tiers given by items or [[tag-list|Feats]].

If a PC lowers any of those Stats during play, the Pain Maximum goes down accordingly.

## Wounds
A PC starts with 0 Wounds, and their maximum equals their **Constitution Stat Tier, minimum of 1**.

When the Pain Threshold is exceeded, the PC takes a wound. The damage dealt by the attack factors in the calculation of the Wound.

### Rolling in the Wound Table
The Wound taken is selected from an appropriate Wound table.

> [!important] Calculating the Wound table result:
> 1. Roll the [[luck|Luck Stat]] [[tier-die|Tier Die]].
> 2. Subtract the damage taken by the attack.
> 3. Consult the table entry of the resulting number.

### Effect of the Wound
Wounds have several effects on a PC:
- **PC death**: If a PC has a **number of Wounds equal to their maximum**, and they suffer another one, the PC **dies**.
- **Stat damage**: Some wounds reduce a Stat.
	- Part or all of that reduction is a **"ransom"**.
	- For some Tags, part of the reduction is permanent.
- **Negative Tags**: Some wounds function as **negative Tags of any [[tag-classes|Class]]**. These can be temporary or permanent.

> [!tip] GM tip:
> I don't create wounds that affect [[constitution|CON]] or [[willpower|WIL]] on purpose, so it doesn't get messy in a combat, having to recalculate the stat.

### Healing Wounds
> See [[recovery-scars]]

Some wounds heal by themselves
By healing them, many or all of the stat Tiers go back to being available. Also you cannot upgrade the stat because you have to first spend XP healing.



