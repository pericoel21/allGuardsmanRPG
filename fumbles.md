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
A fumble is a special case where the **Tier of Success is calculated even when the result is a failure**.
The calculation is done by **adding or subtracting all Tags and Feats to a Luck Tier Die Roll**.
- The **[[luck|Luck]] [[tier-die|Tier Die]]** is the *Tier Di*e associated to the *Luck* score of the PC.
- Regarding **Tags and Feats**:
	- **Silver Tags and Feats** which did affect the Stat for the roll: They get **added or subtracted again**, this time to the *Luck Tier Die*.
	- **Bronze Tags and Feats** which affect the *Tier of Success* (typically after the roll succeeds): They get **added or subtracted** to the *Luck Tier Die*.
	- **Golden Tags and Feats** affect with **Disadvantage on the *Luck Tier Die***. If the *Golden Tag* gave **Advantage, it doesn't factor** on a Fumble.

The resulting *Tier of Success* is consulted on a Fumble table.
### About Fumble Tables
 The **consequence of a Fumble** is determined by consulting the *Tier of Success* obtained on a **Fumble table**:
- Fumble tables **represent worst-case scenarios for specific situations**, areas, weapons, enemies...
- The **higher, the better**. The worst consequences on a fumble table are in the lower numbers.