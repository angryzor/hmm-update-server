# v0.0.25
* Added sound sync


# v0.0.24
* Reapplied v0.0.22 and added temporary workaround for issues with Super Sonic mod.


# v0.0.23
* Reverted v0.0.22.


# v0.0.22
* Added GOCVisualModel visibility synchronization.


# v0.0.21
* Fixed GameNetworkingSockets crashing on Steam Deck due to an older MSVC redistributable.


# v0.0.20
* Fixed a bug where effects would not be removed when a remote player object got destroyed.


# v0.0.19
* Fixed a crash when other player objects are deleted before the name tag UI is (happened when completing training room objective).


# v0.0.18
* Fixed tutorial room crash.
* Fixed Boss Rush (Master King trial) crash.
* Fixed name tags not reappearing after death or retry.


# v0.0.17
* Increased name tag render distance to 100 meters.
* Fixed a potential hang.
* Made it possible to toggle name tags with F11.


# v0.0.16
* Fixed packaging problem.


# v0.0.15
* Added nametags.


# v0.0.14
* Removed InstaGib.


# v0.0.13
* Fixed messages for unknown handles causing a crash.


# v0.0.12
* Added InstaGib.


# v0.0.11
* Localization.

## Shadow Generations
* Now shows join/leave messages.


# v0.0.10
* Made it not connect to localhost.


# v0.0.9
* Added quaternion extrapolation (smoother rotations).
* Fixed badly initialized transform rotation.
* Limited effect replication to max 50 units distance (this is a temporary solution).

## Sonic Frontiers
* Added support for Amy, Knuckles and Tails.


# v0.0.8
* Fixed a crash on stage exit after death due to respawned players not registering themselves.
* Fixed not all players being respawned on death.
* Fixed a potential but in practice unlikely bug when a player disconnects.


# v0.0.7
* Added effect replication.
* Fixed players not respawning on level rebuild.
* Fixed full snapshots not actually being full snapshots, granting less T-posing Sonics.


# v0.0.6
* Fixed wrong update server link in mod.ini for SXSG.


# v0.0.5
* Server now does a protocol version check. If your version doesn't match, you are kicked.
* Added support for multiple realms on the server. This makes it so different stages are actually different stages.
* Fixed join/leave announcements so they don't show every time a player dies.

## Sonic Frontiers
* Added support for the following game modes:
  * Battle Rush
  * Boss Rush
  * CyberStage Challenge
  * Fishing
  * Hacking
  * Master Trial
