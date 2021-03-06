# GoToMeeting Removal Tool
Unofficial GoToMeeting Removal tool for macOS.  
Version 1.5.0

Just need to download the tool? [Click Here](https://github.com/robotmachine/GoToMeeting-Removal-Tool/releases/download/latest/GoToMeeting-Removal-Tool-latest.zip)  

## CHANGELOG

### 18 December, 2018 (V1.5.0)
* Added new application paths
* Added cookies
* Added new plists

### 2 November, 2017 (V1.4.4)
* Updated log file path to remove Citrix Online
  
### 11 July, 2017 (V1.4.3)
* Updated for LogMeIn name in paths

### 18 May, 2017 (V1.4.0)  
* Removal tool now cleans up GoToMeeting icons from the dock  
  
### 22 March, 2017 (v1.3.8)
* Removed references to Citrix

### 2 November, 2016 (v1.3.7)
* Added yet another location for the launcher
* Added LauncherLock file

### 2 November, 2016 (v1.3.6)
* Added another location for the launcher
* Fixed icon to include transparency

### 31 October, 2016 (v1.3.5)
* Added app icon

### 29 September, 2016 (v1.3.4)
* Added support for macOS Sierra  


### 01 March, 2016 (v1.3.3)
* Updated notice to explain what is and is not deleted
* Changed icon in Automator workflow

### 12 February, 2016 (v1.3.2)
* Fixed typo in plist removal

### 12 February, 2016 (v1.3.1)
* Fixed `mdfind` command
* Added backup command to remove plist files

### 04 February, 2016 (v1.3.0)
* Added logging to ~/Library/Logs/com.citrixonline.g2mremoval.log

### 24 July, 2015 (v1.2.0)
* Using `mdfind` to find any stray GoToMeeting.app files

### 22 July, 2015
* Quits GoToMeeting and GoToMeeting Recording Manager if they are open
* Using an array for plists to avoid errors

### 17 July, 2015:  
* Added to version control
