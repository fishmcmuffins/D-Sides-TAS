# Monika's D-Sides TAS Project

This repository contains TAS files for the mod [Monika's D-Sides](https://gamebanana.com/mods/150759) for the video game [Celeste](celestegame.com).

## About

TAS files contain lists of inputs for a program (e.g. libTAS) or physical device (e.g. TASBot) to perform. TAS files for Celeste in particular are written in a custom format for use with the mod [CelesteTAS](https://gamebanana.com/tools/6715), which itself is designed for use with the modloader [Everest](https://everestapi.github.io/).

All TASes in this repository have the goal of completing certain objectives on a new file in the least in-game time possible (without using timer overflow) without using cheat mode (unless stated otherwise below) and without using any variants.

 - Main Pack (root + `9D` directory): Latest versions of each D-Side, Dark Side, and Final Goodbye, all on the mod's current patch (v4.81 as of 2025 Aug 7).
   - `100%`: Beat all Main Pack levels and get all of their collectibles except deathless berries.
   - `All D-Sides`: Beat all D-Sides through Epilogue D.
   - `All Dark-Sides`: Enable cheat mode, then beat all Dark Sides from their Start checkpoints.
   - `All Levels`: Beat all main pack levels.
   - `Beat Epilogue`: Beat Epilogue D.
   - `Darkny%`: Beat all Dark Sides.
   - `Dny%`: Unlock 8D.
   - `Drue Ending`: Beat Post-Epilogue.
   - `Max%`: Beat all Main Pack levels and get all of their collectibles, including deathless berries.
 - `Museum` (`Museum` directory): Unused content and old versions of Main Pack levels.
   - `100%`: Beat all Museum and Bonus levels and get all of their collectibles except deathless berries. Only use cheat mode after beating all levels accessible without it.
   - `All Levels`: Beat all Museum and Bonus levels. Only use cheat mode after beating all levels accessible without it.
   - `All Main Levels`: Beat the A-Side of each Museum chapter.
   - `Max%`: Beat all Museum and Bonus levels and get all of their collectibles, including deathless berries. Only use cheat mode after beating all levels accessible without it.
 - `All Packs` (`Museum` directory):
   - `100%`: Main Pack `100%` and Museum `100%`
   - `All Levels`: Main Pack `All Levels` and Museum `All Levels`
   - `All Main Levels`: Main Pack `All D-Sides`, `9D` (Final Goodbye), and Museum `All Main Levels`
   - `Max%`: Main Pack `Max%` and Museum `Max%`
 - `BerryHunt2025`: Copies of all of the above for v4.77 of the mod, which acted as a limited-time event with extra content. See [the BerryHunt2025 README](https://github.com/fishmcmuffins/D-Sides-TAS/blob/main/BerryHunt2025/README.md) for details.

## Viewing

TASes from this repository can be viewed either by watching published recordings or by running TAS files on your PC using [CelesteTAS](https://gamebanana.com/tools/6715).

### Recordings

  - [Beat Epilogue showcase](https://www.youtu.be/VxJJegTyc-w)
  - [Final Goodbye Max% showcase](https://www.youtu.be/npSNabouT_4)
  - recordings of Dark Sides: [1Dark](https://www.youtu.be/rKMGs8QMLB0), [4Dark](https://youtu.be/dEut86kWKAw), [5Dark](https://www.youtu.be/Ya6lxjrGoCI), [6Dark](https://www.youtu.be/SUo2iC8UY3o), [7Dark](https://youtu.be/cHdfAiX2-nw)
  - recordings of museum levels: [Old 8Ds Mashup](https://youtu.be/6_0hd2D_KSw)

### Running TAS files

To run a TAS file on your PC, follow these steps:
 1. Download the dependencies listed below.
 2. Download a copy of this repository. The green Code button above the timestamp column opens a menu with download options. Or, since CelesteTAS v3.46.2, in Studio you can use `File -> Clone Git Repository...` with URL `https://github.com/fishmcmuffins/D-Sides-TAS`.
 3. Select a TAS file. Either open it in Studio or copy its contents into `Celeste.tas` in your Celeste directory.
 4. Press the "Start/Stop TAS" bind in Celeste.

Dependencies for this project (last checked 2025 Aug 7):
 - the game [Celeste](celestegame.com)
 - the modloader [Everest](https://everestapi.github.io/), v5617 or later
 - the mod [CelesteTAS](https://gamebanana.com/tools/6715), v3.46.2 or later
 - the mod [Monika's D-Sides](https://gamebanana.com/mods/150759), v4.80 or later, and its required dependencies
 - for the Final Goodbye Platinum, the mod [Platinum Strawberry Asset Pack](https://gamebanana.com/mods/442093), any version

## Contributing

Currently, all contributions to this repository have come from the [D-Sides TASing Discord server](https://discord.gg/pqcRSnQbzg). We strongly recommend sending drafts and improvements there, as the server uses the [CelesteTAS Improvements Tracker](https://github.com/Kataiser/CelesteTAS-Improvements-Tracker) Discord bot which catches lots of oversights and formatting errors and automatically manages `contributors.txt`. Since the TAS files in this repository make heavy use of `read` commands, we also recommend using software such as [GitHub Desktop](https://desktop.github.com/) to make it easier to stay up-to-date and avoid desyncs.

To suggest/request changes to the repository (e.g. (re)organizing files, adding non-TAS content like READMEs), please contact a recent GitHub contributor or bot project admin, preferably through Discord in either the server linked above or direct messages.