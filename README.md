# WinverUWP
A UWP version of winver.
Fork of Winver UWP by Dongle

NOTE: To add your own branding images, please replace the Windows10-(theme).png or Windows11-(theme).png with your images.
Also change occurences of Windivs to your custom name.

![WinverUWP on Windows 11 (Dev)](/images/WinverUWP-dark-11.png)

## System requirements
Windows 10 Creators Update (1703) or newer using the x86, x64, ARM32 or ARM64 CPU architecture.

## Installing

#### Package files
1. Go to the [Releases](https://github.com/dongle-the-gadget/WinverUWP/releases) page.
2. Look for the latest release (usually at the top of the page).
3. Download the correct architecture (x86, x64, arm32 or arm64).
4. Open the downloaded `appx` file and choose **Install** or **Update**.

**Note:** Choosing the correct architecture is critical, otherwise the app would fail to read the registry and crashes on launch.

### For Release 1.x
**Note:** These builds don't support ARM64 and has been officially deprecated.

1. Download [Release 1.1](https://github.com/dongle-the-gadget/WinverUWP/releases/download/v1.1.0.0/WinverUWPPackage_1.1.0.0.zip).
2. Extract the ZIP file.
3. Run the Install.ps1 file and the application will be installed.
   
   **Note:** During installation, PowerShell may ask you about execution policies and administrator privileges. For execution scopes, select **Unrestricted**, and for administrator privileges (User Account Control), select Yes or enter in your administrator credentials.

## Launching
You could launch this program in one of these three ways:
- As an app entry in Start, Search, PowerToys Run, ... (whatever has you)
- Using the app execution alias: `winveruwp.exe`
- Using the app protocol: `winveruwp://`

<!--
