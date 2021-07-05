# Skyrim Install Guide

Goal : Lore friendly, lots of content, babes you can shag, no HP sponge all build are valid combat but you are still gonna die from time to time.           
By combining MLU, Ordinator, Wildcat and an explosive player power gain trough unccapper, players start weak but able to tackle the first few dungeons if they are careful while endgame progress will not slow down to a crawl and will not require resetting skills.   

Relative to endgame exploit, some + Alchemy/Smithing items exist, but those enchants cannot be learned, and no recipe to craft fortify enchantement potions exist, and hence the loop is broken.   
           
Updated : 2021-07-05        

Notes : Mods are in the order they need to override each others files. See at the bottom for load order.

## Prerequisite

### Skyrim Special Edition        
https://steamcommunity.com/app/489830/             
Install it, run it at least once, set settings to ultra and display subtitles.

### Vortex + Nexusmods Account
https://www.nexusmods.com/about/vortex/          
Once skyrim has be installed, install vortex and learn how to use it       

### Microsoft Visual C++ Redistributable for Visual Studio 2019
https://support.microsoft.com/en-us/help/2977003/the-latest-supported-visual-c-downloads

## Optional

### FallrimTools - Script cleaner and more
https://www.nexusmods.com/skyrimspecialedition/mods/5031   
Save cleaner.

### Xedit
https://github.com/TES5Edit/TES5Edit/releases/tag/xedit-4.0.3
           
 ## Mods/tools needing some manual install work 
 
 ### SKSE64        
https://skse.silverlock.org        
Download the SE version 7z archive, extract next to SkyrimSE.exe. Configure vortex to run it by default.    

### Fores New Idles in Skyrim SE - FNIS SE   
https://www.nexusmods.com/skyrimspecialedition/mods/3038   
FNIS Behavior SE 7_6   
FNIS Creature Pack SE 7.6   
FNIS Spells SE 7.0    
   
Configure it in Vortex, then to run every time the load order is changed.   


### SSE Engine Fixes (skse64 plugin)
https://www.nexusmods.com/skyrimspecialedition/mods/17230               
Download and install part 1 with vortex normally, manually download and extract part 2 at the root of your Skyrim folder

### xSHADOWMANx's Dll Loader
https://www.nexusmods.com/skyrimspecialedition/mods/3619/?tab=files   
Extract to root

### DLL Plugin Loader
https://www.nexusmods.com/skyrimspecialedition/mods/10546?tab=description   
1. Go to your Skyrim Special Edition root directory. This is the same folder where SkyrimSE.exe is, usually "C:\Program Files (x86)\Steam\steamapps\common\Skyrim Special Edition\"   
2. Rename "binkw64.dll" to "binkw64_.dll" <- now there's a _ at the end.   
3. Put the "binkw64.dll" from downloaded archive into the folder mentioned in step 1.   
4. If you did it correctly you should have two files in your folder now: "binkw64.dll" and "binkw64_.dll", that's all, you can start the game now.   

### SSE Parallax Shader Fix (BETA)   
https://www.nexusmods.com/skyrimspecialedition/mods/31963   
SSE Parallax Shader Fix v1.0 (BETA)    
d3dcompiler_47  <= Install manually by extrating to root

## Mods that can be fully installed from within vortex

### Address Library for SKSE Plugins
https://www.nexusmods.com/skyrimspecialedition/mods/32444  
All in one

### .NET Script Framework
https://www.nexusmods.com/skyrimspecialedition/mods/21294   
NetScriptFramework SkyrimSE v14   

### More Informative Console
https://www.nexusmods.com/skyrimspecialedition/mods/19250   
More Informative Console 0.42   

### PapyrusUtil SE - Modders Scripting Utility Functions
https://www.nexusmods.com/skyrimspecialedition/mods/13048   
PapyrusUtil SE - Scripting Utility Functions   

### SkyUI   
https://www.nexusmods.com/skyrimspecialedition/mods/12604   
SkyUI_5_2_SE   

