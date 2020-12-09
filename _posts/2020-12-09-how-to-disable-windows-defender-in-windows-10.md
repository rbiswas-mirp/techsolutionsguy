---
layout: post
title:  "3 Easy Ways To Disable Windows Defender in Windows 10"
author: rahul
categories: [ Windows ]
image: assets/images/Disable-Windows-Defender-in-Windows-10.png
---
### What is Windows Defender?

Windows Defender (now known as Microsoft Defender Antivirus) is an always on, anti-malware software that guards your computer from external threats. The antivirus is developed by Microsoft to protect computers from virus threats that are running the Windows 10 operating system.

This antivirus comes preinstalled with any version of Windows 10. Windows Defender protects your computer in realtime from not only viruses, but also ransomware, rootkits, trojans, spyware, and many forms of malicious attacks. The program is free to use, and Microsoft sends regular updates on Windows 10.

### Why turn off Windows Defender?

Good question you ask! If Microsoft Windows Defender is a free antivirus that protects your system from malware attacks, then why would anyone feel the need to disable it or turn it off? There are however specific cases where you would want to disable the Windows Defender.

You may want to install specific software or program on your system, but Microsoft Windows Defender in Windows 10 might keep interrupting. Take 3rd Party Software as an example. Windows Defender can treat programs or applications from small developers as a threat, and it will not allow you to install it. This can sometimes be helpful as you don’t know if the software is legitimate or it may contain some form of malware which may breach your security.

Nevertheless, sometimes you’re sure that the software is safe and legitimate and want to install it, but the Windows Defender keeps deleting it. In this case, you might want to disable Windows Defender temporarily.

There may arise a case where you don’t trust the capabilities of Microsoft Windows Defender and decide to install a third-party antivirus for virus threat protection. There are numerous third-party antivirus programs on the market that can be used in place of Windows Defender.

One benefit of installing a third-party antivirus is that it gives you more security and control over it. You can disable it at any time and re-enable it again.

You may also want to disable Windows Defender in Windows 10 as it utilizes a lot of resources when it runs in the background. You may not have enough ram, or you may want the processor to focus on some specific task rather than waste resources on scanning your computer.

These are just a few reasons for disabling the Microsoft Defender antivirus.

Whatever your reason may be, Microsoft Windows Defender in Windows 10 is still a valuable resource. Something is better than nothing, meaning your computer is much more prone to being infected while using it with the Defender disabled. If you’re planning to use another antivirus, then disabling the Windows Defender is justifiable. The Defender antivirus does not have a disable or uninstall option anywhere. Keep in mind that when Windows Defender disable, the security of your computer will be at risk of malware attacks.

**Let’s look into how to turn off Windows Defender.**

Windows Defender can still be disabled on Windows 10 through settings, registry, and through group policy.
Let’s look into each one, step by step on how to turn off Windows Defender.

Turn off Windows Defender through settings:
This is one of the fastest and easiest ways to disable Windows Defender. All of the operations are going to be done through settings. Just follow these steps:

* Open Start by clicking on the Windows logo on the bottom left of your screen.

* On the Start menu, locate and click on Open Settings by clicking on the gear-shaped icon on the left panel.

![Windows Settings](/assets/images/1.png)

* Windows Settings will open up. Proceed by clicking on Update & Security. It will be the last option.

![Windows Settings](/assets/images/2-1024x548.png)

* Next, proceed by clicking on Windows Security on the left side panel.

![Windows Settings](/assets/images/3.png)

* Under Protection Areas, click on Virus & threat protection.

![Windows Settings](/assets/images/4-1024x548.png)

* The Virus & threat protection Window will open up. Under Virus & threat protection settings, proceed by clicking on Manage settings.

![Windows Settings](/assets/images/5-1024x542.png)

* Real time protection will be the first option in front of you. Under real time protection, click on the blue ON switch.

![Windows Settings](/assets/images/6-1024x549.png)

* Windows will prompt you if you want to make the change. Click on Yes. You’ll see the message stating that real time protection is off, an indication that you have successfully turned off the Windows Defender.

![Windows Settings](/assets/images/7-1024x545.png)

**Anytime you can follow steps 1 to 7 and again click on the Off button to re-enable real time protection.**

