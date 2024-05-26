![alt text](https://i.imgur.com/LLmFq2o.png "Logo Title Text 1")
First things first: this list contains adult content, and you must be of legal age in your country. This means 18+ in most countries, 21+ in others. It is up to you to be sure of the age requirement in your country.
Support and general talk about N.Y.A you can find on the following Discord: https://discord.gg/V38xZ6CtzQ


#### N.Y.A Mod List Version 2.0+
This list contains adult content, so you must be of legal age in your country to access it. In most countries, this means 18+, while in others, it’s 21+. Please ensure you meet the age requirement in your country.

The NSFW elements in this list are designed to be non-intrusive. NPCs will not be seen in overly revealing armor, and you won't encounter unwanted interactions like those in mods such as Troubles of Heroine. This version of N.Y.A runs on Skyrim version 1.6.640, and Wabbajack will automatically handle the downgrade for you. However, you will need the Anniversary Edition and the latest Skyrim version from Steam.

The mod list includes over 2,300 mods, resulting in a total size of over 650GB when downloaded and installed. A performance version is also available in the downloads folder for those looking to optimize performance. To save FPS, you can use the console command tg to remove grass.

We utilize the Pandora Behavior Engine, eliminating the need for Nemesis or FNIS. The list features over 110 monster mods and more than 30 combat mods. We use MCO + MCO Dodge and Stances, a system where each weapon type has four different animation sets. With the additional attack button, each weapon has a special attack. Additionally, you can purchase over 100 unique special attacks to customize your fighting style.

There are over 100 armor and clothing mods, comprising more than 2,500 individual pieces. These modded items can be found in chests throughout the open world. Unique bosses drop exclusive items upon defeat, adding an extra layer of challenge and reward.

Every possible graphical element has been enhanced. We use the Picho ENB to ensure the best visual experience. Explore a transformed Skyrim with this comprehensive mod list, blending enhanced gameplay, stunning visuals, and unique content to create an immersive and captivating experience.



#### N.Y.A-NSFW-Modlist-Skyrim

Release Beta Test Version of N.Y.A. The List runs on 16640 Version. AE on its own.
You still need latest Skyrim Version + AE Content. You get the AE Content when you start Vanilla and Download it all at least once.



#### Accounts

In terms of accounts you will need a Nexus Account. Premium would be best to prevent needing to manually click download many times and get faster speeds.

ALSO WARNING: You can't login anymore into Loverslab in the Wabbajack Settings. You have to do it now when the first Loverslab Mod pops up, you need to login over the Windows that pops up. If it works for you first time, good, if not only Login then restart the Install.


#### Manual Downloads

Wabbajack has bugs downloading some mods. Please download these mods manually before downloading the list with Wabbajack. Otherwise, you are likely to encounter confusing errors in Wabbajack.

List of mods: https://github.com/Millionsfrost/N.Y.A-NSFW-Modlist-Skyrim/blob/main/Downloads.md

When downloading mods from Mega, always right click > Standard Download. Mega defaults to its "Download as ZIP" option will means it recompresses already compressed files and Wabbajack won't be able to recognise the download.
After downloading the non-Nexus mods, put them all into the folder you'd like the rest of the N.Y.A downloads to be stored in. If you have an existing Skyrim mods downloads folder from other modlists or your own modding, use that as you might have mods N.Y.A needs already, meaning you won't need to download those mods again.



#### Preparation

Install Microsoft Visual C++ Redistributable Packages
This package is a must as it is needed by MO2 - you may already have it if you've used MO2 before. If you do not have it, you want to download the x64 version under "Visual Studio 2015, 2017 and 2019".



#### Download Visual C++ Redistributable Package and the Thing underneath it.

Also get the Thing underneath, i think it was needet for Sexlab+.

https://dotnet.microsoft.com/en-us/download/dotnet/thank-you/runtime-desktop-7.0.15-windows-x64-installer



#### Setup your Page File

Skyrim modlists need a large amount of memory purely because of the amount of stuff in them - especially modlists on the larger side or with a lot going on. For the best experience, you should setup a pagefile of at least 20GB - yes, even if you have a million GB of RAM. To setup your pagefile;

Hold down the LEFT Windows key and press R
Type in systempropertiesadvanced in the run box and then press ENTER
Under the "Performance" option, click the "Settings..." button
Switch to the "Advanced" tab
Under "Virtual Memory", click the "Change..." button
Uncheck Automatically manage... if it's checked
Select your fastest SSD in the list of drives
Check "Custom Size"
Set Initial Size to 20480
Set Maximum Size to 40000
Press the "Set" button
Press OK
Press APPLY and then OK
Restart your PC to apply the pagefile setting
Setup your Shader Cache
Driver defaults from Nvidia and AMD for shader cache size is limited to 4GB. Being this small can lead to rare crashes in heavily modified out 4 installs. Increasing the shader cache size is done via the Nvidia Control Panel (I assume the same for AMD users is true also but I don't have AMD hardware to check with).

AMD USERS: See this link for some manual tweaks that may or may not help.

Open the NVidia Control Panel
Head to Manage 3D Settings
Scroll down in Global Settings to find the Shader Cache Size option
Set the Shader Cache to at least 10GB
Done

![alt text](https://github.com/iAmMe27/WoD/raw/main/img/ShaderCache.png "Logo Title Text 1")

#### Setup your Antivirus

Before you go down the route of "I don't have an antivirus" - you do, it's built into Windows. You need to exclude your Wabbajack folder and your WoD installation folder from your antivirus' real-time protection stuff as it will likely interfere with your install and worst case, it can remove files, ruining your install. It can and will interfere whilst you are playing too, causing poor performance and obvious stuttering.

Note: If you're using Webroot or any other free 3rd party antivirus it's likely that adding the folders to exclusions will not be enough and you'll need to disable or uninstall your 3rd party AV as they can incorrectly mark usvfs_proxy_x86.exe, among other files, as a virus, a file needed for Mod Organizer 2 to work. We recommend doing so anyway in case it's a free one, as Windows Defender is likely much better at stopping threats than that is (according to data from av-test.org https://www.av-test.org/en/antivirus/home-windows/).



#### Disable Steam Overlay

The Steam overlay is known to cause issues when using ENBs. I recommend you turn it off to be sure that it doesn't interfere in any way, and you can do so by heading into Steam, right clicking on Skyrim Special Edition in your game library and clicking Properties > General > Deselect "Enable Steam Overlay while in-game".



#### Set game language to English

Wabbajack and the modding tools out there only support the English language versions of games. Setting the language to English in Steam will stop issues like Wabbajack file verification failures when installing. As with disabling the overlay, right click on Skyrim Special Edition in your game library and click Properties > Language > Select English.



#### Change Steam's Updating Behavior

If for some reason Bethesda decide to release an update for Skyrim, everything will probably break. Well, not everything but something will definitely break until mods can be updated to suit. To stop this from happening, you need to tell Steam that you only want to update when you tell it to. You can do this by right clicking on Skyrim in your game library and clicking Properties > Updates > Change Automatic Updates to "Only update this game when I launch it". Whilst you're in here, it's also recommended to disable Steam Cloud too.

Clean current Skyrim Special Edition installation
If you have not yet installed Skyrim Special Edition, you can skip this part.

Right click on Skyrim Special Edition in your game library and click Properties > Local Files > Browse.
Uninstall the game via Steam - right click on Skyrim Special Edition in your game library and click Manage > Uninstall.
Check the explorer window for any left over files - if there are any, delete them.
Open Windows start menu/search and type in %LOCALAPPDATA%.
Delete the Skyrim Special Edition folder.
Head to Documents\My Games and delete the Skyrim Special Edition folder.
Install Skyrim Special Edition
Once you've done the steps above, you can now set Steam to download Skyrim Special Edition again but do not install Skyrim Special Edition to a protected folder, such as Desktop, Downloads or Program Files of any kind. It's best to create a new, dedicated folder for it using the Steam Library function somewhere on the root of your drive such as C:\SteamLibrary. A lot of people have a dedicated secondary drive for their games, keeping the OS install separate; using this secondary drive will also work.



#### Start Skyrim Special Edition

That's right - start the game. You need to let the game do its initial start up jobs such as creating registry entries and generating default config files. Once you've gotten to the main menu you can close the game again. Also download all AE Content.



#### Wabbajack

Installing the list is straight forward: Wabbajack will do most of the heavy lifting for you - you only have to tell it where to put stuff.

Set the installation location to a folder on the root of a drive, something like C:\NYA. Do not install it to one of the protected folders as mentioned earlier. The download location will have likely been filled in for you too - ensure it matches the directory you set for the installation location, or if you have multiple Skyrim Special Edition modlists installed, use a common download folder - this will stop you from having to redownload common mods across multiple modlists.

Once you have everything set in Wabbajack, hit GO and let it do its thing. It might take a while as there is a fair bit to download, and the speed of this will depend on your internet performance as well as your CPU in the later stages for hashing and unpacking the downloads.

You can verify your Install here: https://github.com/Oghma-Infinium/Modding-Guides/blob/main/tutorials/Verifying%20your%20Modlist%20Install.md



#### Please read very carefully from here on!!!!!!!!!!!!!!!!!

#### MCM Recordings

In the MCM Menu Skyrim Unbound, press Lets go. When you are done with Character Creation, please click Stay Here. Then go into the MCM Menus and go to MCM Recorder. Please run N.Y.A Nr1 Recording. When everything is finished ( Let Sexlab Install in Peace ) then please click enter and then Continue.

#### IMPORTANT: I removed Sexlab + from the MCM recording bcs the Error doesnt go away. You need to manually install it now on every Name Game and add the 2 Settings: Turn ON ( Disable Victim Controls ) and Turn OFF ( Auto Advances Stages ) Added this to the Readme aswell.
Installing Sexlab is Easy. After the MCM Recording has finished, you just go to Sexlab MCM and click Install. Then you let it do its Thing. After that do the 2 Settings i mentioned above.


#### Post Installation
#### Manual Settings

"Set CompassCheat to 1". Then save, quit Skyrim, and re-load your save. ( If you want the compass back, the lorefriendly way is Campfire Perks )

Please change the Hotkey from the Where are you MCM Menu for opening the Menu. Normal Key is F3 and that interferes with our Stances Mod. So pls rebind that. I use it on Comma Key and it works.

Later in the Game you can open the Int. Voiced Ditry Talk. Under Assign Voice you will pick Voice Slot 1. Then a new Screen opens. On the right side you will manually enter the Name of your Character, beware Typos. In the top right you can listen to Samples.
Under assign Voice as Default you pick Voice 2 for Females and for the Male one you can pick 1-8. Keep in Mind this is an Alpha Patch, so not everything might work 100%. Dialogue Options dont work yet.
You can also ignore all this and just dont use this Feature if you dont like Voices during Scenes. But this Mod also has moaning and such, so i think you wanna use it. You can fiddle around with it as you want.

In the Sexlab+ MCM, activate "Disable Victim Controls" and disable "Auto Advance Stages".

The game defaults to Novice difficulty. You should change this to at least Apprentice for a balanced play through.

SexLab and the key to target enemies are both both to mouse 3 by default. Change SexLab by running "SCConfHotkeySex to XX" in your console where XX is the DX Scan Code, see https://ck.uesp.net/wiki/Input_Script#DXScanCodes


#### WARNING

If your Sexlab+ doesn't get started correct via MCM Recorder, ignore it and do it manually afterwads yourself. Just open it in MCM and click Install.


NOTE: DO NOT USE VANILLA as A START


#### Survival Mode

Do not use Survival Mode. It has been reported that with Survival there are many Freezes and Stuff and your Game will stop working!




#### Buttons

Middle Mouse out of Combat = Masturbation, but also you can try to seduce People while looking at them via your Sexcraft Perk Tree. ( You can change Sexcraft Key via Console Command, how to is on Sexcraft Modpage. )

To change the sex key use "set SCConfHotkeySex to XX" where XX is the DX Scan Code, see https://ck.uesp.net/wiki/Input_Script#DXScanCodes
To enable/disable the curves perk controlling weight use "set SCConfCurvesEnableWeightUpdate to 0/1" where 0 is off, 1 is on (Default is 1)
lots of other settings, see full list at https://www.loverslab.com/files/file/31540-sexcraft-a-speechcraft-overhaul-beta/



ß Button = Free Cam ( Button next after 0, can be adjustet. -> -_ Button = Free Cam ( Button next after 0, can be adjusted. For Sexlab/Scenes.

Middle Mouse = Target Lock

G Button = Quick Light

C Button = Dodge Roll

V Button = Block

< Button = Additional Attack ( Every Weapon Type has a Special Attack, if you equip an Ashes of War, same Button uses that. < Button is left of Y, in US cases Z i think. You can change this in the Additional Attack MCM.

L Button = Hunters Pride ( Turning this on and off lets you interact with downed Enemies, taking actions like capturing them )

ß Button = Free Cam ( Button next after 0, can be adjustet. Lets you go into free Cam in Sex Scene, or well in general. Dont use auto Freecam.


#### SexLab+

This list uses SexLab+, a newer version of SexLab.

You can check for additional SexLab mod compatibility here: https://gist.github.com/MissCorruption/887725102fb18d96d43e26555e008bbb 

I should also mention Sexlab+ and Pandora are in an Alpha State, so some thing Like Orgasms/Sounds, Voices, Seperate Orgasms, Schlong Control Up/Down and some other Thints don't work yet, or don't work that well. I thought i just tell people upfront.
PS: We don't have Intelligent Dirty Talk working atm in an Alpha State aswell.



#### Simple Super Ultrawide (32:9) Guide

Created for N.Y.A
This guide is tailored specifically for 32:9 users. Currently, Edge UI only offers support for 21:9, so follow these steps to optimize your experience for 32:9.

Steps to Set Up:
Download the Required Mod: Untarnished UI - Super Ultrawide Fix by TheWalkyrian

Run the FOMOD Installer, during the installation, select the Quick Loot System EE option.
Disable Conflicting UI Elements:

-Edge UI Wheeler
-Edge UI

These elements will conflict with the setup, so make sure they are disabled.

You're All Set!
After completing these steps, you'll be ready to play with the 32:9 setup. Hopefully, Edge UI will offer support for 32:9 in the future.

