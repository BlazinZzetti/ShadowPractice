# ShadowPractice
WiiRd codes to be used on Gamecube, Wii, or Dolphin Emulator to help practice Shadow the Hedgehog

## What does it do?
* Lives are set to 99 lives
* All songs for sound test are unlocked (used for cheat settings)
* The score is set to the true value of the Dark or Hero Meter
* Scores set to 0 and time is set to 99:59.99 to prevent personal best times and scores from being overwritten on accident.
* Allows manipulation of Chaos Meters to activate or deactivate Chaos Powers.
* Displays the Meter's true value in the score display underneath it. (Currently overwrites the point score, will try to fix in a future release.)
* Enter a stage's Expert Mode through stage select.
* Enter The Last Way (Normal or Expert) through Stage Select.

## Controls
Z + R = Fill Hero Meter

Z + L = Fill Dark Meter

Z + L + R = Empty Both Meters

Z + DPad Up = Enter Stage's Expert Mode from Stage Select

Z + DPad Down = Enter The Last Way (Select Final Haunt or it will crash)

Z + DPad Right = Enter The Last Way Expert (Select Final Haunt or it will crash)

The following are activated when you are in the option menu and the selection for the sound test is selecting the noted song.

| Cheat activated when pressing Z + L | Song currently highlighted |
|---|---|
| Unlock Last Story | I Am |
| Unlock Expert Mode | Almost Dead |
| All Cutscene Viewed | Waking Up |
| All Stages and Bosses Selectable | Chosen One |
| Unlock All Special Weapons | All Hail Shadow |
| Unlock All Keys | Never Turn Back |
| No Special Weapons | Westopolis |
| No Keys | Digital Circuit |
| Remove Shadow Rifle | Glyphic Canyon |
| Remove Samurai Blade | Lethal Highway |
| Remove Satellite Laser | Black Bull |
| Remove Vacuum Egg | Cryptic Castle |
| Remove Omochao Gun | Prison Island |
| Remove Heal Cannon | Circus Park |
| Set Samurai Blade to LV 1 | Egg Breaker |
| Set Satellite Laser to LV 1 | Central City |
| Set Vacuum Egg to LV 1 | The Doom |
| Set Omochao Gun to LV 1 | Sky Troops |
| Set Heal Cannon to LV 1 | Mad Matrix |
| Set Samurai Blade to LV 2 | Death Ruins |
| Set Satellite Laser to LV 2 | Heavy Dog |
| Set Vacuum Egg to LV 2 | The ARK |
| Set Omochao Gun to LV 2 | Air Fleet |
| Set Heal Cannon to LV 2 | Iron Jungle |

## How to use
1. Download the latest release .zip of ShadowPractice.
2. Open the folder for the region you want to play.
3. Follow the directions below depending on how you want to play.

### Swiss (GC or Wii)
----
If you don't already know how to use Swiss, read the main page here: [https://www.gc-forever.com/wiki/index.php?title=Swiss](https://www.gc-forever.com/wiki/index.php?title=Swiss)

Copy the <GameID>.txt to the cheats folder on your SD Card.
	
### Nintendont (Wii Homebrew)
----
If your Wii is not set up for Homebrew, you can read this page to get started: [https://wii.guide/](https://wii.guide/)

If you don't already know how to use Nintendont, read this link for more info: [https://gbatemp.net/threads/nintendont.349258/](https://gbatemp.net/threads/nintendont.349258/)

Copy the .gct file to the codes folder on your SD Card.
  
#### ...with a physical disc
1. Copy the gct file to `[SD or USB]:\codes\`
#### ...without a physical disc
1. Copy the gct file to `[SD or USB]:\games\Shadow The Hedgehog [GUPE8P]\` (same folder as game.iso)
----
2. In Nintendont, hover over "Boot GC Disc in Drive [DISC01]" and press B to open settings
3. Set Cheats On

Nintendont will **not** provide a 1:1 performance match to running in GameCube mode.

The game will have higher fps and loading will be faster.

Consider using Swiss or other GameCube mode homebrew to have a closer experience to the original

### Dolphin
----
Open the DolphinFormattedCodes.txt

Method 1: Add in Dolphin
1. Within Dolphin, Access the game properties and navigate the the Gecko Codes tab.
2. Press the "Add New Code..." button.
3. Fill out the provide prompt as:<ul><li>Name: Practice Codes</li><li>Creator: BlazinZzetti or Zzetti</li><li>Code: Copy paste code from DolphinFormattedCodes.txt excluding top line.</li></ul>
			
Method 2: Modify game .ini file
1. Find the GameSettings folder (Documents\Dolphin Emulator\GameSettings).
2. Use a notepad application to open either GUPE8P.ini (ENG) or GUPJ8P.ini (JPN)<ul><li>if the file doesnt exist, use Method 1.</li></ul>
3. Paste the contents of DolphinFormattedCodes.txt underneath '[Gecko]'
4. To enable without using the Dolphin GUI, add the following underneath the code.
~~~text
*
[Gecko_Enabled]
$Practice Codes
~~~
