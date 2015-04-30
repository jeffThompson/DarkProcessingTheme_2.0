![screenshot](https://raw.github.com/jeffThompson/DarkProcessingTheme_2.0/master/screenshot.png)

Dark Processing Theme (for 2.0 and (mostly) for 3.0)
===================

A dark theme for the Processing IDE (a little easier on the eyes!) for Processing 2.0 - for a Processing 1.5 theme, see [this repository](https://github.com/jeffThompson/DarkProcessingTheme). Should also work for most of Processing 3.0, as features are added to the new IDE.

A few changes in how themes are handled in 2.0:

1. The default theme is located in the main Processing app (on the Mac it's in `~/Applications/Processing.app/Contents/Resources/Java/lib/theme.txt` - a separate `theme.txt` file for each mode will selectively override items from this default ([this is done here in the IDE source](https://github.com/processing/processing/blob/909e3a5609d5b7738e33067657a82a33cd663ac5/app/src/processing/app/Mode.java)).

(Windows users, look in `\processing-2.2.1\modes\java\theme` and do the same.)
2. In 1.5x Processing used image files for tabs, etc. As of 2.0 this is handled dynamically, so we just do this in the theme/preferences file.
3. The Android mode has an `icons` folder, where you can change the default app icon (very nice!).

\- \- \-

####INSTALLATION
1. **PREFERENCES.TXT**
Replace your `preferences.txt` with mine. A lot of color preferences have been moved from the `theme.txt` file to this one, which is nice.
2. **THEME FOLDER**
Look in `~/Applications/Processing.app/Contents/lib`. This is a change from previous versions, which allows you to change everything for all installed modes. Windows users, look in `\processing-2.2.1\modes\java\theme` and do the same.
Replace the `theme.txt` file inside (making a copy of the original in case you hate my changes!). This file contains the bulk of the changes (mostly colors).
3. **SCREENSHOT**
Self-explanatory :)

\- \- \-

\[ all code available under [Creative Commons BY-NC-SA license](http://creativecommons.org/licenses/by-nc-sa/3.0/) - feel free to use but [please let me know](http://www.jeffreythompson.org) \]
