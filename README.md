# Instructions to configure csgo properly.
 In short, the idea is to have a single file (autoexec.cfg) containing all possible keybuttons, settings, crosshair etc. 
 This file is then read each time csgo is launched.
 The effect is the same as if the lines in the file 'autoexec.cfg' were manually copy-pasted to the console window.
 Therefore, all changes should be done in the file 'autoexec.cfg' and the file should be located in a place where csgo can find it.


## Step 1: Make changes to the autoexec.cfg file
Begin by making changes to the file. For instance, if you want to bind the flash grenade to something other than the f-button, you would change line 16 from the autoexec.cfg file. Note that if there is an overlap in the bindings (f-button is used for flash grenade and reload, for example), the one specified later in the file will be used and the other will be left unbinded.


## Step 2: Place the autoexec.cfg file to a correct place

The best way to check the correct path is to open Steam, right click csgo Properties -> Local files -> Browse. This will open the csgo installation path. From there navigate back few times to the Steam installation folder and go to 
 
 ```
 Steam/userdata/<SOME_LONG_NUMBER_CORRESPONDING_TO_ACCOUNT_ID>/730/local/cfg
 ```
 Copy paste the autoexec.cfg file to the path above. If you have logged in to multiple accounts on the same computer, you will have multiple account id's under Steam/userdata. You can check the correct id using [these](https://www.businessinsider.com/how-to-find-steam-id?r=US&IR=T) instructions.

 **NOTE! Do NOT place the autoexec.cfg file to 'cfg' located under the csgo installation folder. Also, DO NOT make any changes to the config files there. Those   files are automatically modified when changes are done from the in-game options.** 


## Step 3: Execute autoexec.cfg whenever csgo is launched

To execute the autoexec.cfg file during startup of csgo. Open Steam, right-click csgo and go to Properties -> General -> Launch options and type (at least)

```
+exec autoexec
```

Personally, I also like to specify the in-game resolution, update frequency etc. in the launch options

```
-w 1280 -h 960 -freq 144 -console -novid -tickrate 64 +exec autoexec
```


## FAQ
### How do I make the autoexec.cfg file based on the configuration I have specified in-game? 
* asd fasdf asfdsafgasdf

* Few of the bindings do not work. You are likely using the same button for many 
