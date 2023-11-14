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
    - [custom-portals-3.2.2-1.20.2](#custom-portals-322-1202)
    - [toms_storage-1.20.2-1.6.6](#toms_storage-1202-166)
    - [trashcans-1.0.18b-fabric-mc1.20](#trashcans-1018b-fabric-mc120)
    - [iris-mc1.20.2-1.6.10](#iris-mc1202-1610)
    - [BetterF3-8.0.2-Fabric-1.20.2](#betterf3-802-fabric-1202)
    - [doubledoors-1.20.2-5.1](#doubledoors-1202-51)
    - [graves-3.1.1+1.20.2](#graves-3111202)
    - [RoughlyEnoughItems-13.0.675](#roughlyenoughitems-130675)
    - [harvestwithease-1.20.2-7.1.0.0-fabric](#harvestwithease-1202-7100-fabric)
    - [perfomance mods](#perfomance-mods)
      - [forcecloseloadingscreen-2.2.0](#forcecloseloadingscreen-220)
      - [lithium-fabric-mc1.20.2-0.12.0](#lithium-fabric-mc1202-0120)
      - [starlight-1.1.3+fabric.5867eae](#starlight-113fabric5867eae)
      - [sodium-fabric-mc1.20.2-0.5.3](#sodium-fabric-mc1202-053)
    - [Chunky-1.3.92](#chunky-1392)
    - [spark-1.10.54-fabric](#spark-11054-fabric)
    - [boring zone (dependency mods)](#boring-zone-dependency-mods)
      - [supermartijn642configlib-1.1.8-fabric-mc1.20.2](#supermartijn642configlib-118-fabric-mc1202)
      - [fabric-api-0.90.7+1.20.2](#fabric-api-09071202)
      - [fabric-language-kotlin-1.10.13+kotlin.1.9.20](#fabric-language-kotlin-11013kotlin1920)
      - [libIPN-fabric-1.20.2-4.0.0](#libipn-fabric-1202-400)
    - [cloth-config-12.0.109-fabric](#cloth-config-120109-fabric)
    - [modmenu-8.0.0](#modmenu-800)
    - [completeconfig-2.5.0](#completeconfig-250)
    - [architectury-10.0.8-fabric](#architectury-1008-fabric)
    - [collective-1.20.2-7.7](#collective-1202-77)
    - [ForgeConfigAPIPort-v9.0.0-1.20.2-Fabric](#forgeconfigapiport-v900-1202-fabric)
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

### custom-portals-3.2.2-1.20.2

Adds custom portals. Lets you create portals any size out of any block and connect them. Needs a special item to activate.

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

### iris-mc1.20.2-1.6.10

This mod is used to add shaders to the game. It also does a bunch of game optimization.

If you know how to use shaders you can add shaders like with any other shader mod (Optifine, standalone Iris, etc.)
If you dont know how to add them, just look up how to add shader with Iris. This mod works exactly like standalone Iris.

### BetterF3-8.0.2-Fabric-1.20.2

Improves the F3 view to be more readable.

### doubledoors-1.20.2-5.1

Makes double doors open together.

### graves-3.1.1+1.20.2

Adds graves that hold your items when you die.

### RoughlyEnoughItems-13.0.675

Adds huge crafting recipe lookup menu. You can look up every item in the game. Also the new items added by the other mods.

### harvestwithease-1.20.2-7.1.0.0-fabric

Lets you harvest ready plants with right click. Also replants the seed.

### perfomance mods

the mods listed here are only for perfomance, some of these are client only, but some are here to improve server performance.
All of these are from this [optimization guide](https://gist.github.com/HexedHero/aab340a84db51913cb1106c2d85f4e4f).

#### forcecloseloadingscreen-2.2.0

Removes the hardcoded Loading terrain screen.
This mod saves you like 2 seconds when joining a world.

#### lithium-fabric-mc1.20.2-0.12.0

Improves game rendering time

#### starlight-1.1.3+fabric.5867eae

Replaces minecraft light engine with a more optimized one

#### sodium-fabric-mc1.20.2-0.5.3

Uses improved rendering system to improve ingame fps

dependency mod for the iris shader mod. Client side optimization mod.

### Chunky-1.3.92

This mod is used to pregen chunks. If used properly this can improve the chunkloading immense.

### spark-1.10.54-fabric

This mod is a perfomance profiler. Its used to find sources of lag.

### boring zone (dependency mods)

#### supermartijn642configlib-1.1.8-fabric-mc1.20.2

dependency mod

#### fabric-api-0.90.7+1.20.2

dependency mod for basicly all fabric mods

#### fabric-language-kotlin-1.10.13+kotlin.1.9.20

language tranlator for some fabric based mods

#### libIPN-fabric-1.20.2-4.0.0

dependency mod

### cloth-config-12.0.109-fabric

dependency mod for custom portals

### modmenu-8.0.0

Adds a mod overview in the menu. Also a dependency mod for custom portals

### completeconfig-2.5.0

lets you configure some mods in the mod menu. Also dependency mod for custom portals

### architectury-10.0.8-fabric

dependency mod for some fabric mods

### collective-1.20.2-7.7

dependency mod

### ForgeConfigAPIPort-v9.0.0-1.20.2-Fabric

dependency mod

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
