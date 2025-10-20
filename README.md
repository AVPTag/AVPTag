# AVPTag 
(created by [Hopefullty](youtube.com/@hopefullty) on YouTube.)

AVPTag is a way to run Gorilla Tag on a Apple Vision Pro. Here is how.

1.  Every time a Gorilla Tag Steam VR (PC-VR) update comes out, our app will detect that.
    
2.  When an update is released, your Windows device will be asked to update it on Steam.
    
3.  Your MacOS will release the update to your Vision Pro, like a middleman.

4.  Your Vision Pro will install the update with the AVPTag app.

5.  Enjoy AVPTag!

# How to set up

Our GitHub repo requires A LOT of patience and time. However, it actually doesn't take so long. Read below!

# Requirements

A Windows Device with at least 5 GB free (To install Gorilla Tag) and MUST not be arm windows (only x86_64, 64 bit, or 32 bit, recommended to use 64 bit)

An  **Apple Silcon** MacOS Device with at least 30 GB free (To sideload apps onto the Vision Pro)

An Apple Vision Pro -- any type of Apple Vision Pro. Must have 6 GB free at the bare minimum.

# Setup

Mac:

 1. Install Homebrew with `/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"`
 2. Run this command: `brew install git`
 3. Run this command: `mkdir ~/AVPTag/ && cd ~/AVPTag/ && git clone https://github.com/CanvasONETech/AVPTag.git`
 4. Install Xcode: [https://apps.apple.com/us/app/xcode/id497799835]
 5. Install the visionOS SDK
 6. Continue the rest of the set up below.
    
Windows:

 1. Install git from [https://git-scm.com/downloads/win] or Install in Powershell with `winget install --id Git.Git -e --source winget`
 2. Run this command: `mkdir "%USERPROFILE%\AVPTag" && cd "%USERPROFILE%\AVPTag" && git clone https://github.com/CanvasONETech/AVPTag.git`
 3. Install Steam if not already done.
 4. Log in to Steam if not already done.
 5. Purchase Gorilla Tag if not already done
 6. Download & Install Gorilla Tag if not already done.
 7. Continue the rest of the set up below.
    
Apple Vision Pro:

 1. Connect to the same Wi-Fi network as your macOS Device.
 2. Open General > Remote Devices
 3. Continue the rest of the set up below.
    
Mac:

 1. Click Open Existing Project.
 2. Go to your user's folder (~ in Terminal), you can do this by pressing Downloads on the side and Command + Up
 3. Click on AVPTag
 4. Click on AppleVisionPro
 5. Click on AVPTag
 6. Click and open AVPTag.xcodeproj
 7. On the menu bar (the top bar), press Window > Devices and Simulators
 8. Under your Apple Vision Pro, select Pair.
 9. Continue the rest of the set up below.
    
Apple Vision Pro & Mac

 1. Input the code from the Apple Vision Pro onto the MacOS Device.
 2. Click Continue
 3. Continue the rest of the set up below.
    
Apple Vision Pro

 1. Go to Privacy and Security
 2. Scroll down until you find Developer Mode
 3. Press Developer Mode
 4. Toggle the switch for Developer Mode on
 5. Press Restart
 6. Log back in
 7. Open Settings
 8. Open General
 9. Scroll down to VPN and Device Management
 10. Press VPN and Device Management
 11. Continue the rest of the set up below.
     
Mac:

 1. In Xcode, where it says "AVPTag > Anything it says here" at the top, select what it says next to the arrow and click your Apple Vision Pro
 2. Click the Play or Build button in the left corner
 3. An error **should** appear telling you about an unsigned enterprise certificate. Return to your vision pro.
 4. Continue the rest of the set up below.
    
Apple Vision Pro:

 1. Press OK on the warning symbol
 2. IN VPN and Device Management, press Apple Development: yourappleid@email.com
 3. Press Trust "Apple Development: yourappleid@email.com"
 4. Press Trust again.
 5. Continue the rest of the set up below.
    
Mac:

 1. Close out the popup by clicking "OK".
 2. Press the Play or Build button in the left corner once again.
 3. Continue on the Vision Pro.
 4. Continue the rest of the set up below.
    
Apple Vision Pro:

 1. Close out the app open currently (Optional)
 2. You may turn off the Apple Vision Pro as it is not needed for the next steps (Optional)
 3. Continue the rest of the set up below.
    
Windows:

 1. Navigate to the user you were logged into when we created the folder "AVPTag"
 2. Go to C:\Users\yourcurrentusername\AVPTag\Windows
 3. Click "pair.bat"
 4. A 6 digit code will appear in Command Prompt. Keep this window open and return to your Mac.
 5. Continue the rest of the set up below.
    
Mac:

 1. Connect to the same internet as the Windows Device.
 2. In Terminal, run this command: `cd ~/AVPTag/MacOS && ./pair.sh`
 3. Enter the code from the Windows Device.
 4. Continue the rest of the set up below.
    
Windows:

 1. Open Steam
 2. Click Library at the top
 3. Locate Gorilla Tag
 4. Click Gorilla Tag
 5. Click Settings next to the info button
 6. Click Manage
 7. Click Browse local files
 8. Where it shows the location (e.g. "C:\Program Files (x86)\Steam\steamapps\common\Gorilla Tag\") copy this text.
 9. Enter Command Prompt
 10. Paste the text you just copied
 11. Press "Enter" on your keyboard
 12. When a menu shows up asking if you would like to link or sync, press "S" on your keyboard, then press Enter.
 13. Continue the rest of the set up below.
     
Mac:

 1. On your Mac, type ~/AVPTag/Sync/
 2. Press Enter
 3. When a menu shows up asking if you would like to link or sync, press "L" on your keyboard, then press Enter.
 4. Continue the rest of the set up below.
    
Windows & Mac:

 1. On both devices, a menu will pop up asking for you to turn this on in the background. Type "Y". You only need to do this on one device.
 2. Continue the rest of the set up below.
    
Windows:

 1. Type "R" to start running AVPTag. This will start AVPTag in the background, and will start Gorilla Tag on Steam. Steam will also not show up and will run in the background, however, you can still access Steam and the AVPTag app.
 2. Continue the rest of the set up below.
    
Mac:

 1. Type "R" to start running AVPTag. This will start AVPTag in the background, and will run Terminal in the background. Xcode will also not show up and will run in the background, however, you can still access Terminal, Xcode, and the AVPTag app.
 2. Continue the rest of the set up below.
    
Apple Vision Pro:

 1. Make sure your Apple Vision Pro is powered on.
 2. Open Home View (or Home Screen)
 3. Open AVPTag
 4. Press "Install Gorilla Tag"
 5. Continue the rest of the set up below.
    
Mac:

 1. In Xcode, press the play button or build button again.
 2. Continue the rest of the set up below.
    
Apple Vision Pro & Windows:

 1. Open AVPTag if not already opened by Xcode
 2. Press "Install Gorilla Tag" again
 3. A code will appear. In Command Prompt, which should still be opened since the Vision Pro is not paired, input that code to the Vision Pro. This will pair your Windows, Mac, and Vision Pro all together.
 4. Continue the rest of the set up below.
    
Apple Vision Pro:

 1. Press "Sync Gorilla Tag"
 2. Press "Open Gorilla Tag"
 3. Gorilla Tag is now installed!


# How to Update Properly

Windows:

 1. Check Steam before you play Gorilla Tag.
 2. If it says "Update", press the button and install it.
 3. Continue the rest of the update process below.

Mac & Windows:

 1. Make sure AVPCLI is open.
 2. Continue the rest of the update process below.

Mac:

 1. In AVPCLI, type "settings"
 2. A menu will appear. Press right arrow, down arrow, and you should be selected on "Auto Update". Press Enter.
 3. Continue the rest of the update process below.

Windows:

 1. Go to Steam > Library > Gorilla Tag and press the settings icon and press Properties.
 2. Go to the "Updates" tab.
 3. Under automatic updates, press the dropdown.
 4. Press "Immediately download updates"
 5. Continue the rest of the update process below.

Apple Vision Pro:

 1. Launch AVPTag from the Home View (or Home Screen)
 2. When the menu appears, press "Update Sync Settings"
 3. You will now get automatic updates!


# How to automatically sign the application every 6 days

Mac or Windows:

 1. On one of the two above, open AVPCLI.
 2. Type "settings" and press Enter
 3. You should be selected to AutoSign. Press Enter.
 4. Continue the rest of the signing process below.

Apple Vision Pro:

 1. Launch AVPTag from the Home View (or Home Screen)
 2. When the menu appears, press "Update Sync Settings"
 3. Press "Open Gorilla Tag"
 4. After you load into Gorilla Tag, you can close the app.
 5. Your AVPTag will now automatically sign itself as long as AVPCLI runs in the background on your Mac (at the least)

# Package Information

Bundle ID: com.hopefullty.avptag
Open Source: false
Age Rating: 13+ to use the Steam version, however this is not enforced as anyone can build our programs.
Category: Gaming
Subcategory: Virtual Reality
Platform: Built for visionOS, but streams from Windows.
License: Proprietary (Personal Project)
Region Availability: Anywhere that does not enforce Steam
Multiplayer/Online Gaming: Yes
Release Status: [==========5%==========] - Completed GitHub README, Completed Concept, Working on creating Xcode Project
Developer Notes: This is a solo, fan-made project — not affiliated with or endorsed by Another Axiom.
