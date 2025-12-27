[![Language](https://img.shields.io/badge/Language-C%23-blue.svg)](https://dotnet.microsoft.com/en-us/languages/csharp)
[![Framework](https://img.shields.io/badge/Framework-.NET%208.0-purple.svg)](https://dotnet.microsoft.com/download)
[![Database](https://img.shields.io/badge/Database-SQLite-003b57.svg)](https://www.sqlite.org/)

# DMDashboard Release Page

**DMDashboard** is a Windows app used to automate many of the bookkeeping tasks required of DMs when running D&D 5E. This page is used to manage releases. 

## Features
* Build/load/save/edit/run encounters
* Build/edit monster and character databases
* Save/load sessions
* Roll/sort by initiative
* Roll saving throws
* Add/track conditions, including optional reminder popups
* Track PC’s hit points, hit dice, death saving throws, AC, passive perception, and ability scores
* Track monster’s recharge actions, spell slots, and saving throw proficiencies
* Add monsters under the control of PCs (familiars, minions, hirelings, etc.)
* Add characters/monsters to an encounter in progress
* Log XP of defeated monsters
* View party status summary

## Installation
Choose the installation method that works best for you:

### Option 1: ClickOnce Installer
**Best for:** Standard Windows installation with automatic updates.
* **[Click here to Install DMDashboard](https://hudson4351.github.io/DMDashboard-Release/setup.exe)**

---

### Option 2: Portable Version (.zip)
**Best for:** Running the app without installation (USB drives, restricted permissions).
* **[Download Latest ZIP Release](https://github.com/hudson4351/DMDashboard-Release/releases/latest)**

**How to use the Portable version:**
1. Download the `DMDashboard-vX.X.X.X.zip` from the **Assets** section of the latest release.
2. **Right-click** the downloaded ZIP and select **Extract All...**.
3. Open the extracted folder and run `DMDashboard.exe`.
4. *Note: Ensure the `x64` and `x86` folders remain in the same directory as the .exe for database support.*

---

## Security Instructions (Windows SmartScreen)
Because this is an independently developed hobby project, Windows may display a blue warning screen during installation and/or at runtime that says **"Windows protected your PC."** **Don't worry!** This happens simply because the app is not signed with a $300/year "verified publisher" certificate. The app is safe to run.

**To bypass this:**
1. On the blue warning screen, click **"More info"**.
2. Click the **"Run anyway"** button that appears at the bottom.

| Step 1: Click More Info | Step 2: Click Run Anyway |
| :---: | :---: |
| <img src="DMDashboard%20-%20more%20info.JPG" width="100%"> | <img src="DMDashboard%20-%20run%20anyway.JPG" width="100%"> |



---

## Requirements
* **Windows 10/11**
* **.NET Framework 4.8.1** (The installer will prompt you to download this if you don't have it).
