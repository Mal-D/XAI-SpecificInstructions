# IMPORTANT INFORMATION - PLEASE READ THIS

We have included couple of Mods - with the gracious permission from the authors @FrostRaptor and T-Bone - that in themselves don't add any player functionality however, they do add significant elements that allow Flashpoint actions that are not normally available and provide a more immersive game play.

The Mods in particular are  

    MapRandomiser Version: 1.2.0.3
    IRBTUtils Version: 2.0.0


Both mods have been supplied in the BattlePak but the **MapRandomiser** mod has been disabled as there is a slight incompatability that only manifests itself while playing the intial Story campaign. Supplying it in this state is necessary to prevent a "Map not Found" error softlocking the game.

# 1.    Players in Story Campaign Mode

If you are planning playing the Kaema Story Campaign - Use the MODS button on the bottom Left of the Main Screen. Scroll through the list of Mods and make sure there is a 'disabled' Mod called MapRandomizer - this is normal and does not need any further action.

![Mod Button](https://github.com/Mal-D/XAI-SpecificInstructions/blob/main/For%20MapRandomizer/Images/MapRandomizerSetup-0003.png)

There is a file in the following directory 
[game installation]\BATTLETECH\Mods\MapRandomizer called modstate.json it has only one line

{"Enabled":false}

this is set to prevent the error mentioned above error. 
### When you have completed the Campaign

When you have finished the Story Campaign and you are planning to play the Open career Mode - Use the MODS button on the bottom Left of the Main Screen. Scroll through the list of Mods and find the 'disabled' Mod called MapRandomizer and select the square on the left of the entry to enable the mod. 
Click - save and follow the game prompts. Restart the game. The Mod will now be enabled.

# 2. Players jumping straight into Career Mode.    

Before you launch into your new Career, there is a change you need you need to carry out. The file in the following directory 
['gameinstallation']\BATTLETECH\Mods\MapRandomizer
 
called **modstate.json** it has only one line

1.    Change {"Enabled":false} to {"Enabled":true} and save the file.

At any later date you wish to play the Story Campaign you will need to set this back to **false**

## 3.    Other important information

### ColourfulFlashPoints Mod

While we supply the folder and settings for this mod you will have to download ColourfulFlashPoints from 

    https://github.com/wmtorode/ColourfulFlashPoints

Just replace the original settings file with the one in the folder to see all the XAI Flashpoints appear in all their glory.

 
