## [中文版（施工中）](README-CHN.md)
# Arbiter-help

This repository serves for these purposes:
- Export the texts from Minesweeper Arbiter help file which is no longer supported by Microsoft.
- Share various settings, including Counters, Automation, etc.

Below are texts exported from `INDEX.HLP` with modification for markdown layout.
_______________________________________

Minesweeper Arbiter Readme File
Copyright 2005 Dmitriy I. Sukhomlynov
________________________________________

## Contents

- [1. Introduction](#1-introduction)
- [2. Menu](#2-menu)
  * [2.1. Game Menu](#21-game-menu)
    + [2.1.01. New](#2101-new)
    + [2.1.02. Play Video](#2102-play-video)
    + [2.1.03. Load Custom Board](#2103-load-custom-board)
    + [2.1.04. Save Custom Board](#2104-save-custom-board)
    + [2.1.05. Multiplayer Mod](#2105-multiplayer-mod)
    + [2.1.06. Beginner](#2106-beginner)
    + [2.1.07. Intermediate](#2107-intermediate)
    + [2.1.08. Expert](#2108-expert)
    + [2.1.09. Custom Board](#2109-custom-board)
    + [2.1.10. Local High Scores](#2110-local-high-scores)
    + [2.1.11. Statistics](#2111-statistics)
    + [2.1.12. Boss-Key](#2112-boss-key)
    + [2.1.13. Exit](#2113-exit)
  * [2.2. Options Menu](#22-options-menu)
    + [2.2.01. Preferences](#2201-preferences)
    + [2.2.02 Cheat Options](#2202-cheat-options)
    + [2.2.03. Language](#2203-language)
    + [2.2.04. Mouse / Open Mouse Control Panel](#2204-mouse---open-mouse-control-panel)
    + [2.2.05. Mouse / Increase or Decrease Sensitivity](#2205-mouse---increase-or-decrease-sensitivity)
    + [2.2.06. Mouse / Mouse Speed Accelerator](#2206-mouse---mouse-speed-accelerator)
    + [2.2.07. Show Debug Protocol](#2207-show-debug-protocol)
    + [2.2.08. Show Counters Window](#2208-show-counters-window)
    + [2.2.09. Screenshot / Make JPG Screenshot](#2209-screenshot---make-jpg-screenshot)
    + [2.2.10. Screenshot / Make BMP Screenshot](#2210-screenshot---make-bmp-screenshot)
    + [2.2.11. Plugins](#2211-plugins)
    + [2.2.12. Screenshot / Make FULL Screenshot](#2212-screenshot---make-full-screenshot)
    + [2.2.13. IRC addon](#2213-irc-addon)
    + [2.2.14. Community](#2214-community)
  * [2.3. Help Menu](#23-help-menu)
    + [2.3.1. Index](#231-index)
    + [2.3.2. About](#232-about)
- [3. Gameplay Definitions](#3-gameplay-definitions)
- [4. Preferences Window](#4-preferences-window)
  * [4.1. Player Setup](#41-player-setup)
    + [4.1.1. Player Identification Text](#411-player-identification-text)
    + [4.1.2. Replay Player Name](#412-replay-player-name)
    + [4.1.3. Default Replay File Name](#413-default-replay-file-name)
    + [4.1.4. Mode Names](#414-mode-names)
    + [4.1.5. Game History Log Checker](#415-game-history-log-checker)
    + [4.1.6. Country](#416-country)
  * [4.2. Game Style Setup](#42-game-style-setup)
    + [4.2.01. Startup Mode](#4201-startup-mode)
    + [4.2.02. Skin](#4202-skin)
    + [4.2.03. Timer Skin](#4203-timer-skin)
    + [4.2.04. Marks (?)](#4204-marks----)
    + [4.2.05. Tenths and Hundredths in Timer](#4205-tenths-and-hundredths-in-timer)
    + [4.2.06. Show Counters Window](#4206-show-counters-window)
    + [4.2.07. Show 3BV after Game Over](#4207-show-3bv-after-game-over)
    + [4.2.08. Board Clearance on Fail](#4208-board-clearance-on-fail)
    + [4.2.09. Board Clearance on Middle Mouse Click](#4209-board-clearance-on-middle-mouse-click)
    + [4.2.10. Fill Finished Boards with Flags](#4210-fill-finished-boards-with-flags)
    + [4.2.11. Show Equals in Statistics Tables](#4211-show-equals-in-statistics-tables)
  * [4.3. Cheat Mode](#43-cheat-mode)
    + [4.3.01. Disable Timer](#4301-disable-timer)
    + [4.3.02. Start Timer form Zero](#4302-start-timer-form-zero)
    + [4.3.03. Auto Flag Set at the Game Start](#4303-auto-flag-set-at-the-game-start)
    + [4.3.04. Disable Group Auto Open on DoubleClick](#4304-disable-group-auto-open-on-doubleclick)
    + [4.3.05. Disable Right Mouse Clicks](#4305-disable-right-mouse-clicks)
    + [4.3.06. Infinite Lives](#4306-infinite-lives)
    + [4.3.07. Show Mines Presence Probabilities](#4307-show-mines-presence-probabilities)
    + [4.3.08. Show Mines Positions](#4308-show-mines-positions)
    + [4.3.09. Show 3BV after the Game Start](#4309-show-3bv-after-the-game-start)
    + [4.3.10. Board Must Have 7](#4310-board-must-have-7)
    + [4.3.11. Board Must Have 8](#4311-board-must-have-8)
    + [4.3.12. 3BV <= Value](#4312-3bv----value)
  * [4.4. System Setup](#44-system-setup)
    + [4.4.1. Set High Process Priority](#441-set-high-process-priority)
    + [4.4.2. Enable Boss-Key](#442-enable-boss-key)
    + [4.4.3. Clip Cursor to the Board](#443-clip-cursor-to-the-board)
    + [4.4.4. Always on Top](#444-always-on-top)
    + [4.4.5. Prohibit Multiple Instances](#445-prohibit-multiple-instances)
    + [4.4.6. Justify Arbiter Windows by Center](#446-justify-arbiter-windows-by-center)
    + [4.4.7. Register Arbiter Video File Extension](#447-register-arbiter-video-file-extension)
    + [4.4.8. Create Desktop Shortcut](#448-create-desktop-shortcut)
  * [4.5. Language Setup](#45-language-setup)
  * [4.6. Automation Setup](#46-automation-setup)
    + [4.6.1. Replay save condition formula](#461-replay-save-condition-formula)
    + [4.6.2. Replay save filename formula](#462-replay-save-filename-formula)
  * [4.7. Multiplayer Setup](#47-multiplayer-setup)
- [5. Counters Window](#5-counters-window)
- [6.  Statistics](#6--statistics)
  * [6.01. Mode Review](#601-mode-review)
  * [6.02. Mode Top Time](#602-mode-top-time)
  * [6.03. Mode Top 3BV/s](#603-mode-top-3bv-s)
  * [6.04. Mode Times Review](#604-mode-times-review)
  * [6.05. Mode 3BV/s Review](#605-mode-3bv-s-review)
  * [6.06. Mode 3BV Review](#606-mode-3bv-review)
  * [6.07. Mode Style Chart](#607-mode-style-chart)
  * [6.08. Overall Style Chart](#608-overall-style-chart)
  * [6.09. Overall Games Chart](#609-overall-games-chart)
  * [6.10. Activity](#610-activity)
  * [6.11. Entire Statistics (debug info)](#611-entire-statistics--debug-info-)
  * [6.12. Setup](#612-setup)
    + [6.12.1. Save Full Statistics to HTML-file](#6121-save-full-statistics-to-html-file)
    + [6.12.2. Save Statistics (no debug) to HTML-file](#6122-save-statistics--no-debug--to-html-file)
    + [6.12.3. Backup History](#6123-backup-history)
    + [6.12.4. Restore History](#6124-restore-history)
    + [6.12.5. Clear History](#6125-clear-history)
    + [6.12.6. Load External History File](#6126-load-external-history-file)
  * [6.13. Search](#613-search)
- [7.  Replay Engine](#7--replay-engine)
- [8.  Debug Protocol](#8--debug-protocol)
- [9.  Antihack Features](#9--antihack-features)
- [10. Multiplayer Mod](#10-multiplayer-mod)
- [11. System Requirements](#11-system-requirements)
- [12. Known Bugs](#12-known-bugs)
- [13. Special Thanks](#13-special-thanks)
  * [13.1. Thanks for the help in program creation](#131-thanks-for-the-help-in-program-creation)
  * [13.2. Translation team :)](#132-translation-team---)
- [14. Future Enhancements](#14-future-enhancements)
- [15. Version Information](#15-version-information)

________________________________________
## 1. Introduction

  Minesweeper Arbiter is a Minesweeper type game, supposed to be identical to the original Windows(R) Minesweeper, but with many additional features and a great anti-hack abilities:

- considered friendly human interface
- a lot of additional game-style options
- cheat mode
- built-in replay engine
- full statistics + full stats search
- IRC scripting
- Plugins support!
- multilanguage support
- system integration support
- debug protocol
- board skin support
- multiplayer game support (-)
- minesweeper-type hack attacks detection engine
- 3-level encrypt engine

________________________________________
## 2. Menu

### 2.1. Game Menu

#### 2.1.01. New

  All the previous game data is cleared and the program is ready for a new game.
  Shortcut for this menu is [F2]

#### 2.1.02. Play Video

  The Arbiter Video File (.AVF) Open dialog is executed and, if you select a video file, the replay would be loaded and run.
  Shortcut for this menu is [F3]

#### 2.1.03. Load Custom Board

  You can load previously saved board and replay it (in Custom mode) as many times, as you wish.
  Full .MBF format support
  Shortcut for this menu is [Ctrl+C]

#### 2.1.04. Save Custom Board

  You can save any game board and to replay it (in Custom mode) in future as many times, as you wish. You can also share nice boards between other minesweepers.
  Full .MBF format support
  Shortcut for this menu is [Ctrl+C]


#### 2.1.05. Multiplayer Mod

  The Multiplayer Mod window would be shown
  Shortcut for this menu is [F4]
  NOTE: Multiplayer Mod is not written.

#### 2.1.06. Beginner

  The Beginner game mode is selected. In this mode board size is 8x8 cells and board has 10 hidden mines.
  Shortcut for this menu is [1]

#### 2.1.07. Intermediate

  The Intermediate game mode is selected. In this mode board size is 16x16 cells and board has 40 hidden mines.
  Shortcut for this menu is [2]

#### 2.1.08. Expert

  The Expert game mode is selected. In this mode board size is 30x16 cells and board has 99 hidden mines.
  Shortcut for this menu is [3]

#### 2.1.09. Custom Board

  The Custom game mode is selected. You can manually set the board size and mines density. Board sizes – up to 30x30 cells and mines density up to 99%. Custom mode is a cheat mode, however you CAN save your game replays but NOT logs to history. Of course, you could make the board screenshots too.
  NOTE: while playing or viewing replays on custom mode, the “custom” labels would be present in the board’s corners.
  Inside the Custom Board Size window you can save or load board preset files. Doubleclick on the preset in the list to load it.
  Shortcut for this menu is [4]

#### 2.1.10. Local High Scores

  In the Local High Scores window you can see the local high scores for three legal game modes. A high score includes a player name information and time-jump since previous high score time.
  You can reset your local high scores by pressing the Reset button.
  Remember, you couldn't restore your local high scores information if you reset it.
  Shortcut for this menu is [F6]

#### 2.1.11. Statistics

  The statistics window would be shown.
  For more information about Minesweeper Arbiter game Statistics see the Statistics chapter.
  Shortcut for this menu is [F7]

#### 2.1.12. Boss-Key

  So called Boss-Key option can immediately hide all the Minesweeper Arbiter windows and taskbar button.
  To restore game, simply press the shortcut button combination again.
  Shortcut for this menu is [Ctrl+F2]

#### 2.1.13. Exit

  The game would be terminated and all the preferences saved.
  Shortcut for this menu is [Alt+F4]


### 2.2. Options Menu

#### 2.2.01. Preferences

  Opens the Preferences window
  Shortcut for this menu is [F5]

#### 2.2.02 Cheat Options

  Opens the Preferences window with Cheat Mode Setup page opened.
  Shortcut for this menu is [C]

#### 2.2.03. Language

  Opens the Preferences window with Language Setup page opened.
  Shortcut for this menu is [L]

#### 2.2.04. Mouse / Open Mouse Control Panel

  Opens the Window Control Panel page with all Mouse settings.
  Shortcut for this menu is [M]

#### 2.2.05. Mouse / Increase or Decrease Sensitivity

  Allows you increase or decrease mouse sensitivity in the real time.
  NOTE: all changes would be applier after the next user logon.
  NOTE: currently trying to make this option REALTIME.
  Shortcuts for this menu are [Num +] and [Num -]

#### 2.2.06. Mouse / Mouse Speed Accelerator

  This is windows system control that allows to use or not to use the mouse movement accelerator.
  NOTE: all changes would be applier after the next user logon.
  NOTE: currently trying to make this option REALTIME.
  Shortcuts for this menu are [Ctrl + A] 

#### 2.2.07. Show Debug Protocol

  Opens the Debug Protocol window.
  Shortcut for this menu is [D]

#### 2.2.08. Show Counters Window

  Counters window would be shown even if this option is not checked in the Preferences. This option is useful when some other application covers the counters window.
  As Counters window has constant always on top state, it may be covered only by the new always on top application.
  There is not a shortcut for this menu.

#### 2.2.09. Screenshot / Make JPG Screenshot

  Sometimes it is interesting to save a good/bad/smart board image.
  Minesweeper Arbiter can help you!
  A game window screenshot in JPEG format would be saved in the Minesweeper Arbiter folder in \Screenshots\ subfolder.
  Screenshot filename is "ScreenShot_####.jpg", where #### are the numbers.
  Any screenshot file would not be overwritten while saving - file number would be increased.
  The default compression level is 100% - the highest JPEG quality.
  Shortcut for this menu is [F12]

#### 2.2.10. Screenshot / Make BMP Screenshot

  A game window screenshot in Windows(R) Bitmap format would be saved in the Minesweeper Arbiter folder in \Screenshots\ subfolder.
  Screenshot filename is "ScreenShot_####.bmp", where #### are the numbers.
  Any screenshot file would not be overwritten while saving - file number would be increased.
  Shortcut for this menu is [Ctrl+F12]

#### 2.2.11. Plugins

  Minesweeper Arbiter may support external plugins! If the “Seek Plugins at Startup” option selected, then all found plugins would be present in the plugins list. Feel the minesweeper emulation/support freedom!
  Plugins are available at the Minesweeper Arbiter homepage. If you want to create a new plugin, you may use a free demo plugin source code on Delphi or C++ Builder.

#### 2.2.12. Screenshot / Make FULL Screenshot

  The whole Screen screenshot in JPEG format would be saved in the Minesweeper Arbiter folder in \Screenshots\ subfolder.
  Screenshot filename is "ScreenShot_####.jpg", where #### are the numbers.
  Any screenshot file would not be overwritten while saving - file number would be increased.
  The default compression level is 100% - the highest JPEG quality.
  Shortcut for this menu is [Shift+F12]

#### 2.2.13. IRC addon

  If you want to tell your game scores, progression, or simply the last game information in the IRC chat, and you do not want just type in the numbers and other stuff, you may choose one of the IRC scripts to copy the needed statistic information to the clipboard, and after that you may simply paste this strings to the IRC chat message. All the strings are colorized in a random way, and all the numbers and valuable data is highlighted using bold text style.
  NOTE: You may choose between CGI and mIRC formating.
  Here is and example of a chat string:

* RILIAN My Arbiter game #1091 is: 90,53sec   3BV=135   3BV/s=1,50 mode=exp   "flagging"   rank: 1st time!, 20th 3bv/s

#### 2.2.14. Community

  This menu contains links to the most known Minesweeper Community websites.
  Websites would be opened with the system default browser.
  There is not any shortcut for Community Links Menu.
  You can send your feedback to the Minesweeper Arbiter Author by selecting the Feedback menu.


### 2.3. Help Menu

#### 2.3.1. Index

  This help file is shown
  The help provides you the full help about the Minesweeper Arbiter gameplay, configuration and features.
  Shortcut for this menu is [Ctrl+F1]

#### 2.3.2. About

  The Minesweeper Arbiter About window is opened.
  The About window contains the Author information, program version information, short game introduction, "thanks" list and anti-hack features list.
  Shortcut for this menu is [F1]

________________________________________
## 3. Gameplay Definitions

  MINESWEEPING - you should define all the mines positions without blasting on a mine.

  1½ CLICK METHOD – you may hold down the left or right mouse button and click with another (right or left) button as much as you wish, moving cursor over the game board and opening flagged areas. So you save some time to press up and down mouse buttons if you want to open few flagged areas.

  3BV VALUE - Bechtel's Board Benchmark Value. This value represents the minimal amount of left mouse clicks to open the board.
To calculate the board 3BV value you can sum the conditions:

 opening the hole (0 mines area) gives +1 bbbv,
 opening the cell from hole border does not give you a bbbv,
 all other cells gives +1 bbbv per cell.

  3BV/s VALUE - Bechtel's Board Benchmark Value per second. It is your actual Minesweeper game speed. Formula for calculations:

  3bv/s = 3bv / (time - 1) - when timer starts at 1.00 sec.
  3bv/s = 3bv / (time) - when timer starts at 0.00 sec (in Cheat Mode).

  BOARD GENERATION – when you press a New Game button, the board is not generated, but all the game-data is re-mutated to prevent the memory scan in the idle-runtime state. Only when you do the first left click on the board, all the mines are set to the board in the random way. If a mine was set to that cell, where the left click was done, this mine is not deleted nor moved to the left-top corner (or any defined board cell). Simply this mine is deleted and set to the random free board cell.
  Arbiter math module produces random numbers with Gaussian distribution about the mean.
  If there were set some flags before the main game start, all of them are cleared. This is made to prevent the super speed style when you (for example) set a flag, then click on the near cell, get “1” and do the right (double) click.

  DONE VALUE - every time you open a cell, the done value is calculated. This value represents the good cell openings (the valuable cells for victory, which are used to calculate the 3BV value)

  GAME MODE - Minesweeper Arbiter has 4 standard game modes: 

 Beginner (board 8x8, 10 mines)
 Intermediate (board 16x16, 40 mines)
 Expert (board 30x16, 99 mines)
 Custom Board (board 8..30x8..30, 1..891 mines)

  GAME RANK – when you finish a game, the time and 3BV/s ranks of this game are calculated. The game number for the current play mode is calculated too. The game rank is shown in the caption of the main window.

  ESTIMATED TIME - while you are sweeping, the Minesweeper Arbiter can estimate your time for the whole game completion. If you blast on a mine, this value can help you to define your quickness.

  MBF FILE – Minesweeper Board File. Format specifications: binary file:
[BoardWidth=1..255] [BoardHeight=1..255] [MinesCount div 256] [MinesCound mod 256] [First_MinePositionX=0..255][First_MinePositionY=0..255] … [Last_MinePositionX=0..255] [Last_MinePositionY=0..255].

  MINIMIZE FEATURE – when you minimize the board when the timer is active, then the timer would be stopped. It would run again when you restore window. So, there is a screenscot trick. In the hard situation you may do a board screenshot (F12), minimize the board and try to find the solution using the screenshot. When you find it – restore board and resume the game.

  REPLAY DATA STAMP - the visible part of replay file, made for minesweeper administrators/arbiters. it can be found in the first 512 bytes of replay file. Data stamp contains the game date, hour, 3bv value, solved 3bv value and game time value. Data Stamp value is independent from the other replay file. The actual replay information is not read from the Data Stamp while loading.

  TIME - the time you use to win a game. Note, that in legal game mode (without using cheat options) the game time is the real time passed + 1 second. For example, if you win a game with real time = 5,50 seconds, then game time value would be 6,50 seconds.

________________________________________
## 4. Preferences Window

  You can select one of 7 Preferences Pages:

  Player Setup
  Game Style Setup
  Cheat Mode Setup
  System Setup
  Language Setup
  Automation Setup
  Multiplayer Setup

  You can set the default Preferences by pressing button Default.
  When you press Cancel button, any changes in the Preferences are canceled.
  Apply button used to apply changed preferences.


### 4.1. Player Setup

#### 4.1.1. Player Identification Text

  This string is used to identify the player and player's replay file author. You can use any characters in this string.
  You may choose to show the ID label or not, checking the proper checkbox. If not selected, then the Arbiter interface would be exactly similar to the original Minesweeper interface.

#### 4.1.2. Replay Player Name

  This string is used to identify the player. In general, this string is not significant, because the player name is used only in the file names.
  All the incorrect for the file name symbols like :"/\<> etc would be changed to "_" symbol when saving the replay file. The player name would not be changed in this case.

#### 4.1.3. Default Replay File Name

  This is the formula to create a replay file name. You can use the defined patterns like <time> and any symbols (except :"<>/\ etc) beside the patterns.
  When you finish or fail the game, a button to Save Replay appears on the Counters window. And the default replay name is used in the save dialog when you press the Save Replay button.
  All the incorrect for the file name symbols like :"/\<> etc would be changed to "_" symbol when saving the replay file.
  You can use this patterns in the replay file names:

<NAME> - player name
<MODE> - game mode - beg/int/exp/custom
<TIME> - game time in format "xxx,xx"
<INTTIME> - game time in integer format
<COMPLETION> - board opening completion in percents
<3BV> - 3bv value
<3BV/S> - 3bv/s value in format "xx,xx"
<HH> - current hour in format "xx"
<MIN> - current minute number in format "xx"
<SEC> - current second number in format "xx"
<DD> - current day number in format "xx"
<DDD> - current day of week in format "xxx" (sun, mon  etc)
<MM> - current month number
<MMM> - current month in format "xxx" (jan, feb  etc)
<MMMM> - current month full name
<YY> - current year number in format "xx"
<YYYY> - current year number

  The default filename string is
  "<mode>_<time>_3BV=<3bv>_<name>"

  So, the replay file name would be like
  Path+"Beg_3,21_3BV=5_Yourname.AVF"

  NOTE: you may add the Folder to the filename in format, using “\” symbol
  "Foldername\<mode>_<time>_3BV=<3bv>_<name>"

  NOTE: you may use only one subfolder. Linked paths like \folder1\folder2\ are prohibited.

  NOTE: you may store the played boards automatically. Just add in the replay filename the <board> pattern in any place. Then, if the condition would be accepted, the board would be saved in the \boards\ subfolder in the ABF/MBF (Minesweeper Board File) file format.

#### 4.1.4. Mode Names

  These strings are used in the replay file name pattern <MODE> instead of default mode names: Beg, Int, Exp
  All the incorrect for the file name symbols like :"/\<> etc would be changed to "_" symbol when saving the replay file.
  NOTE: all custom game mode names would be set in the format
“Custom_<width>x<height>_<mines>”

#### 4.1.5. Game History Log Checker

  If selected, after every success game the game information like date, time, 3bv, 3bv/s, game-style etc would be saved in the history file.
  It is strongly recommended to check this option on!

#### 4.1.6. Country

  If you want your Country's Flag be shown when you are playing or when your replay is played, then select your country.
  If your Country Flag is not present in the Country list, then, please, send the request to the Author and include in the e-mail your flag's picture in format BMP and with size 24x16 pixels (the image must have the black 1 pixel border). Then the new version of Minesweeper Arbiter would be released with your Country Flag included in the list.
  If you do not want to see any flag in your Minesweeper Arbiter game window, select the (N/A) country in the list.


### 4.2. Game Style Setup

#### 4.2.01. Startup Mode

  You can select the startup mode.
  Note, that the Startup Mode value is re-saved after every Minesweeper Arbiter close.

#### 4.2.02. Skin

  You can select the board skin. To prevent the OCR-scan hack attacks, only one skin is supported now.
  The skin and the OCR Mutate Engine are independent each from other.

#### 4.2.03. Timer Skin

  You can select the timer indicator skin.
  Now there are 2 timer skins:

  Minesweeper Original skin
  Predator Number skin

#### 4.2.04. Marks (?)

  Serious minesweepers do not use this option.
  When you put a flag on the board and you are not sure that that cell contains a bomb, you can mark the cell like a "?" symbol by pressing the right mouse button above the cell.

#### 4.2.05. Tenths and Hundredths in Timer

  The time indicator can show the time value in formats:

  x.xx
  xx.x
  xxx

#### 4.2.06. Show Counters Window

  The Counters Window would be shown.
  For more information see the part 5. Counters Window

#### 4.2.07. Show 3BV after Game Over

  When you finish the game, the 3bv, 3bv/s, estimated time, solved cells indicator would be shown in the Counters window.

#### 4.2.08. Board Clearance on Fail

  When you blast on a mine, the board immediately would be prepared for a new game, so you should not move mouse to the yellow face button or press the new game button or F2 to start the new game.
  Minesweeper Arbiter provides you the real speed!
  More game time - more experience - more success.
  You could not save your fail-replay when this option is checked, because all the data is cleared and re-mutated when a new game is prepared.

#### 4.2.09. Board Clearance on Middle Mouse Click

  When you press the middle mouse button, the board immediately would be prepared for a new game, so you should not move mouse to the yellow face button or press the new game button or F2 to start the new game.
  Minesweeper Arbiter provides you the real speed!
  More game time - more experience - more success.


#### 4.2.10. Fill Finished Boards with Flags

  When finish the original Minesweeper game, all not-flagged cells at the board are filled with the flags. In this case, you can not define, how much flags you have used to play the board. But, in fact, you would not chaotically search the unopened cell when the game has been finished already. So, you may choose, to fill the flags in the finished board, or not.

#### 4.2.11. Show Equals in Statistics Tables

  When browsing the Statistics Top Times and Top 3BV/s you may choose to show or not to show the equal values. When the option is selected, ALL the times and 3bv/s in the tables would be listed, with the equals. They would be sorted only by the game date. In other case, you will see only the different values. Actually, only the first (by the game date) appearance of the equal time or 3bv/s would be in the list.


### 4.3. Cheat Mode

  If you do not want to save your game replays, to log the history and to gain the high scores - you can use the cool cheat options for the maximal enjoy of the Minesweeper Arbiter game.
  NOTE: All the Cheat Options are checked off when a replay file is loaded.

#### 4.3.01. Disable Timer

  If you do not want to estimate your game speed, you can disable the timer indicator and play as long, as you wish.

#### 4.3.02. Start Timer form Zero

  As you can see, the legal game time is calculated like the actual game time plus one second. It was made to prohibit scores like 0 seconds etc.
  If you want to know your actual game time - use this option.

#### 4.3.03. Auto Flag Set at the Game Start

  When you start the game, all the mines-cells are marked with the flags.

#### 4.3.04. Disable Group Auto Open on DoubleClick

  Double Click means the left-right, right-left click sequence or the middle mouse button click. If you do not want to use the legal game accelerations - use this option.

#### 4.3.05. Disable Right Mouse Clicks

  The right Mouse clicks are disabled.
  It is the best Non-Flag style teacher, especially with the "infinite lives" option.

#### 4.3.06. Infinite Lives

  When you try to open the cell with the mine - you would not fail the game and the mine would not blast.

#### 4.3.07. Show Mines Presence Probabilities

  When you do the left mouse down, the mine presence in the clicked cell is calculated. If the mine presence probability is more than 50%, then the cell would be marked with the red square. When mpp < 50% - you would get the green led. In other cases you would get the yellow led.
  The showing mpp after the click is caused to prevent the OCR scan.

#### 4.3.08. Show Mines Positions

  This option allows you to see the mines positions when you are playing.

#### 4.3.09. Show 3BV after the Game Start

  When you start the game and during the whole game all the information in the Counters window is shown.

#### 4.3.10. Board Must Have 7

  The board generation would be restarted for approximation attempts * 1000 times or until the board would have the "7" cell.
  About the approximation value see the part 4.3.11.

#### 4.3.11. Board Must Have 8

  The board generation would be restarted for approximation attempts * 1000 times or until the board would have the "8" cell.
  About the approximation value see the part 4.3.11.

#### 4.3.12. 3BV <= Value

  If you want to play the board with the preferred 3bv value, then you should select the 3bv value and the quantity of approximation attempts * 1000.


### 4.4. System Setup

#### 4.4.1. Set High Process Priority

  Minesweeper Arbiter system process status would be set to the High Priority.
  When some idle programs need the system resources like CPU time, GDI, RAM etc, then this resources could be taken at the other programs. Setting the High Priority process status would prevent the Arbiter system resource grab and, as a result, any slowdown. 

#### 4.4.2. Enable Boss-Key

  So called Boss-Key option can immediately hide all the Minesweeper Arbiter windows and taskbar button.
  
#### 4.4.3. Clip Cursor to the Board

  When you are playing like a maniac and your cursor often appears outside of the board, this option can help you to prevent this problem. Usually, when on the beginning of a game, most players tend to click randomly in order to find openings, and it is not difficult to click outside the main window. By checking this option, your cursor would be always inside the game board borders.
  NOTE: the cursor is clipped only when timer is active.

#### 4.4.4. Always on Top

  If you want to be always on the top of the bestever sweepers list, this option can help you! All your time scores would be divided by 2! :-)
  Also, this option provides the always on top window state to all the Minesweeper Arbiter’s windows.

#### 4.4.5. Prohibit Multiple Instances

  This option prevents loading of 2 or more Minesweeper Arbiters at the same time.

#### 4.4.6. Justify Arbiter Windows by Center

  The Main Arbiter window would be justified by the screen center.

#### 4.4.7. Register Arbiter Video File Extension

  If you register the AVF files in your system (WinAll) then you could be able to open the replay files just from the file explorer.
  NOTE: to delete Minesweeper Arbiter registry entries, run regedit.exe and delete 2 registry nodes by mask "avf".

#### 4.4.8. Create Desktop Shortcut

  A shortcut for the Minesweeper Arbiter would be created in the Desktop folder. The shortcut name is "Minesweeper Arbiter".


### 4.5. Language Setup

  Just select preferred language file.
  If you want to translate the Minesweeper Arbiter to your language, then, please, see the instructions in the “_English.lng” language file.

### 4.6. Automation Setup

  Your replays could be saved automatically in the "silent" mode.
  If the replay file was automatically saved, then in the right-bottom corner of the Counters window would appear the label "SAVED".
  You can build up to 3 rules for replay file automatic saving. For every rule you should note the condition formula for saving and the file name formula.

#### 4.6.1. Replay save condition formula

  This is the formula to create a replay file save conditions. You can use the defined patterns and spaces beside them.
  Note, that most patterns MUST HAVE "AND" or "OR" part.
  The pattern must have this format:

  <pattern name>=<integer or real value>

  You can use this patterns in the replay save condition formulas:

<MODE> - the game mode. The only variants: "mode=1", "mode=2", "mode=3"
<AND TIME> - integer time value in seconds
<OR TIME> - integer time value in seconds
<AND 3BV> - integer 3BV value
<OR 3BV> - integer 3BV value
<AND 3BV/S> - 3BV/s value. May be in integer format or in real format.
<OR 3BV/S> - 3BV/s value. May be in integer format or in real format.
<AND COMPLETION> - integer value of board completion in percents
<OR COMPLETION> - integer value of board completion in percents

  You can use any relation symbols:  <  >  =  >=  <=  <>

  NOTE: the floating point separator in the conditions is comma (",") symbol!
  Examples: "and 3bv/s>=1"   "and 3bv/s>=1,8"
  All non-significant symbols in formulas are ignored.

  The default save condition string (for Beginner mode) is 
  "mode=1 and time<15 and completion=100"

#### 4.6.2. Replay save filename formula

  For the file formula information, please, see the help file 
  part 4.1.3. Default Replay File Name.


### 4.7. Multiplayer Setup

  The Multiplayer Mod is not defined/written yet.

________________________________________
## 5. Counters Window

  When you check on the option to show counters window at game start, then this window is shown. You can easily drag and drop counters window in any screen place. Just do the left click and move a cursor.
  Counters window is used to output the game data: quantity of left, right, double clicks; board 3BV value; estimated 3BV/s and time values. In legal mode when you play, you can see only the clicks variables. When you blast or win a game, all other data is shown and in legal mode else appears the button to save the replay. When replay is manually or automatically saved, a label "saved" appears.
  In cheat mode you can set the option to show the counters additional data by checking on the option to show 3bv information after game start. You can use this option in cases when you want to play on a low or high 3BV and to know this value before the game.

________________________________________
## 6.  Statistics

  Minesweeper Arbiter provides a full game statistics. Information about every finished game is stored in a history file, if the Game History Log option is checked on. With the entire collection of games, you can select tables or charts that give a full statistics about the player speed, game times, 3BV distribution, style and other (including average) parameters.
  The entire statistics is split to full mode statistics, overall style chart, activity chart, entire debug list and setup panel.
  You can save current grid to HTML-file by pressing the Save Grid button at the top-left window corner.

### 6.01. Mode Review

  This grid provides you the information about playing on selected legal mode (beginner, intermediate, expert):
 * total number of games
 * number of games in flag-style
 * number of games in non-flag-style
 * full success game time on current mode
 * best, average, worst time on current mode
 * best, average, worst 3BV/s on current mode
 * least, average, worst 3BV that came on current mode

### 6.02. Mode Top Time

  This is the list of your game times on current mode, sorted by time. Every time value has information about the date and hour of play, 3BV, 3BV/s and style information.
  If you have 2 games played with equal times, then in the Top Time table would be shown the first appearance in history of that time.

### 6.03. Mode Top 3BV/s

  This is the list of your game 3BV/s on current mode, sorted by 3BV/s. Every 3BV/s value has information about the date and hour of play, 3BV, time and style information.
  If you have 2 games played with equal 3BV/s, then in the Top 3BV/s table would be shown the first appearance in history of that 3BV/s.

### 6.04. Mode Times Review

  This is the list of number of games played with the same (integer value of) time. Except total number of games, for every time value is provided additional information:
  * average time value 
  * minimal, average, maximal 3BV/s value
  * minimal, average, maximal 3BV value

### 6.05. Mode 3BV/s Review

  This is the list of number of games played with the same (with tenths) 3BV/s. Except total number of games, for every 3BV/s value is provided additional information:
  * average 3BV/s value 
  * minimal, average, maximal time value
  * minimal, average, maximal 3BV value

### 6.06. Mode 3BV Review

  This is the list of number of games played with the same 3BV values. Except total number of games, for every 3BV value is provided additional information:
  * minimal, average, maximal time value
  * minimal, average, maximal 3BV/s value

### 6.07. Mode Style Chart

  This is a proportion between the number of your games played with flag-style and non-flag.
  You can click on the chart to stop the animation.
  NOTE: In order to draw correctly the chart-pie, if number of flag-style and non-flag-style games is equal, then increasing flag-style number by 1. This bug is provided by chart component draw procedures.

### 6.08. Overall Style Chart

  The same like Mode Style Chart but for all games.

### 6.09. Overall Games Chart

  This is the chart of total number of games for all modes.

### 6.10. Activity

  This is your total activity of playing (and winning) Minesweeper Arbiter.
  This table also provides your full game time information.
  For Every hour, day of week and month there is information:
  * total number of games
  * the same in percents
  * total game time

### 6.11. Entire Statistics (debug info)

  This is all your sweeping history, sorted by the inverted game date/hour.

### 6.12. Setup

#### 6.12.1. Save Full Statistics to HTML-file

  All the statistics including entire games list would be saved to the HTML-file that you selected.

#### 6.12.2. Save Statistics (no debug) to HTML-file

  All the statistics without entire games list would be saved to the HTML-file that you selected.

#### 6.12.3. Backup History

  If you want to backup you current history, then the history file would be copied to "history_backup_<date>" file.

#### 6.12.4. Restore History

  If your current history file is corrupted (by who?), you can simply restore your previously saved history file.

#### 6.12.5. Clear History

  If you want to clear your entire history, then it’d be deleted forever.
  NOTE: Do not forget to backup your history before you delete it. If you deleted all your history files, even the Minesweeper Arbiter Author could not restore them.  

#### 6.12.6. Load External History File

  You may load an external history file, if you want to browse it. The Minesweeper Arbiter and Minesweeper Clone history file both supported.

  DAT – the extension of a Minesweeper Arbiter history file.
  INF  - the extension of a Minesweeper Clone history file.

  NOTE: the correctness of the Minesweeper Clone history file is not checked, only the file size.
  NOTE: the current Minesweeper Arbiter history would be reloaded after you close the history window.

### 6.13. Search

  You may input ANY statistics search parameters and select proper check-boxes. Then, just press [Search] button and choose the sorting style. Of course, you may save the searched table to an HTML-file.
  NOTE: you can not sort the table by the day-times; to sort the table by the date, just press the search button again (if you already done another sorting style).

________________________________________
## 7.  Replay Engine

  One of the main Minesweeper Arbiter features is built-in replay engine (works only for legal mode: beg, int, exp and clear custom game without cheat options).
  When you play, all your mouse clicks and moves are carefully remembered and after the game end saved to the replay file (.AVF - Arbiter Video File). After that you can easily load and play your replay file using Load Replay menu, button [F3] or simply executing replay file from the shell (WinAll).
  A replay file is the most efficient way to prove your game scores. All your player information like nickname, country etc is saved (and encrypted too) in the replay file as well as the replay data stamp, so it's very easy to identify the replay author.
  To switch On the ability to run replay files from the shell (WinAll) you should register the AVF extension using a command from Preferences/System page.

  NOTE: your replay is stored like full-pattern replay for best understanding of your moves. The engine is made in this way because when recording only (for example) on_time patterns, then most of your mouse moves (especially if you are a fast minesweeper) are simply not recorded and true replay picture is lost. Replay played in normal speed. You may use the play speed tracker in 0.05x – 5.00x interval.
  NOTE: replay file is well encrypted using independent parallel checksums and 128-bit checksum for the whole file. Also, the file creation system-time is hidden in the file, so when you change any file part, Arbiter administrator will easily detect this. And if you change any of the file parts, your replay would not run even on your platform.
  NOTE: replay files may be dramatically compressed with archievers, for example winRAR – 8%.

________________________________________
## 8.  Debug Protocol

  The debug protocol is used to log all the Minesweeper Arbiter engine information, messages, debug messages, hack detection etc. And all the board parameters for every game are logged in the protocol too.
  When the Arbiter system crashes or hack attack is detected, the debug protocol is saved to the Minesweeper Arbiter default folder and after that the system is terminated.
  Debug protocol also provides some debug commands. To access them, just press [Enter] or use menu Command [Enter]

"<mode> 3bv distribution table <type>" is used to list the random 3bv value distribution for every mode. You can see the borders of mode-available 3bv values or something like that.
  The "easy"-type command generates 100.000 boards.
  The "full"-type command generates 1.000.000 boards.
  The faster your processor - the less time the calculations take.

“get_cpu_speed” calculates your processor speed in MHz. Calculation takes 500 milliseconds

________________________________________
## 9.  Antihack Features

  One of the main Minesweeper Arbiter usage purposes is strong antihack system.
  Every antihack system has been passed QA tests.
  Author provides only basic attack/defense information to prevent hack enhancements.
  If you wish to know more about some minesweeper-type attack/defense engines, use feedback system.
  PE - portable executable file.
  ATTACK - minesweeper-game type attack.

  Detectable hack attacks/exploits list:

  File Decryption
  ATTACK: decrypt the PE and change some code.
  DEFENSE: when the PE was compiled and compressed, the polymorphs encrypt code was used. After that some PE code was rewritten in the taken file. So, before disasm /you/ should decrypt all the data.

  File Resource Hack
  ATTACK: extract/reload PE image/string/dialog resources.
  DEFENSE: the PE crypt was used to protect the PE res.

  File Patch
  ATTACK: change PE image/string/dialog resources.
  DEFENSE: the PE crypt / checksums were used to protect the PE res.

  Memory Access
  ATTACK: read program runtime memory.
  DEFENSE: polymorph runtime data store system used. In the idle mode all the main data is mutated. Different random variables used for different games.

  Memory Freeze
  ATTACK: find where the game data memory is stored. Replace values with constant ones.
  DEFENSE: 3 levels of checksums: data checksums are well stored just after every valid data operations. And read before.

  Memory Pre-definition
  ATTACK: pre-define program data, for example mines coords.
  DEFENSE: game data restore/usage only in play mode. In idle mode all the data is mutated and changes would not take effect except checksum mismatch.

  WinAPI OCR scan
  ATTACK: <information access prohibited>
  DEFENSE: board mutation engine.

  WinAPI Sendmessage
  ATTACK: sending API message where to click or like that.
  DEFENSE: sender check used. Random-type variables are used like a sender for different games.

  WinAPI Brutal Overmind
  ATTACK: <information access prohibited>
  DEFENSE: <information access prohibited>

  WinAPI Handle Access
  ATTACK: access to runtime handle variable to change the API params.
  DEFENSE: primitive handle mutator based on the handle-read prevention. Memory mutation system.

  WinAPI Script Lock
  ATTACK: erase/stop the procedure PE/runtime code.
  DEFENSE: most procedures have start/end checksums.

  WinAPI Hotkey Access
  ATTACK: use custom hotkeys for /your/ hack-tool.
  DEFENSE: hotkey API globalysator.

  WinAPI Alphablending
  ATTACK: read main game data, set program to transparent mode, provide /your/ map behind the program window.
  DEFENSE: memory polymorph storage and idle mutation used.

  1. Any program has at least one error.
  2. If a program has not error, read RTFM.
  3. Most bugs are features.

________________________________________
## 10. Multiplayer Mod

  Multiplayer is not defined/written yet. :-)
  NOTE: minesweeper multiplayer concept is developed (June 2005).

________________________________________
## 11. System Requirements

  OS WinAll
  Pentium 200 Mhz
  32 MB of free RAM
  2 MB of free Video-RAM
  2 MB of free disk space to store replays

  You can get your system parameters list by saving a debug protocol's initial part.
  You can estimate your CPU speed using debug command Get_CPU_Speed

________________________________________
## 12. Known Bugs

  Some bugs are pleasantly provided by the OS WinAll, others - by I/O routines.

- PRODUCE: it is unable to detect the releasing of right_mouse_button when player does right_mouse_down on the board, then moves cursor out of the game board, then releases right_mouse_button. If you do this sequence, you would get the right_mouse_button_is_down=true state.
  SOLVE: solving this problem (with no final result) took at the author 14 days of "no releasing the game". It's unable to solve in windows platform.

- PRODUCE: it is unable to detect the releasing of middle_mouse_button when player does middle_mouse_down on the board, then moves cursor out of the game board, then releases middle_mouse_button. If you do this sequence, you would get the middle_mouse_button_is_down=true state.
  SOLVE: solving this problem (with no final result) took at the author 14 days of "no releasing the game". It's unable to solve in windows platform.

- PRODUCE: when replay file size > 500 KB then the replay load error MAY OCCUR. The same: when replay time approximately more than 350 seconds.
  SOLVE: Not found yet.

- PRODUCE: a "256" bug may occur when loading replay. It is a "warning" bug and does not affect on the replay load/run procedures. Relax, you can not see whether this bug occurs, only the program Author can.
  SOLVE: Hidden and conservated.

  NOTE: use feedback feature to report a bug.

________________________________________
## 13. Special Thanks

### 13.1. Thanks for the help in program creation

Vladimir Ogurtsov (Ukraine) for the general arbiter project help
Vladimir Puzanov (Ukraine) for some WinAPI ideas and web hosting
Rodrigo Camargo (Brazil) for some interface solutions and some options ideas
Sorin Manea (Romania) for the counters window idea and replay-engine idea
Gregoire Duffez (France) for 3bv/s formula correction and stats ideas
Stephen Arnason (Canada) for the important 1½ click method bug found
Marko Jeznik (Slovenia) for the critical bug described and some features ideas
Curtis Bright (Canada) for some interface bugs found and described
Stevan Gvozdenovic (Montenegro) for the flags help and some bug detection help
Elmar Zimmermann (Germany) for some IRC script format examples
Dan Cerveny (USA) for some IRC script format examples
Alain Rousseau (France) for some external history file browsing ideas
Yaeli Amir (Israel) for some feature ideas and replay engine debugging help


### 13.2. Translation team :)

ENG Author

________________________________________
## 14. Future Enhancements

* replay "I/O 300K" and "256 bug" debug
* Linux porting… hum… not too easy… Kylix failed
(+thanks Sok Ann Yap)
* auto stop game on <level><time> (no sense?????)
* not log history on <level><time> (no sense?????)
* multiplayer mod (use udp)
* 3bv/s chart
* loop replay checker - if checked and eof then press restart button
* mouse id text
* notifications mod
* clone plugin
* on/off - show the timer indicator
* load best times/jump from history

NOTE: use feedback feature to add your cool idea/option/etc.

________________________________________
## 15. Version Information

  * means the fix
  + a new feature
  - known bug, new future idea or something like that

Alpha 0.00 (14.01.2005)
+ human interface
(+thanks Rodrigo Camargo)

Alpha 0.01 (17.01.2005)
+ works like simple minesweeper but with hack-protection
+ memory freeze mutator!

Alpha 0.02 (23.01.2005)
+ 60% of options work properly
+ preferences save/load engine
+ about window

Alpha 0.03 (25.01.2005)
* more bug fix
+ more compares added
+ more lamer protection
+ system process priority changer
+ windows registry edition

Beta 0.04 (28.01.2005)
It’s beta version now - all works, no replays
+ (so writing took 14 days)
+ whole statistics procedures and grids written 
+ alphablending detection disabled as useless 'cos of memory mutation engine

Beta 0.05 (30.01.2005)
* fixed formula for 3bvs calculations: 3bvs=3bv/(time-<time_state>)
(+thanks Gregoire Duffez)
+ even more additional statistics
+ language engine complete (253 strings)
+ history encryption
+ skins engine
+ OCR-scan mutator engine!
+ API sendmessage hack detection
(+thanks Vladimir Puzanov)
+ all overflow bugs defined
+ processor usage attack detection
+ multiplayer options/mod defined and conservated
+ replay base-procedures. debug replay written
+ replay file format defined
+ automation pre-base-definitions
+ community links
- left replays
- .avf extension support
- left automation analysator
- automation conservated
- multiplayer

Beta 0.06 (01.02.05)
+ full arbiter video file (.avf) extension support
+ replay_name variable added
+ replay window upgrade
+ initial replay
+ replay game info visible stamp
+ buggy replay load/save procedures
+ .avf-file encryption
+ free disk space probe
+ about information protection/encryption
+ replay program info stamp
+ some human interface ideas
+ history file format changed, more encryption
+ history language_strings added
- left replays
- left automation analysator
- multiplayer
- development progress slowing (replay problems)
- bug with expert stats grid found

Beta 0.07 (03.02.05)
* bug with grid stats fixed for sure
* replay file format finally fixed and encrypted
+ redefine replay file format
+ replay file format mutator added
+ replay file checksum added
+ added community links
- extra-large replay load bugs ~2.5 MB time=990 found
- disabled replay speed tracker (conservation)
- left replays
- left automation analysator
- multiplayer (define use UPD + winsock2)
- idea add (future) submit replays window - simple mailer

Beta 0.08 (04.02.05)
* corrected while-game mouse_move stops detection
* replay-cursor alignment fixed
+ replay_speed tracker works in interval 0.05 - 2.00 seconds
+ buuuuggy replays work
- unknown replay save/load bug - file checksum check canceled !!!
- large replay file checksum bug [~2.5 MB time=999] found
- automation analysator
- multiplayer (define use UPD + winsock2)
- idea add (future) to grid daily time / 3bv/s evolution
- idea add (future) auto stop game on <level><time>

Beta 0.09 (07.02.05)
* fixed replay saving when 3bv = 1, time=1,00. used 3bv/s=99,99
* fixed mouse coords in replay saving
* fixed few small bugs in is_replay_mode check
* fixed that all flags, if they were set to the board before the first left click, are cleared. Author doesn't see any sense to save them.
* fixed that equal times or 3bv/ss not shown in top lists
+ add numbers to the top time and 3bv/s lists
+ few human interface improvements
+ buuuuggy replays work
+ country flag support
+ add replay save filename conditions  support
+ add mode names in filename conditions
+ automatically rename symbols /\:*?'"<>| to "_" in the filenames
+ language file additional strings - now 255
+ auto increment filename to "name_(###)" if a same file exists
- known bug that in replay end time shown like time+0.01 sec

Pre-release 0.10 (10.02.05)
It’s pre-release version now
* replay great fix/debug
* replay mouse coords values fixed finally (i hope)
* fixed first mouse_down in replays
* fixed replay loading procedure
* fixed replay end timer indication
* about window text rewritten
* time indication fixed
* replay_add_mouse_button_action procedures fixed (coords)
* if while game cursor goes out of borders -> stop it in replay
+ history format changed. size reduced by 30%
+ history encryption format changed
+ added ability to save statistics to html-files
+ not refresh board on_mouse_move when replay speed > 1,00x
+ added link to www.ttp.unicyb.kiev.ua - homepage
+ redefine replay speed indicator
+ initial replay position indication tracking
+ added replay 5,00x speed
+ changed 3bv restriction to <= value (was =)
+ UPX file PE compression/encryption
(+thanks http://upx.sourceforge.net)
+ replay load/save bug checksum delta included for incorrect but true files
- idea (future) out_game video recording to avi-file
- board mutation engine upgrade to real mutation
- replay file checksum bug detected but not found !!! this bug is found 100% in large replay file with time ~ 999 sec. for files ~300 sec bug not found (yet 8-))

RELEASE 0.11 (12.02.2005)
It’s release version now !
* replay coords finally fixed again
* fixed replay mouse clicks
* correct high score replay saving
* great replay debug
* do_replay procedure optimized
* replay coords fixed again
* replay time representation when blast finally fixed
+ full replay save automation condition engine written
+ part of help file data written
- no multiplayer
- not defined "large time" checksum bug

RELEASE 0.12 (15.02.2005)
* A GLOBAL REPLAY BUG FINALLY DETECTED & FIXED (01:53 13.02.05)!!!!!!
* more replay coords corrections (final?)
* KNOWN BUG LIST ADDED. PLEASE, REVIEW IT TO PREVENT GETTING BUGS!!!!
* fixed integer values indication in counters window: format x,xx
* some security fixes
+ replay progress made like "PATTERN 1.00x speed playing"!!
 (for the best knowledge)!!!
+ minor interface improvements
+ more data stamp in replay file. see help part 3. REPLAY DATA STAMP
+ added global replay file checksum: header at the file end
+ known "1280" bug renamed to "256" bug and conservated
+ 4 parts of help file written
+ additional 128-bit replay file checksum
+ replay time correctness check procedure added
+ some small corrections in debug win/blast messages
+ more help file written
+ more board mutation
+ some board optimizations

RELEASE 0.13 (20.02.05)
* image_reload slowdown fixed for big boards
* fixed estimated time indication when blast
* fixed float values in automation conditions: format xx,xx or xx
+ board reload optimization: refreshing only changed cells
+ cpu_usage_attack detection disabled as senseless cos of
+ timer now synchronizes from BIOS!
+ game reset when the preferences window opened
+ more help file written
- idea to implement parallel DirectX_7 Minesweeper Arbiter

RELEASE 0.14 (21.02.05)
* finally fixed time indication when blast and in replay mode
+ more help file written

RELEASE 0.15 (01.03.05)
* some interface fixes
+ feedback link added
+ add thanks to Sorin Manea for counters window idea
+ more help file written
- error in average 3BV at beg/int/exp found (00:41 03.03.05)

RELEASE 0.16 (03.03.05)
* fixed average 3bv calculation in mode review grid
+ game menu string cut when used long captions
+ full help file written
+ history converter Clone 0.96 -> Arbiter 0.16 written

RELEASE 0.17 (12.03.05)
+ more board refresh optimizations
+ human interface fixes
+ forum link added
+ history converter advancements: style detection
+ add debug command get_CPU_speed

RELEASE 0.18 (13.03.05)
* 1 ½ click method bug fix
(+ thanks Stephen Arnason)
+ more code optimizations

RELEASE 0.19 (15.03.05)
* disabled system parameters scan at startup
* disabled hotkey globalysator, and, as its part, the boss-key
* fixed game over state: run cheat_disable_timer when time=250; total gameover at 999 sec.

RELEASE 0.20 (16.03.05)
* fixed time correctness check at replay load
* ”debugmode” parameter recognition for the program startup params
* changed image reload priority to HIGHEST instead of TIME_CRITICAL
+ some code optimizations

RELEASE 0.21 (16.03.05)
* few critical fixes
(+thanks Marko Jeznik)
+ platform, memory, language detection

RELEASE 0.22 (18.03.05)
* fixed unfinishable cycle for captions-cut under winXP
* fixed replay_coords saving for 1 ½ click method
+ replay playing like normal replay playing with real 1.00x, not pattern-style
+ some interface improvements
+ more code optimizations
+ more stable startup procedure
+ more debug information saving if any bug occurs
+ mark mines with flags when game win

Version 0.23 (19.03.05)
* great security debug. all videos from previous versions NOT COMPATIBLE with 0.23
* beginner mode block from 0.22 fixed

Version 0.24 (24.03.05)
* replay bug when up-click was done to the board border fixed for sure
+ added feature stop on minimize 
+ added link to Damien’s site

Version 0.25 (24.03.05)
* fixed replay filename condition pattern <3bv/s>

Version 0.26 (27.03.05)
* counters window decimal values representation fixed for sure
(+thanks Curtis Bright)
* game win state detection fixed: when there were some more flags, than needed
* fixed releasing left mouse button outside the board - bug from 0.24
* fixed names of corrupted and backup history files
+ saving corrupted copy and clearing history when history is corrupted
+ added button to save full statistics without entire debug stats
+ added weekly and monthly activity in the stats/activity page
+ overall games chart page added to stats

Version 0.27 (01.04.05)
* fixed games chart drawing when values are equal
* security code optimizations
* fixed board mutation engine
+ board refresh optimizations
+ new feature – fill finished board with flags

Version 0.28 (06.04.05)
* corrected screenshot saving path
+ BitBlt board draw method supported - the fastest screen refresh

Version 0.29 (14.04.05)
* fixed corrupted video file shell execution procedure
* minor gameplay and interface fixes and optimizations
* date detection at mid-months fixed for sure
+ new flags support + 40 countries added, total 84
(+thanks Stevan Gvozdenovic)

Version 0.30 (05.05.05)
* bug, when not all the mines were drawn after a blast, fixed
* interface fixes
* security fixes
+ finished game time and 3bv/s rank is shown in the board caption
+ IRC addon - stats info strings copied colorized to the clipboard for further pasting to the chat
(+thanks Elmar Zimmermann)
(+thanks Dan Cerveny)

Version 0.31 (09.05.05)
+ statistics search engine, sorting and HTML-saving supported

Version 0.32 (14.05.05)
* history entries limit set to 256k (was 64k)
* interface fixes
+ external history files (.DAT or .INF) browsing support
(+thanks Alain Rousseau)

Version 0.33 (20.05.05)
* external history file loading bug, when gamemode was not recognized correctly, fixed
* averages calculation in the search table
* minor interface fixes

Version 0.34 (07.06.05)
* fixed blast bug, when flags were changed to mines
* fixed inverse sorting by mode in stats search engine
* fixed DayOfWeek detection in the stats activity page
* menu captions cut fixed
* some interface fixes
* fixed the program protected caption string
+ not drawing "cheat" labels when the game finished
+ sub-folder name in the replay filename support
+ added option show/hide user ID text

Version 0.35 (08.06.05)
+ option to show/not show equal times and 3bv/s in statistics

Version 0.36 (26.06.05)
* automation <3bv/s> saving bug fixed
* show time and 3bv/s equals defaults changed to true
* interface fixes
* links fixes
+ mIRC format scripting added
+ <3bv/s> added to automation default filenames


Version 0.37 (30.06.05)
* optimized stats columns widths
* interface fixes
* debug protocol buffer expanded to 3k lines
+ CUSTOM GAMES RECORDING/REPLAYING!
+ added cheat option to show mines positions
+ initial mouse sensitivity control
+ custom games board size expansion to 30x30
+ custom games max mines amount expansion to 99%
+ added debug protocol status label

Version 0.38 (01.07.05)
* finally fixed mid-months init_timer function
* statistics proper first-page opening fixed
+ added options to save/load boards in Minesweeper Board File format (mbf/abf)
+ added board REPLAY options
+ added save/load/delete custom board sizes interface

Version 0.39 (02.07.05)
* finally fixed dayofweek function
+ <board> pattern in automations to save boards
+ screenshots now would be saved in the proper \screenshots\ folder

Special Version 0.40 (04.07.05)
* 300K bug solved. 500K bug found. (see help file, part 12)
* minimize feature bug fixed
(+thanks Yaeli Amir)
* fixed bug with showmines cheat option
* "cheat" labels in custom game mode renamed to "custom"
* custom board size window interface fixes

Special Version 0.41 (04.07.05)
* custom boards save bug fixed
(+thanks Yaeli Amir)

Version 0.42 (29.08.05)
+ index of speed calculator (see stats window – search page)
(+thanks Roman Gammel)
+ plugins support!!!!!
+ minesweeper calculator plugin available
(+thanks Aryeh R D)
* fixed links


________________________________________
Minesweeper Arbiter, Copyright 2005 Dmitriy I. Sukhomlynov

 

