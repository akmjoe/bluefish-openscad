# bluefish-openscad
Language files and quick menu for editing OpenSCAD files in Bluefish editor

Install:
Copy bflang/openSCAD.bflang2 to the bflang directory on your computer
On Linux this is at /usr/share/bluefish/bflang/ or /usr/local/share/bluefish/bflang/ if you compiled Bluefish from source. On Mac OSX go to Applications. Right click on Bluefish and select Show Package Contents. Then navigate Contents->Resources->share->bluefish->bflang

OpenSCAD will now be in the list of languages. You can customize the syntax highlighting under Edit > Preferences

To import snippets:
In the snippets side pane, create a new branch called openSCAD. Right click this branch, and select Import. Choose the snippets file from this repository and click Open. The snippets will be imported. You can drag and drop them to rearrange.

rcfile-2.0 is a user configuration for light text on a dark background. It also adds menu shortcuts to the openSCAD cheat sheat and preview in openSCAD (linux only - edit for your system). This is located in your bluefish profile folder. Make sure to backup your existing profile. 
