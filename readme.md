# Caviar: A Soda Dungeon 2 MOD

Welcome to Caviar, a Soda Dungeon 2 MOD that contains only the finer things in life.

To get started, see the [instructions](#instructions) section for installing the mod, or the [features](#features) section to know what Caviar is all about.

> ℹ️ See the [remarks](#remarks) section regarding support.

If you have a question, see the [FAQ](#faq) section.

## Versions

There are two versions of Caviar: `Live` and `Beta`. The `Live` version will be the latest release shown in the releases section, while the `Beta` version will be marked as a preview release and can be found in the [releases](https://github.com/caviyacht/SodaDungeon2Mod/releases) page.

> ℹ️ If there is a current beta going on, the Live version will not be updated during that time.

- Current Live Version: [Caviar-113.4](https://github.com/caviyacht/SodaDungeon2Mod/releases/tag/v1.2.0b113-4)
- Current Beta Version: n/a

> ℹ️ Caviar's versioning is based on the game's build number (not the game's version).
>
> To find the game's build number, click the version number on the game's title screen (it's at the bottom). This is the version of Caviar to download.
>
> Example: The latest build of v1.1.1 is b106, so Caviar-106.x is the version to download.

## Instructions

Installing and uninstalling _(I guess this is goodbye?)_ Caviar is so simple, even you can do it! Just **READ** the instructions below and you'll be just fine... _I think_.

> ℹ️ According to a recent survey by a local mod author, it was found that reading the instructions can (and will) improve one's ability to install a mod correctly.
>
> Do yourself a favor and read the [instructions](#instructions) today!

### Installing Caviar

Installing Caviar is as easy as counting to 3... _and reading all of the warnings_.

> ⚠️ **INSTALLING THE INCORRECT VERSION CAN (AND WILL) FREEZE THE GAME**

1) Find the version of Caviar that you need in the [releases](https://github.com/caviyacht/SodaDungeon2Mod/releases) page (see the [versions](#versions) section regarding versioning)
   - Download the file: `Assembly-CSharp.dll`
2) Find your Soda Dungeon 2 installation folder
   - **I Know What I'm Doing:**
     - **Windows:** `C:\Program Files (x86)\Steam\steamapps\common\Soda Dungeon 2\SodaDungeon2_Data\Managed`
     - **Mac:** `~/Library/Application Support/Steam/steamapps/common/Soda Dungeon 2/SodaDungeon2.app/Contents/Resources/Data/Managed`
     - **Linux:** `~/.local/share/Steam/steamapps/common/Soda Dungeon 2/SodaDungeon2_Data/Managed`
   - **I Don't Know What I'm Doing:**
     - Open Steam
     - Find `Soda Dungeon 2` in your massive game list
     - Right-click `Soda Dungeon 2`, rollover `Manage`, and then click `Browse local files`
     - Navigate into `SodaDungeon2_Data`
     - Navigate into `Managed`
3) Copy the downloaded file, `Assembly-CSharp.dll`, from Step 1 into the directory from Step 2
   - Overwrite the file when prompted
   - If not prompted to overwrite, then make sure the file name is `Assembly-CSharp.dll` and try again

### Uninstalling Caviar

So, you've decided you want to leave? Let me show you the way out.

1) Open Steam
2) Find `Soda Dungeon 2` in your massive game list
3) Right-click `Soda Dungeon 2` and click `Properties`
4) In the modal, click `Local Files`
5) Click `Verify integrity of game files...`
6) Follow the prompts to revert the game back to its original form

## Known Issues

If there are any known issues, you'll find them here.

