# SkyrimInstallGuide

This is intended to be semi retard proof. Basic profficency with a computer is expected (Opening archives, knowing what a root folder is, etc...)        

## Table of Contents : 

[1: Buying and installing the game](#1-buying-and-installing-the-game)                
[2: Setting up the modding framework](#2-setting-up-the-modding-framework)                     
[3: Installing the Script Injector](#3-installing-the-script-injector)               

## 1: Buying and installing the game 
  
Have a steam account.           
Go to https://store.steampowered.com/sub/626153/ and buy The Eldar Scrolls V: Skyrime Special Edition as well as The Elder Scrolls V: Skyrim Anniversary Upgrade                    
**Install the game on an SSD**                

Once the game is installed, launch the game, go to Creation Clubs and select download all 
![Download All](https://drive.google.com/uc?id=1c2pkRK_YGjiiyhdU9AbFUL07AfdAriTz)

The download will take some time. Once completed, skyrim will ask to reload the game.

You can start the game now if you want for the Skyrim - Anniversary Edition completely vanilla experience. (No Mods outside of the paid one of anniversary edition).

## 2: Setting up the modding framework   
   
Create an account on https://www.nexusmods.com   
   
Download [Vortex Mod Manager](https://www.nexusmods.com/about/vortex/)                
Install it on the same drive as Skyrim.                
Launch it, and let it detect/manually setup Skyrim AE installation folder.              
Then, and that's very important, setup Vortex **Mod Staging Folder** to be in the **SAME DRIVE AS SKYRIM**. For that purpose create a new folder in your drive and then pickup this folder from vortex.                  
![Staging](https://drive.google.com/uc?id=17AtbueW7tl3KlcUvmdQDSgT4kxxEJyKD)

## 3: Installing the Script Injector
    
Because you are on PC, any function call made by a software can be intercepted, monitored and modified. Skyrim Script Extender (SKSE) extend the base functions of the skyrim app and unlock a lot of advanced features for mods that would otherwise would not be possible. As such, nearly every modlist for PC you'll find will require SKSE.       
       
Download SKSE [here](https://skse.silverlock.org).            
You need the latest Anniversary edition.        
[Direct link](https://skse.silverlock.org/beta/skse64_2_02_03.7z)                
Open the archive, and drags and drop it's content at the root of the skyrim game folder, next to the game .exe files     
![Copy the archive content at the root](https://drive.google.com/uc?id=1wZX5SRcOzTWviEByDnZCX9dxjhzVz4EV)      

In vortex, go to the skyrim dashboard, and then click the ( + ) icon within the tools dashlet.            
![Dashboard](https://drive.google.com/uc?id=16s83ZzmYv31P-U0cxbYJbuAB5fz2FAZf)    

Select new, and then fill in the form with the following values :             
Name : SKSE                  
Target : REPLACE_THIS_WITH_SKYRIM_ROOT_FOLDER\skse64_loader.exe                        
You can click on the Icon and pick the skyrim exe for the icon if you wish.                          
![ConfSkse](https://drive.google.com/uc?id=1CqydznTW5Pcw3rRhvvSQvm4LQxZDZJzT)              
              
Finally, click on the hamburger menu of the SKSE Tools tile, and select Set as Primary. Enable the toolbar.  
 ![Toolbaring](https://drive.google.com/uc?id=1epVnqroHlj2hHAV0vA6uPGfS-mftvTql)        

Launch skyrim using the new tool shortcut to check if everything worked. You should not see the launcher anymore, the game should start straight up.          
In the future, only use vortex or a shortcut to skse64_loader.exe to launch skyrim. If you don't, mods will break.            
           

            

