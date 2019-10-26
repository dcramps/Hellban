# Hellban

A hellbanned player can type and voice chat as much as they want, but nobody will ever see or hear it in game. Admins will see it in the server logs.

# Usage

Add player IDs to an array in `Mod.ini` with the following format:

```
[Hellban.Server]
PlayerIDs=xd83abe496ca401497b5adf4e412bf2c
PlayerIDs=yd83abe496ca401497b5adf4e412bf2c
PlayerIDs=zd83abe496ca401497b5adf4e412bf2c
```

Local clients can do the same in their `Mod.ini`:

```
[Hellban.Client]
PlayerIDs=xd83abe496ca401497b5adf4e412bf2c
PlayerIDs=yd83abe496ca401497b5adf4e412bf2c
PlayerIDs=zd83abe496ca401497b5adf4e412bf2c
```

A menu will be built soon to allow for mid-game hellbans by rcon admins, and allow players to mute people as they wish if playing a game mode with a non-standard HUD (Which as of now is everything but Blitz probably)

In the meantime, IDs of annoying players can be found at [UT4Stats.com](https://ut4stats.com/player_history/801ca4da156b49f4a302bc386a77666d/)  (the last part of the `player_history` URL is the ID you want. Remove the trailing /)
