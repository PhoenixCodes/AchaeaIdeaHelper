# Achaea Idea Helper - A small helper for IDEAS

This small script is intended to help you see which IDEAS you have yet to review, and help you go through them. It adds a bit of functionality, as detailed below
- Adds idea lifespan to the existing `IDEA SHOW` output
- Adds clickable links to new ideas and ideas in the `IDEA LIST` to show those ideas
- Adds clickable links within the `IDEA LIST` and `IDEA SHOW` to support or censure

Finally, there are currently three specific commands for this script. Both of these commands require you to check the `IDEA LIST` at least once. If you check `IDEA LIST MATCHING <string>`, they will only function on the ideas that were displayed until you redo `IDEA LIST`. 

#### IDEA SHOW NEXT
This will show the next idea that you have not yet voted on. If you've gotten through all of the ideas, it will cycle through to the beginning again. 

#### IDEA SHOW NEXT ALL 
This will show the next idea numerically from the last read one, even if already voted on. At the end, it will cycle back to the beginning of the list again. 

#### IDEA SHOW LAST
This will show the last idea you viewed, nothing fancy!

*Last Updated January 15, 2021*


# Installing

You may download the script by right-clicking [here](https://github.com/PhoenixCodes/AchaeaIdeaHelper/raw/main/IdeaHelper.xml) and clicking 'save as'. Then simply import the package into mudlet via the package manager, importer, or module manager. No restart is necessary!
