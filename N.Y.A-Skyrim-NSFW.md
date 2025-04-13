# N.Y.A NSFW Modlist Version 6.0+
Welcome to the N.Y.A Modlist! This comprehensive mod compilation aims to enhance your Skyrim experience with a plethora of exciting features that are not explicitly centered around adult content, though they are *certainly* included.

![alt text](https://i.imgur.com/GjGgP7U.png "N.Y.A Poster Image")

## ATTENTION
*This content is intended for individuals who are of legal age in their respective countries. By accessing or using this material, you confirm that you meet the age requirement to view adult content. If you are not of legal age, please exit immediately.
Please be aware that it is your responsibility to comply with local laws and regulations regarding age restrictions.*

 
Before posting a new support request in #unmodified-support or #modified-support, **please check our [Frequently Asked Questions (F.A.Q.)](https://discord.com/channels/1201567388248834108/1257432068250669096/1257432068250669096)** on the Discord, and *ensure you have read the ReadMe properly* (you are here).

[Community Discord](https://discord.gg/vermishub)

# Pre-installation Steps
Before you install the modlist, there are some very important steps you need to take in order for a smooth installation process as well as a more seamless experience in-game.
Before diving into the modlist, it's essential to prepare your game environment. These pre-installation steps will help ensure a smooth installation process and a more seamless experience in-game. Follow **all** guidelines carefully:


## Requirements
Verify that your system meets the recommended requirement for running the modlist. Having a "worse" computer than this will not stop you from playing, but being below these requirements will likely result in performance issues.

Modlist was also tested on 6.0 on 8GB Vram and the Person got average 65 FPS.

![alt text](https://i.imgur.com/6nJCmTo.png "Logo Title Text 1")



#### Page File and Shader Cache
You will need to manually increase your page file as well as increase the size of your shader cache in order to avoid performance issues, even if you have a monster PC.

To increase your page file, press Windows+R and enter **systempropertiesadvanced** into it. Under "Performance", click "Settings..." and swap to the Advanced tab. Here you want to click "Change" under virtual memory.


Uncheck "Automatically manage..." and select your fastest SSD in the list of drives. Check "Custom Size" and set **Initial Size to 20480** and set **Maximum Size to 40000**. Now press "Set" and then APPLY before restarting your PC.


Increase the shader cache size via Nvidia Control Panel to at least **10GB**. You can skip this if you're using an AMD GPU, this is set up by default for them. If you have it disabled or want to see how to enable it you can [go here](https://www.amd.com/en/resources/support-articles/faqs/dh-012.html#DH-012-Shader).


## Microsoft
Download the latest x64 version beneath "Visual Studio 2015, 2017, 2019, and 2022" for [Microsoft Visual C++ Redistributable Packages](https://learn.microsoft.com/en-us/cpp/windows/latest-supported-vc-redist?view=msvc-170).

You are also going to need to download and install [.NET runtime](https://dotnet.microsoft.com/en-us/download).

Make Onedrive exclude folders from syncing:
https://support.microsoft.com/en-us/office/choose-which-onedrive-folders-to-sync-to-your-computer-98b8b011-8b94-419b-aa95-a14ff2415e85

or Disabling Onedrive:
https://support.microsoft.com/en-us/office/turn-off-disable-or-uninstall-onedrive-f32a17ce-3336-40fe-9c38-6efb09f944b0


## Accounts
You need an account on [Nexus](https://www.nexusmods.com). Premium is recommended to avoid having to manually click the download button for an entire day or so.

You will also need an account on [Loverslab](https://www.loverslab.com). You will have to log in for manual downloads (a step later on), and you might need to log in to Loverslab inside Wabbajack once the modlist download actually begins.

![alt text](https://i.imgur.com/pGixxkm.png)

# Preparing For Installation
In order to avoid issues when installing through Wabbajack, you will need to follow these **VERY IMPORTANT** steps.

## Setting Up Your Folders
Press Windows+E and locate the Driver you would like to play Skyrim from, for example "C:\" or "D:\". Ensure that you have enough space for the list (750+ GB). You want to create 4 folders on the *root* of the drive (Here C:\).

C:\NYA

C:\wabbajack

C:\ModDownloads

C:\SkyrimGAME

If you already have a folder on your PC which has mods from another modlist such as Eldergleam or your own collection, you can use this one instead of "C:\ModDownloads". However, make sure it is easily accessable via Wabbajack by having it placed on the root of the drive.


You then **need** to *exclude* these folders completely in all of your Antivirus Programs, even if it is just Windows Defender. You should also disable or uninstall any third-party antivirus to avoid issues with usvfs_proxy_x86.exe.

## Manual Downloads
Wabbajack has issues downloading some mods which are not found on Nexus. This means you *need* to download a portion of the modlist manually before you begin.

Make sure that every single digit matches for the downloads, because there are many mods which have slightly different versions. These mods must be placed into your mod folder "C:\ModDownloads". For **Mega Downloads**, *always* right-click > Standard Download, or they will not be recognized properly by Wabbajack.

[Manual Download List](https://github.com/Millionsfrost/N.Y.A-NSFW-Modlist-Skyrim/blob/main/Downloads.md)


## Steam Settings
*Disable Steam Overlay*. Right-click on Skyrim Special Edition in your Steam > "Properties" > "General" > untick "Enable Steam Overlay while in-game". 

*Set Game Language to English*. Right-click on Skyrim Special Edition in your Steam > "Properties" > "Language" > select English.

*Change Updating Behavior*. Right-click Skyrim Special Edition in your Steam > "Properties" > "Updates" > change "Automatic Updates" to "Only update this game when I launch it". Disable Steam Cloud as well.

After you have completed these steps, you will need to add a new library on the root of your drive so that Skyrim is **not** installed to Program Files (x86). We already made a folder for this earlier here: "C:\SkyrimGAME". To make this a Steam library, you need to click on Steam (top left of your Steam) > Settings > Storage > click the tab at the top > "Add Drive". From here, locate C:\SkyrimGAME *(or whatever you named it)* and select this as the folder. 

It seems that Steam has issues when it comes to adding more libraries to the same drive, so in the case that it does not create a new library for you, you can try to follow the steps listed here: [Changing the default install folder](https://steamcommunity.com/discussions/forum/1/3395163747110198261/#c3395163747110912094).

## Clean Your Skyrim Installation
If you already have Skyrim Special Edition (with AE) installed, right-click on Skyrim Special Edition in your Steam library, click Properties > Local Files > Browse. Keep this explorer tab open and *uninstall* your Skyrim through Steam. If any files remain in the explorer, make sure to delete them. Following this, locate %localappdata% and delete the Skyrim folder. You must also delete the Skyrim folder in Documents\My Games.


Reinstall Skyrim Special Edition in a dedicated folder on the root of a drive, e.g., C:\SkyrimGAME.


Start the game to create registry entries and default config files. Make sure you do not alt-tab while the Creation Club content is installing. To avoid issues down the lines, also go into Creations menu and install all owned Creation Club content. Then close the game.

After you have done this, you need to make sure to download Creation Kit for SE. This must be installed to the same Steam Library as your Skyrim *(for example "C:\SkyrimGAME")*.

![alt text](https://i.imgur.com/KrIDlCk.png)

## Installing via Wabbajack
If you have completed **all** steps above, you can now begin to download N.Y.A through Wabbajack! For this, you naturally need to have [Wabbajack](https://www.wabbajack.org) installed *(into C:\wabbajack which should be excluded by antivirus)*.


You need to log into Nexus within Wabbajack by clicking the Gear at the top before you begin your installation. Set the install location to an empty folder on the root of a drive, such as C:\NYA, and downloads to something like C:\ModDownloads. Note that you should usually tick the "Overwrite" if it is available.


If you encounter any issues during the installation process, consider going through the steps of the ReadMe once more. If you still cannot figure out what the problem is, please refer to the [Frequently Asked Questions (F.A.Q.)](https://discord.com/channels/1201567388248834108/1257432068250669096/1257432068250669096) in the Discord.


# Post Installation

Once you get into the game, listen to the Announcer in the Main Menu for more Explanations. If you skip the Main Menu you are in the Starter Room, wait 30 seconds or until mod notifications in the top right have disappeared Press Escape and open up the MCM Menu go to Skyrim Unbound and Configure your starting options and Click Lets go when finished. 

Make your character. Once you finish your character, follow the Instruction on the Prompt. Another Prompt will tell you that everything is finished, but you still should wait atleast 1 Minute in the Room before you press Enter to start your Game!

<ins>**MIDDLE-MOUSE CLICK THE BELOW IMAGES TO PLAY THE RESPECTIVE VIDEOS**</ins>	

<ins>N.Y.A NSFW Modlist Tutorials. Bodyslide and General Information
[![IMAGE ALT TEXT](https://i.imgur.com/RTx5nj8.png)](https://www.youtube.com/watch?v=1dPJON9KIe4 "N.Y.A NSFW Modlist Tutorials. Bodyslide and General Information")

<ins>NYA Character Creation and MCM Tutorial</ins>	
[![IMAGE ALT TEXT](https://i.imgur.com/VxINNNU.png)](https://www.youtube.com/watch?v=PhWjJdBLcO4 "NYA Character Creation and MCM Tutorial")

***There is a good chance that the game may crash on character creation. It is a known issue and being investigated. Do not report it in a bug report.***
***The same goes for starter room crashes.***

<ins>Things you want to know for N.Y.A 6.0</ins>	
[![IMAGE ALT TEXT](https://i.imgur.com/a5mk6CG.png)](https://www.youtube.com/watch?v=szeUFI5vGAY "Things you want to know for N.Y.A 6.0")

### Manual Settings:

In the Sexcraft MCM you can change your Sex Key. Normally its Z for me, Y for Americans i think. Pressing Z will initiate Dialogue and Masturbate, holding Z is surrender to initiate Scenes with Enemies. Later when you get more Perks you can also click Z to steal Stuff in the Act and hold Z to drain Enemies.

### [N.Y.A Custom Background System](https://docs.google.com/spreadsheets/d/1tfuKo3nGhs8_owsJUz-d7d7Cb3du-Hd1Q6CmiLBWMFc/edit?usp=sharing) ( Class Mod but its called Backgrounds bcs its not Classes but if i say Classes you wont think its a Wallpaper Backgrounds Mod or something like that lmao )

1. How to Use "Legends of the Forgotten Paths" to Choose Your Background
Open the Book
Locate and open the book titled "Legends of the Forgotten Paths". Reading it will grant you a spell called "Journey's Genesis".

2. Learn About Backgrounds
As you flip through the book, take some time to review the available backgrounds. Consider which one fits your character best.

3. Equip the Spell
After deciding, go to your Powers menu, find the spell "Journey's Genesis", and equip it.

4. Activate the Spell
Cast the spell. A message box will appear, allowing you to browse through the list of backgrounds.

5. Choose Your Background
Scroll through the message box until you find the background you want. Once you're sure, select it to apply the background to your character.

Note: Be careful with your choice! After selecting a background, the spell "Journey's Genesis" will be removed from your inventory, and you won’t be able to change your background later.

### ENB Information

N.Y.A 6.0 now uses a customized version of Cabbage ENB with Sswaye's ReShade. 3 ReShade presets are available to choose from. Do not change the ENB or alter the ENB settings.
![alt text](https://i.imgur.com/YhDDnm3.png)

### Beth Pie

<ins>**DO NOT USE BETH PIE EVER! THIS WILL BREAK THINGS IN THE LIST!**</ins>	

## NOTE:
DO NOT USE VANILLA as A START

### Survival Mode
Do not use Survival Mode. It has been reported that with Survival, there are many freezes and issues causing the game to stop working.

## Buttons

Please open as Fullscreen in your Brower or download the Picture.
*Note* that Vermillion is left-handed so you may need to change your mouse buttons back to right-handed if they are not changed before an update.

![alt text](https://i.imgur.com/pUlMzvk.png)


### New Combat Animations

There is a new trader in Riverwood named Scarlet who sells rings and custom weapons that unlock animations.
![alt text](https://i.imgur.com/fFk3Hsy.png)

## Extra Buttons not on Picture:

### Lazy Item Hider

Lazy Item Hider - Toggle helm weapons and more. When you equip a Helm now, it automaticly hides when you put your Weapon away. This Mod has an MCM and is highly adjustable. You can hide all Kinds of Things like Weapons etc etc, even use a Hotkey or dont use Auto hide. Its all on you. I only set it up for Heads so its not so intrusive. Normally the manual way is right Shift, but you should be able to set it up later ingame after you are in the Gameworl, set it up as you see fit.


## Obody HotSwap Collisions

We now use OBody HotSwap - CBPC presets for OBody, meaning and i quote from the Authoe " The same thing CBPC CCC does (and something extra), but for all supported presets you load via OBody.
In few words, if the preset is included in CBPC CCC's supported list then it can get its own custom collisions, tuned to the shape of that body. The "something extra" is to not only allow collisions but custom bounce configs as well.
Supported Body Presets atm are the following:

D-sney Mommy - 3BA Edition - Bodyslide Preset
Pomona Amphora Bodyslide Preset for CBBE-3BA-3BBB and BHUNP
Elven Supremacy Preset (CBBE 3BA)
My Lovely Body - Sexy Beauty - CBBE 3BA Bodyslide Preset
Diamond Body 3BA - Bodyslide Preset
Lovely Lady - 3BA (3BBB) CBBE Bodyslide Preset
My Sensual Body - CBBE 3BA Bodyslide Preset
Ceres Deluge BodySlide Preset for 3BA BHUNP CBBE COCO 3BBB
Greek Goddess - Bodyslide and Racemenu Preset - CBBE-3BA-3BBB
Demonic Bodyslide Preset CBBE 3BA and BHUNP Nemesisoll post
The Luscious Body - CBBE 3BA Bodyslide Preset
Dominion Body (3BA preset)
Sonderbain's Waifu Bodyslide - Kaisel 3BA
THE P3ACH -CBBE Preset-
3BA) Temptations Body (Nude)
(3BA) (SDZ21) The Shape of Warrior (Nude)
(3BA) CurvyBreton
(3BA) Velma
(3BA) CBBE Body Special DW Preset 1 Female

Edit: Ceck HotSwap Modpage for Compability.

I also added them into the Obody Preset thingy, so basicly NPCS can only get these Presets applied to them. All the other Presets are basicly only applicable manually, or for the Player. Check out Obody HotSwap to learn more! More Presets will be added every Week.


### SexLab+
This list uses SexLab+ aka P+, a newer version of SexLab.

### Pandora Animation Behavior Overhaul:
If you decide to mod the list and need to rerun Pandora, ensure to delete the meshes folder before running.
![alt text](https://i.imgur.com/iNCJVVC.png)

## Simple (Ultra)wide Guide


Basic ultrawide setup
1) Reinstall Edge UI selecting 21:9, on the patches select all Non-Automated Patches, leave rest unchanged. 
2) Grab EdgeUI C.O.C.K.S 21-9 fix https://www.nexusmods.com/skyrimspecialedition/mods/136604
3) Install it and put at the end of load order
4) Optional Grab and install Widescreen Scale Removed put at the end of load order too, should fix some minor issues with scaling. https://www.nexusmods.com/skyrimspecialedition/mods/136793
5) Grab Configurable Notification Messages https://www.nexusmods.com/skyrimspecialedition/mods/65573
6) In game use MCM menu to align notifications position
7) ?????
8) PROFIT


## - Optional Mods - (included in N.Y.A)
If you want to activate the Halgari RPG Loot mod *(adds custom enchantments to gear distributed throughtout the world, but also increases initial load time)* ensure to place the ESP in the plugins list under the NYA Backgrounds plugin.


