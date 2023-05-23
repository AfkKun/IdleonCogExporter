# This repository is not maintained anymore. To use it again someone needs to update the used IdleonAPI version of this project




# Idleon Cog Exporter

This exporter exports all cogs and players from the board and storage and writes them in the csv format used by automorphis' "Cogstruction" algorithm.
It's built on Corbeno's Idleon API v0.2.

# How to get

1. Download the repository by clicking the green Code button on this page then click "Download ZIP"
2. Unzip the file to your location of choice (download folder works fine)
3. Navigate to chrome://extensions in chrome browser or edge://extensions in the chromium edge
4. Make sure "Developer mode" is checked at the top right of the screen
5. Click "Load unpacked" then select the folder you unzipped
6. You are good to go! You might want to pin the extension for ease of use in game

# How to use

First you need to install the Cogstruction algorithm and the Python environment: https://github.com/automorphis/Cogstruction#cogstruction

When the extension is installed you just need to log into the Legend of Idleon website. Open the extension once you are logged in and are in the character selection or already on a character.

For both the cogs data and the empties data you can either copy the data to the clipboard or download the csv-files directly.

These files can directly be placed into the Cogstruction folder and are ready to be used (Continue with the Cogstruction Step 7 in the [How-To](https://github.com/automorphis/Cogstruction#how-to-run)).

# Planned

Adding the function to load back the output.txt of Cogstruction and try to visualize a more straight forward way of rearranging the cogs after the calculation as this is still a tedious process.

# Known Possible Problem

Currently I don't have all possible cogs and therefore had to put in placeholder names for the row/column and omni cogs which may or may not be correct!

I also have no cog with the "flaggy_speed" attribute (not flaggy_rate) and have it filtered out for now as I don't now which key it is using.

These issues will be resolved soon when I get the last missing cogs or someone is able to provide his cog information

# Other Issues?

Feel free to contact me here on github or on Discord AfkKun#1244

# Special Thanks
To [Corbeno](https://github.com/Corbeno) for building this awesome and easy to work with API and cleaned up JSONs: https://github.com/Corbeno/Idleon-Api-Downloader
