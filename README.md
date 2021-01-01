# HogRacing
 
Place the maps folder in your Heroes of the Storm root directory, and this will replace the initial tutorial available in the games main menu.

If you would like to replace the Battleground Training tutorial, then the file contained in the deepest folder directory can be renamed to tutorialmapmechanics.stormmap, and if you would like to instead replace the veteran tutorial, then it can instead be named tutorialveteran.stormmap. I personally have not tested this, but it should all still function properly.

Courses are saved as StormBank files in the heroes bank directory for your account - this can be accessed by going to the Watch tab in the Heroes client, clicking the "Show in Folder" button above the replay file listings, and then navigate backwards to the #-Hero-#-###### folder, and in there there should be a "Banks" folder. If you have succesfully initiated the bank procedure in the Hog Racing battleground, you will see a Track1-Track15.StormBank files. The bank system can be initialised by typing "HogBuilder" once the gates have opened(which will happen approximately 3 seconds after your hero has spawned). This will also spawn & select the builder unit, which you can use to create courses.

In order to use the bank from another player, simply place their saved bank in your Banks folder, and replace a .StormBank file of your choice.

For a full list of text commands you can use, type "HogHelp" into text chat

Note that text commands need to not have the quotation marks to work properly, so if you wish to load the track saved into slot 3, you simply type **LoadTrack 3**, if you wish to save the currently loaded track, typing **SaveTrack** will save to the lowest known slot, but if you type **SaveTrack 6**, then it will be saved into slot 6.

The lowest known slot is only initialised when the **HogBuilder** or a similar text command is used.
