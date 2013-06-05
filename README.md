![screenshot](https://raw.github.com/jeffThompson/DarkProcessingTheme_2.0/master/screenshot.png)

Dark Processing Theme (for 2.0)
===================

A dark theme for the Processing IDE (a little easier on the eyes!) for Processing 2.0 - for a Processing 1.5 theme, see [this repository](https://github.com/jeffThompson/DarkProcessingTheme).

A few changes in how themes are handled in 2.0:

1. The default theme is located in the main Processing app (on the Mac it's in `~/Applications/Processing.app/Contents/Resources/Java/lib/theme.txt` - a separate `theme.txt` file for each mode will selectively override items from this default.
2. In 1.5x Processing used image files for tabs, etc. As of 2.0 this is handled dynamically, so we can easily change tab color in the theme file.
3. The Android mode has an `icons` folder, where you can change the default app icon (very nice!)

\- \- \-

####INSTALLATION
1. **PREFERENCES.TXT**  
Replace your `preferences.txt` with mine - note the only main change is setting `editor.antialias` to true, which makes your fonts look WAY better!  Note that this can also be accomplished using the Preferences menu in the IDE.
2. **THEME FOLDER**  
Look in `~/Applications/Processing.app/Contents/Resources/Java/Modes` and in the folder of the Mode you want to change (ie: Java, Experimental).  Replace the `theme` folder inside (making a copy of the original in case you hate my changes!). Note that the Android and Javascript themes are now inside your sketchbook folder in a subfolder named `modes`.
This folder contains a 'themes.txt' file with the bulk of the changes (mostly colors)  
The new theme structure removes many of the buttons (I've left them default) but introduces a somewhat distracting banner image - it has been replaced with a clear PNG which should show any colors you choose in the theme.txt file. Otherwise, change them yourself to something more your style!
3. **SCREENSHOT**  
Self-explanatory :)

\- \- \-

\[ all code available under [Creative Commons BY-NC-SA license](http://creativecommons.org/licenses/by-nc-sa/3.0/) - feel free to use but [please let me know](http://www.jeffreythompson.org) \]