> ℹ️ There are currently no known issues other than the lack of reading the [instructions](#instructions).

## Features

Caviar has many features that will improve your quality of life while playing Soda Dungeon 2.

Just ask yourself these questions:

- Do you live and breathe gold?
- Do you drink from the Stein?
- Do you hate clicking?
- Do you love stats?
- If a tree falls in a forest and no one is around to hear it, does it make a sound?

If you answered **YES** to any of these questions, then Caviar is the mod for you!

### Adventure HUD UI

The following features update the Adventure HUD in the top-right of the screen while in the dungeon.

The Adventure HUD has two types of features: `Always-on` and `Toggleable`. The `Always-on` features are always displayed, while the `Toggleable` features can show/hide based on which view you want, but will always show something.

#### Always-on

##### Warp Bonus Counter (from Sword of Space and Time)

  - Displays the current warp bonus next to the dungeon floor number
    - Example: `123,456 (+123)`
  - Only displays if there are currently pending bonus warps

##### Elapsed Dungeon Time

  - Displays the current elapsed adventure time next to the dungeon floor number
    - Example: `123,456 | 01:23:45`

##### Floors per Hour (FPH)

  - Displays both FPH and FPH-warps at the same time
    - Example: `1234/567 FPH`

> ℹ️ Requires the Floors per Hour Oddity.

#### Toggleable

##### Castle Equivalent Floor (CEF) / Primal Lands Equivalent Floor (PEF)

  - Displays the current Castle/Primal Lands equivalent floor for the current dungeon floor
    - Example: `CEF 123,456` or `PEF 123,456`
  - Only displays in the dungeon
  - Click the dungeon floor number to toggle

> ℹ️ Due to the nature of the exponential scaling in the Primal Lands, the Castle Equivalent Floor might not update all the time, or it might look slightly off.

##### Gold per Hour (GPH)

  - Displays the current earned gold per hour
    - Example: `123.4 k GPH`
  - Only displays in the dungeon
  - Displayed by default

> ℹ️ The gold per hour is calculated by taking the current earned gold and dividing it by the current adventure elapsed time. This ends up just being an average and is ok for the Castle.
> 
> However, because of the exponential scaling in the Primal Lands, the gold per hour will be slightly off over a longer run.

##### Battle Credits per Hour (CPH)

  - Displays the current earned battle credits per hour
    - Example: `123 CPH` or `123.4 k GPH | 123 CPH`
  - Only displays when you have earned battle credits
  - Displayed by default

##### Relics per Hour (RPH)

  - Displays the current leveled relics per hour from Stein
    - Example: `123 RPH` or `123 HPH | 123 RPH`
  - Only displays when Stein has leved a relic
  - Click the `GPH` or `CPH` line to toggle

##### Heals/Cleanses per Hour (HPH)

  - Displays the current group heals and cleanses per hour
  - Format: `{group_heals}/{cleanses}`
    - Example: `123 HPH` or `123/4 HPH` or `0/123 HPH`
  - Only displays when you have group healed or cleansed
  - Click the `GPH` or `CPH` line to toggle

### Adventure Character UI

The following features update the character display while in the dungeon.

#### Character HP/MP Stats

- Displays the abbreviated number for HP and MP
  - Example: `123.4 q`
- Characters on the right have had their stats moved slightly to the left

### Adventure Results UI

The following features update the adventure results screen.

#### Enemies Killed

- Displays the breakdown of enemies killed by type
  - Format: `{norm}/{mini}/{boss}`
    - `{norm}` are the normal everyday mobs
    - `{mini}` are the mini-bosses
    - `{boss}` are the bosses
  - Example: `123/45/6`

#### Floors Completed

- Displays the breakdown of floors by type
  - Format: `{completed}/{warps}/{bonus}`
    - `completed` are the floors completed (previous behavior)
    - `warps` are the floors that were warped (does not include bonus)
    - `bonus` are the floors that were warped from the Sword of Space and Time
  - Example: `123/45/6`
- Only displays warps when warping
- Only displays bonus when warping and using the Sword of Space and Time

### Currency HUD

The following features update the currency hud (bottom of screen).

#### Battle Credits

- Displays the current battle credits alongside gold/keys/caps/essence

### Relic UI

The following features update the relic screen.

#### Level-up Buttons

- +10k button
- +100k button
- +1M button
- MAX button

> ⚠️ Be careful when using the `MAX button` as it is very CPU intensive and will cause the game to not respond for a while depending on how many levels it needs to calculate.
>
> If you have a lot of essence on-hand and know that it could level a relic for millions of levels, avoid navigating to the `MAX button` unless you know what you're doing and accept the consequences.
>
> See the [remarks](#remarks) section.

### Scripts UI

The following features update the scripts screen.

- Scripts sorted alphabetically by name

### Book Character UI

The following features update the book character screen.

- Scripts sorted alphabetically by name

## Beta Features

The following features are only found in the beta version of the mod.

### Title Screen

The following features update the title screen.

#### Beta Warning
  - Allows clicking to skip

## Deprecated Features

The following features have been removed from the mod due to either being not very useful, experimental, or were added to the official game itself.

### Adventure HUD UI

#### Leveled Gold Find Relic Counter

- Displayed the number of leveled Gold Find Relic from Stein

#### Essence per Hour (EPH)

- Displayed the essence per hour

### Battle Credits UI

#### Battle Credit Remembrance

- Remembers the previous battle credit amount (current session only)
- **ADDED TO OFFICIAL GAME**

### Scripts UI

#### Small Script Triggers 

- Reduces the size of the script triggers by half
- **ADDED TO OFFICIAL GAME**

## FAQ

Do you have a question? Well... I might have an answer for you.

### Q. I want th-

I don't care what you want. The answer is no.

### Q. I liked feature X, can you put it b-

I said no.

### Q. Why 'Caviar'?

Caviar is considered one of the finer things in life. It's also what the 'cavi' in 'caviyacht' stands for, so... yeah.

### Q. How often will Caviar update?

The `Live` version of the game will only be updated if there is currently not a beta active, and will only be updated if there is a **MUST** have feature that I need. The `Beta` version of the game will be updated any time I see a new feature I want to have and is generally updated more often.

### Q. The game doesn't load, what do I do?

More than likely this is caused by the downloaded dll having the incorrect name. Make sure that when you download the dll, it is named `Assembly-CSharp.dll`.

> ℹ️ If you have downloaded the mod before, there is a chance that the downloaded file will end up named `Assembly-CSharp (1).dll` upon downloading it again, if the previous file was still there.

## Remarks

I take no responsibility for anything you do. Always make a backup of the original dll and your save data before using Caviar, or any mod.

> ℹ️ If the mod does not work for some reason, it's you; not me. Check the [FAQ](#faq) for potential support.
>
> As always, remember to read the [instructions](#instructions).

## Credits

Thanks to Shawn for creating this game.
