# Monika's D-Sides TAS Project

This repository contains TAS files for the mod [Monika's D-Sides](https://gamebanana.com/mods/150759) for the video game [Celeste](celestegame.com).

## About

TAS files contain lists of inputs for a program (e.g. libTAS) or physical device (e.g. TASBot) to perform. TAS files for Celeste in particular are written in a custom format for use with the mod [CelesteTAS](https://gamebanana.com/tools/6715), which itself is designed for use with the modloader [Everest](https://everestapi.github.io/).

All TASes in this repository have the goal of completing certain objectives on a new file in the least in-game time possible (without using timer overflow) while using cheat mode as little as possible and without using any variants.

 - Main Pack (root directory + `9D` subdirectory): Latest versions of each D-Side, Dark Side, and Final Goodbye, all on the mod's current patch (v4.80 as of 2025 June 5).
   - `100%`: Get all collectibles, excluding deathless berries, in all main pack levels.
   - `All D-Sides`: Beat Epilogue D. Progress only by beating D-Sides.
   - `All Dark-Sides`: Beat 1-7Dark using cheat mode.
   - `All Levels`: Beat all main pack levels.
   - `Beat Epilogue`: Beat Epilogue D. It may be unlocked by any means except cheat mode.
   - `Darkny%`: Unlock 8D by only beating Dark Sides.
   - `Dny%`: Unlock 8D by any means except cheat mode.
   - `Drue Ending`: Beat Post-Epilogue. It may be unlocked by any means except cheat mode.
   - `Max%`: Get all collectibles, including deathless berries, in all main pack levels.
 - `Museum` (museum directory): Unused content and old versions of Main Pack levels.
   - `100%`: Get all collectibles, excluding deathless berries, in all museum levels. Only use cheat mode after beating all levels accessible without it.
   - `All Levels`: Beat all museum levels. Only use cheat mode after beating all levels accessible without it.
   - `All Main Levels`: Beat the A-Side of each museum chapter.
   - `Max%`: Get all collectibles, including deathless berries, in all museum levels. Only use cheat mode after beating all levels accessible without it.
 - `All Packs` (museum directory):
   - `100%`: Main Pack `100%` and Museum `100%`
   - `All Levels`: Main Pack `All Levels` and Museum `All Levels`
   - `All Main Levels`: Main Pack `All D-Sides`, `9D` (Final Goodbye), and Museum `All Main Levels`
   - `Max%`: Main Pack `Max%` and Museum `Max%`
 - `BerryHunt25`: Copies of all of the above for v4.77 of the mod, which acted as a limited-time event with extra content. See that subdirectory's readme for details.

## Viewing

There are two ways to watch a TAS from this repository:
 - Watch a recording or showcase of a TAS:
    - [Beat Epilogue showcase](https://www.youtu.be/VxJJegTyc-w)
    - [Final Goodbye Max% showcase](https://www.youtu.be/npSNabouT_4)
    - recordings of Dark Sides: [1Dark](https://www.youtu.be/rKMGs8QMLB0), [4Dark](https://youtu.be/dEut86kWKAw), [5Dark](https://www.youtu.be/Ya6lxjrGoCI), [6Dark](https://www.youtu.be/SUo2iC8UY3o), [7Dark](https://youtu.be/cHdfAiX2-nw)
    - recordings of museum levels: [Old 8Ds Mashup](https://youtu.be/6_0hd2D_KSw)
 - Run a TAS file on your PC by following these steps:
    1. Download the dependencies:
      - the game [Celeste](celestegame.com) and modloader [Everest](https://everestapi.github.io/)
      - the mod [CelesteTAS](https://gamebanana.com/tools/6715) and its required dependencies
      - current patch of the mod [Monika's D-Sides](https://gamebanana.com/mods/150759) (v4.80 as of 2025 June 5) and its required dependencies
      - for the Final Goodbye Platinum, the mod [Platinum Strawberry Asset Pack](https://gamebanana.com/mods/442093)
    2. Download a copy of this repository. There's a button in the green Code menu above the timestamp column.
    3. Select a TAS file (either open it in Studio or copy its contents into `Celeste.tas` in your Celeste directory), then press the "Start/Stop TAS" bind in Celeste.

## Contributing

Currently, all contributions to this repository have come from the [D-Sides TASing Discord server](https://discord.gg/pqcRSnQbzg). We strongly recommend sending drafts and improvements there, as the server uses the [CelesteTAS Improvements Tracker](https://github.com/Kataiser/CelesteTAS-Improvements-Tracker) Discord bot which catches lots of oversights and formatting errors and automatically manages `contributors.txt`. Since the TAS files in this repository make heavy use of `read` commands, we also recommend using software such as [GitHub Desktop](https://desktop.github.com/) to make it easier to stay up-to-date and avoid desyncs.

To suggest/request changes to the repository (e.g. (re)organizing files, adding non-TAS content like READMEs), please contact a recent GitHub contributor or bot project admin, preferably through Discord in either the server linked above or direct messages.