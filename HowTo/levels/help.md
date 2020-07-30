# Level map characters

## Spawn

* 1...9 - enemy spawn points. 1-4 = Racoon, eagle, frog, goose.

* @ - player start point


## Walls/floors (can walk on, can't walk through)

* g - grass

* d - dirt

* f - stone floor

* c - concrete


## ladders (can walk on, can walk through)

* H - ideal ladder

* l - random ladder, with broken/rusty parts


## Active points

* x - level exit

* P - teleport (todo add 3 more kinds of teleports)

* ^ - spikes, kill immediately

* { } - limits for moving platform, each pair must be on one level


### Lever and doors

* & - lever, activates # and $

* # - door, opens on triggering &

* $ - door, closes on triggering &


### Arrow sign and face doors

* a - arrow sign, activates [ and ]

* [ - door, opens on triggering a (left direction door)

* ] - door, closes on triggering a (right direction door)


## Bonus objects

* * - gem

* % - cherry (health)

* m - mushroom (shield)


## Decorations, can walk through

* t/T - tree

* q - random fruit tree (qumquat)

* r - rock

* ! - candles

* b - bush


## AI control points

* < - set preferred direction for AI, also stops enemy
* > - set preferred direction for AI, also stops enemy


# Per level game settings (infoX.prop)

This file is optional.

## Rain

An ```rain=true``` setting enables rain effect on level.

## Darkness

An ```dark=true``` setting will turn on dark mode: just a small
part of level around the player is visible.