The benefit of turning off real time protection through virus threat protection settings is convenience and speed. You can quickly turn it off and then again on. One thing to keep in mind is that when you restart your computer, Windows Defender will automatically be turned on. By disabling real time protection, you can install your desired application or software which you previously could not, but your security will be at risk. You can also make your desired system changes. This is not a permanent solution, but it is the fastest solution through virus threat protection settings.

### How to disable Windows Defender through the registry:

This is a bit of lengthy process to disable Windows Defender:
 Follow these steps to permanently disable Windows Defender through Registry.

* Open Start, by clicking on the Windows logo on the bottom left of your screen.

* Type “Regedit” in the search bar, and proceed by clicking on the Registry Editor with the blue icon. Click on yes when prompted by Windows.

![Windows Settings](/assets/images/8.png)

* The registry editor will open.  On the left side, you’ll see different options. You need to locate to Microsoft Defenders location, by expanding the following:

* First, expand the “HKEY_LOCAL_MACHINE” folder by double-clicking on it.
* Next, expand the “SOFTWARE” folder.
* Scroll down and find the “Policies” folder and expand it.
* Expand the “Microsoft” folder.
* Next, click once on the “Windows Defender” folder.

![Windows Settings](/assets/images/9.png)

* Now, right-click on the “Microsoft Defender” folder and hover your cursor above “New.” A new menu will pop out. Proceed by clicking on “DWORD (32-bit) Value”.

![Windows Settings](/assets/images/10.png)

* A new file will appear on the right side with the option to name it. Enter “DisableAntiSpyware” as the name and hit Enter.

![Windows Settings](/assets/images/11.png)

* Next, double click on the newly created “DisableAntiSpyware” file.

* Edit the value under “Value data:” as 1.

![Windows Settings](/assets/images/12.png)

* Press “Ok” on the bottom to save the value.

* Finally, restart your system for the changes to take place. After restarting, the Microsoft Windows Defender will be disabled successfully.

**If anytime you want to enable the Windows Defender again, follow these steps:**

* Open the registry editor.
* Locate to the “Windows Defender.”
* Double click on “DisableAntiSpyware.”
* Edit the “Value Data” as 0, and click on Ok.
* Restart your system for the changes to take effect.

This method is a bit tricky and lengthy, but this will disable Windows Defender **permanently**. Restarting your computer will not enable the Defender again. Through this method, you can install any app and tweak any setting without the fear of Windows Defender interrupting in Windows 10. Your computers security will be compromised so make sure to enable the Defender again so your security stays active.

### How to turn off Windows Defender through Group Policy:

This is our last instruction set to disable Windows Defender.
 Follow these steps to turn off Windows Defender permanently:

* Press “Win + R,” Window key, plus the “R” key together.

* A dialogue box will appear. Type in “gpedit.msc” and hit Enter.

* The local group policy editor Window will open in front of you.

![Windows Settings](/assets/images/13.png)

* Under “Computer Configuration,” double-click on “Administrative Templates.”

* Next, click on “Windows Components” to expand it.

* Scroll down, locate, and click on “Windows Defender Antivirus.”

![Windows Settings](/assets/images/14.png)

* On the right side, double-click on “Turn off Windows Defender Antivirus.”

![Windows Settings](/assets/images/15.png)

* A new Window opens. Highlight the “Enabled” option on the left and click on Apply and then Ok.

![Windows Settings](/assets/images/16.png)

* Finally, restart your computer for the changes to take effect.

**In case you need to enable Windows Defender again, follow steps 1 to 7, highlight the “Not Configured,” click on Apply and then Ok. Restart your computer, and Windows Defender will be enabled again.**

This is the third and final way to disable Windows Defender permanently. In this way, the Defender antivirus will not enable itself automatically when you restart your system. This is a permanent fix for the Defender antivirus.

### Verdict:

Temporarily disabling the Defender antivirus to install some software or tweak some settings, is fine. There is no issue with that, but disabling the Defender antivirus for a prolonged time can put your security at risk. At any time, your system can be attacked by malicious programs. So, it’s a good practice to at least have a third-party antivirus installed, or to just disable it temporarily.

