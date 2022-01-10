# Instructions to configure csgo properly.
 In short, the idea is to have a single file (autoexec.cfg) containing all possible keybuttons, settings, crosshair etc. 
 This file is then read each time csgo is launched.
 The effect is the same as if the lines in the file 'autoexec.cfg' were manually copy-pasted to the console window.
 Therefore, all changes should be done in the file 'autoexec.cfg' and the file should be located in a place where csgo can find it


* Begin by making changes to the file. For instance, if you want to bind the flash grenade to something other than the f-button, you would change line 16 from the autoexec.cfg file. Note that if there is an overlap in the bindings (f-button is used for flash grenade and reload, for example), the one specified later in the file will be used and the other will be left unbinded.

* Make sure autoexec.cfg is located in a place where csgo can find it. The best way to check the correct path is to open Steam, right click csgo Properties -> Local files -> Browse. This will open the csgo installation path. From there navigate back few times to the Steam installation folder and go to 

** Steam/userdata/<SOME_LONG_NUMBER_CORRESPONDING_TO_ACCOUNT_ID>/730/local/cfg


