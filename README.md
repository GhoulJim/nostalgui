# nostalgui
A simple World of Warcraft UI created using ElvUI and 'stylized' using kgPanels.

![](img01.png)

## Required AddOns

All required addons can be installed using the [WoWUP](https://wowup.io/) addon manager. 
- ElvUI 
- kgPanels 
- Details!

## Installation

After installing the required addons, log in to a character to begin the process of importing the various profiles that are needed.

### ElvUI Profile

Copy the contents of the `elvui-profile-import-string.txt` file. In-game, open the ElvUI config window by typing `/ec` and pressing the Enter key. On the sidebar on the newly opened window, select 'Profiles'. Click the 'Import Profile' button and paste the file contents in to the provided text area. Click 'Import Now'.

### ElvUI Private Settings

Copy the contents of the `elvui-private-settings-import-string.txt` file. Perform an 'import' the same way that you did in the previous step. This will just copy over character-specific ElvUI settings, and should not affect the profile that you've already imported.

### kgPanels 

Open the kgPanels config window by typing `/kgpanels config` and pressing the Enter key. From the sidebar, select `General Options > Layouts`. Under the `Import New Layout` section, enter a name in the `Import As...` field (such as 'NostalgUI'). Copy the contents of the `kgpanels-import-string.txt` string and paste them in to the `Import Layout` text area. Press `Import`.

### Details!

Open the Details! configuration window by typing `/details config`. Ensure that the `Options` button on the sidebar is selected. On the second sidebar, select `Profiles`. Click on the `Import Profile` button. Copy the contents of the `details-profile-import-string.txt` file and paste them in to the text area provided by Details.  Press `Okay` to finish.

### Finishing

Just to be safe, reload your UI by typing `/reload`. Enjoy!
