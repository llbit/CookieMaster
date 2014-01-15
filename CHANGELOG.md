# CookieMaster Release History

### Version 1.6.5 - _2014-01-15_

 - Fixed shortening of large numbers so that trailing zeroes are shown

### Version 1.6.3 - _2014-01-15_

 - Hosted on cm.llbit.se

### Version 1.6.3 - _2013/12/14_

 - Fixed typo that prevented Reindeer audio alert from playing (oops!)

### Version 1.6.2 - _2013/12/14_

 - Added more number formatting options (scientific, scientific "e" notation and compact scientific notation)
 - CpS chart now shows a logarithmic scale with a zero baseline for easy of use
 - Fixed delay on Golden Cookie and Reindeer alert sounds (credit to Jesper Öqvist - https://github.com/llbit)

### Version 1.6.1 - _2013/12/09_

 - Fixed some logic with logging when saving user settings and reloading the page

### Version 1.6.0 - _2013/12/09_

 - Added persistent stat logging. You can now track your base and effective CpS across your session(s) (Currently in BETA)
 - Massive and wildly unncecessary refactoring of the bootstrap file :(

### Version 1.5.3 - _2013/12/08_

 - Fixed bug in webkit browsers where audio alerts would only play once
 - Added volume slider for audio alerts

### Version 1.5.2 - _2013/12/08_

 - Prevented Wrinklers getting clicked when clicking Golden Cookies and Reindeer (yay!)
 - Cleaned up some methods

### Version 1.5.1 - _2013/12/08_

 - Fixed incorrect audio file URLs in build directory

### Version 1.5.0 - _2013/12/08_

 - Added building efficiency stats. Methods for calculating stats are derived from [Maxime Fabre's forked Cookie Monster repo](https://github.com/Anahkiasen/cookie-monster), which improves on the original Cookie Monster calculations considerably
 - Added option to show a table with color-coded keys for building efficiency stats
 - Added option to auto-click the Golden Cookie during Click Frenzies
 - Audio files for Golden Cookies and Season Popup now moved into the repo
 - Enhanced Golden Cookie stats with time remaining to reach Lucky/Lucky+Frenzy required bank
 - Added effective CpS method and modified all relevant stats to use this when calculating time remaining
 - Added stat to show your effective CpS
 - Added stat to show reward for clicking Reindeer
 - Improved accuracy of certain stats
 - Fixed Cookie Chain stats bug where normal/Wrath chain values and rewards were reversed
 - Minor visual fixes and tweaks

### Version 1.4.2 - _2013/12/02_

 - Fixed wrong stats showing for current Luck and current Frenzy + Lucky rewards when player is under the max bank required value

### Version 1.4.1 - _2013/12/02_

 - Fixed wrong stats showing for Cookie Chain bank and CpS values

### Version 1.4.0 - _2013/12/02_

 - Added option to choose rounding precision for large numbers
 - Added option to make Golden Cookies more visible when they spawn
 - Added option to increase the clickable area of Golden Cookies to help clicking accuracy, especially during cookie chains
 - Golden Cookie clicks now register as soon as the mouse is pressed, instead of when released
 - Added more stats for CpS and CpC
 - Added stats for maximum cookie chain rewards and bank/CpS needed to advance to next chain tier
 - Reorganized some of the stats
 - Fixed crash when importing a save into a new, unsaved game
 - Fixed bug where timers wouldn't show the min limit when importing a save into a new, unsaved game
 - Fixed bug in stats for Frenzy and Elder Frenzy CpS values

### Version 1.3.2 - _2013/12/31_

 - Stats panel now updates instantly when opened
 - Added CookieMaster version info to Stats and Settings panels

### Version 1.3.1 - _2013/12/31_

 - Fixed bug where clicking a Golden Cookie would sometimes not register properly

### Version 1.3.0 - _2013/12/31_

 - Integrated Stats and Settings windows into the center game panel
 - Added option to display timers at the top or bottom of the left panel
 - Added option to auto-click the big cookie (with speed control)
 - Moved button to pop all reindeer into left panel, now only displays when needed
 - Added more stats
 - Visual tweaks and improvements
 - Cleaned up some messy code

### Version 1.2.4 - _2013/12/31_

 - Fixed broken bookmarklet code

### Version 1.2.3 - _2013/12/30_

 - Fixed bug where Golden Cookie audio alert would play Reindeer alert sound instead

### Version 1.2.2 - _2013/12/29_

 - Fixed bug where title bar counters would display "undefined"
 - Now using stricter linting of source files
 - Minor performance enhancements

### Version 1.2.1 - _2013/12/29_

 - Fixed bug where audio alert settings would not work correctly
 - Improved accuracy of large number formatting (still not perfect though)
 - Improved precision of time to next HC stat

### Version 1.2.0 - _2013/12/29_

 - Moderate refactoring of many methods for clarity and performance
 - Added more granular control over audio and visual alerts
 - Reduced playback volume for audio alerts
 - Added section headings to the stats panel
 - Added a button to pop all Wrinklers at once
 - Removed "s" suffix from timer countdown values
 - Minor performance tweaks
 - Improved source formatting and commenting

### Version 1.1.3 - _2013/12/28_

 - Added check to prevent loading CookieMaster more than once
 - Made some error and warning messages a little clearer

### Version 1.1.2 - _2013/12/28_

 - Removed cache buster parameter from jQuery dependency file

### Version 1.1.1 - _2013/12/28_

 - Fixed bug where top bar would remain visible when Clean UI was active

### Version 1.1.0 - _2013/12/28_

 - Ads are no longer hidden when Clean UI is active
 - Added several suffix options when shortening numbers
 - Upgrade prices now display correct number formatting
 - Moved project to Grunt
 - Bookmarklet now loads a bootstrap file that handles all dependencies
 - All external sources are now loaded in minified for speeeeed

### Version 1.0.0 - _2013/12/28_

 - First public release :)
