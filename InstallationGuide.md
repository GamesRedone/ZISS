# Z.I.S.S. | Installation Guide
![Alt text](https://github.com/GamesRedone/ZISS/blob/main/Images/logo_installationguide_v1.0.png)

<h4 align="center"><a href="https://github.com/GamesRedone/ZISS/tree/main">Read Me</a> | Installation Guide | <a href="https://github.com/GamesRedone/ZISS/blob/main/StarterGuide.md">Starter Guide</a> | <a href="https://github.com/GamesRedone/ZISS/blob/main/CustomizationGuide.md">Customization Guide</a> </h4>

---

<br><br>This work is licensed under <a href="https://creativecommons.org/licenses/by-nc-sa/4.0/">CC BY-NC-SA 4.0</a><br><br><img src="https://mirrors.creativecommons.org/presskit/icons/cc.svg" alt="" style="max-width: 1em;max-height:1em;margin-left: .2em;"><img src="https://mirrors.creativecommons.org/presskit/icons/by.svg" alt="" style="max-width: 1em;max-height:1em;margin-left: .2em;"><img src="https://mirrors.creativecommons.org/presskit/icons/nc.svg" alt="" style="max-width: 1em;max-height:1em;margin-left: .2em;"><img src="https://mirrors.creativecommons.org/presskit/icons/sa.svg" alt="" style="max-width: 1em;max-height:1em;margin-left: .2em;">

<br>

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

>*When running at the minimum specs it is recommended to disable any in-game overlays you may use such as Steam or NVIDIA overlays. Also ensure to follow all the steps in the [Recommended Preparations](#Recommended-Preparations) section of the this guide for the best experience.*

<br>

| Requirement | Minimum | Recommended |
| :--- | :--- | :--- |
| **Processor** | Intel Core i7-11800H / AMD Ryzen 7 5800h | TBD |
| **Graphics** | NVIDIA GeForce RTX 3050 Ti Laptop / Radeon RX 7900M | TBD |
| **Memory** | 16 GB RAM | 24 GB RAM |
| **Storage** | ~80 GB SATA SSD | ~80 GB NVMe SSD |

<br><br>
ZISS is lightweight and only requires a total of ~30 GB.

With that said, Wabbajack requires around 30 GB of extra space on your main drive for temporary and working files during installation and the game files themselves are ~20 GB.

You can [delete downloads](#Freeing-Up-Storage-Space-Post-Installation) once the list is successfully installed to free back up more space.

<br><br>

# **Required Game Files**

ZISS requires the [Steam version](https://store.steampowered.com/sub/626153/) of `Skyrim Anniversary Edition v1.6.117` *(The newest version)*

Follow these five steps to ensure you have the correct required game files installed on your system.
<br><br><br>
:warning: If mods are *NOT* downloading or you are unable to download `Skyrim_Default.ini` you probably have the wrong game files installed on your system.
<br><br><br>1. **Check what version of the game you own**

  > ZISS utilizes some of the Creation Club content included in the `Skyrim Anniversary Upgrade`<br>
  > So it is required that you purchase either a copy of...<br><br>
  > `Skyrim Anniversary Edition` or the `Skyrim Anniversary Upgrade`<br><br>
  > ...from [Steam](https://store.steampowered.com/sub/626153/).<br><br>
  > If your key has been activated/purchased on another platform it will not work.

:no_entry: **Pirated copies of the game WILL NOT WORK...**
>*...and I will not tell you how to get them to work.*

<br>2. **Use a fresh install**

>[All mods will be installed completely separate from your Steam installation of Skyrim](https://www.nexusmods.com/skyrimspecialedition/mods/31720), so a fresh install is required to ensure ZISS runs smoothly. This is especially true if you have ever modded Skyrim in the past and have used [ENB](http://enbdev.com/download.html) or [SKSE](https://skse.silverlock.org/) before.

:no_entry: ***DO NOT* "Verify Integrity of Game Files" through Steam.**
> *If you ever have, or are unsure if you ever have, you should remove all game files and reinstall the game.*

<br>3. **Launch the game and check that all Creation Club content has been downloaded**

    1. Launch the game and select `"Creations"` from the `Main Menu`.
    2. Access the `Options`, and select `"Download all owned Creation Club Creations"`.
    3. The Creation Club content you are missing will now download, this may take some time if you are missing a lot of the content.

<br>4. **Stop Steam from automatically updating**

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

Ensure the following software is installed and up to date.

- Visual C++ x64 Redistributables
- Microsoft .NET 9.0 Desktop Runtime
-

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

If your game does crash, thanks to [Crash Logger SSE AE VR - PDB support](https://www.nexusmods.com/skyrimspecialedition/mods/59818), a crash log will appear in a TxT file open on your screen. Please include this when [reporting a crash related issue](https://github.com/GamesRedone/ZISS/tree/main#Reporting-Issues).

<br>

### **Shader Cache**

If you have an NVIDIA graphics card you should increase your shader cache size to reduce micro-stutters and smooth out frame drops.

1. Open your `NVIDIA Control Panel`
2. Click `Manage 3D settings`
3. Scroll in `Global Settings` until you reach `Shader Cache Size`
4. Double-click `Driver Default` to the right and set it to `"10 GB"`
5. Click `Apply`
<br><br><br>
# **Installing the List**

Once you have ensured you have the correct [Required Game Files](#Required-Game-Files) and [Other Prerequisites](#Other-Prerequisites) set, you're ready to install ZISS.

Installation can be completed in as little as an hour or two depending on your internet speed.
<br><br><br>
1. Download the latest version of [Wabbajack](https://www.wabbajack.org/) and place it in a folder at the root of your drive, such as `"C:\Wabbajack."` Do not place it in your `Program Files`, or in any default Windows folders like `Desktop` or `Downloads`

2. Create a folder at the root of your drive called `"ZISS"`

3. Download the .wabbajack file from the [Nexus page](https://www.nexusmods.org/), add it to your Wabbajack folder you made in step 1, and open it

4. Set your installation folder to the folder you made in step 2 (e.g. `"C:\ZISS"`)

    >*Your downloads folder should be set automatically*<br>
    >*If it isn’t, set it to `"ZISS\downloads"`*

5. Click the start button to begin, follow any prompts on-screen

6. Add exclusions for [MO2](https://www.nexusmods.com/skyrimspecialedition/mods/6194) and [Nemesis (Animation Behavior Framework)](https://www.nexusmods.com/skyrimspecialedition/mods/60033) in your antivirus software ([Click Here](#Antivirus-Exclusions) to learn how)

<br><br>
## ***Antivirus Exclusions***

>*If you have modded games before this will not come as a huge surprise.*

[MO2](https://www.nexusmods.com/skyrimspecialedition/mods/6194) and [Nemesis (Animation Behavior Framework)](https://www.nexusmods.com/skyrimspecialedition/mods/60033) are known to be automatically detected as viruses.

This is because of how they inject code, rewrite game memory, and modify core game files. Malicious software operates in the same way, so your antivirus software will most likely flag them due to a false positive.
<br><br>

:warning: Antivirus programs like BitDefender, Norton, and Webroot in particular will likely need to be fully removed from your PC in order to launch the game through MO2.
<br><br><br>
**Windows Defender users should set up antivirus exclusions for MO2 and Nemesis**
> Instructions for Windows 11

1. Open Windows Defender. (Press the `Windows Key` type `"Windows Security"` and press `Enter`)
  
2. Click `Virus & threat protection` >  Under `Virus & threat protection settings` click `Manage settings`
   
3. Scroll to the bottom and click `Add or remove exclusions`
    > You may get a pop up asking you `Do you want to allow this app to make changes to your device`, click `Yes`
    
4. Click `"+ Add an exclusion"` and select `Folder`
   
5. Navigate to your installation folder (e.g. `"C:\ZISS"`) and then click `Select Folder`

<br><br>
## ***Having Problems with Installation***

- **Mods are not downloading or unable to download `Skyrim_Default.ini`**

    *This most likely is caused by not having the correct game files installed on your system.*

    *Go through the [five steps](#Required-Game-Files) to ensure your have the correct game files.*
    
    *It could also be a Nexus connection issue.*
    
    *Try logging out of Nexus (in MO2) and logging in again.* 

- **Not a `"whitelisted"` download**

    *This happens sometimes when I update the list. Check the Nexus page to see if there are any updates.*
<br><br>
## ***Freeing Up Storage Space Post Installation***
<br><br><br><br><br><br><br><br>
