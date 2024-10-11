# call-of-duty-cleaner

Instructions for Using the Call of Duty Cleaner Script Automatic Path Detection
The script will attempt to automatically detect the locations of the shader cache 
and Call of Duty Documents folders. If it fails to find these paths, you will be prompted to enter them manually.
------------------------------------------------------------------------------------------------------------------

:: 1. Running the Script
Choose Option 3: This will automatically search for the shader cache and Call of Duty Documents folders across common drive letters.
If the paths are detected successfully, you’ll see a message confirming the paths.
If the paths are not detected, you can enter them manually when prompted.

:: Setting Custom Paths (If Necessary)
If the script cannot locate the paths automatically or if you need to specify different paths, you can manually set the paths as follows:

:: Battle.net Users:

Specify the path for the shader cache. Example: set shaderCachePath="D:\Call of Duty\_retail_\cod23\shadercache"
your Drive letter may be different.

----------------------------------------

:: Steam Users:

Specify the Steam path for the shader cache. Example: 
set shaderCachePath="C:\Program Files (x86)\Steam\steamapps\common\Call of Duty HQ\cod23\shadercache"
if your game is on steam but in a different drive just find where your game is intsalled follow similar path below.

:: D:\SteamLibrary\steamapps\common\Call of Duty HQ\cod23\shadercache Drive letter mae be different.

----------------------------------------

Call of Duty Documents Folder Path:
The script will look for the Documents folder in the default location:

:: C:\Users\YourUsername\Documents\Call of Duty 

If it does not find the folder, you will be prompted to enter the path manually.

----------------------------------------

:: Backup Your Configuration File:
Backup options.4.cod23.cst:
Before running the script, it’s recommended to copy this file from the Call of Duty Documents folder. It contains your game settings, graphics configurations, and other preferences.
Backing up this file allows you to restore your settings after running the cleaner.

:: Running the Cleaner:
Select Option 1 for cleaning the shader cache.
Select Option 2 for cleaning the Call of Duty Documents folder.
After cleaning, launch the game. You may see a "safety message" prompt—select "No" to proceed.
You will need to re-watch the intro cutscene, and the shader cache will be re-downloaded automatically.

::  Understanding the Process:
This script deletes old shader cache files and the Call of Duty Documents folder.
Upon re-launching the game, new shader cache files and a new Documents folder will be created with default configurations.
Note: You can manually delete these files by navigating to their respective folders. The script provides a convenient, automated way to perform the cleanup.

