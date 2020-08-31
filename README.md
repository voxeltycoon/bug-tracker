# Voxel Tycoon bug tracker

This tracker is intended to report bugs, or look for known issues.

* Please use [predefined template](https://github.com/voxeltycoon/bug-tracker/issues/new?assignees=&template=bug.md&title=) for new issues
* [Search](https://github.com/voxeltycoon/bug-tracker/issues?q=is%3Aissue) before posting in case such a bug was already repoted.

If you want to suggest a feature, or think some aspect should be improved or changed, we have a [suggestions tracker](https://github.com/voxeltycoon/suggestions/issues) for that.

# Logs/saves locations

### Logs

* Windows: `%appdata%/../LocalLow/VoxelTycoon/VoxelTycoon/Player.log`
* macOS: `~/Library/Logs/VoxelTycoon/VoxelTycoon/Player.log`
* Linux: `~/.config/unity3d/VoxelTycoon/VoxelTycoon/Player.log`

> Please note that logs are cleared when the game starts, so send us logs just after the issue appeared, before restarting the game.

### Saves

* Windows `%appdata%/../LocalLow/VoxelTycoon/VoxelTycoon/Saves`
* macOS `~/Library/Application Support/VoxelTycoon/VoxelTycoon/Saves`
* Linux `~/.config/unity3d/VoxelTycoon/VoxelTycoon/Saves`

# Troubleshooting

## Game doesn't start on macOS

### Description

Game doesn't load past `Loading assets...` screen on macOS.

### Solution

Run the game via [Itch App](//itch.io/app).

If your purchase is not linked to your account, or you doesn't remember your acccount, please go there for help: https://itch.io/docs/buying/already-bought.

### 

## Audio not working

### Description

No audio in the game, `FMOD failed to initialize. This may be because your sound card is configured to give applications exclusive access` error appears in logs.

### Solution

Unintall **Asus Sonic Studio**, **Asus Sonic Radar**, and **Hahimic** apps.
