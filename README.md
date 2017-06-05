![Icons Preview](https://github.com/RoccoDev/Breeze-Cursor-Theme-Green/raw/master/IconsPreview.png "Icons Preview")

# Breeze Cursor Theme - Green Fork

Building the Bridge Icon set from the Inkscape SVG:

1. Ensure you have inkscape and xcursorgen installed.
2. Run build.sh in a terminal. The script may take several minutes.
3. Copy the folder created by the script (should match the name of the theme)
   to your cursors folder.

No trimming will have been done to the cursors, and X11 *may* give you
split-second glitches when switching cursors making them appear to 'jump'
for an instant. To remedy this, you will need to open any auto-generated in
gimp and re-export when with the “trim whitespace” option checked. I do not
beleive it impacts all versions of X, or Wayland.

You will need the “X11 Mouse Cursor (XMC)” plugin for GIMP installed to trim
the cursors if you choose to do so.


**Added by RoccoDev's Green fork**
## How to customize colors

* Edit the cursors.svg file.

There are multiple ways to edit a .svg file.
You can:

* Edit it in a vector editor (e.g., Inkscape, Illustrator)
* Edit the text file directly.

If you edit the file with a text editor, you can **Find/Replace** "5caf52" with your preferred color (if you don't know the hexadecimal value, just google "rgb color picker").

Once you finished editing, run the build.sh file.



*Note: I do not own the icons. All the credits go to people listed in the AUTHORS file. I only edited the icons to be green-ish.*

