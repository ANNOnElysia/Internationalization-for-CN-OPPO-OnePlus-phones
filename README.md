# Enable Google Services (GMS) & Native Android UI/Features for CN OPPO/OnePlus Phones

This repository aims to achieve the **internationalization and debloating** of certain features on OPPO/OnePlus devices purchased in the CN region.

---

**This tutorial is tested on OnePlus 15 and verified useful, there might be nuances between different models or system versions, check before proceeding.**

---



## 1. Enable Stock Android APK Installer & Notification  Style

Download the Android CTS tools from [here](https://source.android.com/docs/compatibility/cts/downloads), install and open it once, it will exit automatically with a warning

Don't mind that warning and restart your phone, you can see the apk installer has been set to the Android default




## 2. Change The Default Global Search to Google Search

You need to enable Google Settings first before using any Google components on your phone in the following way

	*Settings --> System & update --> Google Settings --> Google Mobile Services(GMS)*

To use google search services, please download the Google Play, Google and Gemini from trusted download sites.(e.g. [ApkMirror](https://www.apkmirror.com/))

Go to **Apps settings** and Show system apps by tapping on the three dots on the top right of the screen in **App Management**, then go search : **Global Search**

Simply click Disable and enter your lock screen password (If required) to avoid launching the original Chinese Global search from anywhere

Download the Google Play version of [Global search](https://play.google.com/store/apps/details?id=com.oppo.quicksearchbox) as a trigger for Google Search

You can set using Google Search (instead of using Global Search) while swiping down in home screen with following settings

	 *Home screen, Lock screen & style --> Home screen settings --> Swipe down on Home screen*

Toggle it to Global search, don't mind, It won't open a Global Search window since we've already disabled it, instead, you'll see the Google search.



## 3. Enable Gemini as The Default Voice Assistant

*Disable Breeno, Breeno memory and Breeno Touch in AI settings if you like, this step is not necessary.*

Open Gemini app installed before, Click your profile photo on the upper right corner, click *Switch to Google Assistant*,scroll down and click *Android default digital assist app*, please make sure that the default app is set as Google. If Gemini became unavailable later, just toggle it again.

A navigation gesture app is required to launch the Gemini, you can choose what you like. I'll choose [FNG](https://www.apkmirror.com/apk/francisco-barroso/fluid-navigation-gestures/fluid-navigation-gestures-2-0-beta11-release/) to show you the steps 

Open your navigation gesture app, grant the required permissions, select a gesture and pick **voice assistant** or other relevant options. Go back to your Home screen, trigger your gesture and you can have Gemini working on your device

**Important : Don't use the same gesture with any system default gesture since it can cause navigation issues!**



## 4. Make the Quick Glance Cleaner

Swipe left on your Home screen and tap your **profile picture** on the upper left,tap the **Settings** button on the upper right corner

Turn off *All* settings under the **Notifications**, **Customize layout** and all the subdirectories

Go back and tap the upper right "+" to add what you want on the Quick Glance



## Others

###  Google Wallet

To use Google wallet instead of the original Wallet app, you can change the default Wallet app in

	*Apps --> Default apps --> Wallet app*

then choose Wallet(Google) or any other wallet apps you prefer



### Gboard

Download Gboard from a trusted Apk file provider or [Google Play](https://play.google.com/store/apps/details?id=com.google.android.inputmethod.latin&pcampaignid=web_share) 

Follow the instructions in the Gboard app to change to Gboard
