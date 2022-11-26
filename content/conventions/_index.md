+++
title = "Conventions (DRAFT)"
description = "DESU conventions for pickup groups"

sort_by = "title"

[extra]
direct_nav = true
+++
These **DRAFT** conventions represent the recommendations of DESU for pickup groups. For more information, read the [FAQ].

[FAQ]: faq

These are not rules. They are recommendations. Guidelines. Don't treat them like rules.
Conventions exist largely because, in many cases, making *any* decision is more important than making any particular decision.
Getting everyone on the same page gets everyone progging faster, clearing more often, and having a better time.
But the conventions are having the opposite effect if they're ruining anyone's fun.

The conventions _will_ change over time. Right now they will change a lot.

<!-- FIXME: Properly numbered headers? -->

## 0. The party leader is ultimately responsible for strategy

If there is discussion or disagreement about strats, the party leader should call the shots by default.
The party leader can also designate someone else as the shot-caller in their place.
Any time alternative strategies are discussed, the shot-caller should make the call on what strategy will be followed, and be clear about it.

Why?

1.  The party leader controls the PF advertisement and therefore what people see before they join the party.
    Party members will join the party expecting the PF advertisement to be followed.
2.  Without one person clearly making decisions about which strats to use, the party may be confused about whether a new suggestion was agreed to.
    If a party goes into a pull with different ideas of the strats, then there is a good chance the pull is doomed and a complete waste of time.
    Most of the time, it is more important that there be a clear decision than that the decision be "correct".

When the leader already knows what strats they want to use,

* The leader should put strategy info in the PF description. There isn't really enough room for a detailed list of strats, so the name of a comprehensive strategy is preferred (e.g. "DESU strats"). If modifying a strat from the standard, indicate that (e.g. "DESU strats w/ variations").
* The leader should be prepared to link to resources explaining the strats.
* The leader should have a macro with a summary of the strats.

It is completely okay for the leader to be learning or relearning the fight and not know it.
Nobody should be upset at someone learning the fight for the first time!

Likewise, it's completely okay if the leader doesn't want to be the shot-caller, especially when learning the fight. But they should designate someone else to do it.

## 1. The #1 marker goes in the north-east by default

{{ image(alt="A diagram of markers showing #1 in the top-right corner.", src="markers.png", caption="Marker diagram") }}

The #1 marker is not consistently placed in North American parties. Some groups place it in the north-west corner, others in the north-east. On occasion, we even see groups that put letters on the cardinals and numbers on the intercardinals.

#1 in the NE is the most common worldwide, and also makes the markers more consistent: both cardinal and intercardinal makers can be read clockwise from north, like an actual clock. With #1 in the northwest, you would have to read clockwise starting from the northwest.

## 2. Ask questions.

If you are unclear about part of the strat, ask about it.

If the party wipes and you don't understand why, ask what happened.

If you die and you don't understand why, ask what killed you.

If someone doesn't seem to be following the strat, ask if they understand it.

On average, questions will save more time than they waste.

_Corollary_: Don't get snippy at others for asking questions.

## 3. Claim positions in chat rather than the clock spot dance

Rather than placing a marker on the ground and the party positioning themselves around it, the party should claim positions in chat.
Specifically, tanks are `MT` (main tank) and `OT` (off-tank), healers are `H1` and `H2`, melee DPS are `M1` and `M2`, and ranged DPS are `R1` and `R2`.
If the party composition is different, players may have to overflow onto other roles' spots (most often a ranged DPS taking a melee spot).

The specific assignment of spread spots and light parties is often fight specific, designed to optimize for good melee uptime or particular mechanics.
If the party has a fight-specific macro, it will set out the spread spots and light parties, among other things.
If the party doesn't have a fight-specific macro, then the default positions are per the diagram (a macro for this diagram is available in the DESU server).

{{ image(alt="A macro readout showing spread spots and light parties. The spread spots, clockwise from north, are: main tank, ranged 2, healer 2, melee 2, off-tank, melee 1, healer 1, ranged 1. The first light party has the main tank and healer and DPS 1; the second has the off-tank and healer and DPS 2.", src="spots.png", caption="Diagram of default positions" }}

### 3a. Job priorities for positions

To speed things up, certain jobs have particular priorities for positions.
This is most significant for tanks, because of the mechanical differences between the tank jobs.
For other roles, the job priorities are mostly to speed up selection of positions, and there is ab
Note: someone wants a position other than the one suggested by these priorities, it is usually faster to just let them have that position than to argue about it.

For tanks, the main tank priority is WAR > DRK > GNB > PLD.
The tank whose job comes first in the list should be main tank.

For healers, the priority is WHM > AST > SCH > SGE.
The healer whose job comes first in the list should be H1.
Generally this means that the pure healer will be H1 and the barrier healer will be H2.

For DPS, the ranged physical DPS should typically be R1 and the caster should be R2.

## 4. Tank the boss in the center facing north

In fights where the tank can control the boss's position and/or facing, by default the boss should be lured to the middle of the arena and faced north.
After mechanics where the boss moves or turns, the tank should return it to that position if possible.
This applies even after a tank swap.

### 4a. `MT` and `OT` positions swap if needed to keep the boss facing north

The terms "main tank" and "off-tank" are ambiguous with tank swaps.
The main tank could be either the player who had the `MT` position at the start of the fight, or the player who currently has aggro.

In general, it is simpler to have the `MT` position stay with the player who had it at the start of the fight.
But this means that, after a tank swap, the `OT` will be at the north position in order to keep the boss facing north.
Tanking the boss north takes priority.

So the `MT` and `OT` may have to swap positions for a mechanic, such as spread spots, to keep the boss facing north.
If there is no need for a swap, as often happens with light party stacks, the tanks retain their original positions.

If there's any confusion, tanks should hash things out on a mechanic-by-mechanic basis.

## 5. Party split priotities: G1/TH go N/W; G2/DPS go S/E

Many mechanics require half the party to go in one direction, half togo the other direction.

For these mechanics, group 1 will go north or west towards the purple and red markers, and group 2 will go south or east towards the blue and yellow markers.
For mechanics where the split is relative to a mechanic, group 1 should go left and group 2 should go right.
For soaks, the default soak positions are east and west, i.e. markers B and D.

Group 1 is either light party 1 or the tanks and healers, depending on the split required by the mechanic.
Group 2 is either light party 2 or the DPSs.

## 6. Pairs default to colour pairs (DPS rotate counterclockwise)

Many mechanics require players to pair up one tank with one DPS.
By default, this should be colour pairs: A with 1, B with 2, etc.

For some mechanics, there are large targeted AoEs that require everyone to be well spread out while also paired up.
For these mechanics, the default is to meet on the cardinal points with the letter markers.

This is the same as saying that the default is that DPS rotate counterclockwise from their spread spots.