### SkyUI SE - Flashing Savegames Fix
https://www.nexusmods.com/skyrimspecialedition/mods/20406/   
SkyUI SE - Flashing Savegames Fix   

### Unofficial Skyrim Special Edition Patch
https://www.nexusmods.com/skyrimspecialedition/mods/266    
Unofficial Skyrim Special Edition Patch

### Cutting Room Floor - SSE
https://www.nexusmods.com/skyrimspecialedition/mods/276   
Cutting Room Floor

### Open Cities Skyrim - SSE
https://www.nexusmods.com/skyrimspecialedition/mods/281   
Open Cities Skyrim    

### Castle Volkihar Rebuilt - SSE
https://www.nexusmods.com/skyrimspecialedition/mods/324       
Castle Volkihar Rebuilt   

### Point The Way   
https://www.nexusmods.com/skyrimspecialedition/mods/352   
Point The Way   

### The Paarthurnax Dilemma   
https://www.nexusmods.com/skyrimspecialedition/mods/365    
The Paarthurnax Dilemma

### Dawnguard Map Markers   
https://www.nexusmods.com/skyrimspecialedition/mods/20931   
Dawnguard Map Markers               

### Fuz Ro D-oh - Silent Voice
https://www.nexusmods.com/skyrimspecialedition/mods/15109   
Fuz Ro D'oh   

### Odin - Skyrim Magic Overhaul   
https://www.nexusmods.com/skyrimspecialedition/mods/46000   
Odin 1.8.0   

### Ordinator - Perks of Skyrim
https://www.nexusmods.com/skyrimspecialedition/mods/1137         
Ordinator 9.30.1 (or later)               
50 percent More Perk Points         
Odin - Ordinator Compatibility Patch          

### Growl - Werebeasts of Skyrim
https://www.nexusmods.com/skyrimspecialedition/mods/31245   
Growl 2.3.0

### Sacrosanct - Vampires of Skyrim
https://www.nexusmods.com/skyrimspecialedition/mods/3928   
Sacrosanct 5.17.0   

### A Quality World Map        
https://www.nexusmods.com/skyrimspecialedition/mods/5804         
8.4 A Quality World Map - Classic with All Roads           

### Acquisitive Soul Gems Multithreaded       
https://www.nexusmods.com/skyrimspecialedition/mods/1469      
Acquisitive Soul Gems Multithreaded  

### The Forgotten City   
https://www.nexusmods.com/skyrimspecialedition/mods/1179   
The Forgotten City   
   
### AI Overhaul SSE   
https://www.nexusmods.com/skyrimspecialedition/mods/21654       
AI Overhaul 1.6.4 =         

### AI Overhaul - Open Cities Compatibility
https://www.nexusmods.com/skyrimspecialedition/mods/38031      
AI Overhaul - Open Cities       

### Touring Carriages SE
https://www.nexusmods.com/skyrimspecialedition/mods/15948
Touring Carriages

### Convenient Horses
https://www.nexusmods.com/skyrimspecialedition/mods/9519   
Convenient Horses

### Immersive Amazing Follower Tweaks SE
https://www.nexusmods.com/skyrimspecialedition/mods/14722   
Immersive Amazing Follower Tweaks SE      
USSEP and DLC Patch    
Cicero Dances Patch

### Relationship Dialogue Overhaul - RDO SE
https://www.nexusmods.com/skyrimspecialedition/mods/1187          
Relationship Dialogue Overhaul - RDO Final   
RDO - CRF and USSEP Patches Final   
RDO - iAFT SE Patch Final   

### what777's Castle Volkihar Rebuilt Patches
https://www.nexusmods.com/skyrimspecialedition/mods/45796    
Castle Volkihar Rebuilt - Relationship Dialogue Overhaul Patch

### Opening Scene Overhaul SE
https://www.nexusmods.com/skyrimspecialedition/mods/168/   
Opening Scene Overhaul (Final)   
OSO Better Amplified Hadvar Voice Files   
   
