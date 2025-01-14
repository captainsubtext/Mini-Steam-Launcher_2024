# Mini-Steam-Launcher
Rainmeter skin showing the top 3 most recently played games by user.

![sizes_example](https://github.com/Azland/Mini-Steam-Launcher/assets/55637202/6bd9c295-98f0-4392-8dfc-7038276ebb22)

How to install:

1. Download the latest release (.zip): https://github.com/captainsubtext/Mini-Steam-Launcher_2024
2. Unzip the package 
3. Run the .rmskin file (ensure you have Rainmeter installed)
or copy & paste the folder "Mini-Steam-Launcher_2024" into C:\Users\YourName\Documents\Rainmeter\Skins\
4. Edit the "#SteamName#" variable within the .ini files to load your own profile

----
General Usage:

Profile Image
* Left Click: Open Friends

Steam Image:
* Left Click: Open Games
* Right Click: Open Store
* Middle Click: Open Downloads

Game Images:
* Left Click: Launch the selected Game


Troubleshooting:

* Q: Launcher isnt loading?
  A: 1. Open Rainmeter, go to Skin Tab and close the loaded      
        Skin
     2. Restart Rainmeter and go into load the Skin again
        (Sometimes its trolling and nessescary to clean the     
        cache)

----
Forked from here:
https://github.com/Azland/Mini-Steam-Launcher

Notes by Azland:
Originally built by "J0SH37" - 
https://web.archive.org/web/20140708041345/http://www.reddit.com/r/Steam/comments/29u9cd/ministeam_launcher_that_automatically_displays/
https://web.archive.org/web/20141007080220/http://j0sh37.deviantart.com:80/art/Mini-Steam-Launcher-465160849

There have been other 2.x and 3.x versions floating around, fixing various things. I've therefore started this at version 4.0 as a non-official continuation of this skin, which seems to have been abandoned. 

The skin has been broken by a number of updates to how Steam are handling their profile data. In 2023, even with a fully "public" profile, it is not possible to view recent games by user without either logging in, or having an API key. For this reason, I've altered the skin to use the "top 3" recent games which steam does display on public profiles. The skin therefore lacks features compared to older versions, but this is the only publicly available data which can be used. 
