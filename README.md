Join our [discord](https://discord.gg/stozu) or submit an issue (or a pull request fixing it!)

[![Stozu](https://i.imgur.com/P1m0hoi.png)](https://stozu.net/)

# How to clear ~90% of the space used by your server without any loss!

It's possible to think that it won't be possible to have big SMP maps, but that's not exactly true when you remember about chunks occupying your space that can be deleted without any data being lost.

> **What will happen when you do this process:**
- Your world size could decrease by up to 90%.
- No truly important chunk will be deleted.
- No player will notice any changes.
- A `~20GB` map can shrink up to `~2GB` of space.

## 1. Archive your world.
*Use the special actions to archive your world, it's recommended to clean up all dimensions.*

## 2. Download your world.
*By clicking on the three dots, you can download the file you created when you compressed the world.*

## 3. Download [MCASelector](https://github.com/Querz/mcaselector/releases).
*You'll probably want to use the .exe, **DON'T** download the .jar file.*

## 4. Open MCASelector, choose your `world` folder on it.
*After downloading the world to your PC, unarchive it and open your world folder in MCASelector by going to File > Open World.*

## 5. Open the selection filter.
*Go to Filter > Filter chunks and change the default `InhabitedTime` minutes settings to at least `2 minutes`, more than this could cause a destructive selection for such a small gain.*

## 6. Once the selection process is complete, the chunks selected for deletion will be orange on your screen.
*It's extremely likely that the chunks selected have never been used by anyone, and have only been made on player trips. Deleting these chunks will not cause any losses because if a player returns, the chunk will be the same as it always was.*

## 7. Delete the selected chunks.
*Go to Selection > Delete selected chunks.*

## 8. Use [SFTP](https://stozu.net/help/sftp.php) to transfer the clean world to your Stozu server again after deleting the original world!
