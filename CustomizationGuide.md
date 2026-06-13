# Z.I.S.S. | Customization Guide
![Alt text](https://github.com/GamesRedone/ZISS/blob/main/Images/logo_customizationguide_v1.0.png)

<h4 align="center"><a href="https://github.com/GamesRedone/ZISS/tree/main">Read Me</a> | <a href="https://github.com/GamesRedone/ZISS/blob/main/InstallationGuide.md">Installation Guide</a> | <a href="https://github.com/GamesRedone/ZISS/blob/main/StarterGuide.md">Starter Guide</a> | Customization Guide </h4>

---

<br><br>This work is licensed under <a href="https://creativecommons.org/licenses/by-nc-sa/4.0/">CC BY-NC-SA 4.0</a><br><br><img src="https://mirrors.creativecommons.org/presskit/icons/cc.svg" alt="" style="max-width: 1em;max-height:1em;margin-left: .2em;"><img src="https://mirrors.creativecommons.org/presskit/icons/by.svg" alt="" style="max-width: 1em;max-height:1em;margin-left: .2em;"><img src="https://mirrors.creativecommons.org/presskit/icons/nc.svg" alt="" style="max-width: 1em;max-height:1em;margin-left: .2em;"><img src="https://mirrors.creativecommons.org/presskit/icons/sa.svg" alt="" style="max-width: 1em;max-height:1em;margin-left: .2em;">

<br>

## **Navigation**
<br>

- [Introduction](#Introduction)

- [Custom Controller Keybinds](#Custom-Controller-Keybinds)

- [Resetting MCM settings & switching between difficulty presets](#Resetting-MCM-settings-and-switching-between-difficulty-presets)

- [Savings your MCM settings (MCM Recorder)](#Saving-your-settings-with-MCM-Recorder)

- [Optional Mods](#Optional-Mods)

- [Key Combat Modifiers](#Key-Combat-Modifiers)

- [Key Balancing Changes](#Key-Balancing-Changes)

- [Performance Tweaks](#Performance-Tweaks)

- [Adding Mods](#Adding-Mods)

<br>

# **Introduction**


The difficulty presets are there to simplify mod configuration, but if your looking to customize your experience, your in the right place.

Often there are many different mods that do the same / similar thing. The ones included in this list are the most configurable mods among other similar mods. With almost every key gameplay modifier being able to be tweaked, not to mention most of the mods included are highly compatible with tons for great quest, armor, and spell mods.

<br><br>
**ZISS can be customized in two separate places**

1. **In game, from the MCM**, you can customize things such as the [Key Combat Modifiers](#Key-Combat-Modifiers), [Key Balancing Changes](#Key-Balancing-Changes), and more.

2. **In MO2, by creating a new profile**, you can disable [Optional Mods](#Optional-Mods) and [add new mods](#Adding-Mods).

<br><br>

:floppy_disk: It's always a good idea to backup your save files first, just in case your save files get corrupted.
> MO2 Profile Specific Save Files are found in your `ZISS\profiles` folder. (i.g. `ZISS\profiles\ZISS - Default\saves`)<br><br>
> If you are not using Profile Specific Saves with your MO2 Profile, your files are found in<br>`Documents\My Games\Skyrim Special Edition\Saves`

:no_entry_sign: Do *NOT* `Right Click` > `Reinstall` or change the load order any of the mods in MO2. Always be sure to have `ZISS - Settings loader` active in MO2.
> *This will save you a lot of headaches since many `.ini` files have been been modified to make everything work nicely together.*

:warning: Many mods store their configuration files tied to your save file and you must save your game for any changes to save.
>*Do not forget to [reset your MCM settings](#Resetting-MCM-settings-and-Switching-Between-Difficulty-presets) when switching between difficulty presets. If you would like to save your settings so they can be used across multiple saves or with a new save, checkout the [Saving your settings (MCM Recorder)](#Saving-your-settings-with-MCM-Recorder) section. MCM Recorder will *NOT* take a snapshot of your current settings. It works by recording every button press or value you enter into the MCM.*

<br>

# **Custom Controller Keybinds**

ZISS uses [Complete Controller Setup](https://www.nexusmods.com/skyrimspecialedition/mods/99978) by [ROYGBIVx420](https://www.nexusmods.com/skyrimspecialedition/users/187780980) as the main mod to map the keybinds for the controller.

<br>

:warning: You can reinstall Complete Controller Setup to choose a different button layout, but you shouldn't! Many keybinds will break.
>*Unless you would like to go through all the manual corrections that I have made to many other mods yourself...*

:thumbsup: You can customize the D-Pad *"combo"* buttons with [Gamepad++](https://www.nexusmods.com/skyrimspecialedition/mods/27007) in game from the MCM.

:raised_hand: Before you change any settings, I suggest reading [Saving your settings (MCM Recorder)](#Saving-your-settings-with-MCM-Recorder). MCM Recorder will *NOT* take a snapshot of your current settings. It works by recording every button press or value you enter into the MCM.

<br>

**How to customize the D-Pad *"combo"* buttons**

1. Open the Mod Configuration Menu and go to `Gamepad++` > `Combo Key 1`
	> Do *NOT* change any of the settings in the `Keys & Settings` / `Action Keys` tabs

2. Enter your keybinds
	> Do *NOT* change `A` + `D-Pad: Right` (`Combo + Single Press`)

3. Go to the presets tab and click `Save Preset`

<br>

<br><br>

# **Resetting MCM Settings and Switching Between Difficulty Presets**

<br>

If you are trying to change the difficulty preset of an existing save file...

***or***

you are changing from one save file to another and they are both use different difficulty preset...

<br>

**You must reset your MCM settings**

1. Before you launch the game you must [disable the preset your currently using and enable the preset you want to use in MO2](https://github.com/GamesRedone/ZISS/edit/main/StarterGuide.md#selecting-a-preset).
	> If you followed along the guide in the Saving your settings (MCM Recorder) section; `ZISS - Settings Loader`, any preset you may be using, and your mod (If you made one) should be active.

2. Launch the game, load your save, and reset MCM settings in Skyrim's console

        1. Press [~] while in game
        2. Type: "nsetstage ski_configmanagerinstance 1"
        3. Press [enter]

4. Go to MCM recorder within the MCM and run `"1 ZISS - Settings Loader"`

	> *Ensure you are in a safe spot, it may take a few minutes, if interrupted you must start from `Step 1`. Wait for the settings to load.*

<br><br>

# **Saving your settings with MCM Recorder**

:clap: Hats off to [mrowrpurr](https://www.nexusmods.com/skyrimspecialedition/users/121646123) for creating [MCM recorder](https://www.nexusmods.com/skyrimspecialedition/mods/61719). Thank you!

Many mods store their configuration files tied to your save file, meaning that if you want to play on a different save you would have to enter all the changes to your settings again.

MCM Recorder changes that. It allows you to easily record any changes you make in the Mod Configuration Menu and load them back up at anytime, on any character.

<br>

:raised_hand: I recommend modifying an [existing Difficulty Preset's settings](https://github.com/GamesRedone/ZISS/edit/main/StarterGuide.md#preset-settings-comparison) if you want to create your own preset.
> This will save you a lot of headaches since many `.ini` files have been been modified to make everything work nicely together.

<br>

**How to modify a Difficulty Preset's existing settings**

1. [Ensure the preset you wish to modify is active in Mod Organizer 2 before you launch the game.](https://github.com/GamesRedone/ZISS/edit/main/StarterGuide.md#selecting-a-preset)
	> To modify the Default Preset only enable `ZISS - Settings Loader`.<br><br>
	> I would create a ".txt" file noting what preset you used because it will need to be active when Resetting MCM Settings & Switching Between Difficulty Presets.

3. Launch the game, create a new character and wait for MCM recorder to finish running. Then save the game.
	> This just ensures the settings get saved correctly, so don't worry, you can load them back up on your existing save when your done.

4. Open the Mod Configuration Menu and go to `MCM Recorder` click on `1 ZISS - Settings Loader`. Click `Yes` on the pop up and close the MCM.

5. Click `Add to recording`. You will get a pop up letting you know that the recording has restarted. You can now begin to make changes in the MCM.
	>If you click on `Run` by mistake, load the save you created in `Step 2`. This happened to me at times when using a controller. Mouse and keyboard is recommend for this part.<br><br>
	>Sometimes you will get a notification that MCM recorder cannot record a setting. This is because of how the mod author has set up their mod. In order to save the settings for these mods you will have to manually configure the mod's `.ini` file, if it has one. This is a little more advanced and files are located in various places depending on the mod, so I won't be covering how to do this in this guide.

6. When you are done making the changes to your settings, return to `MCM Recorder` in the MCM and click `FINISH RECORDING`

8. Continue playing with the new character, or return to an existing save. If are returning to a existing save file, be sure to [reset your MCM Settings](#Resetting-MCM-Settings-and-Switching-Between-Difficulty-Presets) after you load back in to apply the changes you made to the difficulty preset.

<br>

⚠️ If you update ZISS you will lose any existing settings you may have saved. You must mark these files in an `empty mod` so Wabbajack skips over them durring an update.

:floppy_disk: MCM recorder saves all of the steps of all recordings as `.json` files named after the mod they configure.
> *You can find the files in your MO2 `Overwrite` folder under `McmRecorder` > `1 ZISS - Settings Loader`. If you want to backup these files, create an `empty mod` in MO2 and drag the `McmRecorder` folder from `Overwrite` to the `empty mod`. GamerPoets has a [great video](https://www.youtube.com/watch?v=Ksp_yPq637s) describing how. Do NOT rename the folder `1 ZISS - Settings Loader` within the `MCMRecorder` Folder. You can rename your `empty mod` whatever you'd like (e.g. "My Custom Preset") just include [NoDelete] at the start of the name (e.g. `[NoDelete]My Custom Preset`) so Wabbajack skips over the files. Be sure to load the mod you create LAST in your load order (the bottom).*

![Alt text](https://github.com/GamesRedone/ZISS/blob/main/Images/howto_overwrite.jpg)

<br><br>

# **Optional Mods**

There are many optional mods included in ZISS.

All mods that are *NOT* considered optional can either be [tweaked/turned off from the MCM](#Key-Balancing-Changes), are required by other mods in the list, or have been heavily patched. Stick to this list when it comes to disabling mods unless you know what you are doing. 

<br>

:warning: If you choose to deactivate any mod listed below, do so at your own risk of corrupting existing save files. Your issue/bug report(s) may be ignored.

<br>

:raised_hand: Before you start deactivating any mods it is best to create a new profile in MO2 so you can revert back if anything goes wrong

1. Click the dropdown next to `Profile` in top section of MO2 where it says `"ZISS - Default"` and click `Manage`
2. Select `"ZISS - Default"` and click `Copy`
3. Enter any name you'd like and click `OK`

:floppy_disk: If you update ZISS you will lose all MO2 profiles you have created. You must backup these files in a seperate folder from your ZISS installation.
> MO2 profiles are located in your `profiles` folder (i.g. `ZISS\profiles\My Custom Profile\`). Backup the entire folder. Drag the folder back into the `profiles` after update.

<br>

**Now that you have created a new profile in MO2, deactivating mods is simple! Just uncheck the mod you want to deactivate in MO2.**


<img src="https://github.com/GamesRedone/ZISS/blob/main/Images/howto_disablemods.gif" width="100%">

<br>

**Optional mods**

<details><summary>Click Here to Show Mods</summary>
	
> Many optional mods are not located in the `Optional` section on the mod list. This is due to load order restrictions. To locate and disable these mods, use the search bar within MO2 at the bottom of the mod list.<br><br>Do ***NOT*** change the load order any of the mods.

:mag: Checkout the [Starter Guide](https://github.com/GamesRedone/ZISS/blob/main/StarterGuide.md) to learn more about what these mods do

:floppy_disk: It's always a good idea to backup your save files first, just in case your save files get corrupted.
> MO2 Profile Specific Save Files are found in your `ZISS\profiles` folder. (i.g. `ZISS\profiles\ZISS - Default\saves`)<br><br>
> If you are not using Profile Specific Saves with your MO2 Profile, your files are found in<br>`Documents\My Games\Skyrim Special Edition\Saves`

| Mod Name | Category |  New Save Required? |
| :--- | :--- | :--- |
| **[Ricochet](https://www.nexusmods.com/skyrimspecialedition/mods/160603)** | Arrow Ricochet | YES |
| **[Realistic AI Detection (RAID)](https://www.nexusmods.com/skyrimspecialedition/mods/2345)** | Stealth | YES |
| **[Suspicious City Guards](https://www.nexusmods.com/skyrimspecialedition/mods/38762)** | NPC Reactions | NO |
| **[NPCs React To Necromancy](https://www.nexusmods.com/skyrimspecialedition/mods/70428)** | NPC Reactions | NO |
| **[NPCs React To Invisibility](https://www.nexusmods.com/skyrimspecialedition/mods/91480)** | NPC Reactions | NO |
| **[Experience](https://www.nexusmods.com/skyrimspecialedition/mods/17751)** | XP Scaling/Skill Cap | YES |
| **[Skyrim Souls](https://www.nexusmods.com/skyrimspecialedition/mods/27859)** | No Pause in Menus | YES |
| **[Open World Loot](https://www.nexusmods.com/skyrimspecialedition/mods/49681)** | Encounter Zones | YES |
| **[You Hunger](https://www.nexusmods.com/skyrimspecialedition/mods/9143)** | Food Spawns | YES |
| **[Journeyman](https://www.nexusmods.com/skyrimspecialedition/mods/92220)** | Fast Travel | YES |
| **[Dungeons - Revisited](https://www.nexusmods.com/skyrimspecialedition/mods/51798)** | New dungeon layouts & POIs | YES |
| **[Hidden Hideouts of Skyrim](https://www.nexusmods.com/skyrimspecialedition/mods/2625)** | New dungeon layouts & POIs | YES |
| **[Nordic Ruins of Skyrim](https://www.nexusmods.com/skyrimspecialedition/mods/20382)** | Locations enhanced | YES |
| **[Trees in Cities](https://www.nexusmods.com/skyrimspecialedition/mods/1941)** | Locations enhanced | YES |
| **[Simply Bigger Trees](https://www.nexusmods.com/skyrimspecialedition/mods/5281)** | Other notable enhancements | YES |
| **[Edmond's Official Unique Flowers and plants](https://www.nexusmods.com/skyrimspecialedition/mods/29154)** | Other notable enhancements | YES |
| **[Waterplants](https://www.nexusmods.com/skyrimspecialedition/mods/6092)** | Other notable enhancements | YES |
> You can find even more mods that can be safely disabled in the [Performance Tweaks](#Performance-Tweaks) section.

</details>

<br>

**Optional mods that are not listed in the Starter Guide**

<details><summary>Click Here to Show Mods</summary>

| Mod Name | Mod Author | Description | New Save Required? |
| :--- | :--- | :--- | :--- |
| **[Notification Filter](https://www.nexusmods.com/skyrimspecialedition/mods/67925)** | [miere43](https://www.nexusmods.com/skyrimspecialedition/users/6387039) | "SKSE plugin that allows hiding notifications based on customizable rules." *(Used to remove some mod related notifications)* | YES |
| **[Nyghtfall](https://www.nexusmods.com/skyrimspecialedition/mods/39011)** | [Nyghttones](https://www.nexusmods.com/skyrimspecialedition/users/68508590) | *(Disabled with default MO2 profile)* "Includes ~7 hours of original music. Features a generally darker sound that doesn't stray too far from vanilla." *(Replaces vanilla music)* | YES |
| **[Chapter II - Jeremy Soule Inspired Music](https://www.nexusmods.com/skyrimspecialedition/mods/37792)** | [DreymaComposer](https://www.nexusmods.com/skyrimspecialedition/users/53912641) | *(Disabled with default MO2 profile)* "Adds around 3 hours of exploration & town music inspired by Jeremy Soule." *(Does not replace vanilla music just adds tracks)* | YES |
| **[QuickLoot IE](https://www.nexusmods.com/skyrimspecialedition/mods/120075)** | [MissCorruption](https://www.nexusmods.com/skyrimspecialedition/users/91759958) | *(Disabled with default MO2 profile)* "Allows you to look through and take items from containers without the need to open the inventory screen every time, kind of like Fallout 4." *(Little Buggy but nice QoL, if you use disable QuickLoot menu when in combat and when looting animals in the MCM)* | YES |
| **[QuickLoot IE - Favourites style](https://www.nexusmods.com/skyrimspecialedition/mods/51017)** | [LeSwagueMasque](https://www.nexusmods.com/skyrimspecialedition/users/2390394) | *(Disabled with default MO2 profile)* "Retexture of the Quick Loot menu to match SkyUI's menu colour scheme and layout." | YES |
| **[Disarmless](https://www.nexusmods.com/skyrimspecialedition/mods/12631)** | [Anqayas](https://www.nexusmods.com/skyrimspecialedition/users/46531697) | "Removes Disarm shout from Draugrs only." | YES |
| **[Slaughterfish are Extinct](https://www.nexusmods.com/skyrimspecialedition/mods/19987)** | [Ranzitho](https://www.nexusmods.com/skyrimspecialedition/users/3288013) | "Simply removes all slaughterfish from the game." | YES |
| **[Spell Organizer](https://www.nexusmods.com/skyrimspecialedition/mods/15558)** | [MaskedRPGFan](https://www.nexusmods.com/skyrimspecialedition/users/22822094) | "Easily add, remove, and hide learned spells." *(Removes some abilities from some mods)* | YES |

</details>

<br><br>

# **Key Combat Modifiers**

Change almost every key combat modifier right from the MCM.

<details><summary>Screenshot</summary>

> *The MCM can be accessed from the System Menu (Pause Menu) under `Mod Configuration`.*

<img src="https://github.com/GamesRedone/ZISS/blob/main/Images/howto_mcm.jpg" loading="lazy">

</details>

<br>

:raised_hand: Before you change any settings, I suggest reading [Saving your settings (MCM Recorder)](#Saving-your-settings-with-MCM-Recorder). MCM Recorder will *NOT* take a snapshot of your current settings. It works by recording every button press or value you enter into the MCM.

<br>
<details><summary>Click Here to Show Settings</summary>

| Mod Name | Mod Author | Description |
| :--- | :--- | :--- |
| **[Simply Balanced](https://www.nexusmods.com/skyrimspecialedition/mods/15541)** | [Madchieften](https://www.nexusmods.com/skyrimspecialedition/users/6492766) | `Player Damage Taken` and `NPC Damage Taken` control how much damage you take from enemies hits and how much damage you deal. Can be set to Vanilla values.  |
| **[Stamina Matters](https://www.nexusmods.com/skyrimspecialedition/mods/25367)** | [DJD2010](https://www.nexusmods.com/skyrimspecialedition/users/5601927) | `Player Stamina Rate` is what your looking for, as well as the `Consumption` page. Can be fully disabled from MCM. |
| **[Smart NPC Potions](https://www.nexusmods.com/skyrimspecialedition/mods/40102)** | [jayserpa](https://www.nexusmods.com/skyrimspecialedition/users/5201727) | Controls who uses potions and how often potions are used. Can be fully disabled from MCM *(`Chance of NPC using potion` set to `"0%"`)*. |
| **[Deadly Dragons](https://www.nexusmods.com/skyrimspecialedition/mods/23723)** | [Argonil](https://www.nexusmods.com/profile/Argonil) | Adjust dragon damage, armor and health. Can be set to Vanilla values. |
| **[Ultimate Dragons](https://www.nexusmods.com/skyrimspecialedition/mods/26374)** | [tktk1](https://www.nexusmods.com/skyrimspecialedition/users/3841389) | Change the rate a which the are flying vs. on the ground as well as their damage output. Can be turned off as well from MCM. |
| **[Ricochet](https://www.nexusmods.com/skyrimspecialedition/mods/160603)** | [Seb263](https://www.nexusmods.com/skyrimspecialedition/users/825950) | Many settings for realistic arrow and bolt ricochets |
| **[Precision](https://www.nexusmods.com/skyrimspecialedition/mods/72347)** | [Ershin](https://www.nexusmods.com/skyrimspecialedition/users/2749008) | Controls attack collisions. I wouldn't recommend messing with much unless you know what your doing. With that said, you may want to change the `Sweep Attack` settings. |
| **[Archery Gameplay Overhaul](https://www.nexusmods.com/skyrimspecialedition/mods/24296)** | [DServant](https://www.nexusmods.com/skyrimspecialedition/users/10549885) | Mainly handles the new archery animations but there are options for the bow camera. |
> Some of these mods can be fully disabled, checkout the [Optional Mods](#Optional-Mods) section.

</details>

<br><br>

# **Key Balancing Changes**

Don't like the balancing within the ZISS presets? Change it right from the MCM! These are the main mods that have been used to balance the game, as well as some other notable settings you might be looking for.

<details><summary>Screenshot</summary>

> *The MCM can be accessed from the System Menu (Pause Menu) under `Mod Configuration`.*

<img src="https://github.com/GamesRedone/ZISS/blob/main/Images/howto_mcm.jpg" loading="lazy">

</details>

<br>

:raised_hand: Before you change any settings, I suggest reading [Saving your settings (MCM Recorder)](#Saving-your-settings-with-MCM-Recorder). MCM Recorder will *NOT* take a snapshot of your current settings. It works by recording every button press or value you enter into the MCM.

:warning: If you want to change the carry weight, do not touch the settings for [Cobb Encumbrance](https://www.nexusmods.com/skyrimspecialedition/mods/18362) in the MCM. Carry Weight is controlled by [Carry That Weight](https://www.nexusmods.com/skyrimspecialedition/mods/50144), change the settings in that mod instead.
> *Cobb Encumbrance only allows running, sprinting and dodging while encumbered to function normally with the new character animations.*

<br>

**Balancing Settings**

<details><summary>Click Here to Show Settings</summary>

| Mod Name | Category | Setting(s) | Description |
| :--- | :--- | :--- | :--- |
| **[Frostfall](https://www.nexusmods.com/skyrimspecialedition/mods/671)** | Survival Needs | `Exposure Rate` | Do *Not* change `At max exposure`, keep it on `Rescue`. Other settings will conflict with other mods. Can be fully disabled from MCM. |
| **[iNeed](https://www.nexusmods.com/skyrimspecialedition/mods/645)** | Survival Needs | `Hunger/thirst/fatigue rate` | Controls most needs, with many survival options for things such as food spoilage and water contamination. Can be fully disabled from MCM. Dangerous diseases will not work even if checked, due to how the mod was installed. This is on purpose. I would not recommend reinstalling the mod / using this feature. It will cause conflicts.  |
| **[Carry That Weight](https://www.nexusmods.com/skyrimspecialedition/mods/50144)** | Carry Weight | `Base Capacity` |  Controls your carry weight limit. Can be fully disabled from MCM *(Set to `"300"` the Vanilla Value)*. |
| **[Trade and Barter](https://www.nexusmods.com/skyrimspecialedition/mods/23081)** | Barter Prices | `Buying/Selling Prices` |  Set to Vanilla or your own custom settings. |
| **[C.O.I.N.](https://www.nexusmods.com/skyrimspecialedition/mods/51439)** | Currency | `Coins` | All new coins can be set to a value of 1 Septim to return to Vanilla. *(Basically will make this mod just a skin for the currency)* |
| **[Experience](https://www.nexusmods.com/skyrimspecialedition/mods/17751)** | XP Scaling/Skill Cap | `SkillCap Base` & `SkillCap Multiplier` | Determines the skill cap, set to `"100"` to disable. You can also configure the amount of XP you earn for quests/discoveries. Checkout the Starter Guide for more info about the [Skill Cap](https://github.com/GamesRedone/ZISS/blob/main/StarterGuide.md#Experience-and-Leveling-Freedom). |
| **[Leveling Freedom](https://www.nexusmods.com/skyrimspecialedition/mods/69589)** | XP Scaling/Skill Cap | `fXPLevelUpBase` & `fXPLevelUpMult` | Determines XP scaling. Checkout this spreadsheet I made to easily visualize this compared to Vanilla Scaling. Can be fully disabled from MCM *(Set to `Vanilla`)*. |
| **[Missives](https://www.nexusmods.com/skyrimspecialedition/mods/17576)** | Mission Board Quests | `Easy/Hard Quest Chance` & `Rewards` | Change the chance of receiving easy/hard side quests at the new mission boards. Also set the rewards by mission type. |

</details>

<br>

**NPCs & Random Encounter Settings**

<details><summary>Click Here to Show Settings</summary>

| Mod Name | Category | Setting(s) | Description |
| :--- | :--- | :--- | :--- |
| **[City Bag Checks](https://www.nexusmods.com/skyrimspecialedition/mods/112212)** | Encounters | `Bag Check Chance` |  How likely guards are to check your bag when entering a city. Can be fully disabled from MCM (Set to `"0%"`). |
| **[Extended Encounters](https://www.nexusmods.com/skyrimspecialedition/mods/44810)** | Encounters | `Encounter Chance` |  Increase or decrease the likelyhood of encounters. Can be fully disabled from MCM (Set to `"0%"`). |

</details>

<br>

**Survival Mode & Gameplay Settings**

<details><summary>Click Here to Show Settings</summary>

| Mod Name | Category | Setting(s) | Description |
| :--- | :--- | :--- | :--- |
| **[Save System Overhaul 2](https://www.nexusmods.com/skyrimspecialedition/mods/70179)** | MISC | `Time Between Saves (in seconds)` | Change how often the game saves. Only change the `Time Between Saves` setting. Do *NOT* change any other setting. |
| **[Spell Organizer](https://www.nexusmods.com/skyrimspecialedition/mods/15558)** | MISC | `Auto-Remove` | Remove spells from the auto-remove list to add the removed abilities back to the game. *(I removed some abilities from some mods)* |
| **[Shadow of Skyrim](https://www.nexusmods.com/skyrimspecialedition/mods/65136)** | Alternative Death System | `Nemeses` & `Defeat` | Change how the alternative death system functions, or turn it off altogether. Can be fully disabled from MCM. |
| **[Skald's Mail](https://www.nexusmods.com/skyrimspecialedition/mods/31791)** | Mailboxes | `Base Shipping Time` | Change the costs related to mailboxes and how long it takes to send/recieve items. |
| **[Dirt & Blood](https://www.nexusmods.com/skyrimspecialedition/mods/38886)** | Dirt/Blood | `Soap is Required for Baths` | Toggle on or off the requirement for soap when bathing. |
| **[Disguises](https://www.nexusmods.com/skyrimspecialedition/mods/133426)** | Disguises | `Disguise Active` | Toggles on or off the Disguise System. |
| **[Skyrim Reputation](https://www.nexusmods.com/skyrimspecialedition/mods/22374)** | Reputation System | `Output Options` & `Input Options` | Change how reputation is earned/lost and what happens as a result or turn off the reputation system altogether by toggling off all options. |
| **[Hunterborn](https://www.nexusmods.com/skyrimspecialedition/mods/7900)** | Hunting | `Enable Skrimshaw` | Many features of Hunterborn are not enabled in the ZISS presets. You can enable Skrimshaw, and tweak hunting. Can be fully disabled from MCM. |
| **[Wait Carriage in Inns](https://www.nexusmods.com/skyrimspecialedition/mods/83044)** | Carriage/Ferry System | `Enabled Destinations` | Across all the difficulty presets, only the major cities are enabled. You can enable many other locations. |
| **[Honed Metal](https://www.nexusmods.com/skyrimspecialedition/mods/61015)** | Crafting/Enchanting for hire | `Allow crafting / enchanting` | Tweak who can craft/enchant and what they can craft/enchant. |
| **[Fossil Mining](https://www.nexusmods.com/skyrimspecialedition/mods/14107)** | Fossils | `Drop Rate` | Change the drop rate of various kinds of fossils. |

</details>

<br>

📃 There are hundreds of settings you can tweak in the MCM, only the Key Balancing Changes and other main settings are covered here.

:mag: You can find even more key settings to tweak in the [Key Combat Modifiers](#Key-Combat-Modifiers) section. Many mods can also be [fully disabled](#Optional-Mods).

<br>

# **Performance Tweaks**

Some Performance tweaks will effect existing saves. If you are unsure about ZISS running well on your system it is best to run a quick test before you play.

1. From the game's main menu press the `"~"` key

2. Type `"coc whiterun"` and press enter

This will spawn you in Whiterun with some gold and loot. Run around, talk to some people, go in and out of buildings... This area is one of the High-Density (script-heavy) areas within the game if you get good frames here you should be okay!
> *During this test you may run into some unexpected bugs when interacting with NPCs or if you try to complete a quest. That is expected, this test will only tell you if the game is running well. If it runs "okay" try changing your MCM settings. If it runs "poorly" try disabling some mods.*

<br>

**The following MCM settings can be used on new or existing saves to help increase frames**

<details><summary>Click Here to Show Settings</summary>
<br>
	
:raised_hand: Before you change any settings, I suggest reading [Saving your settings (MCM Recorder)](#Saving-your-settings-with-MCM-Recorder). MCM Recorder will *NOT* take a snapshot of your current settings. It works by recording every button press or value you enter into the MCM.


| Mod Name | Mod Author | Discription | Setting | Impact Level |
| :--- | :--- | :--- | :--- | :--- |
| **[FSMP](https://www.nexusmods.com/skyrimspecialedition/mods/57339)** | [DaydreamingDay](https://www.nexusmods.com/skyrimspecialedition/users/92162863) | "Adds physics for capes, clothes, hair, etc!" (Greatly effects performance, but also greatly effects how capes look, especially when rolling. I recommend taking a screenshot of the settings included with ZISS in case you want to go back) | `Presets` > click `Performance.xml` | HIGH |
| **[R.A.S.S.](https://www.nexusmods.com/skyrimspecialedition/mods/22780)** | [lKocMoHaBTl](https://www.nexusmods.com/skyrimspecialedition/users/2361177) | "Adds visual effects to the Player and NPCs during certain conditions. (Snow & Rain)" | `Visual Effects` > `"Off"` | LOW |

</details>

<br><br>

**The following mods can be disabled to help increase frames *(New Save Required)***

<details><summary>Click Here to Show Mods</summary>

> *Never disabled a mod before? It's really easy, click the uncheck the checkbox next to the mod and it's disabled! Just make sure to create a new profile in MO2. Checkout the [Optional Mods](#Optional-Mods) section to learn how.<br><br>Do ***NOT*** change the load order any of the mods.*

:warning: If you choose to deactivate any mod listed below, do so at your own risk of corrupting existing save files. Your issue/bug report(s) may be ignored.

![Alt text](https://github.com/GamesRedone/ZISS/blob/main/Images/howto_increaseframes.jpg)

</details>

<br><br>

**Increase frames even more by disabling complex parallax textures and meshes *(New Save Required)***

<details><summary>Click Here to Show Mods</summary>

>*Do *NOT* pick and choose, just disable them all. Some of these mods have the capacity to break the game. This is more of a last resort.<br><br>Do ***NOT*** change the load order any of the mods.*

:warning: If you choose to deactivate any mod listed below, do so at your own risk of corrupting existing save files. Your issue/bug report(s) may be ignored.

![Alt text](https://github.com/GamesRedone/ZISS/blob/main/Images/howto_parallaxgen.jpg)
> *Also disable PGPatcher and PGPatcher output. They are not in this section but you can find them easily by using the search bar within MO2 at the bottom of the mod list.*

</details>

<br><br>

# **Adding Mods**

There are many mods compatible with ZISS. Listed below are some of my favorite, Vanilla friendly mods that are known to be compatible. These mods were not included in the list to keep ZISS lightweight.

This guide does not go in depth about how to add mods to MO2 but GildyBoye has a [great video](https://www.youtube.com/watch?v=HuMoHTmoE2A) going into the details!

<br>

:warning: If you add any mods to ZISS, and run into issues, your issue/bug reports may be ignored. Modify at your own risk!

:no_entry: Do not add any animation or texture / mesh mods that are incompatible with Nemesis or PGPatcher. If you do add any animations or texture / mesh mods, run Nemesis to load the animations and PGPatcher to load the meshes and textures (Parallax Gen).
> *Here is a guide by SoftGaming on using [Nemesis](https://youtu.be/--W1jhyKHU0?t=146) and a guide by Darkfox127 on how to use [PGPatcher](https://youtu.be/-ZbQBQ05_Ss?t=556). Do not mess with the settings in Nemesis or PGPatcher unless you know what your doing. **THIS CAN BREAK THE GAME**.*

:no_entry: Do *NOT* `Right Click` > `Reinstall` or change the load order any of the mods in MO2.

:heavy_check_mark: Always be sure to have `ZISS - Settings loader` active in MO2.
> *This will save you a lot of headaches since many `.ini` files have been been modified to make everything work nicely together.*

<br>

:raised_hand: Before you start adding any mods it is best to create a new profile in MO2 so you can revert back if anything goes wrong.

1. Click the dropdown next to `Profile` in top section of MO2 where it says `"ZISS - Default"` and click `Manage`
2. Select `"ZISS - Default"` and click `Copy`
3. Enter any name you'd like and click `OK`

:floppy_disk: If you update ZISS you will lose all MO2 profiles you have created. You must backup these files in a seperate folder from your ZISS installation.
> MO2 profiles are located in your `profiles` folder (i.g. `ZISS\profiles\My Custom Profile\`). Backup the entire folder. Drag the folder back into the `profiles` after update.

<br>

**Compatible Mods**

<details><summary>Click Here to Show Mods</summary>

Coming soon

</details>

<br><br><br><br><br><br><br><br>
