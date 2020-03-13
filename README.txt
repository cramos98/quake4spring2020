-------------------------
QUAKE 4 METROID PRIME MOD
-------------------------
How to Use the Mod:
1. Download zip of Metroid_Deliverables Branch
2. Extract zip and move to Quake 4 Folder where the q4base folder and Quake4.exe reside.
3. Modify Quake4.exe properties and add "-disconnect +set fs_game q4metroid" to the end of the "target:".
IMPORTANT NOTE:
When starting up a new game the game may send you back to the main menu once the game finishes loading. This is caused by an animation issue regarding the railgun.
Simply attempt to start a new game again and it will load the game fine.
FOR DEMO:
- Player has all modified weapons by default so they can be tested from the beginning.
- Power Armors and Upgrades must be spawned in the console command line using the following lines:
Power Suit            = "spawn item_power_suit"
Varia Suit            = "spawn item_varia_suit"
Gravity Suit          = "spawn item_gravity_suit"
Fusion Suit           = "spawn item_fusion_suit"
Phazon Suit           = "spawn item_phazon_suit"
Health Upgrade        = "spawn item_health_upgrade"
Health Upgrade(Large) = "spawn item_health_upgrade_large"
Armor Upgrade         = "spawn item_armor_upgrade"

Recommended: Spawn the above items in a flat open space to avoid issues with spawning
-------------------------
Common Deliverables
-------------------------
1. Updated GUI
  - Changed main menu background image to be in metroid prime fashion.
  - Changed Location of Health and Armor Bars to be in the top right of the screen, similarly to Metroid: Other M
  - Changed the names of Weapons and Pickups in the GUI to reflect their Metroid modifications.
2. In Game Visuals showcasing edits
  - Changed various hitscan weapons to projectile based weapons and adjusted their projectiles to appear like the metroid projectiles they are trying to look like.
  - Changed the model of various health and armor pickups to appear as different power armors.
3. README with the description of changes and instructions on how to see them
  - This is the README.
4. Shortcut that auto-launches mod
  - On my computer but details on how to add a personal auto-launch shortcut is mentioned above.
5. Compiling with no additional warnings
  - No additional warnings are produced however the mod does have a slight issue when starting up a new game. This is mentioned above.
------------------------
Personal Deliverables
------------------------
1. Ball Mode
  - Not Implemented
  - Only Modified model of Roller Enemy to appear like the Morph Ball. Was not able to dynamically change player model to morph ball mode with button command.

2. Replace weapons with Metroid weapons
  - Blaster modified to be Beam Cannon and only fires charged shots with appear like energy projectiles from metroid.
  - Shotgun modified to be Wide Beam which fire three projectiles as a fast rate. The rocket launcher projectile has been used for accomplishing this modification.
  - Dark Matter Gun has been to be the Dark Beam.
    Only minor modifications to visual appearance of the projectile and the projectile's damage have been made since the Dark Matter Gun is already fairly similar to the Dark Beam from Metroid.
  - Machinegun has been modified to be like the Annihilator Beam. 
    Fires rocket launcher projectiles at a rapid rate and fires a dark matter gun projectile as the alternate fire since it is similar in nature to the annihilator beam's charged shot projectile.
  - Rocket Launcher has been modified to be the Missile from Metroid Prime. It has a lower fire rate than the other weapons but has high damage.
  - Lightning Gun modified to be the Wave Beam. The lightning gun's tube was modified to have a more of an oscillating wave appearance
  - Railgun has been modified to be the Plasma Beam. 
    Increased fire rate which required changing the animation the gun used otherwise the fire rate would not change, however it created the issue mention above.
  - Napalm gun modified to be the Magmaul. Napalm gun now fire projectiles that bounce off of surfaces and explodes after approximately 3 seconds.
  - All guns have infinite ammo since guns do not have or use ammo in Metroid games.

3. Replace item pick ups with power armors
  - Zero Suit: Not an actual obtainable suit but players base speed and walkspeed were increase to represent Samus without any power armors equip.
  - Power Suit: item_armor_small changed to item_power_suit. Grants player Quad Damage powerup for 99 seconds and 25 Armor
  - Varia Suit: item_armor_small_mp changed to item_varia_suit. Grants player Quad Damage powerup for 99 seconds and 50 Armor
  - Gravity Suit: item_health_large changed to item_gravity_suit. Grants player Haste powerup for 99 seconds and 50 additional Health
  - Fusion Suit: item_health_small changed to item_fusion_suit. Grants player 50 Armor and 50 Health
  - Phazon Suit: item_armor_large changed to item_phazon_suit. Grants 100 Armor

4. Power Suits upgradeable through pickups (ex. Health, Armor, Max Ammo Upgrades)
  - Player Max health changed to 699 To be in line with Metroid Max Energy (Health).
  - Health Upgrade: item_health_shard changed to item_health_upgrade. Increase health by 50. Grant 20 Bonus Health.
  - Large Health Upgrade: item_health_shard_mp changed to item_health_upgrade_large. Increase Health by 99 like in Metroid. Also grants 50 bonus Health.
  - Armor Upgrade: item_armor_shard changed to item_armor_upgrade. Increase Armor by 15.
  - Max Ammo Upgrades not implemented since metroid weapons do not have ammo.