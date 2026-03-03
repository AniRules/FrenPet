# FrenPet Desktop (Unofficial)

A standalone desktop version of [FrenPet](https://frenpet.xyz) built for macOS and Windows. 

## 📜 Credits & Licensing
- **Engine:** Powered by [Electron](https://www.electronjs.org) via [Nativefier](https://github.com).
- **Windows Installer:** Created using [Inno Setup](https://jrsoftware.org).
- **License:** Distributed under the [GNU GPL v3](https://www.gnu.org).

---

## ⚠️ Disclaimer
**I do not own FrenPet.** This is an unofficial, community-made wrapper. 
- All rights, assets, and branding belong to the [FrenPet team](https://frenpet.xyz). 
- **DMCA Takedown:** If you are the owner of FrenPet and wish for this repository to be removed, please contact me or open an issue, and I will take it down immediately.

---

## 💻 How to Install

Download the latest version from the **[Releases Page](https://github.com/AniRules/FrenPet/releases).**.

### **macOS**
Because this app is not signed by an Apple Developer account, macOS will automatically block it for security reasons. Follow these steps:

1. **Download** the `.zip` file from the [Releases](url_to_releases) page.
2. **Unzip** the folder.
3. **Move** `FrenPet.app` to your **Applications** folder.
4. **First Run:** 
   - **Do not** double-click it normally the first time.
   - **Right-click** (or Control-click) the app icon and select **Open**.
   - A popup will appear saying it's from an "unidentified developer." Click **Open** again.
5. **If the app won't open at all:**
   - Open your **Terminal** and type the following command, then hit Enter:
     ```bash
     xattr -cr /Applications/FrenPet.app
     ```

### **Windows**
1. **Download** the `FrenPet-Setup.exe`.
2. **Run** the installer and follow the prompts.
3. Launch FrenPet from your desktop shortcut or Start menu.


### **Linux (x64)**
I have included a build for Linux x64. Please note:
- I don't know how to package this into a `.deb` (Debian/Ubuntu) or `.rpm` (Fedora) installer.
- To run it, download the Linux zip, extract it, right-click the `FrenPet` executable, and select **"Allow executing file as program"** in your file manager permissions.
- I have included the source/build scripts in this repo if you want to compile or package it into a different format yourself.


---

*Enjoy your FrenPet on the big screen!*