### Andromeda - Unique Standing Stones of Skyrim
https://www.nexusmods.com/skyrimspecialedition/mods/14910   
Andromeda 1.1.2         

### Apocalypse - Magic of Skyrim    
https://www.nexusmods.com/skyrimspecialedition/mods/1090    
Apocalypse 9.45.0   
Apocalypse - Ordinator Compatibility Patch    
Apocalypse - Waterstride Spell Addon (Ported by Velgath)

### Triumvirate - Mage Archetypes   
https://www.nexusmods.com/skyrimspecialedition/mods/39170   
Triumvirate 1.7.0

### Immersive Armors
https://www.nexusmods.com/skyrimspecialedition/mods/3479   
Immersive Armors 8.1 SSE => Install UNP support

### Immersive Patrols SE
https://www.nexusmods.com/skyrimspecialedition/mods/718   
Immersive Patrols Lite   

### The Notice Board SE
https://www.nexusmods.com/skyrimspecialedition/mods/3218   
The Notice Board   
The Notice Board - Open Cities Patch    

### Aumriel - The Pale Lady   
https://www.nexusmods.com/skyrimspecialedition/mods/24161   
Aumriel - RDO SE   

### Caesia Follower - Borne of Magic - Revamped
https://www.nexusmods.com/skyrimspecialedition/mods/13389   
CaesiaSE   

### Simple Load Screens   
https://www.nexusmods.com/skyrimspecialedition/mods/49529      
Simple Load Screens   

### Static Mesh Improvement Mod - SMIM 
https://www.nexusmods.com/skyrimspecialedition/mods/659   
SMIM SE 2-08  => Everything

### Blended Roads
https://www.nexusmods.com/skyrimspecialedition/mods/8834
Blended Roads => Blended Roads both options

Solve conflicts by Clicking Afer All on Blended Roads

### High Poly Project
https://www.nexusmods.com/skyrimspecialedition/mods/12029   
High Poly Project => Everything, no patch

Solve conflicts by Clicking Afer All onHigh Poly Project.

### Skyrim 2018 by Pfuscher
https://www.nexusmods.com/skyrimspecialedition/mods/20146    
Skyrim 2018 => Both top options (no armor cubemap), No retexture, no surprise.    
Bugfixes 1.5   
Bugfixes 1.6   

Solve conflicts by Clicking Afer All on Skyrim 2018, then on Skyrim 2018 by Pfuscher - Bugfixes 1.5

### Skyrim 2020 Parallax by Pfuscher 
https://www.nexusmods.com/skyrimspecialedition/mods/2347   
A. Skyrim 2020 - Part I - Highest Quality        
A. Skyrim 2020 - Part II - Highest Quality   
A. Skyrim 2020 - Part I - Highest Quality - Green Caves   
7 Mountain Textures - with FOMod installer   => Pick what you like
Blended Roads Retexture  
Whiterun Street - Alternative 2   
    
Solve conflicts by Clicking Afer All, in that order, for files :    
A. Skyrim 2020 - Part I - Highest Quality   
A. Skyrim 2020 - Part II - Highest Quality 
A. Skyrim 2020 - Part I - Highest Quality - Green Caves   
Skyrim 2020 Parallax by Pfuscher Blended Roads Retexture  
Skyrim 2020 Parallax by Pfuscher - Whiterun Street - Alternative 2 

### Prisoner cart fix SMIM    
https://www.nexusmods.com/skyrimspecialedition/mods/8004   
Prisoner Cart Fix SSE   

Solve conflicts by Clicking Afer All for file Prisoner Cart Fix SSE  

### XxAwesome_PotionsxX SSE   
https://www.nexusmods.com/skyrimspecialedition/mods/5077/   
XxAWESOME_POTIONSxX XL   

### Skyrim Skill Uncapper
https://www.nexusmods.com/skyrimspecialedition/mods/8889/   
Skyrim Skill Uncapper   

