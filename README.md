## How to make original Sega Rally 2 (CD) work on modern PC systems (win 10/11) 

## Created by SpadeTheSkeleton - Last Edited : August 20th 2024 11:04pm



                                                                                                                                                                                                                                                                                                                   
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
                                                                                                                                                                                                    
                                                                                       
                                                                                                                                                           
PLEASE READ THIS BEFORE CONTINUING WITH THE GUIDE!
-----------------------------------------------------


This **guide** may not work for you due to how old the game is and how inconsistent things can be depending on how your system is. Try this method at your own risk and please read **everything** before attempting, a single mistake could mess up your own device.

My guide was constructed under the methods that worked for me, please note that some information may be incorrect due to this being my first time trying to make a 1999 game work on modern systems, this will be **updated** regularly when i can once proper methods are discovered and tested!  


I would highly suggest opening up a text document while you're following the guide and write down which build of the game that you used, which settings you have changed, which OS you were on and any details you can tell. The more information that we can get to have more people play this game, the better.



If you're interested to help to make this game more accessible or interested to join a discord server about everything Sega rally : https://discord.gg/Pn7KX5NG 



If none of the steps in this guide does work for you, I put down below all the known methods of getting this game. The Alcino Major's Portable builds & a Spanish guide that goes very in-depth. 

