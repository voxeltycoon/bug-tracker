# Voxel Tycoon bug tracker

This tracker is intended to report bugs, or look for known issues.

* Please use [predefined template](https://github.com/voxeltycoon/bug-tracker/issues/new?assignees=&template=bug.md&title=) for new issues
* [Search](https://github.com/voxeltycoon/bug-tracker/issues?q=is%3Aissue) before posting in case such a bug was already repoted.

If you want to suggest a feature, or think some aspect should be improved or changed, we have a [suggestions tracker](https://github.com/voxeltycoon/suggestions/discussions) for that.

# Logs/saves locations

### Logs

* Windows: `%appdata%/../LocalLow/VoxelTycoon/VoxelTycoon/Player.log`
* macOS: `~/Library/Logs/VoxelTycoon/VoxelTycoon/Player.log`
* Linux: `~/.config/unity3d/VoxelTycoon/VoxelTycoon/Player.log`

> Please note that logs are cleared when the game starts, so logs should be sent just after the issue appeared, before restarting the game.

### Saves

* Windows: `%appdata%/../LocalLow/VoxelTycoon/VoxelTycoon/Saves`
* macOS: `~/Library/Application Support/VoxelTycoon/VoxelTycoon/Saves`
* Linux: `~/.config/unity3d/VoxelTycoon/VoxelTycoon/Saves`

# Troubleshooting

## Game doesn't start on macOS

Game doesn't load past `Loading...` screen on macOS.

### Solution

[Disable Gatekeeper](https://disable-gatekeeper.github.io/).

### 

## Audio not working

No audio in the game, `FMOD failed to initialize. This may be because your sound card is configured to give applications exclusive access` error appears in logs.

### Solution

Uninstall **Asus Sonic Studio**, **Asus Sonic Radar**, and **Hahimic** apps.

## The game has visual glitches

* The game crashes on start
* Visual glitches occure
* Mouse cursor is blinking
* Framerate too low even in simple scenes

### Solution

Please update your video drivers to the latest version.
* NVIDIA: https://www.nvidia.com/ru-ru/geforce/drivers/
* AMD: https://www.amd.com/en/support