### LeanWolf's Better-Shaped Weapons SE
https://www.nexusmods.com/skyrimspecialedition/mods/2017   
LeanWolfs Better-Shaped Weapons Installer v2.1.03 SE   

Install Everything, All options, No patches, Reflective Glass, Refractive Stalhrim, Dwarven Dawnbreaker, Default for other options.

### Zim's Immersive Artifacts
https://www.nexusmods.com/skyrimspecialedition/mods/9138   
Zim's Immersive Artifacts V1.6.2  => All artifacts; Chillrend: Better Shaped Weapon; Ebony Mail: Dark details; Mace of Molag Baal: Purple; Volendrung: Green Glow
ZIA White Phial Fix    
    
Solve conflict by clicking on After all on 
Zim's Immersive Artifacts - V1.6.2
Zim's Immersive Artifacts - ZIA White Phial Fix    

### Summermyst - Enchantments of Skyrim
https://www.nexusmods.com/skyrimspecialedition/mods/6285/
Summermyst v307

### Lore Weapon Expansion SE   
https://www.nexusmods.com/skyrimspecialedition/mods/9660   
Lore Weapon Expansion   

Only enable the main plugin.

### MorrowLoot Ultimate   
https://www.nexusmods.com/skyrimspecialedition/mods/3058  
MorrowLoot Ultimate      
MLU - Cutting Room Floor   
MLU - Immersive Armors   
MLU - Lore Weapon Expansion - LOTD Version    
MLU - AI Overhaul-ESL    
MLU - Summermyst - Enchantments of Skyrim   
MLU - WACCF-ESL   
MLU - Zim's Immersive Artifacts-ESL    

### Skyrim Alchemy Fixed   
https://www.nexusmods.com/skyrimspecialedition/mods/2262   
Skyrim Alchemy Fixed   
Skyrim Alchemy Fixed - Ordinator   
Patch - Awesome Potions   
Patch - Summermyst   

### Weapons Armor Clothing and Clutter Fixes
https://www.nexusmods.com/skyrimspecialedition/mods/18994          
Weapons Armor Clothing and Clutter Fixes 

Only enable the core Plugin

### Weapons Armor Clothing and Clutter Fixes (WACCF) and Summermyst Enchantments Patch
https://www.nexusmods.com/skyrimspecialedition/mods/19500   
WACCF and Summermyst Enchantments Patch V2

### Wildcat - Combat of Skyrim  
https://www.nexusmods.com/skyrimspecialedition/mods/1368   
Wildcat v700

### Zim's Immersive Artifacts - WACCF Patch
https://www.nexusmods.com/skyrimspecialedition/mods/19489            
Zim's Immersive Artifacts - Weapons Armor Clothing and Clutter Fixes Patch

### Legacy of the Dragonborn SSE   
https://www.nexusmods.com/skyrimspecialedition/mods/11802   
Legacy of the Dragonborn   

### Open Cities - Legacy of the Dragonborn Compatibility Patch
https://www.nexusmods.com/skyrimspecialedition/mods/31272   
LOTD - OCS Patch   

### Gildergreen Regrown   
https://www.nexusmods.com/skyrimspecialedition/mods/348    
Gildergreen Regrown   

### Opulent Thieves Guild   
https://www.nexusmods.com/skyrimspecialedition/mods/931    
Opulent Thieves Guild     
Update ESL Patch - Created by Erstam    

### Even Better Quest Objectives SE - EBQO SE
https://www.nexusmods.com/skyrimspecialedition/mods/159   
Even Better Quest Objectives SE v1.8.4  => Brotherhood forever to misc, accept the pre ticked options of compat patches.

### Stones of Barenziah Quest Markers
https://www.nexusmods.com/skyrimspecialedition/mods/684   
BarenziahQuestMarkers SSE v1-3-1   

### Finding Derkeethus
https://www.nexusmods.com/skyrimspecialedition/mods/19550?   
Finding Derkeethus => Even better quest objectives option

### Better Dialogue Controls
https://www.nexusmods.com/skyrimspecialedition/mods/1429   
Better Dialogue Controls v1_2   

