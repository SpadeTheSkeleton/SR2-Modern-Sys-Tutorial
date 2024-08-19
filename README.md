# SR2-Modern-Sys-Tutorial (New to GitHub Edition)

(open this in full screen or zoom out to see ascii art)   

                                                                                                                                        
                                                                                                                                                                           
       ###############             ################             #################                ########                                                                                           
      ################            #################            ##################               ##########                                                                                          
      ######                      ######                      #######                          ############                                                                                         
      ###############             #################           #######   #########             ###### #######                                                                                        
      ################            #################           #######   #########            #######  #######                                                                                       
                ######            ######                      #######      ######           ##################                                                                                      
      ################            #################           ###################          ####################                                                                                     
      ################            #################            #################          #######        #######                                                                                    
      ##############                 #############%              #############            ######          ######                                                                                    
                                                                                                                                                                                                    
                                                                                                                                                                                                    
                                  ##############                      ####                   #####                       #####                 ######          ######         ################      
                                  ##################                ########                 ######                     ######                  #######       #######         %################     
                                  ##################               ##########                ######                     ######                   #######    #######                      ######     
                                  ######      ######              ############               ######                     ######                     ######  #######              ###############     
                                  ##################             ######  ######              ######                     ######                      #############              ###############      
                                  ##################            ################             ######                     ######                       ##########               #######               
                                  ######      ######           ##################            ######                     ######                        %#######                #################     
                                  ######      ######          ####################           ################           #################              ######                 #################     
                                  ######      ######         #######        #######           ###############            ################              ######                                       
                                                                                                                                                                                                    







If you're reading this on notepad, i recommend enabling Word Wrap ( Format > Word Warp )


                                             
                                                                                        
How to make Sega Rally 2 work on modern PC systems (win 10/11) (Created by SpadeTheSkeleton - August 9th 2024)


                                                                                                                                                           
PLEASE READ THIS BEFORE CONTINUING WITH THE GUIDE!
-----------------------------------------------------


This guide may not work for you due to how old the game is and how inconsistent things can be depending on how your system is. Try this method at your own risk and please read everything before attempting, a single mistake could mess up your own device.

My guide was constructed under the methods that worked for me, please note that some information may be incorrect due to this being my first time trying to make a 1999 game work on modern systems. If none of the steps in this guide does work for you, I put down below this all the known methods of getting this game. The Alcino Major's Portable builds & a Spanish guide that goes very in-depth. 


I would highly suggest to open up a text document while you're following the guide and write down which build of the game that you used, which settings you have changed, which OS you were on and any details you can tell. The more information that we can get to have more people to play this game, the better.


If you're willing to help to make this game more accessible or interested to join a discord server about everything Sega rally : https://discord.gg/Pn7KX5NG ( Sega Rally Series Discord Hosted by Over Jump Rally )


Internet Archive (Old Portable) : https://archive.org/details/segarally2_portable

myabandonware (Latest Portable) : https://www.myabandonware.com/game/sega-rally-2-championship-a62#download

Sega Rally 2 Speed running Discord (Portable) : https://drive.google.com/drive/folders/1QpDH-hres794N_TCOcKEVm_4bN6E1mUo

In-dept Spanish Guide (Translated in English through Google Translate) : https://oldnewpixel-blogspot-com.translate.goog/2024/07/sega-rally-2-pc-1999.html?_x_tr_sl=auto&_x_tr_tl=en&_x_tr_hl=en-US&_x_tr_pto=wapp


This text document purpose is to be shared around with players who love this game but always struggled to get this game running. You are free to edit this guide if new information or new builds has been developed. If done so, please add additional notes that the edit you have added was made by you. Once this document has been completed, this guide will be supported as long that i can with proper information and new methods.


- KNOWN FIXES (So far)

If anything listed below you have issues with, please come back to this! 


- The device settings won't appear!

First step will be try to run LAUNCER.exe under compatibility mode for windows xp or vista service pack 2, ( right click LAUNCHER.EXE > Properties )  if that doesn't work. Under "Change high DPI settings" click the ☑ for "override high DPI scaling behavior" and make sure that its under "Application"



- The game won't appear!

Read above to change DPI settings!



This guide covers a lot of fixes for this game, https://oldnewpixel-blogspot-com.translate.goog/2024/07/sega-rally-2-pc-1999.html?_x_tr_sl=auto&_x_tr_tl=en&_x_tr_hl=en-US&_x_tr_pto=wapp  I highly recommend it!


As a last ditch effort, you could try https://sourceforge.net/projects/dxwnd/ A software that helps win32 software like Sega Rally 2 :]


~ Chapter 1 ~

First step is that we need a few things, go onto • https://www.myabandonware.com/game/sega-rally-2-championship-a62#download •



You will see 4 blue download buttons, get "ISO Version" and also "PATCH". The "PATCH" will fix the music later.



then go onto here • https://archive.org/download/Sega_Rally_2_Championship_Win95_1999_Eng •



