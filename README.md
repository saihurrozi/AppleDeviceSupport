# AppleDeviceSupport
IOS Device Support 

**IOS 16 :**
IOS 16.7 - Download
IOS 16.6 - Download
IOS 16.5 - Download
IOS 16.4 - [Download](https://github.com/saihurrozi/AppleDeviceSupport/blob/main/iOSDeviceSupport/16.4.zip)
IOS 16.3 - [Download](https://github.com/saihurrozi/AppleDeviceSupport/blob/main/iOSDeviceSupport/16.3.zip)
IOS 16.2 - [Download](https://github.com/saihurrozi/AppleDeviceSupport/blob/main/iOSDeviceSupport/16.2.zip)
IOS 16.1 - [Download](https://github.com/saihurrozi/AppleDeviceSupport/blob/main/iOSDeviceSupport/16.1.zip)
IOS 16.0 - [Download](https://github.com/saihurrozi/AppleDeviceSupport/blob/main/iOSDeviceSupport/16.0.zip)

**IOS 15 :**
IOS 15.7 - [Download](https://github.com/saihurrozi/AppleDeviceSupport/blob/main/iOSDeviceSupport/15.7.zip)
IOS 15.6 - [Download](https://github.com/saihurrozi/AppleDeviceSupport/blob/main/iOSDeviceSupport/15.6.zip)
IOS 15.5 - [Download](https://github.com/saihurrozi/AppleDeviceSupport/blob/main/iOSDeviceSupport/15.5.zip)
IOS 15.4 - [Download](https://github.com/saihurrozi/AppleDeviceSupport/blob/main/iOSDeviceSupport/15.4.zip)
IOS 15.3 - [Download](https://github.com/saihurrozi/AppleDeviceSupport/blob/main/iOSDeviceSupport/15.3.zip)
IOS 15.2 - [Download](https://github.com/saihurrozi/AppleDeviceSupport/blob/main/iOSDeviceSupport/15.2.zip)
IOS 15.1 - [Download](https://github.com/saihurrozi/AppleDeviceSupport/blob/main/iOSDeviceSupport/15.1.zip)
IOS 15.0 - [Download](https://github.com/saihurrozi/AppleDeviceSupport/blob/main/iOSDeviceSupport/15.0.zip)


**Could not locate device support files**
![image](https://github.com/saihurrozi/AppleDeviceSupport/assets/15244248/4e0358cd-cb96-445d-9920-c08f80b55262)

If you see image similar to this, follow this step:

Turn on "Developer mode" on your iPhone (Settings -> Privacy & Security -> Developer Mode).
From this issue.

**Note**
If you need upper version of the support files less than 1 iteration (eg. You have "15.0" and you need "15.1.5" - You can simply rename folder from "15.0" to "15.1.5" and it should work or try to use next iteration version of the support files, is exist "15.2", otherwise open an issue);

**⚠️ Warning ⚠️**
Xcode 12 now encrypts the connection between Xcode and paired devices, protecting against an attacker in a privileged network position executing arbitrary code on connected iOS, iPadOS, watchOS, or tvOS devices during a remote debug session. (60386733)

These security benefits are available when Xcode 12 connects to devices running iOS 14, iPadOS 14, watchOS 7, tvOS 14, or later versions.
These OS versions also refuse debugger connections from older Xcode releases.
Xcode 12 continues to support debugging for older OS versions, but without the new encryption.
Comment

For debugging in iOS 14 devices you need Xcode 12 atleast.
Cause Apple have updated their code for debugging apps on iOS 14 and that is not compatible on older version of Xcode.
Comment

🚩🚩🚩🚩🚩🚩🚩🚩🚩🚩🚩🚩🚩🚩🚩🚩🚩🚩🚩🚩🚩🚩

- To get iOS 13.(version) [example iOS 13.5.1] works with iOS 14.0, just rename a folder.
- Like this: 13.5 ~> 13.5.1 (17F80);
How to support iOS 14 devices with Xcode 11.5+:
(tested with 11.6 (11E708))

Download iOS 14.2 Support Files
Unzip it
Put unzipped folder into path:
/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/DeviceSupport/
Restart Xcode

**How to:**
  1. Download version you need listed above;
  2. Unzip it;
  3. Close Xcode;
  4. Copy and paste unziped folder by path: /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/DeviceSupport/

hierarchy like this:
![image](https://github.com/saihurrozi/AppleDeviceSupport/assets/15244248/bfd45ec9-1d8f-48d9-81a4-fea4597b96d6)


  5. Disconnect any physical target device (iPhone, iPad, etc.)
  6. Reopen Xcode;
  7. (Optional) Connect physical target device

Xcode usage license - [Link](https://www.apple.com/legal/sla/docs/xcode.pdf).