### RaceMenu
https://www.nexusmods.com/skyrimspecialedition/mods/19080   
RaceMenu Special Edition v0-4-16   

Do not enable the optional plugin, only the core mod.    

### HDT-SMP (Skinned Mesh Physics)
https://www.nexusmods.com/skyrimspecialedition/mods/30872   
HDT-SMP for SSE 1.5.97 v2.11      

### XP32 Maximum Skeleton Special Extended - XPMSSE   
https://www.nexusmods.com/skyrimspecialedition/mods/1988    
XP32 Maximum Skeleton Special Extended => Weapon style randomizer in Sync, Shlong of Skyrim patch

Note : Never override those files. They should always load last.  

### UNP Female Body Renewal - A female face and body replacer
https://www.nexusmods.com/skyrimspecialedition/mods/1699   
UNP Female Body Renewal 4.6   => Pinup, HDT-STMP, 4k, Scars ans with pubic hairs, Defined scars, Default, SG Female eyebrows.   
  
Solve conflict by clicking on After all on UNP Female Body Renewal 4.6 

### Bijin Skin UNP and CBBE SE   
https://www.nexusmods.com/skyrimspecialedition/mods/20078   
Bijin Skin UNP => 4k Pubic, 4k Default, 4k Default, 4k default, Default x2, 4k default, all the rest default.   

Solve conflict by clicking on After all on Bijin Skin UNP

### Skin Feature Overlays SE - Freckles Scars Birthmarks Stretch Marks Moles and More for Face and Body RaceMenu Overlays
https://www.nexusmods.com/skyrimspecialedition/mods/20183   
SkFO SE - Skin Feature Overlays- 2K   

### The Eyes Of Beauty SSE
https://www.nexusmods.com/skyrimspecialedition/mods/16185   
The Eyes of Beauty SSE   

Solve conflict by clicking on After all on The Eyes of Beauty SSE   

### UNP Body Fit Armors and Clothing   
https://www.nexusmods.com/skyrimspecialedition/mods/11136    
UNP Body Fit Armors and Clothing 2.3  => ESPFE, Immersive TBBP, ESPFE    
    
Solve conflict by clicking on After all on UNP Body Fit Armors and Clothing 2.3   

### Schlongs of Skyrim SE 1.1.4   
https://www.loverslab.com/files/file/5355-schlongs-of-skyrim-se/    
Schlongs_of_Skyrim_SE - v1.1.4.rar => Default; Hairy; Regular, uncheck Skeletons, Shop    

Solve conflict by clicking on After all on SoS SE, then on XP32 Maximum Skeleton Special Extended     

### Tempered Skins for Males - Vanilla and SOS versions
https://www.nexusmods.com/skyrimspecialedition/mods/7902   
Tempered Skins for Males - SOS Full version => A1, B6, C2, D2, E2

Solve conflict by clicking on After all on Tempered Skins for Males - SOS Full version

### The Book of UUNP Volumes 1 2 and 3 - UNP - Sevenbase - UNPB
https://www.nexusmods.com/skyrimspecialedition/mods/7505          
The Book of UUNP-SSE           
Missing DBboots Texture     
01 - The Book of UUNP - SSE UNP meshes         
03 - The Book of UUNP - Waylanders No Skimpy Patch    
     
Solve conflict by clicking on After all on The Book of UUNP-SSE, then on The Book of UUNP - Waylanders No Skimpy Patch    

### Summermyst enchanted Book of UUNP armors
https://www.nexusmods.com/skyrimspecialedition/mods/8975
The Book of UUNP with Summermyst Enchantments 1.6

### Diverse Dragons Collection SE (DDCse)
https://www.nexusmods.com/skyrimspecialedition/mods/695   
Diverse Dragons Collection SE   

### Dynamic Animation Replacer
https://www.nexusmods.com/skyrimspecialedition/mods/33746    
DynamicAnimationReplacer v1.1.0 for SkyrimSE