Download • SEGARally2Championship-Eng-PlayDisc.bin & SEGARally2Championship-Eng-PlayDisc.cue •  Since the internet archive has a download speed cap and your internet speed, this may take awhile. Download one at a time.



Next, we're getting a program that creates a virtual CD drive, i will be using DAEMON Tools (You can also use WinCDEmu if you prefer) • https://www.daemon-tools.cc/products/dtLite#page •  • https://wincdemu.sysprogs.org/download/ •



Press the DOWNLOAD button that's in a white box (free with ads), open the exe and install it. This process should be easy enough.

# WARNING : As it tends with free software, it tries to bundle itself with a crappy VPN service. Please DO NOT mindlessly press next while setting up, once you see the menu to download the VPN. Skip it.



Once DAEMON tools is done installing, the ultimate step to make this work is that we need to create a folder onto your C: drive to put the game in. Open up file explorer and follow this closely, This PC > Windows Hard Drive (C:) > Right click > New > Folder > Name it to "Sega Rally 2" or to whichever you prefer.

Note : I have installed this onto my C: drive since it has worked for me, installing it onto another drive may work but I wasn't able to confirm this. Try it at your own risk.



Next up, open • Sega-Rally-2-Championship_Win_EN_ISO-Version.zip • And inside you'll see a folder named • Sega_Rally_2_ISO • Drag that onto your desktop.



Inside of • Sega_Rally_2_ISO • folder, you will see both a .cue and a .bin file then open DAEMON tools, on the bottom you'll see a quick mount option and select the cue file. And for when you want to remove the CD, you can hover the cd and click on the yellow top right icon.



Now, go onto file explorer then • This PC • and you should see a sega rally icon next to your drive. Double click that then a small setup menu will appear with a few options, click on INSTALL

 


Congrats, this is the first step of many. Hopefully it worked so far! If not, you do got a few options. You could reject the CD and try it again or try another virtual CD software. Remove the mounted CD, and uninstall DAEMON tools. Do try with WinCDEmu instead • https://wincdemu.sysprogs.org/download/ • 

One solution was to restart your computer, or you could go inside of the CD itself and run the setup.exe  If you do have a solution to this, please let me know!




The welcome menu should appear. Press on Next > Yes > Browse > Double Click on "c:\" > Select the folder created on your c: drive > next and continue press next. From there, it should start. This will take less than a few minutes.



When it finishes, click on "Add a SEGA RALLY 2 shortcut to Desktop" > Finished > Exit



Alright, the first part is now done! But, it's time to fix some things to make it fully playable! For the next part, I would recommend keeping one file explorer with the Sega Rally 2 folder opened. Since the next step is to put files inside of said folder :]




~ Chapter 2 - What a lovely mess! ~



For this section, we're fixing 3 core things. CD Music, controller support and proper video settings. Let's start with video settings!



✰✰ VIDEO SETTINGS ✰✰

Due to how old this game is, the game's video settings aren't the greatest. So we need to use a software called dgVoodoo to make the magic work. I personally use version 2.55.4 but newer versions may work for this. 



Go onto • https://rockraidersunited.com/files/general-tools/dgvoodoo-2554-r52/ • and click on the "Download File" button. This is a reupload of this version of an old dgVoodoo version since the official website hasn't worked in awhile BUT you are also free to try the newest version of it, if the old version doesn't work out for you!

Official github : https://github.com/dege-diosg/dgVoodoo2/releases 
Official website : https://dege.freeweb.hu/dgVoodoo2/dgVoodoo2/



dgVoodoo_2_55.4.zip should appear in your Downloads folder if you haven't changed where files are downloaded. To unzip the file with 7zip, right click the zip then its "Extract To". This will create a new folder with all the files. For any other software, do use something similar to that.



Next, we're putting these files from dgVoodoo into sega rally 2

↳ dgVoodooCpl.exe 
↳ dgVoodoo.conf
↳ MS folder 
↳ 3Dfx folder



Once they're inside of the Rally 2 folder, right click • SEGA RALLY 2.exe • then go to properties. Compatibility > Click on the box for • Run this program in compatibility mode • > Windows XP (Service Pack 2) > Apply > Ok. Do the same steps for • dgVoodooCpl.exe • 



With that done, open up • dgVoodooCpl.exe • A permission menu will appear, press on yes. From now on, this is your video settings menu. There's a lot that you can do here, but if you want to follow my setup, here's what I personally do.



•• General ••

Appearance 
------------
Windowed -> Stretched
Everything else is default



Miscellaneous
------------------  
☑ Keep window aspect ratio  
☐ Capture mouse  
☑ Center App window 

Apply (to save your settings)



•• Glide ••
Onboard Ram -> 12mb
Resolution -> 1024x768 (feel free to mess with this at a later time)
Antialiasing (MSAA) -> 2x


Miscellaneous
--------------
☑ Force Vsync
☑ Enable Glide Gamma ramp
Everything else is off

 Apply (to save your settings)



