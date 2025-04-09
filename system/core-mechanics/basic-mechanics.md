---
tags:
  - mechanics
  - hub
  - database
aliases:
  - System 101
  - Basic Mechaincs
abstract: System 101, hub for main mechanics
status:
  - wip
  - untested
---
# The Basic Mechanics
## PC Creation
> Check [[pc-creation]]

> [!info] The style of characters
> This system is mainly intended for players to run human or abhuman characters in a cool, grimdark, science fantasy setting.
> 
> The PCs are not very powerful at the beginning and they don't progress to heroic levels easily. Nonetheless, they can be resourceful and three-dimensional from the get-go.
## Order of play
> Check [[order-of-play]]

The game is always played in rounds. A round contains the turn for each character.
- During [[Exploration]], a round takes 5 to 10 minutes.
- During [[combat]], a round takes seconds. PCs get an action, and might reposition themselves.
- During [[downtime]], a round can take several days to a week.

The order of play can be determined by counting successes on an arbitrary roll, depending on the situation:
- Initiative roll: During combat, a number determined by the enemies must be beaten for each PC to act before the enemies.
- Out of combat, usually there is no need to determine the specific order the players act in. It can be useful and tidy to go clockwise around the table.
## PC Stats
> Check [[pc-stats]]


## Rolls
> Check [[rolling-dice]]

A roll is needed when a PC performs an action where success is not granted, and the PC is under stress, the action is complicated or the action's progress, quality or duration is a factor to be considered.

> [!tip] Rolls in a nutshell
> - **Roll a d100 under or equal to a Stat** tosucceed.
> - **The Tier of Success ($)** is the **tens digit on a successful roll.**
> - **Check: pass or fail.** Tier ($) informs the quality of the success or the time it takes.
> - **Test:** checks until the **Tier ($) meets an arbitrary number** (Tier of the Test).
> - **Opposed Roll:** Rarely used. Useful for PvP situations.

> [!info] Some considerations
> - This system **uses 00 and not 100** as a possible outcome of a dice roll.
> - **96 to 99** are always **failures.**
> - **Failure leads to negative consequences** in any roll.
> - Success Tiers can inform **roleplaying and mechanical consequences.**
## Tags
Check [[tag-tier-system|Tags]]

```mermaid
flowchart TD

subgraph s1["Position &amp; Effect"]

n7["¿What does the player want to do?"]

n20["What does the player mean by success?"]

n1["¿What negative outcomes can a failure bring?"]

n2["¿What elements factor in the roll?"]

n11["Determines $ needed"]

n12["Determines consequences"]

n13["Determines modifiers"]

n21["Determines Stat"]

end

subgraph s3["Roll needed if:"]

n_comm1["Difficult action, under stress or in combat"]

n_comm2["Keeping track of time or progress is necesary"]

end

subgraph s4["No roll needed if:"]

n_comm3["Easy action, not under stress"]

n_comm4["Very easy action during combat"]

end

subgraph s2["Is roll needed?"]

s3

s4

end

subgraph s5["Determining modifiers"]

n14["Tag"]

n15["Factor is very relevant to the situation"]

n16["Add the specified $ after rolling"]

n17["Advantage or disadvantage"]

end

subgraph s6["The roll"]

n18(["Roll"])

n19["Equal or less than the stat?"]

n22["Equal or more $?"]

end

n18 --> n19

n15 --> n17

n14 --> n16

n_input>"Player declares action"] --> s2

n1 --> n12

n2 --> n13

s3 -- Roll needed --> s1

s4 -- No roll needed --> n9>"Action suceeds"]

n13 --> s5

n20 --> n11

n7 --> n21

n21 --> n19

n19 -- Yes --> n22

n11 --> n22

n22 -- Yes --> n23>"Action suceeds"]

n19 -- No --> n24>"Action fails"]

s5 --> n18

n_comm2 --> n11

n24 --> n27["Additional consequences might happen"]

n22 -- No --> n28["Check or Test?"]

n28 -- Test --> n25["Action is in proccess.<br>$ are accumulated.<br>Next turn, roll again"]

n28 -- Check --> n24

  

n11@{ shape: rect}

n12@{ shape: rect}

n13@{ shape: rect}

n15@{ shape: rect}

n16@{ shape: rect}

n17@{ shape: rect}

n19@{ shape: diam}

n22@{ shape: diam}

n28@{ shape: diam}

n25@{ shape: rect}
```