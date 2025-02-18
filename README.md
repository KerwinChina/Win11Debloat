# Win11Debloat

Win11Debloat is a simple, easy to use and lightweight powershell script that can remove pre-installed Windows bloatware apps, disable telemetry and declutter the experience by disabling or removing intrusive interface elements, ads and more. No need to painstakingly go through all the settings yourself, or remove apps one by one. Win11Debloat makes the process quick and easy!

You can pick and choose exactly which modifications you want the script to make, or use the default settings. If you are unhappy with any of the changes you can easily revert them by using the registry files that are included in the 'Regfiles' folder. All of the apps that are removed can be reinstalled from the Microsoft store.

![Win11Debloat Menu](/Assets/menu.png)

#### Did this script help you? Please consider buying me a cup of coffee to support my work

[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/M4M5C6UPC)

## Features 

> [!Tip]
> Select the custom mode to customize the script to your needs or select the [default mode](#default-mode) to apply the recommended changes.

#### App Removal
- Remove a wide variety of bloatware apps, with the option to select exactly what apps to remove and keep.
- Remove all pinned apps from the start menu. NOTE: This applies to all existing and new users. (Windows 11 only)

#### Telemetry & Suggested Content
- Disable telemetry, diagnostic data, app-launch tracking & targeted ads.
- Disable tips, tricks, suggestions and ads in start, settings, notifications, Windows explorer, and on the lockscreen.

#### Bing & Copilot
- Disable & remove bing search & cortana in Windows search.
- Disable Windows Copilot. (Windows 11 only)

#### Windows Explorer
- Show hidden files, folders and drives.
- Show file extensions for known file types.
- Hide duplicate removable drive entries from the Windows explorer navigation pane, so only the entry under 'This PC' remains.

#### Taskbar
- Align taskbar icons to the left. (Windows 11 only)
- Hide or change the search icon/box on the taskbar. (Windows 11 only)
- Hide the taskview button from the taskbar. (Windows 11 only)
- Disable the widgets service & hide icon from the taskbar.
- Hide the chat (meet now) icon from the taskbar.

#### Context Menu
- Restore the old Windows 10 style context menu. (Windows 11 only)
- Hide the 3D objects, music or onedrive folder in the Windows explorer sidepanel. (Windows 10 only)
- Hide the 'Include in library', 'Give access to' and 'Share' options in the context menu. (Windows 10 only)

## Default Mode

The default mode applies the changes that are recommended for most users, expand the section below for more info.

<details>
  <summary>Click to expand</summary>
  <blockquote>
    
    Default mode applies the following changes:
    - Remove the default selection of bloatware apps. (See below for full list)
    - Disable telemetry, diagnostic data, app-launch tracking & targeted ads.
    - Disable tips, tricks, suggestions and ads in start, settings, notifications, Windows explorer, and on the lockscreen.
    - Disable & remove bing search & cortana in Windows search.
    - Disable Windows Copilot. (Windows 11 only)
    - Show file extensions for known file types.
    - Hide the 3D objects folder under 'This pc' in Windows explorer. (Windows 10 only)
    - Disable the widget service & hide the icon from the taskbar.
    - Hide the Chat (meet now) icon from the taskbar.
  </blockquote>

  #### Apps that ARE removed by default
  
  <details>
    <summary>Click to expand</summary>
    <blockquote>
      
      Microsoft bloat:
      - Clipchamp.Clipchamp  
      - Microsoft.3DBuilder  
      - Microsoft.549981C3F5F10 (Cortana app)
      - Microsoft.BingFinance  
      - Microsoft.BingFoodAndDrink 
      - Microsoft.BingHealthAndFitness
      - Microsoft.BingNews  
      - Microsoft.BingSearch* (Bing web search in Windows)
      - Microsoft.BingSports  
      - Microsoft.BingTranslator  
      - Microsoft.BingTravel   
      - Microsoft.BingWeather  
      - Microsoft.Getstarted (Cannot be uninstalled in Windows 11)
      - Microsoft.Messaging  
      - Microsoft.Microsoft3DViewer  
      - Microsoft.MicrosoftJournal
      - Microsoft.MicrosoftOfficeHub  
      - Microsoft.MicrosoftPowerBIForWindows  
      - Microsoft.MicrosoftSolitaireCollection  
      - Microsoft.MicrosoftStickyNotes  
      - Microsoft.MixedReality.Portal  
      - Microsoft.NetworkSpeedTest  
      - Microsoft.News  
      - Microsoft.Office.OneNote (Discontinued UWP version only, does not remove new MS365 versions)
      - Microsoft.Office.Sway  
      - Microsoft.OneConnect  
      - Microsoft.Print3D  
      - Microsoft.SkypeApp  
      - Microsoft.Todos  
      - Microsoft.WindowsAlarms  
      - Microsoft.WindowsFeedbackHub  
      - Microsoft.WindowsMaps  
      - Microsoft.WindowsSoundRecorder  
      - Microsoft.XboxApp (Old Xbox Console Companion App, no longer supported)
      - Microsoft.ZuneVideo  
      - MicrosoftCorporationII.MicrosoftFamily (Microsoft Family Safety)
      - MicrosoftTeams (Personal version only, does not remove MS teams for business/enterprise)
  
      Third party bloat:
      - ACGMediaPlayer  
      - ActiproSoftwareLLC  
      - AdobeSystemsIncorporated.AdobePhotoshopExpress  
      - Amazon.com.Amazon  
      - AmazonVideo.PrimeVideo
      - Asphalt8Airborne   
      - AutodeskSketchBook  
      - CaesarsSlotsFreeCasino  
      - COOKINGFEVER  
      - CyberLinkMediaSuiteEssentials  
      - DisneyMagicKingdoms  
      - Disney 
      - Dolby  
      - DrawboardPDF  
      - Duolingo-LearnLanguagesforFree  
      - EclipseManager  
      - Facebook  
      - FarmVille2CountryEscape  
      - fitbit  
      - Flipboard  
      - HiddenCity  
      - HULULLC.HULUPLUS  
      - iHeartRadio  
      - Instagram
      - king.com.BubbleWitch3Saga  
      - king.com.CandyCrushSaga  
      - king.com.CandyCrushSodaSaga  
      - LinkedInforWindows  
      - MarchofEmpires  
      - Netflix  
      - NYTCrossword  
      - OneCalendar  
      - PandoraMediaInc  
      - PhototasticCollage  
      - PicsArt-PhotoStudio  
      - Plex  
      - PolarrPhotoEditorAcademicEdition  
      - Royal Revolt  
      - Shazam  
      - Sidia.LiveWallpaper  
      - SlingTV  
      - Speed Test  
      - Spotify  
      - TikTok
      - TuneInRadio  
      - Twitter  
      - Viber  
      - WinZipUniversal  
      - Wunderlist  
      - XING
      
      * App is removed when disabling Bing in Windows search.
  </blockquote>
  </details>
  
  #### Apps that are NOT removed by default
  
  <details>
    <summary>Click to expand</summary>
    <blockquote>
      
      General apps that are not removed by default:
      - Microsoft.Edge (Edge browser, only removeable in the EEA)
      - Microsoft.GetHelp (Required for some Windows 11 Troubleshooters)
      - Microsoft.MSPaint (Paint 3D)
      - Microsoft.OutlookForWindows* (New mail app)
      - Microsoft.OneDrive (OneDrive consumer)
      - Microsoft.Paint (Classic Paint)
      - Microsoft.People* (Required for & included with Mail & Calendar)
      - Microsoft.ScreenSketch (Snipping Tool)
      - Microsoft.Whiteboard (Only preinstalled on devices with touchscreen and/or pen support)
      - Microsoft.Windows.Photos
      - Microsoft.WindowsCalculator
      - Microsoft.WindowsCamera
      - Microsoft.windowscommunicationsapps* (Mail & Calendar)
      - Microsoft.WindowsStore (Microsoft Store, NOTE: This app cannot be reinstalled!)
      - Microsoft.WindowsTerminal (New default terminal app in Windows 11)
      - Microsoft.YourPhone (Phone Link)
      - Microsoft.Xbox.TCUI (UI framework, removing this may break MS store, photos and certain games)
      - Microsoft.ZuneMusic (Modern Media Player)
  
      Gaming related apps that are not removed by default:
      - Microsoft.GamingApp* (Modern Xbox Gaming App, required for installing some games)
      - Microsoft.XboxGameOverlay* (Game overlay, required for some games)
      - Microsoft.XboxGamingOverlay* (Game overlay, required for some games)
      - Microsoft.XboxIdentityProvider (Xbox sign-in framework, required for some games)
      - Microsoft.XboxSpeechToTextOverlay (Might be required for some games, NOTE: This app cannot be reinstalled!)
  
      Developer related apps that are not removed by default:
      - Microsoft.PowerAutomateDesktop*
      - Microsoft.RemoteDesktop*
      - Windows.DevHome*
  
      * Can be removed by running the script with the relevant parameter. (See parameters section below)
  </blockquote>
  </details>
</details>

## Usage

> [!Warning]
> Great care went into making sure this script does not unintentionally break any OS functionality, but use at your own risk!

### Quick method

Download & run the script automatically via powershell. Please note that this will install git if it's not already installed on your system.

1. Open powershell as an administrator.
2. Copy and paste the code below into powershell, press enter to run the script:
```powershell
& ([scriptblock]::Create((irm "https://raw.githubusercontent.com/Raphire/Win11Debloat/master/Get.ps1")))
```
3. Wait for the script to automatically install git and download Win11Debloat.
4. A new powershell window will open showing the Win11Debloat menu. Select either the default or custom mode to continue.
5. Carefully read through and follow the on-screen instructions.

This method supports [parameters](#parameters). To use parameters simply run the script as explained above, but add the parameters at the end with spaces in between. Example:
```powershell
& ([scriptblock]::Create((irm "https://raw.githubusercontent.com/Raphire/Win11Debloat/master/Get.ps1"))) -RunDefaults -Silent
```

### Traditional method

Manually download & run the script.

1. [Download the latest version of the script](https://github.com/Raphire/Win11Debloat/archive/master.zip), and extract the .ZIP file to your desired location.
2. Navigate to the Win11Debloat folder
3. Double click the `Run.bat` file to start the script. NOTE: If the console window immediately closes and nothing happens, try the advanced method below.
4. Accept the Windows UAC prompt to run the script as administrator, this is required for the script to function.
5. A new powershell window will now open showing the Win11Debloat menu. Select either the default or custom mode to continue.
6. Carefully read through and follow the on-screen instructions.

### Advanced method

Manually download the script & run the script via powershell. Only recommended for advanced users.

1. [Download the latest version of the script](https://github.com/Raphire/Win11Debloat/archive/master.zip), and extract the .ZIP file to your desired location.
2. Open powershell as an administrator.
3. Enable powershell execution by entering the following command:
```powershell
Set-ExecutionPolicy Unrestricted -Scope Process
```
4. In powershell, navigate to the directory where the files were extracted. Example: `cd c:\Win11Debloat`
5. Now run the script by entering the following command:
```powershell
.\Win11Debloat.ps1
```
6. The Win11Debloat menu will now open. Select either the default or custom setup to continue.
7. Carefully read through and follow the on-screen instructions.

This method supports [parameters](#parameters). To use parameters simply run the script as explained above, but add the parameters at the end with spaces in between. Example:
```powershell
.\Win11Debloat.ps1 -RemoveApps -DisableBing -Silent
```

### Parameters

The quick and advanced method support parameters to tailor the behaviour of the script to your needs. A list of all the supported parameters and what they do can be found below.

| Parameter | Description |
| :-------: | ----------- |
| -Silent                            |    Suppresses all interactive prompts, so the script will run without requiring any user input. |
| -RunDefaults                       |    Run the script with the default settings. |
| -RemoveApps                        |    Remove the default selection of bloatware apps. |
| -RemoveAppsCustom                  |    Remove all apps from the 'CustomAppsList' file. IMPORTANT: Run the script with the `-RunAppConfigurator` parameter to create this file first. No apps will be removed if this file does not exist! |
| -RunAppConfigurator                |    Run the app configurator to create a 'CustomAppsList' file. Run the script with the `-RemoveAppsCustom` parameter to remove these apps. |
| -RemoveCommApps                    |    Remove the Mail, Calender, and People apps. |
| -RemoveW11Outlook                  |    Remove the new Outlook for Windows app. |
| -RemoveDevApps                     |    Remove developer-related apps such as Remote Desktop, DevHome and Power Automate. |
| -RemoveGamingApps                  |    Remove the Xbox App and Xbox Gamebar. |
| -ClearStart                        |    Remove all pinned apps from the start menu. NOTE: This applies to all existing and new users. (Windows 11 update 22H2 or later only) |
| -DisableTelemetry                  |    Disable telemetry, diagnostic data & targeted ads. |
| -DisableBing                       |    Disable & remove bing search, bing AI & cortana in Windows search. |
| -DisableSuggestions                |    Disable tips, tricks, suggestions and ads in start, settings, notifications and Windows explorer. |
| <pre>-DisableLockscreenTips</pre>  |    Disable tips & tricks on the lockscreen. |
| -RevertContextMenu                 |    Restore the old Windows 10 style context menu. (Windows 11 only) |
| -ShowHiddenFolders                 |    Show hidden files, folders and drives. |
| -ShowKnownFileExt                  |    Show file extensions for known file types. |
| -HideDupliDrive                    |    Hide duplicate removable drive entries from the Windows explorer navigation pane, so only the entry under 'This PC' remains. |
| -TaskbarAlignLeft                  |    Align taskbar icons to the left. (Windows 11 only) |
| -HideSearchTb                      |    Hide search icon from the taskbar. (Windows 11 only) |
| -ShowSearchIconTb                  |    Show search icon on the taskbar. (Windows 11 only) |
| -ShowSearchLabelTb                 |    Show search icon with label on the taskbar. (Windows 11 only) |
| -ShowSearchBoxTb                   |    Show search box on the taskbar. (Windows 11 only) |
| -HideTaskview                      |    Hide the taskview button from the taskbar. (Windows 11 only) |
| -DisableCopilot                    |    Disable Windows copilot. (Windows 11 only) |
| -DisableWidgets                    |    Disable the widget service & hide the widget (news and interests) icon from the taskbar. |
| -HideChat                          |    Hide the chat (meet now) icon from the taskbar. |
| -HideOnedrive                      |    Hide the onedrive folder in the Windows explorer sidepanel. (Windows 10 only) |
| -Hide3dObjects                     |    Hide the 3D objects folder under 'This pc' in Windows explorer. (Windows 10 only) |
| -HideMusic                         |    Hide the music folder under 'This pc' in Windows explorer. (Windows 10 only) |
| -HideIncludeInLibrary              |    Hide the 'Include in library' option in the context menu. (Windows 10 only) |
| -HideGiveAccessTo                  |    Hide the 'Give access to' option in the context menu. (Windows 10 only) |
| -HideShare                         |    Hide the 'Share' option in the context menu. (Windows 10 only) |
