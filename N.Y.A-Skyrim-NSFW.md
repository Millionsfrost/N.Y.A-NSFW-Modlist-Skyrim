# N.Y.A NSFW Modlist Version 3.0+
Welcome to the N.Y.A Modlist! This comprehensive mod compilation aims to enhance your Skyrim experience with a plethora of exciting features that are not explicitly centered around adult content, though they are *certainly* included.

![alt text](https://i.imgur.com/LLmFq2o.png "N.Y.A Poster Image")

## ATTENTION
*This content is intended for individuals who are of legal age in their respective countries. By accessing or using this material, you confirm that you meet the age requirement to view adult content. If you are not of legal age, please exit immediately.
Please be aware that it is your responsibility to comply with local laws and regulations regarding age restrictions.*

 
Before posting a new support request in #unmodified-support or #modified-support, **please check our [Frequently Asked Questions (F.A.Q.)](https://discord.com/channels/1201567388248834108/1257432068250669096/1257432068250669096)** on the Discord, and *ensure you have read the ReadMe properly* (you are here).

[Community Discord](https://discord.gg/V38xZ6CtzQ)

[Alternative Google Docs F.A.Q.](https://docs.google.com/document/d/1GPxGqeynqwNBjkZXYeFkhIO0hDv_lxKF3E8MEFg-EcA/edit?usp=sharing) (outdated)

# Pre-installation Steps
Before you install the modlist, there are some very important steps you need to take in order for a smooth installation process as well as a more seamless experience in-game.
Before diving into the modlist, it's essential to prepare your game environment. These pre-installation steps will help ensure a smooth installation process and a more seamless experience in-game. Follow **all** guidelines carefully:


## Requirements
Verify that your system meets the recommended requirement for running the modlist. Having a "worse" computer than this will not stop you from playing, but being below these requirements will likely result in performance issues.

![alt text](https://i.imgur.com/6nJCmTo.png "Logo Title Text 1")

#### Page File and Shader Cache
You will need to manually increase your page file as well as increase the size of your shader cache in order to avoid performance issues, even if you have a monster PC.

To increase your page file, press Windows+R and enter **systempropertiesadvanced** into it. Under "Performance", click "Settings..." and swap to the Advanced tab. Here you want to click "Change" under virtual memory.


Uncheck "Automatically manage..." and select your fastest SSD in the list of drives. Check "Custom Size" and set **Initial Size to 20480** and set **Maximum Size to 40000**. Now press "Set" and then APPLY before restarting your PC.


Increase the shader cache size via Nvidia Control Panel to at least **10GB**. For AMD users, similar steps might apply.



## Microsoft
Download the latest x64 version beneath "Visual Studio 2015, 2017, 2019, and 2022" for [Microsoft Visual C++ Redistributable Packages](https://learn.microsoft.com/en-us/cpp/windows/latest-supported-vc-redist?view=msvc-170).

You are also going to need to download and install [.NET runtime](https://dotnet.microsoft.com/en-us/download).



## Accounts
You need an account on [Nexus](https://www.nexusmods.com). Premium is recommended to avoid having to manually click the download button for an entire day or so.

You will also need an account on [Loverslab](https://www.loverslab.com). You will have to log in for manual downloads (a step later on), and you might need to log in to Loverslab inside Wabbajack once the modlist download actually begins.

![alt text](https://i.imgur.com/zvSoCH9.png)

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

Once you get into the game, Wait 30 seconds or until mod notifications in the top right have disappeared Press Escape and open up the MCM Menu go to Skyrim Unbound and Configure your starting options and Click Lets go when finished. 
Make your character. Once you finish your character, follow the Instruction on the Prompt. Another Prompt will tell you that everything is finished, but you still should wait atleast 1 Minute in the Room before you press Enter to start your Game!

Now you can press enter and spawn in the gameworld. Then proceed to watch my Youtube video https://www.youtube.com/watch?v=pplMle5Tyd4&lc=UgxL2oGjoPVjsJft_5J4AaABAg for additional MCM settings not covered by the automatic MCM setup.


We also got Fill her up working again. In Sexlab MCM under Extra Effects you wanna change the option to Seperate Orgasms. Then Fill her up works again!

### Manual Settings:
Set CompassCheat to 1. Then save, quit Skyrim, and reload your save. (If you want the compass back, the lore-friendly way is through Campfire Perks.)

Later in the game, you can open the Int. Voiced Dirty Talk. Under Assign Voice, pick Voice Slot 1. Then a new screen opens. On the right side, manually enter the name of your character (beware of typos). In the top right, you can listen to samples. Under Assign Voice as Default, pick Voice 2 for females and for the male one, you can pick 1-8. Keep in mind this is an alpha patch, so not everything might work 100%. Dialogue options don’t work yet. You can also ignore all this and just don’t use this feature if you don’t like voices during scenes. This mod also has moaning and such, so you might want to use it. You can fiddle around with it as you want. Normally its setup correct if you are female but it cant hurt to double Check.

Setting Default Male Voice to Slot 0 in IVDT removes male orgasm sound from female Scenes.

In the Sexcraft MCM you can change your Sex Key. Normally its Z for me, Y for Americans i think. Pressing Z will initiate Dialogue and Masturbate, holding Z is surrender to initiate Scenes with Enemies. Later when you get more Perks you can also click Z to steal Stuff in the Act and hold Z to drain Enemies.

## NOTE:
DO NOT USE VANILLA as A START

### Survival Mode
Do not use Survival Mode. It has been reported that with Survival, there are many freezes and issues causing the game to stop working.

## Buttons

Please open as Fullscreen in your Brower or download the Picture.

![alt text](https://i.imgur.com/WvtxOCx.png "Logo Title Text 1")

## Extra Buttons not on Picture:

### Equipment Toggle

This mod will hide certain Slots on your Body with 2 Hotkeys.

Left Arrow Key = Armors Pieces, like Quivers and such. Works for NSFW Scenes

Right Arrow Key = Weapons , like Bows, Right handed Weapons etc. Also good for NSFW Scenes.


### SexLab+
This list uses SexLab+, a newer version of SexLab.

### Note:
Sexlab+ and Pandora are in an Beta and Alpha state, so some features dont work perfectly yet.


## Simple (Ultra)wide Guide


Following are the steps for both 21:9 32:9.

https://www.nexusmods.com/skyrimspecialedition/mods/127233?tab=description

Grab this Mod and put it at the Bottom and boom you are done.