### Immersive Interactions - Animated Actions
https://www.nexusmods.com/skyrimspecialedition/mods/47670    
Immersive Interactions

### Expressive Facegen Morphs SE 
https://www.nexusmods.com/skyrimspecialedition/mods/35785   
Expressive Facegen Morphs SE   

Solve conflicts by clicking on After all on Expressive Facegen Morphs SE

### Expressive Facial Animation -Female Edition-   
https://www.nexusmods.com/skyrimspecialedition/mods/19181   
Expressive Facial Animation - Female Edition   
   
Solve conflicts by clicking on After all on Expressive Facial Animation -Female Edition-   

### Expressive Facial Animation -Male Edition-
https://www.nexusmods.com/skyrimspecialedition/mods/19532   
Expressive Facial Animation - Male Edition   
   
Solve conflicts by clicking on After all on Expressive Facial Animation -Male Edition-   

### Mfg Fix
https://www.nexusmods.com/skyrimspecialedition/mods/11669   
MfgFix   
MfgFix MCM

### OSA - Skyrim Ascendancy Engine
https://www.nexusmods.com/skyrimspecialedition/mods/17217   
OSA    
SkyLife   

Solve conflicts by clicking on *BEFORE all* on OSA - Skyrim Ascendancy Engine - OSA 

### OSex
https://www.nexusmods.com/skyrimspecialedition/mods/17209   
OSex   
OSex_BadGirlsOfSkyrim   
OSex_DuaWield   
OSex_WizardSex   
   
### Flower Girls SE and VR   
https://www.nexusmods.com/skyrimspecialedition/mods/5941   
FlowerGirls SE and VR Main File   
Amorous Adventures FG SSE 3.4.1   
FlowerGirls SE Adventures   
FlowerGirls SE Caesia Patch   
FlowerGirls SE Female Cicero Patch  => Enable only after you have installed Cicero replacer to prevent errors    

Solve conflicts by clicking on After all on FlowerGirls SE Caesia Patch    

### More Adventures for Flower Girls
https://www.nexusmods.com/skyrimspecialedition/mods/40029   
FG More Adventures v1.1   

### FNIS Sexy Move SE
https://www.nexusmods.com/skyrimspecialedition/mods/13303    
FNIS Sexy Move SE 7.2   

### KS Hairdos SSE
https://www.nexusmods.com/skyrimspecialedition/mods/6817  
KS Hairdos SSE   

Solve conflicts by clicking on After all on KS Hairdos SSE   

### KS Hairdos - HDT SMP (Physics)
https://www.nexusmods.com/skyrimspecialedition/mods/31300   
KS Hairdos SMP => Wig option     

### High Poly Head 1.4
https://vectorplexus.com/files/file/283-high-poly-head/   

Special Edition, Expressive Facegen Morphs, All Facial Animations and fixes, BSA only.

### High Poly NPC Overhaul - Resources
https://www.nexusmods.com/skyrimspecialedition/mods/42768   
High Poly NPC Overhaul - Resources 2.06   
High Poly NPC Overhaul - Resources - KS Hairdos HDT SMP Physics Patch 2.05      

Solve conflict by clicking on After all on 
High Poly NPC Overhaul - Resources 2.06    
High Poly NPC Overhaul - Resources - KS Hairdos HDT SMP Physics Patch 2.05     

### High Poly NPC Overhaul - Skyrim Special Edition 2.0 (All Vanilla NPCs)
https://www.nexusmods.com/skyrimspecialedition/mods/44155   
High Poly NPC Overhaul - Skyrim Special Edition 2.04     
Patch Collection => To be manually replaced By nokhal patch        
    
Solve conflict by clicking on After all on High Poly NPC Overhaul - Skyrim Special Edition 2.04      

### High Poly NPC Overhaul - Flower Girls SE
https://www.nexusmods.com/skyrimspecialedition/mods/44486   
High Poly NPC Overhaul - Flower Girls SE    

