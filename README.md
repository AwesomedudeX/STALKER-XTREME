# STALKER XTREME

This is my modded configuration of **S.T.A.L.K.E.R. Anomaly** - a *free*, *standalone* mod in the **S.T.A.L.K.E.R.** game series. This configuration features **G.A.M.M.A.** (*Grok's Automated Modular Modpack for Anomaly*), which is currently the largest and most popular modpack for **Anomaly**.

***JOIN THE S.T.A.L.K.E.R. G.A.M.M.A. DISCORD SERVER:*** *https://discord.gg/stalker-gamma*

**MAKE SURE TO FOLLOW THE INSTALLATION THOUROUGHLY** - if you don't, you may not achieve the expected results, or the game might not run properly altogether.

Good luck with this **hardcore** setup - it features a *Cold System*, a *Stressful Zone* mod that affects your *psy health*, individual *limb health*, complex (yet comprehensive) *item repairs*, and **much**, much more.

I hope you have fun with this - this took a while to make, so I'd appreciate some support or feedback where possible. If you have any problems, you can contact me for help and I'll do what I can to assist you. You can contact me via Discord Direct Messages at *AwesomedudeX*.


# Required/Recommended PC Specs

Note: Required specs are necessary for the game to be remotely playable with all the default mods, whereas recommended specs will run a up to **30FPS** in most areas, and will achieve up to **60-70FPS** in less demanding areas, like the *Truck Cemetery*, or up to **100-120FPS** in the *Fake Start* testing zone, which can be accessed by pressing **F2** from the main menu.

**Storage**: 200/250GB or more

**RAM**: 8GB DDR4/16GB DDR5 or more

**VRAM**: 4GB GDDR5/6GB GDDR6 or more

**CPU**: Intel Core i5-10400F/Intel Core i7-11800H or better

**GPU**: GTX 1650/RTX 3060 or better

# Recommended Graphics Settings

I highly recommend using a resolution of 2K or higher for this, as anything lower can lead to noticeable pixelation in foliage. If you are not playing on 2K, make sure to disable **Tactical Fonts For Anomaly 2K**, and enable 
**Tactical Fonts For Anomaly 4K** if you are playing on 4K. I also recommend using the **user.ltx** file inside of the **Settings Presets.7z** file, as these are my recommended controls and graphics configurations for this modpack.


# Installation:

To download and set up my configuration, you will need to download the necessary files for the installation. The process is fairly easy, though there is one (very) time consuming step in the process. All installation instructions are in the ***instructions.txt*** file, inside of the ***Settings Presets*** file. The files you will need are below. If you want the regular ***mods.7z*** file - which has all the mods already installed - instead of the ***modsOptimized.7z*** file - which has a lot of G.A.M.M.A. mods removed to optimize file size (and therefore requires use of the launcher to install the remaining files, which can take a while), then you can send me a message on Discord and I'll get you the file when possible.

To start, create a folder called "STALKER", and open it. Once inside, create a folder called "Anomaly". This will store all of the base game files, and is playable on its own, but tends to be much more enjoyable with mods.


## Anomaly Files:

Before you start, you will need STALKER Anomaly 1.5.3; to get it, just download this file:

***STALKER Anomaly 1.5.3***: https://www.moddb.com/mods/stalker-anomaly/downloads/stalker-anomaly-153

Once it's done downloading, open it in 7zip (download at https://7-zip.org/download.html), and drag and drop **ALL** of the contents of the Anomaly 1.5.3 file into your Anomaly folder. After that, run the Anomaly launcher, enable the "Delete shader cache" box, select your display settings and launch the game. Once the main menu loads, close the game - running the game was just to have STALKER Anomaly generate the folders and files neccessary to run and modify the game.

You'll also need the latest Demonized Modded Exes so that you can run the mods in this modpack. To get it, go to this link:

***Demonized Modded Exes***: https://github.com/themrdemonized/xray-monolith/releases

Once on the page, click on the latest STALKER-Anomaly-modded-exes.zip file to download it. After that, open it up in 7Zip and drag and drop **everything** in it to the Anomaly folder - replace the files when prompted.

## GitHub Files:

This file is located inside of this repository. To download it, open the file here (or go to the link posted below) and click on the download icon on the right side of the toolbar to download the file.

***Settings Presets.7z*** - https://github.com/AwesomedudeX/STALKER-XTREME/blob/main/Settings%20Presets.7z (includes all graphics, controls, atmospheric, ReShade, MCM and MO2 settings that are used in this modpack)

## Google Drive Files:

These files are located on Google Drive. To download them, just click on the download links associated with each one and click "Download anyway" on the page that pops up.

***modsOptimized.7z*** - **CURRENTLY UNAVAILABLE** (contains most of the mods in this modpack, as well as the Mod Organizer 2 mod configuration files)

***Large Mods.7z*** - *https://drive.google.com/uc?export=download&id=1VmO9DNia2yNczylKNhxS-jlhZMhvDFT0* (contains the largest mods in this modpack, and those related to them)

***XTREME Graphics*** - https://drive.google.com/uc?export=download&id=1fVCSxj7zW2-KlWqC914hreSKS9ULbSj_ (contains the main graphics mods for this modpack compressed into a single mod - delete shader cache and use `cfg_load xtreme` in the game console after installation)

 - Copy the ***XTREME Graphics*** link **with** the underscore at the end ("**_**") and paste it into your URL bar - GitHub thinks it's not part of the link, but it is.

## GAMMA RC3.7z File:

The download link for this file can be found on the S.T.A.L.K.E.R. G.A.M.M.A. Discord Server, but you can also get it here: https://www.mediafire.com/folder/agyul0e6fbban/STALKER_GAMMA


# Performance Tips

## Mod Configuration Menu:

- Lower shadow quality - **Small Impact**
- Lower reflection quality - **Small Impact**
- Lower/disable volumetric light settings in *SSS* - **Medium Impact**

## Base Game Settings:

- **IN THE LAUNCHER:** Lower the shadow map resolution - **Medium Impact**
- Disable or set SSAO to SSDO (less intensive option) - **Small Impact**
- Lower/disable volumetric light settings
- Lower render distance settings - **Medium Impact**
- Lower grass density/size and/or render distance - **Medium to Large Impact**
- If all else fails, lower your game resolution (make sure it matches your screen aspect ratio; most common is **16:9**) - **Large Impact**


# Base Game Information

...


# Gameplay Information

## Cold System

Your STALKER now can get cold, and beyond a certain point, they begin to get a fever. Their temperature - and how it changes - is determined by **environmental factors** (such as wind, time of day, weather and location), **protection factors** (such as clothing type - light, medium, heavy or scientific - and campfire proximity - if you are in range of a campfire, it will warm you up) and the STALKER's **current temperature**. This mod has been implemented with some adjustments of my own, but feel free to check out the original mod at https://www.moddb.com/mods/stalker-anomaly/addons/cold-system-01. The HUD shows as a blue **cold bar**, with two lines on it; the purple line shows the **fever threshold** - when you will start to get a fever - and the red line shows the **critical cold threshold** - when your STALKER is starting to die from hypothermia. The goal is to keep your STALKER's **cold level** as low as possible, by staying inside during rainstorms or at night, warming up near campfires, wearing good clothing and eating and drinking warm items.

Certain items can affect your **cold level**. Artifacts can give you protection from (or negatively influence) your **cold level**. Also, mutant meals, as well as vodka, beer and certain other drinks can also influence your cold level. The way they influence it is shown at the top-right of their description popup, with blue text indicating a cooling effect, and red text indicating a warming effect. Make sure to have warming items on hand when possible to ensure you can keep your STALKER's temperature up in cold weather.

## Stressful Zone

...


# My Keybinds

## Movement Keybinds:

**W**: Move forward

**A**: Move left

**S**: Move back

**D**: Move right

**SPACE**: Jump

**C**: Crouch

**CTRL**: Toggle low crouch (from standing, will put you in a low crouch when **C** is pressed, or will put you in a low crouch if you are already crouching

**Q**: Lean left

**E**: Lean right

**X**: Freelook


## Health Keybinds:

**H**: Cycle health view

**7**: Show **Cold System** HUD (information on this in **Gameplay Information**)


## Inventory Keybinds:

**TAB**: Open inventory

**RIGHT-CLICK**: View more item options

**SHIFT**: Quick-move (if you have opened a container) **OR** drop item - hold this key to drop/move items you are hovering on, and move your mouse over other items to drop/move them as well

**SHIFT**+**LEFT-CLICK**: Quick-move **ALL** items (or pick up a **stash**)


## Weapon & Equipment Keybinds:

**LEFT-CLICK**: Shoot

**RIGHT-CLICK**: Aim

**1**: Primary weapon (right large equipment slot - this is structured this way for some reason, but it's not a very big deal, so I wouldn't bother about it)

**2**: Secondary weapon (left large equipment slot)

**3**: Sidearm/Knife (bottom-left small equipment slot)

**4**: Knife/Binoculars (top-left small equipment slot)

**5**: Alternate aim toggle

**6**: Bolt/empty round casings (left square equipment slot)

**8**: Show radiation counter (mSv)

**9**: Attach/Detach suppressor (if you have one for your currently equipped gun)

**RIGHT-CLICK (hold)**, then **LEFT-ALT**: Point-aim (if you have a lazer) / Underbarrel grenade launcher (if you have one)

**CAPS LOCK**: Detector/Glowstick (upper-bottom-right small equipment slot)

**LEFT ALT**: Toggle quick select wheel (use number keys or scroll wheel to navigate; default is magazines/ammo types)

**RIGHT ALT**: Clean mask (when applicable)

**R**: Reload (if you have a corresponding magazine that was designated to your loadout - RIGHT-CLICK+"add to loadout" to add a magazine to your loadout)

**V**: Cycle firemodes (hold to check firemode)

**Y**: Unjam weapon (or inspect if your weapon is either super-jammed or not jammed - see **Gameplay Information** for more information

**B**: Toggle weapon position (low ready/firing position)

**G**: Grenade (right square equipment slot)

**M**: PDA device - Personal Digital Assistant (lower-bottom-right small equipment slot)



**F1**: Quick-use item 1

**F2**: Quick-use item 2

**F3**: Quick-use item 3

**F4**: Quick-use item 4


**U**: Take off/put on most recent **gas mask**

**Z**: **HOLD** to toggle lazer, **PRESS** to toggle headlamp (for **BOTH**: will only work if you have one)


## HUD/Menu Keybinds

**ESC**: Pause game/Exit current menu

**F5**: Quicksave

**F7** Debugger

**F9**: Load last quicksave

**F10**: Toggle minimap

**F12**: Screenshot

**`**: Console (command entry)


**K**: Show skills

**I**: (**HOLD**) Show current objective

**T**: Companion wheel


**0**: Random shout

**P**: Random comment


**ENTER**: Start/stop radio

**RIGHT-SHIFT**: Start/stop personal audio player

**'**: Cycle channel/playlist


**UP**: (**ARROW**) Volume Up

**DOWN**: (**ARROW**) Volume Down

**RIGHT**: (**ARROW**) Next track

**LEFT**: (**ARROW**) Previous track


**NUMPAD1**: Toggle combat mode (ignore combat/fire at will)

**NUMPAD2**: Toggle movement mode (wait here/follow me)

**NUMPAD3**: Move-to-point (**HOLD**, look at a point and **RELEASE**)

**NUMPAD4**: Toggle stealth/sover mode (stealth/stop stealth)

**NUMPAD5**: Toggle looting mode (loot corpses/don't loot)

**NUMPAD7**: First-person view

**NUMPAD8**: Third-person view (locked+close)

**NUMPAD9**: Third-person view (free+far)

**NUMPADENTER**: Toggle HUD


**\***: Item animations

**LEFT ALT**: Ammo selector (when the Quick Access Wheel mod is disabled)
