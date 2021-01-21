# brutal_randoom
Brutal DOOM with RANDOM MAPS -- infinitely replayability!

## What
Brutal Randoom (Random-doom) is a packed bundle consists of GZDoom 4.5 and a random map generator Oblige 7.70, with bat scripts that makes it easy to generate new games and to continue play with existing maps.

## Usage
Use `GenerateNewGame.bat` to create a new game. It generates a new map `game.wad` (in the same directory) as a full game (30 levels). If there is already a `game.wad`, it will rename it to `game.old`. If `game.old` exists, it will delete it. This is because save files are only compatible with the corresponding maps, so if you accidentally clicked on generate new game, this gives you a way to restore the previous map and continue to play with previous saves.

Use `RunGameWad.bat` to run GZDoom with existing `game.wad`. If it doesn't exist, it will run the original wad (freedoom 2).

## Control / Keybindings
Use the config UI to checkout all the configs, but here are the most important "advanced" controls:
* Quick melee: Q
* Reload: R
* Open/close door: E (you'll find close action more useful)
* Special weapon action: F (for some weapon it's dual wield, for some weapon it's different mode, some require abtaining advanced weapon first, etc.)
* Flashlight: B
* Gerenade: middle mouse button
* Switch gerenade: Z
* Run: shift
* Middle finger: H

## I'm invincible!
That's a mod that make health to regenerate to 100 is installed. I found brutal doom much more enjoyable this way, where I don't have to find and decide when to use a health pack. If this bothers you, think of it more like a COD style gameplay. Of course you should choose higher difficulty to give yourself more chanllenge, then you'll find that being able to survive hordes of enemies is really fun -- then your health will be back to 100 to prepare you for the next round.

If you are REALLY bothered by this, tweak mods from the `mods` folder.

## License
This pack consists of GZDoom, Oblige, Freedom, and a few mods. All of them are free to download and fine for personal use. But if you want to use any of them commercially, check their sites for corresponding licenses.