+ Internet Archive (Old Build) [Link](https://archive.org/details/segarally2_portable)

+ myabandonware (Latest Build) [Link](https://www.myabandonware.com/game/sega-rally-2-championship-a62#download)

+ Sega Rally 2 Speedrunning Discord Portable Build [Link](https://drive.google.com/drive/folders/1QpDH-hres794N_TCOcKEVm_4bN6E1mUo)

+ In-dept Spanish Guide - OldNewPixel **(Translated in English)** [Link](https://oldnewpixel-blogspot-com.translate.goog/2024/07/sega-rally-2-pc-1999.html?_x_tr_sl=auto&_x_tr_tl=en&_x_tr_hl=en-US&_x_tr_pto=wapp)


### This Github purpose is to be shared around with players who love this game but always struggled to get this game running, please do feel free to **fork** this project and report issues when possible! The **more** help towards this, the better!




 KNOWN FIXES
-------------

If anything listed below you have issues with, please come back to this!


## The game won't appear no matter which compatibility mode I use! 

First step will be to change **DPI settings**, right click **• Sega Rally.exe •** > **Properties** > **"Change high DPI settings"** > click the ☑ for **"override high DPI scaling behaviour"**

You could try [dxwnd](https://sourceforge.net/projects/dxwnd/) A software that helps win32 software run 


## When trying to run the DAEMON Tools setup, windows defender shown a warning of PUA:Win32/Puamson

From what i can tell, it's mostly a warning that its an ad based malware, it should be safe to continue due to it bundling a crappy **VPN** service.

Make it an exception and download a general antivirus like [MalwareBytes (direct download link)](https://www.malwarebytes.com/mwb-download/thankyou) to make scans. Make sure to fully close MalwareBytes before installing DTLite, then after installation, run the antivirus to do a scan. It will remove a few files, and you should be fine •ᴗ•



~ Chapter 1 ~
-------------

First step is that we need a few things, 

1. Go to  **• https://www.myabandonware.com/game/sega-rally-2-championship-a62#download •**
2. You will see 4 blue buttons, Click on the **• ISO Version •** button
3. Lastly go to **• https://archive.org/download/Sega_Rally_2_Championship_Win95_1999_Eng •**
4. Download both the **.cue** and **.bin** for **• SEGARally2Championship-Eng-PlayDisc •**  Since the internet archive has a download speed cap and your internet speed, this may take awhile. **Download one at a time.**

Next, we're getting a program that creates a virtual CD drive, i will be using **DAEMON Tools** (You can also use WinCDEmu) 
+ • [DAEMON Tools Lite](https://www.daemon-tools.cc/products/dtLite#page) •
+ • [WinCDEmu](https://wincdemu.sysprogs.org/download/) •


Press the **DOWNLOAD** button that's in a white box **(free with ads)**, open the exe and install it. This process is quite easy.

> [!WARNING]
> **If you can't run the setup exe due to windows defender showing error PUA:Win32/Puamson, please go to the known fixes section.**

> [!CAUTION]
> **As it is a free software, it tries to bundle itself with a crappy VPN service. Please DO NOT mindlessly press next while setting up, once you see the menu to download the VPN. Skip it.**



Once **DAEMON tools** is done installing, the **ultimate step** to make this work is that we need to create a folder onto your C: drive to put the game in. Open up File Explorer and follow this closely, **This PC** > **Windows Hard Drive (C:)** > **Right click** > **New** > **Folder** > Name it to **"Sega Rally 2"** or to whichever you prefer.

> [!TIP]
> **I have installed this onto my C: drive since it has worked for me, installing it onto another drive may work but I wasn't able to confirm this. Try it at your own risk.**



Next up, open **• Sega-Rally-2-Championship_Win_EN_ISO-Version.zip •** And inside you'll see a folder named **• Sega_Rally_2_ISO •** Drag that onto your desktop.



Inside of **• Sega_Rally_2_ISO •** folder, you will see both a **.cue** and a **.bin** file then open **DAEMON tools**, on the bottom you'll see a quick mount option and select the cue file. And for when you want to remove the CD, you can hover the cd and click on the yellow top right icon.



Now, go onto file explorer then **• This PC •** and you should see a sega rally icon next to your drive. Double click that then a small setup menu will appear with a few options, click on INSTALL

 

Congrats, this is the first step of many. **Hopefully it worked so far!**


> [!TIP]
> If the setup doesn't open, there is a potential solution!
> You could reject the CD and try it again or try another virtual CD software. Remove the mounted CD, and uninstall DAEMON tools. Do try with WinCDEmu instead **• https://wincdemu.sysprogs.org/download/ •**  One solution found to restart your computer, or you could go inside of the CD itself and run the setup.exe **If you do have a solution to this, please let me know!**



The **welcome menu** should appear. Press on **Next** > **Yes** > **Browse** > **Double Click on c:** > Select the folder created on your **c: drive** > next and continue press **next**. From there, it should start. This will take less than a few minutes.



When it finishes, Click on ☑ for **"Add a SEGA RALLY 2 shortcut to Desktop"** > **Finished** > **Exit**



Alright, the first part is now done! But, it's time to fix some things to make it fully playable! 



For the next part, keep file explorer opened within the Sega Rally 2 folder. The next step is to put files inside of said folder to make the game work proper *•ᴗ•*




~ Chapter 2 - What a lovely mess! ~
-------------

For this section, we're fixing 3 core things to make them work again. **CD Music**, **control setup** and proper **video settings**. Let's start with video settings!



•• VIDEO SETTINGS ••
-------------

First third party program that we're getting is dgVoodoo2, a software that imitates old graphic cards of the era. Go to • [link](https://dege.freeweb.hu/dgVoodoo2/dgVoodoo2/) • and get the latest release **(v.283 as of this post)**


If you need an old release of dgVoodoo2 for any reason, this is version v.255 • [link](https://rockraidersunited.com/files/general-tools/dgvoodoo-2554-r52/) • 

> [!NOTE]
> Official websites in case you need it •ᴗ•
> + Official github : https://github.com/dege-diosg/dgVoodoo2/releases 
> + Official website : https://dege.freeweb.hu/dgVoodoo2/dgVoodoo2/



**dgVoodoo_2_83.zip** should appear in your **Downloads** folder or to wherever you have downloaded at. To unzip the file with **7zip**, right click the zip then its "Extract To". This will create a new folder with all the files. For any other software, do use something similar to that for simplicity.



Next, we're putting these files from dgVoodoo into the **Sega Rally 2** folder.

> [!IMPORTANT]
> - dgVoodooCpl.exe 
>  - dgVoodoo.conf
>  - **in MS > x86**
>    - D3D8.dll 
>      - D3D9.dll 
>        - D3Dlmm.dll 
>          - DDraw.dll



Once they are inside of the Rally 2 folder, right click **• SEGA RALLY 2.exe •** then go to **Properties** > **Compatibility** > Click on the box for **Run this program in compatibility mode** > **Windows XP (Service Pack 2)** > **Apply** > **Ok** 

Repeat the steps for **• dgVoodooCpl.exe •**


With that done, open up **• dgVoodooCpl.exe •** A permission menu will appear, press on yes. From now on, this is your **video settings** for the game. There's a lot that you can do here, but here's what i personally recommend.


•• General ••
-------------

**・・ Appearance ・・**
+ Windowed -> Stretched
+ Everything else is default


**・・ Miscellaneous ・・**
+ ☑ Keep window aspect ratio  
+ ☐ Capture mouse  
+ ☑ Center App window 

+ Apply 


 •• Glide ••
------------------ 
+ Onboard Ram -> 12mb
+ Resolution -> 1024x768 (feel free to mess with this at a later time)
+ Antialiasing (MSAA) -> 2x


**・・  Miscellaneous ・・**
+ ☑ Force Vsync
+ ☑ Enable Glide Gamma ramp
+ Everything else is off

+ Apply 



•• Direct X ••
------------------ 
+ VRAM -> 128mb
+ Resolution 1024x768 (feel free to mess with this at a later time)
+ ☑ Force vSync

+ Apply > okay to close


+ That's it! To change your settings again. Make sure to close your game and change any settings to your liking. Please keep note of what you have changed so you can easily go back! 


•• CD AUDIO FIX ••
------------------ 
To re-add CD music, there are 2 unofficial methods to this. For this section, I will be using the External method. 

- Method 1 **(Recommended)** : Patching game EXE & extracting game music **( Difficulty : Medium )**
+ Pros : Doesn't rely on the CD for music & have access to control the CD audio volume
+ Con : This method takes the longest 

- Method 2 : Unofficial Patch for CD Music  **( Difficulty : Easy )**
+ Pros : Takes less than 30 seconds to set up. Drag and drop.
+ Con : You cannot control how loud the music is during CD audio sections & can cause slight lag when pausing.

## ・・ External Method (Patching EXE)  ・・
1. Go onto your **Sega Rally 2** folder and create a folder named **Music**. This is where we're gonna extract the music.
2. Open **DAEMON Tools** and mount the **playdisc.bin**, then open up **Windows Media Player**
3. If you're not already in **Library** mode, you can get to that by clicking on the top right icon **(The 3 cubes and an arrow)** On the left, you should see **"Unknown Library"** listed. That's the **Sega Rally 2** Ost. Click on that.
4. For each song shown, a ☐ should be next to it. To save some time, in the **Album** section there's a ☐ to select all the songs at once. 
5. Once selected, go to **Rip settings**. From here you can select the **format** (I will go with .mp3) & the **Audio Quality**. Select **More Options** then click on **Change...** to change where the song will be ripped into. Go to the **Music** folder we created earlier and select that then press ok.
6. Click on **Rip CD** This will start the process of ripping the songs. 
7. When completed, go to this [link](https://community.pcgamingwiki.com/files/file/107-patched-_inmmdll/) to get _inmm. Go into the comments and you'll see **• inmm236.exe •** and click on that. This version of **_inmm** works best with Sega Rally 2
8. Open the **• inmm236.exe •**, uncheck ☐ both available options > **Next** > **Browse** > **Sega Rally 2** > **Install** 
9. Inside of the **Sega Rally 2** folder, open **• _inmmcnf.exe •** then go to the **_inmm.ini** tab. Select **Add** and go to the Music folder created in your Sega Rally 2, hold **Shift** on your keyboard and select **Track 13** first then **Track 1**. This should select all the songs in order. Press on **Open** then **Save**, make sure to save this to the **Sega Rally 2** folder and not in the **Music** folder.
10. Next, go to the **Patch** tab, In the **Search box**, write in **Sega Rally** then press **Find**. Select **Sega Rally 2** > **Patch** > **Ok x2**

Close the software and you're now set! 

> [!NOTE]
> This will make the original EXE into a .org file and a new .exe will appear. If you want to get the exe back, drag the modified exe into **_inmmcnf.exe** and it will bring it back to normal! •ᴗ•


## ・・ Internal Method  ・・

First step is to go onto • [here](https://www.myabandonware.com/game/sega-rally-2-championship-a62#download) • and click on the **PATCH** button. 

Make a copy of **MGAudio.dll** that is inside of the **• MUSASHI •** folder somewhere that is safe. This is so you can revert it back to default at a later time if needed.

Open **• Sega-Rally-2-Championship_Patch_Win_EN.zip •** , open it then simply drag **• _inmm.dll •** onto the Sega Rally 2 folder.

Double click on **• MUSASHI •** folder in the zip, then drag **• MGAudio.dll •** into the SAME FOLDER as Sega Rally 2. It will ask if you want to replace it, click on the first top option.


You're now set and ready to go read the next section! •ᴗ•



•• DEVICE SETTINGS / CONTROL SETUP ••
------------------ 
If you're playing with a controller, **make sure that its plugged before running LAUNCH.exe**. Right click **• LAUNCH.exe •** > **Properties** > **Compatibility** > Click in the ☐ for **• Run this program in compatibility mode •** > **Win 95** > **Apply** > **Ok** 

> [!NOTE]
> You cannot plug a controller after opening **LAUNCH.EXE**, you have to close it and try again.

Double click **• LAUNCH.exe •** then a menu appears. Select **DEVICE SETTINGS**, this may take a few tries. I usually give it 2 seconds before trying again, then it should appear eventually after a minute or so. The only annoying bit that i can't have a 100% success rate so far.

> [!NOTE]
> If Device Settings doesn't appear after a few tries in Win95, the fixes that we found was to run it under Windows XP (Service Pack 2) and/or Change high DPI settings in compatibiltity mode. Click on the ☐ for **High DPI scaling override**. Make sure to apply the changes.

Then, in the **• SELECT YOUR INPUT DEVICE •** box. Select your preferred method of playing the game. For this guide, I will be using an Xbox controller. I've included a list of what each button does for that setup.






 HERE IS THE LIST OF XBOX BUTTONS
----------------
+ •••••••••••••••••••••••••••••••••••••
+  Left (L Joystick)                 
+  Right (L Joystick)                                                    
+  Up (L Joystick)                   
+  Down (L Joystick)                 
+                                    
+  Z Axis+  Right Trigger            
+  Z Axis-  Left Trigger             
+                                    
+  X Rotation+ Left  (R Joystick)    
+  X Rotation- Right  (R Joystick)                                    
+  Y Rotation+  Up  (R Joystick)     
+  Y Rotation-  Down (R Joystick)     
+                                                                      
+  Button 0  A                       
+  Button 1  B                       
+  Button 2  X                       
+  Button 3  Y                       
+                                    
+  Button 4  Left Bumper             
+  Button 5  Right Bumper                               
+  Button 6  Select                  
+  Button 7  Start 
+                                    
+  Button 8  Left Stick Button       
+  Button 9  Right Stick Button      
+ •••••••••••••••••••••••••••••••••••••


Here's what i use for my controls, 

Accel as **Right Trigger - Z Axis+**

Braking as **Left Trigger - Z Axis-**

View Change as **Y Button - Button 3**

Shift Up as **X Button - Button 2**

Shift Down as **B Button - Button A** 

Once you configured everything that you like, make sure to Click **Save** and you're free to close the software!


> [!NOTE]
> If you'd like to test your inputs for **Steering**, **Acceleration** & **Breaking**. Click on the **CALIBRATION...** button and select the ones you want to test. You can adjust the range as well. Once you find something that you enjoy. Press Okay then Save!






~ Chapter 3 - The adventure ends here! ~
------------------ 

From here, open **LAUNCH.exe** then press PLAY! With everything set and done, it should boot up! If not, feel free to try again until it works. I'd recommend visting the KNOWN FIXES section of the guide if **issues persists** •ᴗ•


## •• KEY REMINDERS! ••

> [!NOTE]
> For each time you want to play the game. You need to mount **• SEGARally2Championship-Eng-PlayDisc.cue •** through DAEMON tools, then once it's mounted. You can start playing the game. Once you're **done playing**, you can right click the mounted CD to Unmount it (or you can hover the CD icon and click on the small yellow button)
>
> **I would highly recommend** opening **Task Manager** and select the **"Startup"** tab and make sure that DAEMON Tools doesn't boot when you open up windows. Click on it then **disable**
>
> **I would highly recommend** having the window's **volume mixer** opened during playing the game, since the game can be very loud! Once you're in-game, go to **options** and change your sound settings to your liking **( If you used the internal method, the CD audio will still be loud during CD audio no matter what settings you change.)**
>
> To **pause** the game, you press the **enter key** (trying to find a solution to that for controllers)




CREDITS
----------------
+ SpadeTheSkeleton - For starting this project 
+ Lootria - For guiding me in the right direction for the cd fix and for giving my first initial guide a try
+ peppercornyeen - For being with me for the first few rounds of trying to make it work
+ TransCanadaLimited - For being the biggest inspiration for the rally scene and inspired me for making this work
+ q_angell, OtterlyStoned & Corvoda - For being guide testers!
