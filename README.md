# Terminal to PWD

## Overview
This is a simple apple script that opens a terminal window. The new session's working directory is set to directory open in Finder. 

I recommend assigning this script to a keyboard shortcut.

## Shortcut Setup
    * launch Automator.app
    * create a new service
    * on the left search "Run AppleScript" and drag it to the right
    * copy and paste the entire text of the script into the text box under "Run AppleScript"
    * save the service, remember the name
    * launch System Preferences.app
    * go to Keyboard > Shortcuts > Services
    * find the name of the service you created and assign a shortcut
        * I like to use "cmd-shift-space"

## Script Behavior
If Terminal.app is not running, it will be launched.

If no Finder windows are open the working directory is set to ~.

If multiple Finder windows are open the working directory is set to that of the last window the user touched.
