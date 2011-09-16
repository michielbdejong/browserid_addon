#BrowserID/Sessions API Firefox Addon

This is the BrowserID Firefox addon.  The purpose of this addon is to allow 
sites that support BrowserID to log in using a Firefox doorhanger and 
sites that support sessions API to display the status of their session 
in the browser's URL bar.  This gives the ability to log in, log out,
and check current status.

##To Run:
1. Get the addon-sdk at https://github.com/mozilla/addon-sdk/
2. Start up the addon-sdk environment by cd into the addon-sdk, then 'source 
   bin/activate'.
3. cd out of addon-sdk, and into your copy of this repo, browserid_addon.
4. Now from the addon directory, type cfx run.
5. Go to myfavoritebeer.org to see BrowserID in action!
6. Go to google.com, wikipedia.org, twitter.com or myfavoritebeer.com to see 
   the sessions.

##Running Tests:
Basic tests are found in the test directory. These can be run using 'cfx test'.

##Reporting Bugs:
Bug reports can be filed using the "Issues" in GitHub under the browserid_addon repo.

##Known Problems:
* Caching when going through history is disabled.  Page must be re-rendered.
* When opening multiple Firefox windows at once, only the last instance will have status.
* Must restart Firefox for status to appear in currently opened tabs.


##Author:
* Shane Tomlinson @ Mozilla Labs.
* stomlinson@mozilla.com
* @shane_tomlinson

##Licencing:
Tri licensed under any of the MPL, GPL, or LGPL.
