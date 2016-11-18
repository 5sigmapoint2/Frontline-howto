# FRONTLINE - A Arma 3 PvP mod based on PRA3

  - [Website](http://www.frontline.frl)
  - [Launcher](https://get.frontline.frl)
  - [Join Discord](http://discord.frontline.frl) Ask for `tester status`
  - [Issue tracker](http://issues.frontline.frl)

## Prerequisite
[TeamSpeak 3 Client](http://www.teamspeak.com/downloads)

## How to play
Open [TeamSpeak 3 Client](http://www.teamspeak.com/downloads)
Launch the game using the [Launcher](https://get.frontline.frl)

  - Run
  - Configure (`Options` button)
  - `Install` or `Update` button
  - `Play`

_After leaving the lobby, you'll be automatically assigned to a side_

`Join` a squad and select a role:

  - Rifleman: _cannon fodder_
  - Medic: _armed nurse_
  - Machine Gunner `MG`: _suppression guy__
  - Grenadier: _explosive stones thrower_
  - Engineer: _crazy guy with shotgun and explosives_
  - Anti Tank `AT`: _that other guy_
  - Marksman: _misses [Duck Hunt](https://en.wikipedia.org/wiki/Duck_Hunt)_

If you have commanding skills, then try `creating` a squad and become its Squad Leader (`SL`). As such you can:

  - Place `waypoints` to guide your squad members.
  - Place Rally Points(`RP`): lasts for 2 minutes and has a 2 minutes cooldown period. Available only to your __squad members__.
  - Deploy Forward Outposts (`FOs`): requires two other __team__ mates nearby. Available to the __whole team__
  - Coordinate with other `SL` over the radio (see [Communicate](#communicate))

### Select a spawn point
- Main base
- Uncontested flags ([Advance And Secure gamemode](#aasgamemode))
- Your squad Rally Point (`RP`). It only lasts for 2 minutes once deployed, make sure you time your respawn.
- Forward Outposts (`FO`)

### <a name="communicate"></a>Communicate:
  - TS `push-to-talk` to speak on direct (configure in TeamSpeak settings)
  - `CAPSLOCK` to speak to your squad
  - SL only: `CTRL + CAPSLOCK` to speak on the command channel with other SL

No radio configuration needed.

### Healing
  Access healing options using the __scroll wheel__
  Select `Field dressing` and hold `right mouse button` to bandage yourself. Apply several times if required (might need a medic to fully recover)

  Before dying, a player becomes `incapacitated`, with a bleeding timeout of 2 minutes. To revive an incap'd player:

    1. Apply __1 single bandage__ by selecting `Field dressing` and holding `left mouse button`
    2. Inject `Adrenaline`
    3. Apply `Field dressing`. Will require a medic to fully recover.
    4. If player is shacking, inject `Morphine`

  Drag an incapacitated team mate by pressing `E`
  Medics heal others __faster__ and are the only ones to make wounded players to __fully recover__ when applying `Field dressing`. If you are a medic, _stay alive!_,your squad needs you.

### <a name="aasgamemode"></a>Advance And Secure gamemode
  - Controlling more than half of the flags will result in ticket bleed for the opposing team.
    * Only your __current last flag__ can be taken by the enemy, defend it!
    * Only the next enemy or neutral flag to your last can be taken, take it!
  - To capture a flag you must be within the marked area and the player count difference must be of at least one towards your team.
    * First the game progressively `lowers` the enemy flag
    * Then the area becomes neutral
    * Finally it starts `raising` yours until the area is fully capped.
  - Ending the game:
    * The team that captures all the flags within the time wins the round
    * The team that reaches 0 tickets first loses the round.

### General tips
  - Play the objective
  - __Stick__ to your squad
  - Place marks on the map to let your team know of enemy locations:
    * Open the map
    * `Right click` and select your marker from the list.
  - Destroy enemy `FOs` you find by tactical guarding it within a 75m radius for 2 minutes (minimum 2 players). During that period, the enemy `FO` will be _blocked_. If you leave the area without destroying it, it will remain blocked for 2 minutes.
  - Rearm at `RP` and `FO` by looking at it and pressing `F`. Available again after 5 minutes.