•• Direct X ••
VRAM -> 128mb
Resolution 1024x768 (feel free to mess with this at a later time)
☑ Force vSync

Apply (to save your settings) then okay to close


That's it! Of course, to change your settings again. Make sure to close your game and change any settings to your liking. Please keep note of what you have changed so you can easily go back! 



✰✰ CD AUDIO ✰✰

To re-add CD music, it's very simple. If you haven't downloaded the PATCH from earlier, here is the link to it • https://www.myabandonware.com/game/sega-rally-2-championship-a62#download • and get PATCH

You should get a • Sega-Rally-2-Championship_Patch_Win_EN.zip • and you'll see a folder inside it, open it then simply drag • _inmm.dll • onto the sega rally 2 folder.

Double click on • MUSASHI • in the zip folder, then drag • MGAudio.dll • into the SAME FOLDER as Sega Rally 2. It will ask if you want to replace it, click on the first top option to replace the old one.


There is another method to this! • https://oldnewpixel-blogspot-com.translate.goog/2024/07/sega-rally-2-pc-1999.html?_x_tr_sl=auto&_x_tr_tl=en&_x_tr_hl=en-US&_x_tr_pto=wapp • and look for "Music recovery patch"


And it's now fixed! One last step! :D



✰✰ DEVICE SETTINGS/CONTROLLER SETUP ✰✰

As for this, it's very simple. Right click • LAUNCH.exe • then go to properties. Compatibility > Click on the box for • Run this program in compatibility mode • > Win 95 > Apply > Ok ( but you may need windows xp service pack 2 if it doesn't work )

Do make sure if you do play with a controller that it's plugged BEFORE you open up the launcher. Double click • LAUNCH.exe •, press on yes if a permission menu appears. Then click on DEVICE SETTINGS. This is the part that I can't completely solve, but it might take 1 to 3 tries. Click on it, then wait 3 seconds then try again until it opens. You may need to close the launcher and try again! 


Once it popups, change your controller input device to your controller of choice. I personally got an xbox one controller and it works, but if you play with the keyboard feel free to change to your preferred settings.



HERE IS THE LIST OF XBOX BUTTONS 
•••••••••••••••••••••••••••••••••••••
• Left (L Joystick)                 •
• Right (L Joystick)                •
•                                   •
• Up (L Joystick)                   •
• Down (L Joystick)                 •
•                                   •
• Z Axis+  Right Trigger            •
• Z Axis-  Left Trigger             •
•                                   •
• X Rotation+ Left  (R Joystick)    • 
• X Rotation- Right  (R Joystick)   • 
•                                   •
• Y Rotation+  Up  (R Joystick)     •
• Y Rotation-  Down (R Joystick)    • 
•                                   •
•                                   • 
• Button 0  A                       •
• Button 1  B                       •
• Button 2  X                       •
• Button 3  Y                       •
•                                   •
• Button 4  Left Bumper             •
• Button 5  Right Bumper            •
•                                   •
• Button 6  Select                  •
• Button 7  Start                   •
•                                   •
• Button 8  Left Stick Button       •
• Button 9  Right Stick Button      •
•••••••••••••••••••••••••••••••••••••


Here's what i personally set it up, 

Accel as Right Trigger

Braking as Left Trigger

View Change as Y Button

Shift Up as X Button

Shift Down as B Button 

if you'd like to test your inputs, there's a calibration button. Click on the ones you want to test then press the button you set it up as. Once you're done testing and setting up, press on Save then Ok

AND THAT'S IT! YOU'RE DONE! IT'S TIME TO PLAY! 




~~ Chapter 3 - The adventure ends here!  ~~

From here, open the launcher then press play! With everything set and done, it should boot up! If not, change DPI settings as mentioned in the beginning or compatibility. That's the core solutions i could find so far!


 •• KEY REMINDERS! ••

For each time you want to play the game. You need to mount • SEGARally2Championship-Eng-PlayDisc.cue • through DAEMON tools, then once it's mounted. You can start playing the game. It will unmount each time you reset/close your pc, so the cd will be on at all times as long as the pc is on.

I would highly recommend opening Task Manager and open up the "Startup" tab and make sure that DAEMON Tools doesn't boot when you open up windows. Click on it then disable on the bottom right.

To change controller inputs, you have to do it through LAUNCH.exe then DEVICE SETTINGS.

I WOULD RECOMMEND having the window's volume mixer opened, since the game can be very loud! Once you're in-game, go to options and change your sound settings to your liking.

The game might not boot at first, try again until it works or change some settings as mentioned before!

To pause the game, you press the enter key (trying to find a solution to that)





CREDITS
----------------
SpadeTheSkeleton - For starting this project 
Lootria - For guiding me in the right direction for the cd fix and for trying the first version
peppercornyeen - For being with me for the first few rounds of trying to make it work
TransCanadaLimited - For being the biggest inspiration for the rally scene and inspired me for making this work
q_angell, OtterlyStoned & Corvoda - For being guide testers!


