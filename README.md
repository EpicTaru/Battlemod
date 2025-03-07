## Battlemod

Purpose: To allow chat log customization.

I am not the creator of this addon.  This repo is simply a Ashita packaged version of a depreciated version of `Battlemod` that is reverted to the version necessary for use on servers version-locked <strong>PRIOR</strong> to the beginning of 2020. 

As I do not own this addon, I cannot assist with issues regarding it.  Since this is also a version of the addon that is not current, support with this addon (from the original creator(s) also will probably be limited.

There is a newer/current Ashita plugin version of `Battlemod` available that <ins>should</ins> be used for servers that are on a version <strong>NEWER</strong> than the end of 2019. The newer/current version, as well as to submit issues with the newer/current version, is located at:

[(https://gitlab.com/farmboy0/ashita-addons/-/tree/master/battlemod?ref_type=heads)](https://gitlab.com/farmboy0/ashita-addons/-/tree/master/battlemod?ref_type=heads)

## Setup Instructions

1. Download the latest release from the "Releases tab."

2. Unzip the release package.

3. In the extracted folder, copy the unzipped directory `battlemod-<version>` subdirectory to the Ashita addon directory.

4. Rename the `battlemod-<version>` directory to `battlemod`.

5. Load the addon via the `default.txt` script or Ashita `/addon load battlemod` command.

## Additional information:

Original Author: Byrth<br>
Version: 3.23<br>
Date: 20/9/15<br>
Battlemod, packet version<br>
Abbreviation: /bm <command/utility>

### Commands:

(Toggles):
simplify - Condenses battle text using custom messages (Default: True)

condensetargets - Collapse similar messages with multiple targets (Default: True)

targetnumber - Toggle condensed target number display (Default: True)

condensetargetname - Toggle target name condensation (Default: False)

oxford - Toggle use of oxford comma (Default: True)

commamode - Toggle comma-only mode (Default: False)

condensedamage - Collapses similar damage messages with the same target (Default: True)

swingnumber - Toggle condensed damage number display (Default: True)

sumdamage - Sums condensed damage if true, comma-separated if false (Default: True)

condensecrits - Condenses critical hits and normal hits together (Default: False)

cancelmulti - Cancels multiple consecutive identical lines (Default: True)

showonernames - Shows the name of the owner on pet messages (Default: False)

crafting - Toggle early display of crafting results (Default: True)



### Utilities:

colortest - Shows the 509 possible colors for use with the settings file

reload - Reloads the settings file

unload - unloads Battlemod

help - shows a menu of these commands in game



### Settings Files:
The settings files for battlemod are composed of 3 to 25 xml files (depending on how much you like unique filters). XML files can be opened with Notepad, edited, and saved safely. If you are going to "Save As..." an xml from Notepad, be sure to change "Text Documents (.txt)" to "All Files" file type and make sure the file ends in ".xml"

data/settings.xml         - contains basic flags that control the features of the program.<br>
data/colors.xml           - contains all the color codes relevant to the program, which can be adjusted using colors from the colortext command.<br>
filters/filters.xml       - contains the chat filter settings and is explained more thoroughly therein.<br>
filters/filters-.xml - Several examples are provided, but these are specific filter files that will load for your individual jobs. You can use this to, for instance, make sure your healing jobs can always see damage taken (by unfiltering the  section or make sure your zerg jobs don't have to see the entire alliance's damage spam. The filter file is organized by actor, so if you wanted to filter by target you would have to go through each class of actor and change the setting that affected the given target.
