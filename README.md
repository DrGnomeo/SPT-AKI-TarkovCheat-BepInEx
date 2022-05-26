# SPT AKI TarkovCheat BepInEx 2.3.1
 
code updated by Gnome

(Credits to https://github.com/JoakimCarlsson & @Zat on UC as this is completely based off their release back in march 2020)
(Further Credit to https://github.com/NoClueWhoIAm for updating it later on, which is the version used here.)

## How to Install

As this is now a BepInEx Plugin, it's very straight forward to install from my pre-compiled DLL.

Copy the DLL into your AKI installation folder > BepInEx > plugins
This is all your need to do providing I keep this up to date and you haven't had to update the plugin yourself.
If I fail to update it, or you wish to migrate this to another version, continue to read below.

This is https://github.com/NoClueWhoIAm 's guide with some minor changes due to it being a BepInEx plugin, and it is easier to update.

## How to update to newest version yourself:

Find your way to my github and find the source of this release, download that as a ZIP.

You need the following programs in order to update it.

    Microsoft Visual Studio
    Basic to very low csharp knowledge

Open up the Visual Studio Solution file and open References in the solution explorer. Add any missing reference files. You can find those by going to your EmuTarkov installation folder EscapeFromTarkov_Data > Managed > **.dll

To add missing references you right click on References and click on Add Reference... (sad that I need to explain this sometimes)

If the all references are complete, save the solution and build the solution by doing CTRL + SHIFT + B < default keybind >

The solution will build into the save location of the solution folder into > bin/x64/Debug/EscapeFromTarkovCheat.dll

Copy this dll file and paste it into the AKI installation folder > BepInEx > plugins

You should now have:

EscapeFromTarkovCheat.dll in the plugins folder.

You can now run the EmuTarkov like usual and the cheat should work like intended on the updated version.

