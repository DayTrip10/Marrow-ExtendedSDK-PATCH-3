# Fork Info

This is a MODIFIED FORK of the Marrow-ExtendedSDK, it contains fixed scripts which are functional at this time. (Patch 2 of BL). I didnt bother moving the folders that the scripts were in because I am incredibly lazy, but it doesnt matter, itll still work fine.

THIS ALSO INCLUDES PUPPETMASTER SCRIPTS. They're all dummy scripts, I believe they werent included in the original Extended SDK because of fear of the PuppetMaster people not being alright with it, but it should be fine considering all the scripts are empty anyway (Besides variable names and empty methods).

If you want to use this fork, delete your current "Marrow-ExtendedSDK" folder and download this one via the green code button up at the top. Then place it into your folder where the old Marrow-ExtendedSDK folder was. References should be completely fine and you shouldn't have any missing scripts. Although, since PuppetMaster scripts were added, some script references on NPCs will be MISSING! If you made an NPC prior to this, you should delete your puppetmaster/behavior/NPC dummy scripts that you used prior to this fork as there will be conflicts between the scripts.

# Info
This repository allows the extension of the BONELAB Marrow SDK, allowing you to create custom guns and other types of items not yet supported by the Marrow SDK.

One of the major objectives of this repo, is to remove incentives to decompile the game, through strategic inclusion of assets which aren't useful elsewhere, and thorough documentation of what's possible.

# How to Install

Follow steps 1-5 from the official SDK over at https://github.com/StressLevelZero/MarrowSDK/wiki#project-setup

In step 6, you'll want to import these three packages via github URL:

https://github.com/StressLevelZero/Custom-RenderPipelineCore.git

https://github.com/StressLevelZero/Custom-URP.git#Bonelab

https://github.com/Kairus101/MarrowSDKExt.git

Using the green Code dropdown at the top of this page, download a zip of this repositry, and unzip it's contents into your Assets folder to have Assets/Marrow-ExtendedSDK-PATCH-2

Continue following steps 7+ from the official SDK documentation.

### Check out the included Examples folder for ideas on how to create Guns and Levels.

# Disclaimer
Stress Level Zero's Official Bonelab SDK is MIT licenced, and by extension, so is all of this. Updates to the official SDK may break this repo at any time and there is no guaranteed support, so use at your own risk. With any luck, updates to the Official SDK will make this extension repo obsolete.

### This repo only has dummy scripts and basic data to get people started.
### It deliberately does not have any art, code implementation, or other IP from the Bonelab game or elsewhere. There is nothing useful here that can be used outside of Bonelab modding, and will be kept that way.
## Do not commit files that go against this rule
