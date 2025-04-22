---
display-name: Fumbles
tags:
  - mechanics
  - core
aliases:
  - Fumbles
  - Fumble
abstract: Fumbles, calculations and consequences
status:
  - untested
---
# Fumbles
> See [[tier-system]], [[rolling-dice]], [[tier-die]]

> [!important] Fumbles in a nutshell
> A **Fumble** is a roll where the **natural die result is 12**.

> [!tip] Natural Rolls, modified Stats
> When determining if the outcome of a roll is a Fumble, we **check the result of the dice without applying any modification** - modifications like extra Tiers of Success.
> 
> However, in the case of **Crits**, we check the **natural roll against the modified Stat** - that is, the base Stat plus any modifier to the roll.

## Effect of a Fumble
When a fumble is caused by a roll and **in addition to failing** the attempted action, the PC **suffers a consequence**.
### Calculating the Fumble
The specific consequences of the Fumble are determined in a table.

> [!important] Fumble calculation process:
> 1. Determine if the roll is done with **disadvantage**.
> 2. **Roll** the **[[luck|Luck]] [[tier-die|Tier Die]]**.
> 3. Subtract all **negative Tags**.
> 4. Consult the resulting number in the appropriate **Fumble table**.

The **[[luck|Luck]] [[tier-die|Tier Die]]** is the *Tier Die* associated to the *Luck* score of the PC.

**Counting all the negative Tags and Feats**:
- **Silver Tags and Feats** which did affect negatively the Stat for the roll: They get **subtracted again**, this time to the *Luck Tier Die*.
- **Bronze Tags and Feats** which affect negatively the *Tier of Success* (typically after the roll succeeds): They get **added or subtracted** to the *Luck Tier Die*.
- **Golden Tags and Feats** which affect with **Disadvantage** still get applied, this time to the *Luck Tier Die*.

### About Fumble Tables
 The **consequence of a Fumble** is determined by consulting the *Tier of Success* obtained on a **Fumble table**:
- Fumble tables **represent worst-case scenarios for specific situations**, areas, weapons, enemies...
- The **higher, the better**. The worst consequences on a fumble table are in the lower numbers.