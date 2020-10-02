# RaidAHKScripts

**Collection of scripts designed to automate simple tasks within Raid Shadow Legends.**

The goal is to not to create a fully automated bot that can run the game so many complex tasks are deliberately left out. The intention is to give a few more options to those that are looking to make farming a little less tedious.

All scripts use AutoHotkey found here: https://www.autohotkey.com/

**Commands**
- Ctrl-Alt-d => begins dungeon run script. This should be run from the character selection page with "Start" and "Multi-Battle" buttons. "Auto" should be enabled prior to kicking off this script. The party will rerun the dungeon until out of energy
- Ctrl-Alt-s => begins the sparring pit script. Run from the sparring pit page. Will check each character in the sparring pit once per minute and level up if available.
- Ctrl-Alt-g => helper script that will return the location of the mouse as well as the color of the pixel under the mouse pointer.

**Important Notes**
- It is highly suggested that you familiarize yourself with AuotHotkey prior to running these scripts. These are the scripts I use on my PC and are provided "as is". I can't make any guarantees that these will work on other systems with other resolutions and settings as they have not been tested outside my own environment.
- These scripts make extensive use of pixel color and location for error handling. These have been tested using 3840x2160 resolution with the Raid window maximized. For other resolutions, some adjustment will be required in order to run properly.
- Each script has exit logic in place but should it be necessary to force an exit, you can kill the AutoHotkey process by opening the Task Manager (by pressing Ctrl-Alt-Del). This will abort the script.

**To Do / Bug List**
- [ ] Revisit helper script logic. Sometimes gives inaccurate Pixel Color results
- [ ] Add logic to dungeon script to consume gems for energy if desired
- [ ] Add new script to combine dungeon run and sparring pit scripts. 
- [ ] Add initial GUI to simplify selection of options
