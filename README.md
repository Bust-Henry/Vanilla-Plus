# Vanilla-Plus

The offical Vanilla Plus Modpack of the Driftveil City Discord

This modpack was designed for Minecraft version 1.20.2.
This branch has the exact same mods as the 1.20.2-Forge branch, except some added shader mods (see Iris).
Also some depency mods are different because this branch uses the fabric mod loader insted of the [forge branch](https://github.com/Bust-Henry/Vanilla-Plus/tree/1.20.2-Forge).
An upadte for later versions of Minecraft are not planned yet. (But not impossible if we maybe play minecraft again in a year or something)

This page is a showcase of mods used and also a complete list of mods used!

- [Vanilla-Plus](#vanilla-plus)
  - [Mod List](#mod-list)
    - [chunkloaders-1.2.8a-fabric-mc1.20.2](#chunkloaders-128a-fabric-mc1202)
    - [Clumps-fabric-1.20.2-13.0.0.1](#clumps-fabric-1202-13001)
    - [gravestone-1.20.2-1.0.5](#gravestone-1202-105)
    - [InventoryProfilesNext-fabric-1.20.2-1.10.9](#inventoryprofilesnext-fabric-1202-1109)
    - [journeymap-1.20.2-5.9.16-fabric](#journeymap-1202-5916-fabric)
    - [toms_storage-1.20.2-1.6.6](#toms_storage-1202-166)
    - [trashcans-1.0.18b-fabric-mc1.20](#trashcans-1018b-fabric-mc120)
    - [waystones-fabric-1.20.2-15.0.0](#waystones-fabric-1202-1500)
    - [iris-mc1.20.2-1.6.10](#iris-mc1202-1610)
    - [boring zone (dependency mods)](#boring-zone-dependency-mods)
      - [balm-fabric-1.20.2-8.0.1](#balm-fabric-1202-801)
      - [ConfiguredDefaults-v8.0.1-1.20.1-fabric](#configureddefaults-v801-1201-fabric)
      - [jei-1.20.2-fabric-16.0.0.28](#jei-1202-fabric-160028)
      - [supermartijn642configlib-1.1.8-fabric-mc1.20.2](#supermartijn642configlib-118-fabric-mc1202)
      - [fabric-api-0.90.7+1.20.2](#fabric-api-09071202)
      - [fabric-language-kotlin-1.10.13+kotlin.1.9.20](#fabric-language-kotlin-11013kotlin1920)
      - [libIPN-fabric-1.20.2-4.0.0](#libipn-fabric-1202-400)
      - [sodium-fabric-mc1.20.2-0.5.3](#sodium-fabric-mc1202-053)
  - [Quickstart Guide - Installation](#quickstart-guide---installation)
    - [Client installation](#client-installation)
    - [Server installation](#server-installation)
      - [Server optimization](#server-optimization)
  - [The end](#the-end)

## Mod List

### chunkloaders-1.2.8a-fabric-mc1.20.2

a quality of life mod for permanently loading chunks

Added Items:

![alt text][chunkloading]
![alt text][chunkloadingrecipes]

### Clumps-fabric-1.20.2-13.0.0.1

a mod to compact xp orbs, primarily for server lag reducing

### gravestone-1.20.2-1.0.5

quality of life mod that preserve your inventory on death and places it in a destroyable gravestone

### InventoryProfilesNext-fabric-1.20.2-1.10.9

basicly adds buttons to sort chests

### journeymap-1.20.2-5.9.16-fabric

Map mod. Adds a minimap, waypoints and more map features

Added HUD features:

![alt text][minimap]
![alt text][fullmapview]
![alt text][waypoint]

### toms_storage-1.20.2-1.6.6

adds a simple storage system to link all chests to one terminal

Added Items:

![alt text][toms]
![alt text][tomsrecipe]

### trashcans-1.0.18b-fabric-mc1.20

adds a trashcan block that instantly voids items

Added Item:

![alt text][trashcan]
![alt text][trashcanrecipe]

### waystones-fabric-1.20.2-15.0.0

adds a mod that lets you create waystones, that you can port to. (Combined with chunkloaders, to create farms further away from base)

This mod has to much items to all put them here, but these 2 will be the most important:

- Waystone: Placable block that marks a teleportation spot.
- Warp Scroll: Consumable that warps you to a waystone of your choice.

![alt text][waystones]

### iris-mc1.20.2-1.6.10

This mod is used to add shaders to the game. It also does a bunch of game optimization.

If you know how to use shaders you can add shaders like with any other shader mod (Optifine, standalone Iris, etc.)
If you dont know how to add them, just look up how to add shader with Iris. This mod works exactly like standalone Iris.

### boring zone (dependency mods)

#### balm-fabric-1.20.2-8.0.1

a dependecy mod for the mod waystones-fabric-1.19.4-13.0.1

#### ConfiguredDefaults-v8.0.1-1.20.1-fabric

a dependecy mod for a lot of mods. Used to add ingame config menues for some mods

#### jei-1.20.2-fabric-16.0.0.28

adds an item lookup menu

#### supermartijn642configlib-1.1.8-fabric-mc1.20.2

dependency mod

#### fabric-api-0.90.7+1.20.2

dependency mod for basicly all fabric mods

#### fabric-language-kotlin-1.10.13+kotlin.1.9.20

language tranlator for some fabric based mods

#### libIPN-fabric-1.20.2-4.0.0

dependency mod

#### sodium-fabric-mc1.20.2-0.5.3

dependency mod for the iris shader mod. Client side optimization mod.

## Quickstart Guide - Installation

### Client installation

IMPORTANT:
Requires installed Vanilla Minecraft (1.20.2) and [Openjdk](https://www.oracle.com/de/java/technologies/downloads/#java20) install on your pc.

1. Download the [1.20.2-Fabric-Release](https://github.com/Bust-Henry/Vanilla-Plus/releases/tag/1.20.2-Fabric-Release)
2. Extract rar file (doesnt matter where, can be deleted later) (use winrar, zip, etc.)
3. Run fabric-installer-0.11.2.exe
4. Select install client option
5. Win + R -> %appdata%
6. Open .minecraft/mods/
7. Copy all mods in the mods folder into the .minecraft/mods folder
8. Start minecraft
9. Select new profile called fabric

### Server installation

1. Download the [1.20.2-Fabric-Release](https://github.com/Bust-Henry/Vanilla-Plus/releases/tag/1.20.2-Fabric-Release)
2. Extract rar file (in the folder where your server files should be later) (use winrar, zip, etc.)
3. Run fabric-installer-0.11.2.exe
4. Select install server option
5. Select Minecraft Version 1.20.2
6. Select Loader Version 0.14.24
7. Press install
8. Wait for the installation to finish
9. In the Server successfully installed window click the Download server jar button
10. To generate a launch script press the Generate button
11. Now everything is done and you can press the Done button
12. Run the start.bat

#### Server optimization

Here are some simple settings I suggest to improve server performance:

1. Open the server.properties file with a text editor
2. Set the sync-chunk-writes option to false
3. Set the simulation-distance option to 5
4. Set the view-distance option to 8

## The end

Thats all folks, if you guys want to change something about this modpack (add or remove mods), message me on discord or, post suggestions in the #modpack-disccusion textchannel.

[chunkloading]: https://github.com/Bust-Henry/Vanilla-Plus/blob/master/images/ChunkLoading.gif "Title"
[chunkloadingrecipes]: https://github.com/Bust-Henry/Vanilla-Plus/blob/master/images/ChunkLoadingRecipes.gif "Title"
[fullmapview]: https://github.com/Bust-Henry/Vanilla-Plus/blob/master/images/FullMapView.png "Title"
[minimap]: https://github.com/Bust-Henry/Vanilla-Plus/blob/master/images/Minimap.png "Title"
[toms]: https://github.com/Bust-Henry/Vanilla-Plus/blob/master/images/Toms.gif "Title"
[tomsrecipe]: https://github.com/Bust-Henry/Vanilla-Plus/blob/master/images/TomsRecipe.gif "Title"
[trashcan]: https://github.com/Bust-Henry/Vanilla-Plus/blob/master/images/Trashcan.png "Title"
[trashcanrecipe]: https://github.com/Bust-Henry/Vanilla-Plus/blob/master/images/TrashcanRecipe.png "Title"
[waypoint]: https://github.com/Bust-Henry/Vanilla-Plus/blob/master/images/Waypoint.png "Title"
[waystones]: https://github.com/Bust-Henry/Vanilla-Plus/blob/master/images/Waystones.gif "Title"
