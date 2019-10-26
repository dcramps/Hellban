# Hellban

A hellbanned player can type and voice chat as much as they want, but nobody will ever see or hear it in game. Admins will see it in the server logs.

# Usage

Add player IDs to an array in `Mod.ini` with the following format:

```
[Hellban.Server]
PlayerIDs=fd83abe496ca401497b5adf4e412bf2c
```

Local clients can do the same in their `Mod.ini`:

```
[Hellban.Client]
PlayerIDs=fd83abe496ca401497b5adf4e412bf2c
```

A menu will be built soon to allow for mid-game hellbans by rcon admins, and allow players to mute people as they wish if playing a game mode with a non-standard HUD (Which as of now is everything but Blitz probably)
