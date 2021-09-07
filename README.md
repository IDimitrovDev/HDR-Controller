### What is HDR controller?

![](https://github.com/IDimitrovDev/HDR-Controller/blob/main/screens/hdrcontroller.png)
HDR Controller is tool for managing apps that can activate windows HDR automatically, when get run. It automates the tedious task of switching between using HDR and not using HDR on Windows, for example when playing some HDR media, or game that doesn't automatically trigger it. With HDR controller one can select per monitor which app to activated automatically HDR when it gets started and keep HDR activated while it is running. 
A requirement to use the app is a HDR capable monitor, as such needs to be detected and shown in the app's monitor settings. There two ways of apps that can be added.

 **Microsoft store apps** - selected from the combo with all installed apps from the Microsoft store.

 **Desktop apps** - selected with the browse button by selecting the wanted app's .exe file.

Available configurable settings in the app are:
![](https://github.com/IDimitrovDev/HDR-Controller/blob/main/screens/settings.png)
**HDR Control** - when enabled HDR gets controlled automatically from the app

**Auto-start on Windows login** - when enabled - the app will start automatically when the user logins in Windows.

**Show running HDR preferences apps first** - in monitors settings the app will be sorted by their running status instead of order of add.

**External apps can use HDR controller to enable/disable HDR** - when enabled the app exposes app service functionality that enables external apps to activate or deactivate HDR. For example in [Energy Media Player](https://www.microsoft.com/store/apps/9P9ZH5FL1BFK) HDR Controller integration can be enabled so when HDR media is played on HDR capable monitor, the media player automatically enables HDR(by adding itself into HDR controllers apps requesting HDR) and when the HDR media stops playing it automatically remove itself from HDR Controller and in turn stops Windows HDR. 
 
### Installation

 By downloading the [latest release](https://github.com/IDimitrovDev/HDR-Controller/releases/) and extracting the files from the zip archive.
 Then double click on the certificate HDRControllerPackage_1.0.1.0_x64.cer which will bring a window with information about the certificate. 

![](https://github.com/IDimitrovDev/HDR-Controller/blob/main/screens/certificate_install.png)

Choosing <Install certificate> button, which will start the certificate installation process. 

![](https://github.com/IDimitrovDev/HDR-Controller/blob/main/screens/certificate_import_wizard.png)

Then <Browse> and in the chooser "Trusted Root certification Authorities"

![](https://github.com/IDimitrovDev/HDR-Controller/blob/main/screens/certificate_store.png)

After the certificate is installed, double click HDRControllerPackage_1.0.1.0_x64.msix(if requires a "Open with" app - "App Installer" has to be selected 

![](https://github.com/IDimitrovDev/HDR-Controller/blob/main/screens/msix_app_chooser.png)

Select Install.
 
![](https://github.com/IDimitrovDev/HDR-Controller/blob/main/screens/installer.png)