### RS Children Overhaul
https://www.nexusmods.com/skyrimspecialedition/mods/2650   
RSSE Children Overhaul 1.1.3 with hotfix 1 => USSEP

### RS Children Patch Compendium
https://www.nexusmods.com/skyrimspecialedition/mods/13409   
RS Children - AI Overhaul patch   
RSC FOMOD Beta   

Solve conflict by clicking on After all on    
RS Children Patch Compendium - RSC FOMOD Beta    
RS Children - AI Overhaul patch   

### Bijin NPCs SE
https://www.nexusmods.com/skyrimspecialedition/mods/11287    
Bijin NPCs SE 1.2.1 => All in one, Vanilla Based, Wrinkles for everyone, UNP body.     
    
Solve conflicts by clicking on After all on  
Bijin NPCs SE   

### Bijin Warmaidens SE
https://www.nexusmods.com/skyrimspecialedition/mods/1825   
Bijin Warmaidens SE v3.1.3 => All in one, Wrinkles for everyone, UNP body.  

Solve conflicts by clicking on After all on  
Bijin Warmaidens SE    

### Bijin Wives SE
https://www.nexusmods.com/skyrimspecialedition/mods/11247    
Bijin Wives SE 1.1.2  => All in one UNP body.     
    
Solve conflicts by clicking on After all on    
Bijin Wives SE     

### Seranaholic by rxkx22 - SSE
https://www.nexusmods.com/skyrimspecialedition/mods/13027     
Seranaholic SSE 1.8 => Unp, Red Eye + wght 20, Vampire Style  
Valerica SSE => Unp, Red, Black, Wrinkles  

### Bijin All in One 2020
https://www.nexusmods.com/skyrimspecialedition/mods/11      
Bijin AIO 2020 - Serana Valerica - AI Overhaul    

### Cicero Female SE
https://www.nexusmods.com/skyrimspecialedition/mods/5212   
Cicero Female SE   

### Cicera - Female Cicero Dialogue Edit   
https://www.nexusmods.com/skyrimspecialedition/mods/43990    
Cicera - Female Cicero Dialogue Edit     
Cicera Dialog Edit - CRF Patch   
Cicera Dialog Edit - Even Better Quest Objectives Patch   
Cicera Dialog Edit - LotD Patch   
Cicera Dialog Edit - USSEP Patch    
   
### Elegant Queen - Elisif Replacer for SSE
https://www.nexusmods.com/skyrimspecialedition/mods/39599   
Elisabeth Elisif replacer   

### Sybille Stentor Awakened SE 1.0
https://schaken-mods.com/file/118-sybille-stentor-awakened-se/   
Sybille Awakened.7z    

### Nether's Karliah
https://www.nexusmods.com/skyrimspecialedition/mods/49334   
Nether's Karliah - Universal Installer (LE or SSE) => Special edition, Nether's Karilah, Default x2, UNP, AFT  
   
Solve conflicts by clicking on After all on    
Nether's Karliah - Universal Installer (LE or SSE)  

### Seductress Faye - Custom voiced FG Follower.
https://www.nexusmods.com/skyrimspecialedition/mods/20185   
Seductress Faye - SE - FG   

### Sofia - The Funny Fully Voiced Follower   
https://www.nexusmods.com/skyrimspecialedition/mods/2180   
Sofia Follower v.2.51 (Loose)   

### Sofia - The Funny Fully Voiced Follower - High Poly Heads Replacer
https://www.nexusmods.com/skyrimspecialedition/mods/42420   
Sofia The Funny Fully Voiced Follower - High Poly Heads - ESL   
Sofia Follower High Poly Heads-Sofia Alt Hair-Blond - Overwrite when asked   

Solve conflicts by clicking on After all on    
Sofia The Funny Fully Voiced Follower - High Poly Heads - ESL 
Sofia Follower High Poly Heads-Sofia Alt Hair-Blond - Overwrite when asked   

### Legacy of the Dragonborn Patches (Official)
https://www.nexusmods.com/skyrimspecialedition/mods/30980   
Legacy of the Dragonborn Patches (Official)  => Autodetect setup except last : pick SMIM and Skyrim 2018   

