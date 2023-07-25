# Empty Character Source

Hello, if you are reading this, it is very probable that you are interested in the Empty Character Source Code.

Well, since the app release in September 2021 since that day of writing this README (June 2023) the app source code was not fully available to the public for more than 18 months but the wait has ended
Keep in mind that all the data that include a keystore file has been automatically revoked before committing, so yes feel free to try to compile the app with that or with your own keystore
In this repository, you will find the following contents:

- Decompiled APK File in Folders at / with all the data of the app
- Decompiled AIA File: The AIA file is originally used for the MIT App Inventor Apps but since that Empty Character uses a modified version of it, if you want to open it without any issue follow the compiling instructions below to know how to proceed
- Compiled APK File at /
- Decompiled AIA Files: The same of the AIA file but decompiled
- Revoked Keystore File → Included in the AIA File directly but also available here if you want to try installing it manually on your ~~cat~~, i meant on your phone
- Other Stuff → If i find out some other useful stuff for this repository, i will commit them


### How to compile the app

1. Before beginning please know that this app runs on a custom version of MIT App Inventor and AI2 Offline, I found out that AI2 Offline works fine with almost all the app features without problems but if you ran into an issue during or after compiling the app or during test of the app export feel free to [tell me!](http://t.me/OverloadedTech)
2. Download
   - Head over to [the AI2 Page (If you don't trust the link, you can check it](https://sourceforge.net/projects/ai2offline/) or from [this direct link](https://netcologne.dl.sourceforge.net/project/ai2offline/4.8.3/AI2Offline_x64.exe) and click on the big green button `Download!`. Make sure to not eat the button so other users can use it
     ![images](https://overloadedtech.github.io/EmptyCharacterSource/images/Image1.png)
     ![images](https://overloadedtech.github.io/EmptyCharacterSource/images/Image2.png)
     ![images](https://overloadedtech.github.io/EmptyCharacterSource/images/Image3.png)
   - Now wait for the download to complete and grab a cup of coffee if you want
4. Install
   - Open the downloaded .exe file and allow the setup admin permission and open it
     ![images](https://overloadedtech.github.io/EmptyCharacterSource/images/Image4.png)
   - Now accept the terms and click "Next"
     ![images](https://overloadedtech.github.io/EmptyCharacterSource/images/Image5.png)
   - Now choose to add the app to the home or not and then click "Next"
     ![images](https://overloadedtech.github.io/EmptyCharacterSource/images/Image6.png)
   - Now continue and click again on "Next"
     ![images](https://overloadedtech.github.io/EmptyCharacterSource/images/Image7.png)
   - Now wait, it should take a few seconds/minutes. For me, it took about 1 minute, but it depends on your computer's performance
     ![images](https://overloadedtech.github.io/EmptyCharacterSource/images/Image8.png)
   - Now, if you are still alive after waiting for the installation, click on "Next"
     ![images](https://overloadedtech.github.io/EmptyCharacterSource/images/Image9.png)
   - Finally, tick on "Launch AI2 Offline" and then click on "Finish"
     ![images](https://overloadedtech.github.io/EmptyCharacterSource/images/Image10.png)
5. Server Start & Login
     - After you open the app manually, or it automatically starts up at the end of the setup, make sure to be extremely careful with the next instructions
     - Click on the first button "All AI2 Offline Server" AND THIS IS VERY IMPORTANT: WAIT AT LEAST 20 SECONDS TO ALLOW THE SERVER TO BOOT UP, SOME TERMINALS WILL BE OPENED AND LEAVED OPENED. MAKE SURE TO KEEP THEM OPEN DURING ALL YOUR WORK
       ![images](https://overloadedtech.github.io/EmptyCharacterSource/images/Image11.png)
     - Now after 20 seconds you can click on the next button "Start Invent". It should open a page to a local IP Address that leads to the server
     - Now after the page opens it will be blank for at least 30 seconds, this is completely normal, especially on the first boot ever
     - After waiting it will appear a window telling that the user is not logged it, as this is locally hosted make sure to keep the default address or enter a custom one (nothing will change), make sure to tick the button "Sign in as Administrator" and finally hit the little tiny button "Login" and wait
       ![images](https://overloadedtech.github.io/EmptyCharacterSource/images/Image12.png)
6. Loading the project & Compiling
     - In the homepage it will appear click on the upper Left button called "Projects" and it in the sliding menu click on "Import project (.aia) from my computer ...", now download [this file](https://github.com/OverloadedTech/EmptyCharacterSource/blob/main/Empty_Character.aia) and save it
       ![images](https://overloadedtech.github.io/EmptyCharacterSource/images/Image13.png)
     - Now click on the menu button, and it will ask for your file, watch closely what to do
       ![images](https://overloadedtech.github.io/EmptyCharacterSource/images/Image14.png)
     - Choose the file Empty_Character.aia downloaded in the last section, now make sure to REMOVE the tick to the option "Use Default Package" and in the form it will appear enter "com.empty.character" in the "App Package". Finally, hit the "Ok" button, and it should appear in the home page of the site, and it should automatically open up and show the "Empty Character" home screen
       ![images](https://overloadedtech.github.io/EmptyCharacterSource/images/Image15.png)
       ![images](https://overloadedtech.github.io/EmptyCharacterSource/images/Image16.png)
     - Now you are in the app source code, and potentially you could edit every single aspect of the app, you can firstly start if you want by scrolling down and changing things like the app name and other stuff and the most important thing is the version and build number that you can edit or leave to the ones i did set up
       ![images](https://overloadedtech.github.io/EmptyCharacterSource/images/Image17.png)
     - Now if you have completed all your changes, or you just want to build the app, make sure to hit the top "Build" tab and hit "Generate App (.apk)". Be aware that this operation will take A LOT of time than normal, for me, it took about 5 minutes and took my fans to 100%
       ![images](https://overloadedtech.github.io/EmptyCharacterSource/images/Image18.png)
       ![images](https://overloadedtech.github.io/EmptyCharacterSource/images/Image19.png)
     - During this work, your Windows taskbar should look something like this
       ![images](https://overloadedtech.github.io/EmptyCharacterSource/images/Image20.png)
     - Now wait the compiler to hit 100% and provide you the download link
       ![images](https://overloadedtech.github.io/EmptyCharacterSource/images/Image21.png)
     - Now you can choose to download the APK. Please note that the BARCODE FOR SOME REASON WILL NOT WORK, EVEN IF YOU ARE ON THE SAME LOCAL NETWORK
       Now you can save the project as an aia file using the Project dropdown menu as seen in the next image
       ![images](https://overloadedtech.github.io/EmptyCharacterSource/images/Image22.png)
     - Then if you want to save your projects directly there, you can use the dropdown menu as seen in the next image
       ![images](https://overloadedtech.github.io/EmptyCharacterSource/images/Image23.png)
     - After you saved your project, and you did everything you can shut down the server from the AI2 Offline App clicking on the button "Stop AI2 Offline" and then click on "Exit", you can see it from the next image
       ![images](https://overloadedtech.github.io/EmptyCharacterSource/images/Image23.png)

### Other Modifications
If you want to do other modifications please search the internet, unfortunately other modifications are very generic and i cannot provide documentation for all of them.

# Decompiled App

You can use the decompiled app to make modifications from source. Keep in mind that this operation requires advanced knowledge and it is not recommended

# License

As stated in the LICENSE.md this code is under the MIT License, this means that you can edit and distribute this code as you want, but you cannot impersonate the original app, and you must give credit to the original project, make sure to acknowledge users that your project is based off this original one by @OverloadedTech

### I hope this code can help someone and be useful
