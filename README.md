# THD New Bloodpools - Blood and Bones DLC
![Alt text](Example_Images/Thumbnail.png "a title")

DISCLAIMER - Due to the mod replacing the JSON file for vfx, game updates have a high chance of breaking the mod.

**Last Known Compatiblility for Age of Mythology Retold:** v.100.19.5934.0 (595758R)
      
v 1.3 New Changes: Due to new features, I've decided to split this mod. The myth unit blood assignments has been moved to my new compatible mod "THD Improved Battle Damage," which also assigns the appropriate battle damage color to the unit for their blood. This mod still contains the new and replaced blood pools 

Description: This mod edits the original red bloodpools while adding new red and prismatic bloodpool textures in order to:

     * Be more splattered and less cartoony
     * Recolored textures to be slightly darker
     * Reduced the texture size to have smaller ingame bloodpools
     * Added new blood pools for more variety
     * Ensured the ingame reflections work with new textures

## Changelog

v 1.3

     * Split mod for the following
          + Keeps the replaced red bloodpool textures
          + Keeps the new red and prismatic bloodpool textures
          + Assigns all of these textures to their appropriate blood groups
               + Adds these textures to new <bloodgroups> mythbloodred and titanbloodred
               * These bloodgroups are unused in this mod, but are utilized in the improved battle damage mod
          - Loses myth unit blood color assignments, the proto_mods file is now in the improved battle damage mod.
v 1.2

     * Converted blood.xml into additive xml format
     * Assigned and adjusted blood colors to myth units that were missed in 1.1
     
v 1.1

     * Added 10 new prismatic bloodpools for all colors except white and rainbow. A mix of edited 4 prismatic and 6 recolored small pools
     * Added 5 and 6 new pools to white-gold and rainbow colors, respectively
     * Assigned more lore accurate blood colors to myth units, courtesy of KJohnHayes for color suggestions
          * For Basegame, Japanese, Chinese, Freyr, and Demeter myth units
          * Created a new default bloodgroup "mythbloodred" to act as new default group
          * DLC originally seemed to randomly assign a color to units set to default
     * Incorporated emissive textures for sparkling effect in prismatic blood
     * Attempted to change emissive colors to match blood color (WIP)
          * Changing emissive color setting didn't seem to have an effect. Devs seemed to overlay a color over emissive spots and adjust intensity
     * Added 4 original blood mod pools to the default bloodpool list, courtesy of AlanWake
     * Added 4 edited bloodpool texturese from WankingSkeever's mod
     
v 1.0

     * For AoMR v.100.19.5934.0 (595758R)
     * Edited and replaced basecolor textures for Blood_pools_large_matA, Blood_pools_medium_matA, Blood_pools_small_matA
     * Replaced normals textures for Blood_pools_large_matA, Blood_pools_medium_matA, Blood_pools_small_matA
     * Mapped new textures in the destructionvfx.vfxjson file

## Credits
WankingSkeever - For blood textures from their Skyrim mod

AlanWake - For original blood mod

PngAAA.com - For some blood textures