Solve conflicts by clicking on After all on Legacy of the Dragonborn Patches (Official)    

### kryptopyr's Patch Hub
https://www.nexusmods.com/skyrimspecialedition/mods/19518   
kryptopyr's Patch Hub Installer

# File Conflicts

## Click on "After All" in this order :  
OSA - Skyrim Ascendancy Engine - OSA    
Papyrus Util SE - Scripting Utility Functions   
MfgFix   
Immersive Amazing Follower Tweak SE   
Immersive Amazing Follower Tweak SE - USEEP and DLC Patch   
Smimm SE 2-08     
Blended Roads     
High Poly Project  
Skyrim 2018    
Skyrim 2018 by Pfuscher - Bugfixes 1.5    
A. Skyrim 2020 - Part I - Highest Quality     
A. Skyrim 2020 - Part II - Highest Quality   
A. Skyrim 2020 - Part I - Highest Quality - Green Caves    
Skyrim 2020 Parallax by Pfuscher Blended Roads Retexture   
Skyrim 2020 Parallax by Pfuscher - Whiterun Street - Alternative 2    
Prisoner Cart Fix SSE    
LeanWolfs Better-Shaped Weapons Installer v2.1.03 SE
Zim's Immersive Artifacts v 1.6.2   
Zim's Immersive Artifacts - ZIA White Phial Fix    
UNP Female Body Renewal 4.6    
Bijin Skin UNP    
The Eyes of Beauty SSE       
UNP Body Fit Armors and Clothing 2.3     
SoS SE    
Tempered Skins for Males - SOS Full version    
XP32 Maximum Skeleton Special Extended    
Book of UUNP-SSE   
The Book of UUNP - Waylanders No Skimpy Patch    
Expressive Facegen Morphs SE    
Expressive Facial Animation -Female Edition-    
Expressive Facial Animation -Male Edition-
Caesia Follower - Borne of Magic - Revamped - Caesia SE
FlowerGirls SE Caesia Patch     
KS Hairdos SSE     
High Poly NPC Overhaul - Resources 2.06    
High Poly NPC Overhaul - Resources - KS Hairdos HDT SMP Physics Patch 2.05     
High Poly NPC Overhaul - Skyrim Special Edition 2.04    
RS Children Patch Compendium - RSC FOMOD Beta   
RS Children - AI Overhaul patch    
Bijin NPCs SE    
Bijin Warmaidens SE    
Bijin Wives SE    
Nether's Karliah - Universal Installer (LE or SSE)    
Sofia Follower v.2.51 (Loose)
Sofia The Funny Fully Voiced Follower - High Poly Heads - ESL   
Sofia Follower High Poly Heads-Sofia Alt Hair-Blond - Overwrite when asked    
Legacy of the Dragonborn Patches (Official)   
    


# End setup

## Todo 
Install the two patches provided here. Replace the pex and drop the ESP in data (overwrite)     
Load MLU after WACF     
AFT features compat with convenient horse ?
some weird immersive aft behaviour tofix   

## Remove ESP
The following ESPs are to be disabled or deleted from your /data folder. (I recommend deletion) There is no benefit to leaving these esps in your data folder.      
Bijin Warmaidens.esp   
Bijin Wives.esp   
Bijin NPCs.esp   
Serana.esp   
Valerica.esp    
RDO - USSEP Patch.esp   
Lore Weapon Expansion - Relics of the Crusader.esp   
Lore Weapon Expansion - Goldbrand.esp   
Lore Weapon Expansion - Daedric Crescent.esp   
RaceMenuPlugin.esp   
waccf_vashedpatchlvllistfix.esp

## Remove sofia buggy script
Delete \Skyrim Special Edition\Data\Scripts\ski_playerloadgamealias.pex

Accept changes in Nexus

## Generate Animations
Run Fnis with the first 3 options ticked.  

# DONE. You can now start a new game trough launching SKSE.
