---
layout: post
title:  "How to Stop Windows 10 Auto-Updates"
author: Rahul Biswas
categories: [ Windows ]
image: assets/images/How-to-Stop-Windows 10-Auto-Updates.jpg
---
There are few things that inconvenience us more than software updates. Windows users often make jokes about the updates they receive because they take so long to complete (yes, you should initiate your update overnight). As with any good software, updates are a vital part of our computer’s health and security. But, sometimes it just isn’t practical to perform right now, and other times it can cause problems for other software you’re running.

![Windows 10 Default Wallpaper](/assets/images/windows_10_light_and_mirror_background-scaled.jpg)

Like most technology these days, Windows updates are automatic. The basis for this is that developers really love the software they design, and they don’t exactly have faith that end-users will perform the updates themselves. So, automatic updates were implemented to make your life easier while keeping your system operating smoothly.

An improperly timed automatic update can really cause a headache. Whether the update causes problems and glitches with your PC, or it is initiated while you’re working, this article will walk you through everything you need to know about stopping an update and reversing it if need be.

### How to Disable Windows 10 Updates

There are a few ways that you can disable the Windows updates. Let’s review them:

#### Disable a Windows 10 Update Permanently

You can disable Windows 10 updates by following these steps:

Using the **Win+R** keyboard shortut type **services.msc** to access your PC’s service settings.

![Run services.msc](/assets/images/Screenshot-2020-09-29-115751.png)

Double click on **“Windows update service”** to access the General settings.

![Windows Update Services](/assets/images/Screenshot-2020-09-29-115928.png)

Select **‘Disabled’** from the Startup dropdown.

![Select Disabled](/assets/images/Screenshot-2020-09-29-115310.png)

Once done, click ‘Ok’ and restart your PC.

Performing this action will permanently disable Windows automatic updates. If you’d like to enable it again, follow the same steps as above and toggle the option to ‘Automatic.’

####Disable Windows Updates Via the Settings

Another, more familiar option would be to change the Windows update settings through your PC’s actual Windows Settings. This option may be simpler for some depending on how tech-savvy you are, but it is not a permanent solution.

To disable your updates through the settings, do this:

Go to your Windows Start menu and click on the **‘Settings‘** cog.

![Windows 10 Settings Cog](/assets/images/Screenshot-26-2.png)

Scroll down to the bottom of the page and click on **“Update & Security.”**

![Update and Security](/assets/images/Screenshot-27-2.png)

Now, click on the **“Advanced Options”** tab.

![Advanced Options](/assets/images/Screenshot-28-1.png)

Now, you can choose a date from the dropdown that you’d like to pause automatic updates to.

![Pause Updates](/assets/images/Screenshot-29.png)

As stated above, this is not a permanent solution but it’s great to know if you only need to pause your updates for a while. Pausing your updates means there is no worry that your PC will go severely out of date as the automatic updates will eventually turn back on by itself.

#### How to stop Windows 10 downloading: Via the Registry

The initial instructions largely depend on which version of Windows you’re using, but the method is essentially the same. To stop automatic updates using the Registry, follow these steps:

Open the Start menu and type “regedit.” Click on “Registry Editor.” (TOP TIP: Alternatively you can simply hold **Windows key + R** to bring up the Run window)

![Run](/assets/images/Screenshot-2020-09-24-112055.png)

Now that the Registry Editor is open, you can check the key that records whether your system is ready to download Windows 10. Using the options on the left side, double click as follows: HKEY_LOCAL_MACHINE / SOFTWARE / Microsoft / Windows / CurrentVersion / WindowsUpdate / OSUpgrade

![Registry Editor](/assets/images/Screenshot-25-3.png)

Once you’ve navigated to the right key, you’ll need to add a value that tells the system you don’t want to download Windows 10. To do this, right-click on the key name, select the New submenu and then select DWORD (32-bit) Value. You’ll see that a new value is created called “New Value #1”. Rename it “AllowOSUpgrade”.

The last step in Registry Editor is to make sure that the OS Upgrade feature is turned off. To do this, double-click the file and check that the value is “0”, making sure that the hexadecimal box is checked. To complete the process, refresh the page and then close regedit.

Now you should be able to use Windows Update without having to check whether the Windows 10 Upgrade has sneaked into the Optional upgrade list and ticked itself for download. Result!

###How to Uninstall a Windows 10 Update

Perhaps you’re here because you’ve realized that and Update is already installed and you aren’t happy with the outcome. Unlike other operating systems, Windows does give you the option to uninstall an update as you see fit.

Following the same steps as above, access your PC’s **Settings**, then click on **“Update & Security.”** Once there, follow these steps:

Click **“Delivery Optimization”** in the right menu list. Then click **“View Update History.”**

![View Update History](/assets/images/Screenshot-30.png)

Click **“Uninstall Updates.”**

![Uninstall Updates](/assets/images/Screenshot-31-1.png)

From here you can choose to uninstall the updates as you need to. If you’re doing this because the newest update is causing issues with other software on you computer it’s worth researching before going straight into an uninstall frenzy.

Check your driver and other updates to see if the culprit lies somewhere other than Windows OS.