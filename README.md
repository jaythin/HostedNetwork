# Hosted Network for Windows

Small application to set/start/stop hosted network in Windows

Made this for r/3dshacks to host networks for the 3DS/2DS

---

If you are on Windows 10, you should have a built-in [Mobile Hotspot](https://support.microsoft.com/en-us/help/4027762/windows-use-your-pc-as-a-mobile-hotspot) feature that does pretty much the same thing as this application, so you can try that out.

## Features
- Set the hosted network details (SSID, password, mode)
- Start or stop the hosted network

## Requirements

- A compatible network card that supports hosted networks
- Microsoft Hosted Network Virtual Adapter driver to be enabled

## Issues

If you are unable to see your hosted network after starting the application, then you might need to Sharing options in your Windows Settings.

- Open the 'Run' menu (can be accessed from Start menu)
- Type in `ncpa.cpl`
- Right-click on your primary network connection (it could be the Ethernet or the Wifi, however Ethernet will be used over Wifi) and click Properties
- Click on the Sharing tab
- Tick the 'Allow other users to connect through this computer's Internet Connection'
- You should now have a dropdown under it, select to share connection with `Local Area Connection* ##`
- Done, see if the hosted network can be seen now