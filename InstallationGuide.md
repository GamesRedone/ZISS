# Z.I.S.S. | Installation Guide
![Alt text](https://github.com/GamesRedone/ZISS/blob/main/Images/logo_installationguide_v1.1.0.png)

<h4 align="center"><a href="https://www.nexusmods.com/skyrimspecialedition/mods/181971">Download</a> | <a href="https://github.com/GamesRedone/ZISS/blob/main/README.md">Read Me</a> | Installation Guide | <a href="https://github.com/GamesRedone/ZISS/blob/main/StarterGuide.md">Starter Guide</a> | <a href="https://github.com/GamesRedone/ZISS/blob/main/CustomizationGuide.md">Customization Guide</a> </h4>

<p align="center">
<a href="https://discord.com/invite/WejTdPFBbk">
<img src="https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white">
</a>
</p>

---

<br><br>This work is licensed under <a href="https://creativecommons.org/licenses/by-nc-sa/4.0/">CC BY-NC-SA 4.0</a><br><br><img src="https://mirrors.creativecommons.org/presskit/icons/cc.svg" alt="" style="max-width: 1em;max-height:1em;margin-left: .2em;"><img src="https://mirrors.creativecommons.org/presskit/icons/by.svg" alt="" style="max-width: 1em;max-height:1em;margin-left: .2em;"><img src="https://mirrors.creativecommons.org/presskit/icons/nc.svg" alt="" style="max-width: 1em;max-height:1em;margin-left: .2em;"><img src="https://mirrors.creativecommons.org/presskit/icons/sa.svg" alt="" style="max-width: 1em;max-height:1em;margin-left: .2em;">

<br>

<a href="https://ko-fi.com/gamesredone">
<img src="https://github.com/GamesRedone/ZISS/blob/main/Images/support_me_on_kofi_badge_beige.png" width="15%">
</a>

<br><br>

## **Navigation**
<br>

- [Introduction](#Introduction)

- [System Requirements](#System-Requirements)

- [Required Game Files](#Required-Game-Files)

- [Other Prerequisites](#Other-Prerequisites)

  - [Required Software](#Required-Software)

  - [Recommended Preparations](#Recommended-Preparations)

    - [Crash Prevention](#Crash-Prevention)

    - [Shader Cache](#Shader-Cache)

- [Installing the List](#Installing-the-List)

  - [Antivirus Exclusions](#Antivirus-Exclusions)

  - [Having problems with Installation?](#Having-problems-with-Installation)

  - [Freeing Up Storage Space (Post Installation)](#Freeing-Up-Storage-Space-Post-Installation)

- [How to update](#how-to-update)

<br>

# **Introduction**

Installation can be completed in as little as an hour or two depending on your internet speed.

While not required, it is highly recommended that your purchase [Nexus Premium](https://www.nexusmods.com/premium). Without it you will have to download each individual mod manually.
<br><br>

:question: [Having Problems with Installation?](#Having-Problems-with-Installation)
<br><br><br>
# **System Requirements**

To get even more frames checkout the [Performance Tweaks](https://github.com/GamesRedone/ZISS/blob/main/CustomizationGuide.md#performance-tweaks) section of the [Customization Guide](https://github.com/GamesRedone/ZISS/blob/main/CustomizationGuide.md).

You may be able to run ZISS at lower specs then the minimum processor and graphics requirements but you will not be able to run ZISS with less then 16 GB of RAM.
<br><br><br>
:warning: ZISS was created to be performance friendly, but you should not expect high FPS *(>60 FPS)* at the minimum specs.
<br>

>*When running at the minimum specs it is recommended to disable any in-game overlays you may use such as [Steam](https://www.wikihow.com/Disable-Steam-Overlay) or [NVIDIA](https://www.wikihow.com/Disable-Nvidia-Overlay) overlays. Also ensure to follow all the steps in the [Recommended Preparations](#Recommended-Preparations) section of the this guide for the best experience. Switching to [Community Shaders](https://github.com/GamesRedone/ZISS/blob/main/CustomizationGuide.md#community-shaders) will also provide better performance and stability overall.*

<br>

| Requirement | Minimum | Recommended |
| :--- | :--- | :--- |
| **OS** | 64-bit Windows 10 or Windows 11 (latest version)| |
| **Processor** | [Intel Core i7-11800H](https://www.cpubenchmark.net/cpu.php?id=4358&cpu=Intel+Core+i7-11800H+%40+2.30GHz) / [AMD Ryzen 7 5800h](https://www.cpubenchmark.net/cpu.php?id=3907&cpu=AMD+Ryzen+7+5800H) | - |
| **Graphics** | [NVIDIA GeForce RTX 3050 Ti Laptop](https://www.videocardbenchmark.net/gpu.php?gpu=GeForce+RTX+3050+Ti+Laptop+GPU&id=4393) / [Radeon RX 7900M](https://www.notebookcheck.net/AMD-Radeon-RX-7900M-GPU-Benchmarks-and-Specs.760883.0.html) | - |
| **Memory** | 16 GB RAM | 24 GB RAM |
| **Storage (Pre-Install)** | ~112 GB SATA SSD | ~112 GB NVMe SSD |
| **Storage (Post-Install)** | ~62 GB SATA SSD | ~62 GB NVMe SSD |

<br><br>
ZISS itself is lightweight and only requires a total of ~62 GB durring installation, and roughly ~36gb post installation. 

> You can delete the downloads folder once the list has successfully and installed to free back up ~26gb. (e.g. `ZISS/downloads`)

Wabbajack requires around 30 GB of extra space on your main drive for temporary and working files during installation and the game files themselves are ~20 GB.

<br><br>

# **Required Game Files**

ZISS requires the [Steam version](https://store.steampowered.com/sub/626153/) of `Skyrim Anniversary Edition v1.6.117` *(The newest version)*

Follow these five steps to ensure you have the correct required game files installed on your system.
<br><br><br>
:warning: If mods are *NOT* downloading and you have already tried the [stuck download/missing archive fix](https://github.com/GamesRedone/ZISS/blob/main/InstallationGuide.md#having-problems-with-installation). OR you are unable to download `Skyrim_Default.ini`, you probably have the wrong game files installed on your system.

<br><br><br>1. **Check what version of the game you own**

  > ZISS utilizes some of the Creation Club content included in the `Skyrim Anniversary Upgrade`<br>
  > So it is required that you purchase either a copy of...<br><br>
  > `Skyrim Anniversary Edition` or the `Skyrim Anniversary Upgrade`<br><br>
  > ...from [Steam](https://store.steampowered.com/sub/626153/) directly, or by purchasing a Steam Product Key.<br><br>
  > G2A offters Skyrim AE product keys at 50%+ off the retail price<br><br>
  > LINKS: [Skyrim AE](https://www.g2a.com/n/gamesredone-skyrim-ae) | [Skyrim AE Upgrade](https://www.g2a.com/n/gamesredone-skyrim-ae-upgrade)<br><br>
  > *These are affiliate links. If you choose to make a purchase after clicking one of these links, I may receive a commission at no additional cost to you. Support from people like you is how I can do what I do, thank you!*<br><br>
  > If your key has been activated on platform other then steam it will not work.

:no_entry: **Pirated copies of the game WILL NOT WORK...**
>*...and I will not tell you how to get them to work.*

<br>2. **Use a fresh install**

>[All mods will be installed completely separate from your Steam installation of Skyrim](https://www.nexusmods.com/skyrimspecialedition/mods/31720), so a fresh install is required to ensure ZISS runs smoothly. This is especially true if you have ever modded Skyrim in the past and have used [ENB](http://enbdev.com/download.html) or [SKSE](https://skse.silverlock.org/) before.<br><br>
>To fully uninstall Skyrim, uninstall through Steam and delete the Skyrim Special Edition folder that Steam was using.<br>As well as the Skyrim Special Edition folder inside `\Documents\My Games`.<br><br>

✋ You can install the game in any location ***EXCEPT*** Program files.
> If you have multiple drives you can simply install it on to the secondary drive. If you do not have a secondary drive you can [follow this guide](https://github.com/LostDragonist/steam-library-setup-tool/wiki/Usage-Guide#step-1-download-the-tool) to install it in a seperate location on your `C:\` drive.<br><br>Do ***NOT*** use an external hard drive.

:no_entry: ***DO NOT* "Verify Integrity of Game Files" through Steam.**
> *If you ever have, or are unsure if you ever have, you should remove fully remove all game files (see step 2), and reinstall the game.*

<br>3. **Launch the game and check that all Creation Club content has been downloaded**
> The game should prompt you to download all Creation Club content included with Aniversary Edition. If for whatever reason you are missing some of the content, or you just want to make sure you have all the content, follow the 3 steps below.

    1. Launch the game and select `"Creations"` from the `Main Menu`.
    2. Access the `Options`, and select `"Download all owned Creation Club Creations"`.
    3. The Creation Club content you are missing will now download, this may take some time if you are missing a lot of the content.

:no_entry: ***DO NOT* tab out during the download**
> *Some files may be skipped, or the download may get stuck. If it gets stuck, close the window and follow the 3 steps above.*

🔍 **Check your `Skryrim Special Edition\Data` folder to ensure you have the correct version of these files :**<br><br>
**`ccBGSSSE037-curios.esl` and `ccBGSSSE037-curios.bsa`**
> The version you need must be spelled with a ***LOWER CASE*** `c` (e.g. `ccBGSSSE037-curios.esl` ***NOT*** `ccBGSSSE037-Curios.esl`)<br>
> If you have the wrong version, delete these two files, launch the game, select `"Creations"` from the `Main Menu`, search for `Rare Curios` and download.

<br>4. **Stop Steam from automatically updating**

  > From here on out you should *NOT* launch the game through Steam.<br><br>
  > Select `"Only update this game when I launch it"` within Skyrim's Steam `Properties`.<br><br>
  > Right click `The Elder Scrolls V: Skyrim Special Edition` in your Steam `Library` > `Properties` > `Updates`

<br>5. **Ensure the language is set to English**

  > Unfortunately the only language I speak is English and there are major differences between the game versions. Apologies to all the those non-English speakers out there.<br><br>
  > Select `"English"` within Skyrim's Steam Properties.<br><br>
  > Right click `The Elder Scrolls V: Skyrim Special Edition` in your Steam `Library` > `Properties` > `General`

<br><br><br>
# **Other Prerequisites**

<br>

## ***Required Software***

Ensure the following software is installed and up to date. The links below are direct download links.

- [x64 .NET 8 Desktop Runtime](https://dotnet.microsoft.com/en-us/download/dotnet/thank-you/runtime-desktop-8.0.28-windows-x64-installer) | Desktop Runtime 8.0.28
- [x64 Microsoft Visual C++ Redistributable for Visual Studio](https://aka.ms/vc14/vc_redist.x64.exe) | Latest supported v14

<br>

## ***Recommended Preparations***

These preparations are not required but will ensure you have the best overall experience.
<br><br>

### **Crash Prevention**

As of v1.0 ZISS is stable, but just like many other large mod lists,  ZISS requires a lot of memory. Sometimes if there isn't enough memory in the moment it is needed a memory-related crash will occur, typically in the form of `"EXCEPTION_ACCESS_VIOLATION"`
<br><br>
In order to prevent this from happening, you can create virtual memory by increasing your pagefile size.

1. Press `"Win + R"` and enter `"sysdm.cpl ,3"`
2. Go to `Advanced tab > Performance Section > Settings`
3. In the new window, go to `Advanced tab > Virtual Memory section > Change...`
4. Disable `Automatically manage paging file size` for all drives
5. Select your disk drive, ideally your fasted SSD Under the Custom Size: option, change `Initial Size (MB)` and `Maximum Size (MB)` to `"20480"`
6. Click `Set`
7. Click `OK`, then `Apply` and `OK`
8. Restart your computer
<br>

![Alt text](https://github.com/GamesRedone/ZISS/blob/main/Images/howto_pagefile.jpg)

If your game does crash, thanks to [Crash Logger SSE AE VR - PDB support](https://www.nexusmods.com/skyrimspecialedition/mods/59818), a crash log will appear in a TxT file open on your screen. Please include this when [reporting a crash related issue](https://github.com/GamesRedone/ZISS/tree/main#Reporting-Issues).

<br>

### **Shader Cache**

If you have an NVIDIA graphics card you should increase your shader cache size to reduce micro-stutters and smooth out frame drops.

1. Open your `NVIDIA Control Panel`
2. Click `Manage 3D settings`
3. Scroll in `Global Settings` until you reach `Shader Cache Size`
4. Double-click `Driver Default` to the right and set it to `"10 GB"`
5. Click `Apply`
<br>

![Alt text](https://github.com/GamesRedone/ZISS/blob/main/Images/howto_shadercache.jpg)

<br><br><br>
# **Installing the List**

Once you have ensured you have the correct [Required Game Files](#Required-Game-Files) and [Other Prerequisites](#Other-Prerequisites) set, you're ready to install ZISS.

:heavy_check_mark: It is recommend that you subscribe to Nexus Premium, otherwise you will have to install each mod manually.
> If you do decide to go the manual route, place the downloaded mods in the downloads folder *(e.g `C:\ZISS\downloads`)*.

Installation can be completed in as little as an hour or two depending on your internet speed.

<br>

1. Download the latest version of [Wabbajack](https://www.wabbajack.org/) and place it in a folder at the root of your drive, such as `C:\Wabbajack`
    > *Do not place it in your Program Files, or in any default Windows folders like "Desktop" or "Downloads"*

2. Launch `Wabbajack.exe`, it will download the most updated version of Wabbajack, after it finishes downloading close it

3. Create a folder at the root of your drive called `ZISS`
    > *(e.g. `C:\ZISS`)*

4. Add exclusions for both the `ZISS` folder and `Wabbajack` folder in your antivirus software
    > *([Click Here](https://github.com/GamesRedone/ZISS/blob/main/InstallationGuide.md#antivirus-exclusions) to learn how)*

5. Download the latest version of ZISS from [Nexus](https://www.nexusmods.com/skyrimspecialedition/mods/181971), extract, and place the `.wabbajack` file into the Wabbajack folder you made in step 1 (e.g. `C:\Wabbajack`). Double click the `.wabbajack` file to start installation.
    > *OR you can go to the [Nexus Collections page](https://www.nexusmods.com/games/skyrimspecialedition/collections/wdztqv) and click "Add to Wabbajack" instead (Be sure Revision 3 is selected). It will automatically begin the install for ZISS.*

8. Set your installation folder to the folder you made in step 3 *(e.g. "C:\ZISS")*<br>
    > *Your downloads folder should be set automatically If it isn’t, set it to `ZISS\downloads`*<br>

9. Launch ZISS through MO2, create a new character, and let MCM recorder run
    > *If MCM recorder is interrupted for any reason, either start over by creating a new character, or [reset your MCM settings](https://github.com/GamesRedone/ZISS/blob/main/CustomizationGuide.md#Resetting-MCM-settings-and-switching-between-difficulty-presets)*

**The ENB profile will be selected by default.**

<br>

👍 Switching between ENB and CS is simple. Just choose between the one of the two MO2 profiles.

<br>

<details><summary>Show Guide</summary>

![Alt text](https://github.com/GamesRedone/ZISS/blob/main/Images/howto_switchtocs.gif)

</details>

<br>

:warning: Save files are specific to ENB and CS, you will need to create a new save file after switching profiles.
> Checkout the [Community Shaders](https://github.com/GamesRedone/ZISS/blob/main/CustomizationGuide.md#community-shaders) section of the [Customization Guide](https://github.com/GamesRedone/ZISS/blob/main/CustomizationGuide.md) to learn how backup your overwrite folder and shader cache.

<br>

[Downloading stuck? Installation failed due to missing archives? Having some other issue?](https://github.com/GamesRedone/ZISS/blob/main/InstallationGuide.md#having-problems-with-installation)

<br><br>
## ***Antivirus Exclusions***

>*If you have modded games before this will not come as a huge surprise.*

[MO2](https://www.nexusmods.com/skyrimspecialedition/mods/6194), [Nemesis (Animation Behavior Framework)](https://www.nexusmods.com/skyrimspecialedition/mods/60033), and [Wabbajack](https://www.wabbajack.org/) are known to be automatically detected as viruses.

This is because of how they inject code, rewrite game memory, and modify core game files. Malicious software operates in the same way, so your antivirus software will most likely flag them due to a false positive.
<br><br>

:warning: Antivirus programs like BitDefender, Norton, and Webroot in particular will likely need to be fully removed from your PC in order to launch the game through MO2.
<br><br><br>
**Windows Defender users should set up antivirus exclusions for both the `ZISS` and `Wabbajack` folders**
> Instructions for Windows 11

1. Open Windows Defender. (Press the `Windows Key` type `"Windows Security"` and press `Enter`)
  
2. Click `Virus & threat protection` >  Under `Virus & threat protection settings` click `Manage settings`
   
3. Scroll to the bottom and click `Add or remove exclusions`
    > You may get a pop up asking you `Do you want to allow this app to make changes to your device`, click `Yes`
    
4. Click `"+ Add an exclusion"` and select `Folder`
   
5. Navigate to your installation folder (e.g. `C:\ZISS`) and then click `Select Folder`

6. Repeat steps 4-5 for your wabbajack folder (e.g. `C:\Wabbajack`)

<br><br>
## ***Having Problems with Installation***

- **Downloading Stuck or Missing Archives**

    This typically happens if you have a slow internet connection.

    If downloads are stuck DO NOT CLICK CANCEL, this will restart the entire installation. 
    > *Instead, close Wabbajack and open the ZISS `.wabbajack` file again. Don't worry it will pick up where you left off. Just click `Install` once it is running to continue.*

    If installation failed due to missing archives...
    > *You can click "Retry", typically this will fix this issue.<br><br>If the issue persists...<br><br>Click `Show Missing Archives` to view the download links to all of the missing files. Download each missing file manually and place them all into the downloads folder (e.g. `ZISS/downloads`), close Wabbajack, open the ZISS `.wabbajack` file, and click `Install` to continue.*

- **Mods are not downloading or unable to download `Skyrim_Default.ini`**

    If you have already tried to fix stuck downloads and missing archives, this most likely is caused by not having the correct game files installed on your system.
    > *Go through the [five steps](#Required-Game-Files) to ensure your have the correct game files.*
    
    It could also be a Nexus connection issue.
    > *Try logging out of Nexus (in MO2) and logging in again.* 

- **Not a `"whitelisted"` download**

    This happens sometimes when I update the list. Check the Nexus page to see if there are any updates.

<br>

❓ A full list of all FAQs can be found [in our Discord's FAQs channel](https://discord.com/invite/WejTdPFBbk).

<br><br>
## ***Freeing Up Storage Space Post Installation***

  You can delete the downloads folder once the list has successfully and installed to free back up ~20gb. (e.g. `ZISS/downloads`)

  Just know that if you do this...
  
  When you update ZISS all mods, not just the changes from the last update, will have to be downloaded and installed again.

<br><br>

## ***How to update***

If you have not used Wabbajack before, don't worry, unless you have deleted your to downloads folder, you will not need to download and install all the mods again. Only the changes download, and your save will be good.

⚠️ **Be sure to backup any customizations you have made within the MCM or MO2.**


<details><summary>Show Guide</summary><br>

If you did not change many settings, it may be easier to just configure them again once the update completes.

1. [Backup your MCM Recording in an `empty mod`](https://github.com/GamesRedone/ZISS/blob/main/CustomizationGuide.md#saving-your-settings-with-mcm-recorder)
> If you already have modified a Difficulty Preset's existing settings

2. Backup your Overwrite folder in an `empty mod` and activate the newly created mod
> Right click the `Overwrite` folder > create `empty mod` > name it `[NoDelete]Overwrite`

3. Backup your MO2 profile (If you disabled any optional mods)
> MO2 profiles are located in your profiles folder (i.g. `ZISS\profiles\My Custom Profile\`).<br><br>Backup the entire folder.<br><br>Drag the folder back into the profiles folder after update ***BEFORE*** launching MO2

4. If you added any mods, make sure to mark them as `[NoDelete]` for Wabbajack
> Rename the mod in MO2 to `[NoDelete]MOD NAME HERE`.<br>As long as [NoDelete] is in the beginning of the name, Wabbajack will not delete the mod durring an update.

5. *(Optional)* Wabbajack will not delete your save files, but checkout the [Where are the screenshots and save files](https://github.com/GamesRedone/ZISS/blob/main/StarterGuide.md#where-are-the-screenshots-and-save-files) section of the [Starter Guide](https://github.com/GamesRedone/ZISS/blob/main/StarterGuide.md) if you would like to back those up.

</details>

<br>

1. [Download ZISS (Most recent version, Main File)](https://www.nexusmods.com/skyrimspecialedition/mods/181971) and place the `.wabbajack` file in Wabbajack folder (e.g. `C"\Wabbajack"`)

2. Open the ZISS Wabbajack file and click `Install`. You will get a warning `Confirm File Deletion` click `Continue`

3. Launch the game, load your save and [reset your MCM settings](https://github.com/GamesRedone/ZISS/blob/main/CustomizationGuide.md#resetting-mcm-settings-and-switching-between-difficulty-presets), save the game.
> Be sure to activate the mod...<br>
> `I JUST UPDATED and I have an existing save - OR - I WANT TO RESET MY MCM SETTINGS` <br>
> Deactivate after. This prevents errors when loading settings.

  
<br><br><br><br><br><br><br><br>
